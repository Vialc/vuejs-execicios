<template>
  <div>
    <h2>Essa é a descrição da pessoa: {{ pessoa }}</h2>
    <Info />
    <Form />
  </div>
</template>
<script>
import Info from './Info.vue'
import Form from './Form.vue';

  export default {
    name: 'Pessoa',
    data() {
      return {
        pessoa: {
          nome: 'Vitor',
          idade: '32',
          sexo: 'masculino',
          profissão: 'programador',
        },
      };
    },
    components: {
        Info,
        Form,
    }
  };
</script>
<style>
</style>