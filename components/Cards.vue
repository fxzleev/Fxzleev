<template>
    <Card v-for="(card, index) in filteredCards" :key="index">
      <p>{{ card.title }}</p>
    </Card>
</template>

<script setup>
import Card from './Card.vue';
import cardsData from '../data/cardsData.json';

const props = defineProps({
  type: {
    type: String,
    required: true
  }
});

const filteredCards = cardsData.filter(card => card.type === props.type);
</script>

