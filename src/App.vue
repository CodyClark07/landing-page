<template>
  <div id="app" class="">
    <navbar />
    <transition name="fade">
      <router-view :key="$route.fullPath" />
    </transition>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar";
export default {
  name: "App",
  mounted() {
    setTimeout(() => window.scrollTo(0, 0), 75);
  },
  components: {
    Navbar,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  overflow-x: hidden;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.4s ease-out;
}

.fade-enter,
.fade-leave-to {
  opacity: 0;
}
::-webkit-scrollbar {
  display: none;
}
</style>
