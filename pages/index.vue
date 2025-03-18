<template>
  <section class="w-312.5" id="About">
    <div class="about w-full flex flex-row justify-between">
      <h1 class="text-2xl w-70">
				<span
        ><span class="text-primary-300">Привет!</span> Меня зовут Игорь. </span
        >Я могу сделать для вас несколько замечательных сайтов.
        <UButton class="mt-10 bg-primary-500" size="xl" to="#Feedback">Давайте Проверим!</UButton>
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
      <div class="mt-2">
        <Cards type="hard"/>
      </div>
    </div>
    <div>
      <h2 class="text-5xl">
        <span class="text-primary-500">Soft </span><span>skills</span>
      </h2>
      <div class="mt-2">
        <Cards type="soft"/>
      </div>
    </div>
  </section>

  <section
      class="w-312.5 flex flex-row items-center justify-center"
      id="WorkExperience"
  >
    <WorkCards/>
  </section>
</template>

<style>
</style>