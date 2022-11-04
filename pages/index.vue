<template>
  <div>
    {{ data.data.name }}
  </div>
</template>

<script setup>
const { data } = await useFetch('https://api.upy.moe/user/info/id/2')
</script>