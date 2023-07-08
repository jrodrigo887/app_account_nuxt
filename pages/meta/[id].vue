<script setup>
definePageMeta({
  layout: false
})

function setLayoutCustom() {
  setPageLayout('custom');
}

</script>
<template>
  <button @click="setLayoutCustom">Click custom</button>
  <p>Meta id: {{ $route.params.id }}</p>
</template>