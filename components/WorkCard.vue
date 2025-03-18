<template>
  <div
      class="workcard w-285 h-84 bg-neutral-800 shadow-md shadow-primary-500 hover:shadow-neutral-500 rounded-2xl transition-all">
    <div class="w-full h-full p-4">
      <data v-if="time" class="date shadow-md shadow-primary-500 rounded-2xl">{{ time }}</data>
      <h3 class="text-4xl font-light m-2">
        <NuxtLink
            v-if="link"
            class="link"
            :to="link"
            target="_blank"
        >
          {{ title }}
        </NuxtLink>
        <span v-else>{{ title }}</span>
      </h3>
      <p v-if="position" class="text-lg text-primary-500 m-2">{{ position }}</p>
      <p v-if="description" class="text-lg font-extralight m-2">{{ description }}</p>
      <div
          v-if="Array.isArray(stackImages) && stackImages.length > 0"
          class="stack__img flex gap-2 ml-2"
      >
        <img
            v-for="(image, index) in stackImages"
            :key="index"
            :src="image"
            :title="stackAlt[index] || 'No description'"
            class="w-8 h-8 rounded-md object-cover shadow-md shadow-primary-500"
        />
      </div>
      <div v-else class="stack__img flex gap-2 m-2 text-gray-400 text-sm">

      </div>
    </div>
  </div>
</template>

<script setup>
defineProps({
  time: {
    type: String,
    default: 'Нет данных'
  },
  title: {
    type: String,
    required: true
  },
  position: {
    type: String,
    default: ''
  },
  description: {
    type: String,
    default: ''
  },
  link: {
    type: String,
    default: null
  },
  stackImages: {
    type: Array,
    default: () => []
  },
  stackAlt: {
    type: Array,
    default: () => []
  }
});
</script>

<style scoped>
.date {
  display: inline-block;
  padding: 1rem;
  font-size: 1rem;
  color: var(--ui-color-primary-500);
  transition: all 0.3s ease;
}

.link {
  transition: all 0.3s ease;
}

.link:hover {
  color: var(--ui-color-primary-500);
}

.link::after {
  background-color: white;
  -webkit-mask: url('/assets/img/linkg.svg') no-repeat center / contain;
  mask: url('/assets/img/linkg.svg') no-repeat center / contain;
  height: 0.4em;
  content: ' ';
  margin-left: 0.25em;
  width: 0.4em;
  transition: all 0.3s ease;
}

.link:hover::after {
  background-color: var(--ui-color-primary-500);
}

.stack__img img {
  background: var(--ui-color-neutral-500);
  margin: 2rem 0;
  padding: .5rem;
  width: 3.5rem;
  height: 3.5rem;
  border-radius: 50%;
  object-fit: cover;
  transition: transform 0.3s ease;
}

.stack__img img:hover {
  transform: scale(1.1);
}
</style>