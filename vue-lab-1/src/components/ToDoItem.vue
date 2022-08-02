<template> 
    <div id="todo-item">
        <span :style="color">To Do Item</span>
        <button @click="done">DONE</button>
    </div>
</template>

<script>
export default {
  methods: {
    done () {
      this.color = 'color:blue'
    }
  },

  data() {
    return {
      color: 'color:red'
    }
  }
  
}
</script>

<style>
#todo-list {
  text-align: left;
}

  #todo-item {
    color:blue !important
  }

 li {
  list-style: none;
 }

</style>