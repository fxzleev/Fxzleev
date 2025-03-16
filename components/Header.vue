<script setup lang="ts">

const items = ref([
	[
		{
			slot: 'components',
			class: 'before:bg-transparent hover:before:bg-transparent',
			to: '/',
		},
	],
	[
		{
			label: 'Обо мне',
			class: 'text-xl',
			to: '#About',
			icon: 'material-symbols:home-app-logo'
		},
		{
			label: 'Навыки',
			class: 'text-xl',
			to: '#Skills',
			icon: 'game-icons:skills',
		},
		{
			label: 'Работа',
			class: 'text-xl',
			to: '#WorkExperience',
			icon: 'carbon:portfolio'
		},
		{
			label: 'Связь',
			class: 'text-xl',
			to: '#Feedback',
			icon: 'material-symbols:feedback-outline'
		},
	],
])
</script>

<template>
	<header
		class="bg-(--ui-bg)/75 backdrop-blur border-b border-primary-500 h-(--ui-header-height) sticky top-0 z-50"
	>
		<UNavigationMenu
			content-orientation="vertical"
			:items="items"
			class="w-full justify-between"
		>
			<template #components-trailing>
				<img class="w-50" src="/assets/img/FxzLeev.svg" />
			</template>
		</UNavigationMenu>
	</header>
</template>

<style>
	header {
		display: flex;
		justify-content: center;
	}
	nav {
		width: 1250px;
	}
</style>
