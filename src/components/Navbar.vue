<template>
  <nav
    class="navbar sticky-top container-fluid navbar-expand-lg navbar-light bg-light"
  >
    <a class="navbar-brand text-warning my-2 py-2 ml-2">
      <router-link :to="{ name: 'Home' }" class="nav-link"
        >Cody Clark</router-link
      >
    </a>

    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarText"
      aria-controls="navbarText"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav mr-auto">
        <li>
          <a href="#about">About Me</a>
        </li>
        <li>
          <a href="#projects">My Projects</a>
        </li>
        <!-- <li class="nav-item" :class="{ active: $route.name == 'Home' }">
          <router-link :to="{ name: 'Home' }" class="nav-link"
            >Home</router-link
          >
        </li> -->
        <!-- <li class="nav-item" :class="{ active: $route.name == 'About' }">
          <router-link class="nav-link" :to="{ name: 'About' }"
            >About</router-link
          >
        </li>
        <li class="nav-item" :class="{ active: $route.name == 'Projects' }">
          <router-link class="nav-link" :to="{ name: 'Projects' }"
            >Projects</router-link
          >
        </li> -->
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "navbar",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
