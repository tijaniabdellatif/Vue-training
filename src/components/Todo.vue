<template>

<secton class="todoapp">

<header>
    <h1 class="">
        Todos
    </h1>

    <input type="text" class="new-todo" placeholder="Add a todo" />
</header>

  <div class="main">

       <ul class="todo-list">
          <li class="todo">
                  <div class="view">
                      <label> Nom de la tache </label>
                  </div>
          </li>
      </ul>

  </div>
</secton>
    
</template>


<script>

export default {



    data(){

        return {
           todos : [{

               name: 'Task Test',
               completed : false

           }]
        }
    }
}

</script>


<style src="./todos.css">

</style>