<template>
	<div class="card shadow-md shadow-primary-500 hover:shadow-neutral-500 hover:shadow-lg">
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
		transition: all 0.3s ease;
	}
	.card-content {
		padding: 20px;
		word-wrap: break-word; /* Перенос длинных слов */
		white-space: normal; /* Разрешение переноса строк */
	}
	.card::before {
		background: var(--ui-color-primary-500);
		content: ' ';
		display: block;
		width: 10px;
		height: 10px;
		border-radius: 50%;
		transition: all 0.3s ease;
	}
	.card:hover::before {
  background-color: var(--ui-color-neutral-500);
	}
</style>
