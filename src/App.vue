<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <h1>Hello this is a test</h1>
    <router-view/>
  </div>
</template>

<style lang="scss">
  @import "assets/sass/main";
</style>
