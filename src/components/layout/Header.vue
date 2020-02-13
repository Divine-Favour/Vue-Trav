<template>
    <header class="header">
        <h1>Todolist</h1>
        <div id="nav">
            <router-link to="/" class="whitel" >Home</router-link> |
            <router-link to="/about">About</router-link>
        </div>
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>  
    #nav {
      padding: 30px;
      text-decoration: none;
    }

    #nav a {
      font-weight: bold;
      color: #ffffff;
    }

    #nav a.router-link-exact-active {
      color: #42b983;
    }

    .header {
        background: #333;
        color: #fff;
        text-align: center;
        padding: 10px;
    }

    .header a {
        color: #fff;
        padding-right: 5px;
    }
</style>