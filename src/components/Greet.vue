<template>
  <h2>Hello {{name}} from Greet component {{ heroName}}</h2>
</template>

<script>
export default {
    meno: "Greet",
    props: ['name', 'heroName']
};
</script>

<style scoped>

</style>