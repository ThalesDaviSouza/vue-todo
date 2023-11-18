<template>
  <div class="about">
    <div>
      <h1>Vue todos</h1>
      <p>
        Vue Todos is a CRUD tracking application created for a Vue 3
        Crash Course by Thales Davi
      </p>
      <p>
        Track your daily task's using this todo tracker with abilities to 
        save, complete, edit & delete todos.
      </p>
    </div>
  </div>
</template>

<style lang="scss">
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;

    div {
      h1 {text-align: center;}
      p {
        margin: 10px;
      }
    }
  }
}
</style>
