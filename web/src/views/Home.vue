<template lang="pug">
.home
	img(src='../assets/logo.png')
	HelloWorld(msg='Welcome to Your Vue.js App')
	ui-button(title="hello")
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import {UI} from '@leonardpauli/lp-vue-lib'

export default {
	name: 'Home',
	components: {
		HelloWorld, ...UI,
	},
}
</script>
