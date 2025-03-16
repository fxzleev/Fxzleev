<template>

	<section class="w-312.5" id="About">
		<div class="about w-full flex flex-row justify-between">
			<h1 class="text-2xl w-70"><span><span class="text-primary-300">Привет!</span> Меня зовут Игорь. </span>Я могу сделать для вас несколько замечательных сайтов.
			<UButton class="mt-10" size="xl" to="#Feedback">Давайте Проверим!</UButton>
			</h1>
			<div>
				<img class="rounded-2xl shadow shadow-primary-400" src="https://t3.ftcdn.net/jpg/03/18/60/62/360_F_318606217_Hk8jo2MVoI33SQOkYrfOF929J7JgIP0P.jpg">
			</div>
		</div>
	</section>

	<section class="w-312.5 flex flex-row justify-between" id="Skills">
		<div>
			<h2 class="text-5xl">
				<span class="text-primary-300">Hard </span><span>skills</span>
			</h2>
			<div class="mt-2 flex flex-col">
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl transition-all hover:bg-neutral-500">HTML(HTML5), TSX, JSX, VUE</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">CSS (CSS3), SASS (SCSS), Bootstrap, Tailwind, Animations</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">JavaScript (ES6+, OOP), jQuery, TypeScript</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">React, Vue</UKbd>
				<UKbd class="skillcard w-100 h-30 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Redux (Redux Toolkit, Redux Persist), MobX, Vuex, Pinia</UKbd>
				<UKbd class="skillcard w-100 h-30 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">React Hook Form, Axios, React Router, React Query, VeeValidate, Vue Router, Vue Query</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Webpack, Vite</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Jest, Vitest</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">REST API, WebSockets</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">BEM, Feature-Sliced Design, Accessibility, UX</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Git (GitHub, GitLab)</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Figma, Adobe Photoshop</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">CMS 1C-Bitrix, OpenCart, MODX</UKbd>
			</div>
			<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Agile, Waterfall, SCRUM</UKbd>
		</div>
		<div>
			<h2 class="text-5xl">
				<span class="text-primary-300">Soft </span><span>skills</span>
			</h2>
			<div class="mt-2 flex flex-col">
				<UKbd class="skillcard w-100 h-40 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Я умею работать в команде, у меня есть опыт общения с дизайнерами, менеджерами и другими разработчиками</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Я ответственно отношусь к срокам</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Я внимательно отношусь к деталям</UKbd>
				<UKbd class="skillcard w-100 h-30 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Я требователен к качеству своего кода, я следую единому code-style</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">У меня есть навыки time management</UKbd>
				<UKbd class="skillcard w-100 h-40 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Я приветствую конструктивную критику и всегда рад найти новые точки профессионального и личностного роста</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Я знаю, как разрешать конфликтные ситуации</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Я умею правильно передавать мысли, формулировать вопросы</UKbd>
				<UKbd class="skillcard w-100 h-30 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">При необходимости я составляю подробные отчеты о проделанной работе</UKbd>
				<UKbd class="skillcard w-100 h-20 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">У меня есть опыт удаленной работы</UKbd>
				<UKbd class="skillcard w-100 h-40 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl text-center transition-all hover:bg-neutral-500">Я мотивирован на совершенствование своих навыков, постоянно изучаю новые технологии в своей сфере деятельности</UKbd>
			</div>
		</div>
	</section>

	<section class="w-312.5 flex flex-row items-center justify-between" id="WorkExperience">
		<UProgress orientation="vertical" class="h-84" />
		<div>
			<UKbd class="workcard w-285 h-84 text-2xl bg-neutral-800 shadow-2xs shadow-primary-500 rounded-2xl transition-all">
				<div class="w-full h-full">
					<p class="date ml-5 mt-5 mb-15 p-2 text-lg text-primary-500">Июль 2020 - Настоящее</p>
					<h3 class="link__icon p-2 ml-5 font-light text-4xl"><NuxtLink class="transition-all hover:text-primary-500" to="https://kwork.ru/user/fxzleev" target="_blank">Фриланс</NuxtLink></h3>
					<p class="font-extralight text-lg ml-7 text-primary-500">Веб Разработчик</p>
					<p class="font-extralight text-lg ml-7 mt-3 mb-5">Разработка сайта. Исправление ошибок верстки. Написание простых скриптов.</p>
				</div>
			</UKbd>
		</div>
	</section>

</template>

<style>
	.skillcard, .workcard {
		margin: 10px 0;
	}
	.date {
		width: fit-content;
		padding: .5rem;
		border-radius: .6rem;
		box-shadow: 0 0 15px 1px rgba(0,0,0,0.2);
	}
	.link__icon::after {
    background: url(../assets/img/linkg.svg) 50% / contain no-repeat;
    height: 0.4em;
    content: ' ';
    margin-left: .25em;
    width: 0.4em;
	}
</style>