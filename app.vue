<template>
	<div class="bg-gray-50">
		<NuxtLayout>
			<NuxtPage />
		</NuxtLayout>
	</div>
</template>
<template>
  <div
    :class="{
      'theme-light': !darkMode,
      'theme-dark': darkMode,
    }"
    class="h-screen bg-themeBackground p-5"
  >
    <h1 class="text-themeText">Nuxt 3 Tailwind Dark Mode Demo</h1>
    <Toggle v-model="darkMode" off-label="Light" on-label="Dark" />
  </div>
</template>
