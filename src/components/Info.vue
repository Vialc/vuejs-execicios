<template >
  <div>
    <p>Estou trabalhando com as seguintes tecnologias:</p>
    <ul >
      <li v-for="(tech, index) in technologies" :key="index"> {{ tech }} </li>
    </ul>
    <p>For de Lista Usando Objetos</p>
    <ul>
      <li v-for="techO in techObj" :key="techO.id" > {{ techO.framework}} </li>
    </ul>
  </div>
</template>
<script>
  export default {
    name: 'Info',
    data() {
      return {
        technologies: ['Javascript', 'CSS', 'Typescript', 'HTML', 'SCSS'],
        techObj: [ 
          {id: 1, framework: 'Angular'},
          {id: 2, framework: 'ReactJS'},
          {id: 3, framework: 'VueJS'},
        ]
      }
    },
  };
</script>