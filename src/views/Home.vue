<template>
  <div class="home bg-image"></div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
<style>
.bg-image {
  background-image: url("~@/assets/MossTree.jpeg");
  background-size: cover;
  min-height: 60rem;
  background-repeat: no-repeat;
}
</style>
