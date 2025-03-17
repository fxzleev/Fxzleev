<template>
	<section class="w-312.5" id="About">
		<div class="about w-full flex flex-row justify-between">
			<h1 class="text-2xl w-70">
				<span
					><span class="text-primary-300">Привет!</span> Меня зовут Игорь. </span
				>Я могу сделать для вас несколько замечательных сайтов.
				<UButton class="mt-10 bg-primary-500" size="xl" to="#Feedback"
					>Давайте Проверим!</UButton
				>
			</h1>
			<div>
				<img
					class="rounded-2xl shadow-md shadow-primary-500"
					src="https://t3.ftcdn.net/jpg/03/18/60/62/360_F_318606217_Hk8jo2MVoI33SQOkYrfOF929J7JgIP0P.jpg"
				/>
			</div>
		</div>
	</section>

	<section class="w-312.5 flex flex-row justify-between" id="Skills">
		<div>
			<h2 class="text-5xl">
				<span class="text-primary-500">Hard </span><span>skills</span>
			</h2>
			<div class="mt-2 flex flex-col">
				<Card><p>HTML(HTML5), TSX, JSX, VUE</p></Card>
				<Card><p>CSS (CSS3), SASS (SCSS), Bootstrap, Tailwind, Animations</p></Card>
				<Card><p>JavaScript (ES6+, OOP), jQuery, TypeScript</p></Card>
				<Card><p>React, Vue</p></Card>
				<Card><p>Redux (Redux Toolkit, Redux Persist), MobX, Vuex, Pinia</p></Card>
				<Card><p>React Hook Form, Axios, React Router, React Query, VeeValidate, Vue Router, Vue Query</p></Card>
				<Card><p>Webpack, Vite</p></Card>
				<Card><p>Jest, Vitest</p></Card>
				<Card><p>REST API, WebSockets</p></Card>
				<Card><p>BEM, Feature-Sliced Design, Accessibility, UX</p></Card>
				<Card><p>Git (GitHub, GitLab)</p></Card>
				<Card><p>Figma, Adobe Photoshop</p></Card>
				<Card><p>CMS 1C-Bitrix, OpenCart, MODX</p></Card>
				<Card><p>Agile, Waterfall, SCRUM</p></Card>
			</div>
		</div>
		<div>
			<h2 class="text-5xl">
				<span class="text-primary-500">Soft </span><span>skills</span>
			</h2>
			<div class="mt-2 flex flex-col">
				<Card><p>Я умею работать в команде, у меня есть опыт работы с дизайнерами, менеджерами и другими разработчиками</p></Card>
				<Card><p>Я ответственно отношусь к срокам</p></Card>
				<Card><p>Я внимательно отношусь к деталям</p></Card>
				<Card><p>Я требователен к качеству своего кода и следую единому code-style</p></Card>
				<Card><p>У меня есть навыки time management</p></Card>
				<Card><p>Я приветствую конструктивную критику и всегда рад найти новые точки
					профессионального и личностного роста</p></Card>
				<Card><p>Я знаю, как разрешать конфликтные ситуации</p></Card>
				<Card><p>Я умею правильно передавать мысли, формулировать вопросы</p></Card>
				<Card><p>При необходимости я составляю подробные отчеты о проделанной работе</p></Card>
				<Card><p>У меня есть опыт удаленной работы</p></Card>
				<Card
					class="skillcard"
					><p>Я мотивирован на совершенствование своих навыков, постоянно изучаю
					новые технологии в своей сфере деятельности</p></Card>
			</div>
		</div>
	</section>

	<section
		class="w-312.5 flex flex-row items-center justify-between"
		id="WorkExperience"
	>
		<UProgress orientation="vertical" class="h-84" />
		<div>
			<UKbd
				class="workcard w-285 h-84 text-2xl bg-neutral-800 shadow-md shadow-primary-500 rounded-2xl transition-all"
			>
				<div class="w-full h-full">
					<p class="date ml-5 mt-5 mb-15 p-2 text-lg text-primary-500">
						Июль 2020 - Настоящее
					</p>
					<h3 class="p-2 ml-5 font-light text-4xl">
						<NuxtLink
							class="link__icon hover:text-primary-500"
							to="https://kwork.ru/user/fxzleev"
							target="_blank"
							>Фриланс</NuxtLink
						>
					</h3>
					<p class="font-extralight text-lg ml-7 text-primary-500">
						Веб Разработчик
					</p>
					<p class="font-extralight text-lg ml-7 mt-3 mb-5">
						Разработка сайта. Исправление ошибок верстки. Написание простых
						скриптов.
					</p>
				</div>
			</UKbd>
		</div>
	</section>
</template>

<style>
.date {
	width: fit-content;
	padding: 0.5rem;
	border-radius: 0.6rem;
	box-shadow: 0 0 15px 1px rgba(0, 0, 0, 0.2);
}
.link__icon {
	transition: all 0.3s ease;
}
.link__icon::after {
	background-color: white;
  -webkit-mask: url('../assets/img/linkg.svg') no-repeat center / contain;
  mask: url('../assets/img/linkg.svg') no-repeat center / contain;
	height: 0.4em;
	content: ' ';
	margin-left: 0.25em;
	width: 0.4em;
	transition: all 0.3s ease;
}
.link__icon:hover::after {
	background-color: var(--ui-color-primary-500)
}
</style>
