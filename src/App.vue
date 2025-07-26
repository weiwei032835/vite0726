<script setup>
  import { ref } from 'vue';

  const num = ref(2);
  const clickMe = () => {
    num.value++;
  };
</script>


<template>
  {{num}}
  <button type="button" v-on:click="clickMe">點我</button>
</template>

