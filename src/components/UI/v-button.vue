<template>
  <button class="btn">
    <slot></slot>
  </button>
</template>

<script>
import {defineComponent} from "vue";

export default defineComponent({
  name: 'v-button'
});
</script>

<style lang="stylus" scoped>
@import '@/App.vars.styl';
@import '@/App.mixins.styl';

button
  padding 10px 20px
  background $block-sec
  border-radius 1px
  border none
  cursor pointer
  color $text-third

</style>
