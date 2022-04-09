<template>
  <div>
    <NovoComponente />
    <LifeCycle />
    <Pessoa />
    <Picture />

  </div>

</template>

<script>
  import NovoComponente from './components/NovoComponente.vue';
  import LifeCycle from './components/LifeCycle.vue';
  import Pessoa from './components/Pessoa.vue';
  import Picture from './components/Picture.vue';

  export default {
    name: 'App',
    components: {
      NovoComponente,
      LifeCycle,
      Pessoa,
      Picture,
    },
  };
</script>

<style lang="scss">
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  input:focus {
    box-shadow: none;
    outline: 0;
  }

  a {
    text-decoration: none;
  }

  body {
    font-family: 'Roboto', sans-serif;
    width: 100%;
    height: 100vh;
    background: linear-gradient(
      180deg,
      rgba(234, 91, 12, 0.63) 27.6%,
      rgba(234, 91, 12, 0) 100%
    );
  }
</style>