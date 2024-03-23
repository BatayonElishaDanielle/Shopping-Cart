<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}

body {
  margin: 0;
}

button {
  font: inherit;
  cursor: pointer;
  background-color: rgba(110, 147, 239, 0.991);
  color: rgb(242, 239, 239);
  border: 1px solid ;
  padding: 0.4rem 1.6rem;
  border-radius: 20px;
  margin-bottom: 10px;


}

</style>
