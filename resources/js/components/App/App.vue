<template>
  <div>
    <div class="titulo">Ejemplo</div>
    <button @click="count++">
        You clicked me {{ count }} times.
    </button>
  </div>
</template>

<script>
const App =  {
  name: "app",
  data() {
    return {
      count: 0
    }
  },
}

export default App;
</script>

<style>
.titulo {
  padding-bottom: 15px;
}
</style>
