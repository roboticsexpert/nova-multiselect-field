<template>
  <span class="multiselect__tag" v-on:mousedown.prevent>
    <span v-html="option.label"/>
    <i class="multiselect__tag-icon" @click="remove(option)"></i>
  </span>
</template>

<script>
export default {
  props: ['option', 'remove'],
};
</script>
