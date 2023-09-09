<template>
    <div>
        <h1>{{ message }}</h1>
        <h4>{{ message2 }}</h4>
    </div>
</template>

<script setup>
import { ref } from 'vue'

defineProps({
  message: String,
  message2: String,
})
</script>

<style>
#app{
    text-align: center;
    color: blueviolet;
}
</style>
