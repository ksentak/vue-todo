<template>
  <div id="app">
    <Todos/>
  </div>
</template>

<script>
import Todos from './components/Todos'

export default {
  name: 'App',
  components: {
    Todos
  },
  data() {
    return {
      todos: [
        {
          id: 1,
          title: 'Learn Vue',
          completed: false
        },
        {
          id: 2,
          title: 'Optimize portfolio',
          completed: false
        },
        {
          id: 3,
          title: 'Do laundry',
          completed: false
        }
      ]
    }
  }
  
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');

* {
  box-sizing: border-box;
  margin: 0;
  padding:0;
}

body {
  font-family: 'Rubik', sans-serif;
  line-height: 1.4;
}
</style>
