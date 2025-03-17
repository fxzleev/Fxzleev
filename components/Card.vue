<template>
	<div class="card shadow-md shadow-primary-500">
		<div class="card-content">
			<slot></slot>
		</div>
	</div>
</template>

<style>
	.card {
		background: var(--ui-color-neutral-800);
		border-radius:var(--radius-2xl);
		font-size: var(--text-2xl);
		text-align: center;
		padding: 20px;
		min-width: 500px;
		max-width: 500px;
		margin: 10px auto;
	}
	.card-content {
		word-wrap: break-word; /* Перенос длинных слов */
		white-space: normal; /* Разрешение переноса строк */
		& ::before {
			background: var(--ui-color-primary-500);
			content: ' ';
			display: block;
			width: 10px;
			height: 10px;
			border-radius: 50%;
		}
	}
</style>
