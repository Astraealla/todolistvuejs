<template>
  <div>
    <h1>To Do List</h1>

    <h2>Nom de la Liste</h2>

      <div class="container">
        <ul>
          <li>Nom de la tâche</li>
          <li>Nom de la tâche</li>
          <li>Nom de la tâche</li>
          <li>Nom de la tâche</li>
        </ul>
      </div>
  </div>
</template>

<script>
import List from './components/List.vue'
import Tasks from './components/Tasks.vue'

export default {
  name: '',
  components: {
   
  }
}
</script>

<style>
h1{
  border: 1px solid black;
  text-align: center;
  color: blue;
  width: 500px;
  margin-left: 350px; 
}

h2{
  border: 1px dotted blue;
  color: maroon;
  text-align: center;
  width: 300px;
}

.container{
  border: 1px dotted blue;
  color: red;
  width: 300px;
}
</style>
