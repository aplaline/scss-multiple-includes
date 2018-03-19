<template>
  <div>
    <button role="button">Click me!</button>
    <input type="text" placeholder="Enter your name" />
  </div>
</template>

<script>
import Vue from 'vue'
import Component from 'vue-class-component'

import './button.scss'
import './input.scss'

@Component({
})
export default class App extends Vue {

}
</script>

<style lang="scss">
</style>
