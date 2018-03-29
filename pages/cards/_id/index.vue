<template>
  <section class="single-card">
      <h1>{{ $route.params.id }} </h1>
      <div>
          <img src="" alt="">
      </div>
      <p>The card description</p>
  </section>
</template>

<style scoped>
.single-card {
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 30px;
}
</style>

