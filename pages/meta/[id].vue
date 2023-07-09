<script setup>
definePageMeta({
  layout: false
})

const test = useTestUse();


function setLayoutCustom() {
  setPageLayout('custom');
}

</script>
<template>
  <button @click="setLayoutCustom">Click custom</button>
  <p>Meta id: {{ $route.params.id }}</p>
</template>