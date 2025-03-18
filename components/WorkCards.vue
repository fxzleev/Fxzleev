<template>
  <div class="work-cards-container">
    <WorkCard
        v-for="(card, index) in workCards"
        :key="index"
        :time="card.time"
        :title="card.title"
        :position="card.position"
        :description="card.description"
        :link="card.link"
        :stack-images="card.stackImages"
        :stack-alt="card.stackAlt"
    />
  </div>
</template>

<script setup>
import {ref} from 'vue';
import WorkCard from './WorkCard.vue';

const workCards = ref([]);
import workCardsData from '../data/workCardsData.json';

workCards.value = workCardsData;
</script>

<style scoped>
.work-cards-container {
  display: flex;
  flex-direction: column;
  gap: 20px; /* Расстояние между карточками */
}
</style>