<template>
	<footer id="Feedback" class="mb-20 flex flex-col items-center">
		<div
			class="flex justify-between w-312.5 shadow-md shadow-primary-500 rounded-4xl h-30"
		>
			<div class="flex flex-col gap-8 m-5">
				<p class="text-3xl text-primary-500 text-center">Хотите связаться со мной?</p>
				<p class="font-mono text-neutral-400 text-center">
					Связаться со мной можно с 10:00 до 19:00 по МСК.
				</p>
			</div>
			<div class="flex flex-col gap-8 m-5">
				<div>
					<NuxtLink class="mr-2" to="https://github.com/fxzleev" target="_blank">
						<UIcon name="mdi:github" class="size-8 bg-neutral-500 hover:bg-primary-500" />
					</NuxtLink>
					<NuxtLink class="mr-2" to="https://t.me/fxzleev" target="_blank">
						<UIcon name="ic:baseline-telegram" class="size-8 bg-neutral-500 hover:bg-primary-500"/>
					</NuxtLink>
					<NuxtLink class="mr-2" to="https://vk.com/fxzleev" target="_blank">
						<UIcon name="entypo-social:vk-with-circle" class="size-8 bg-neutral-500 hover:bg-primary-500"/>
					</NuxtLink>
					<NuxtLink to="https://kwork.ru/user/fxzleev" target="_blank">
						<UIcon name="arcticons:freelancer-upwork" class="size-8 bg-neutral-500 hover:bg-primary-500"/>
					</NuxtLink>
				</div>
				<p class="text-center">&copy;<span> Fxzleev.ru, 2024</span></p>
			</div>
		</div>
	</footer>
</template>
