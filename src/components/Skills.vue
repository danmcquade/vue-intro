<template>
  <div class='skills-section'>
    <ul>
      <li v-for="skill in skills">{{skill.skillName}}</li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: 'Skills',
    data () {
      return {
        skills: [
          {skillName: 'JavaScript'},
          {skillName: 'HTML/CSS'},
          {skillName: 'Ruby'},
          {skillName: 'Ruby on Rails'},
          {skillName: 'React'}
        ]
      }
    }
  }
</script>
<style scoped>
  .skills-section li {
    display: inline-block;
    margin: 5px;
    padding: 10px;
    background: #dddddd;
    border-radius: 15px;
    font-family: 'Arial-Black';
    background: #3498db;
    color: #ffffff;
  }
  .skills-section ul {
    margin: 0;
    padding: 0;
  }
</style>
