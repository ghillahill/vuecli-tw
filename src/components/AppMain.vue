<template>
  <div class="wrapper">
      <div class="card">
        <h1 class="font-bold text-9xl">Component</h1>
        <h2 class="text-3xl font-bold">
            Using VUE CLI
        </h2>
      </div>
  </div>
</template>

<script>

export default {

}
</script>

<style lang="scss" scoped>
.wrapper{
    @apply flex justify-center items-center h-screen text-center text-emerald-500 bg-gray-50;
}
.card{
    @apply rounded-lg border border-emerald-300 bg-emerald-100 p-10 shadow-lg;

    h2{
       @apply p-5;
    }
}
</style>
