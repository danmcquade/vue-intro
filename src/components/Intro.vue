<template>
  <div class='intro'>
    <div class='intro-header'>
      <img src='../assets/dan.jpg' v-on:click='greet'>
      <h1>{{user.firstName}} {{user.lastName}}</h1>
      <h3 v-text='intro'></h3>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Intro',
    data () {
      return {
        title: 'Dan McQuade',
        user: {
          firstName: 'Dan',
          lastName: 'McQuade'
        },
        intro: 'A Washington, DC-based Full-Stack Web Developer'
      }
    },
    methods: {
      greet: () => {
        alert('Hello')
      }
    }
  }
</script>

<style scoped>
  h1 {
    font-family: 'Helvetica';
  }
  .intro-header img {
    max-width: 250px;
    border-radius: 250px;
    box-shadow: 0px 0px 5px rgba(0,0,0,0.7);
  }
  .intro-header img:hover {
    box-shadow: 0px 0px 5px rgba(0,0,0,1);
  }

</style>
