<template>
  <div class="Projects row justify-content-center">
    <div class="col-12 col-md-6 text-white">
      <h3>Bug-Report</h3>
      <p>This app...</p>
      <a href="http://buggreport.herokuapp.com">
        <img
          src="@/assets/Bug-Report.png"
          alt="Bug-Report"
          class="img-fluid rounded border cursor img-size"
        />
      </a>
    </div>
    <div class="col-12 col-md-6 text-white">
      <h3>Kanban</h3>
      <p>This app...</p>
      <a href="https://kanban-app-clone.herokuapp.com/">
        <img
          src="@/assets/Kanban.png"
          alt="Kanban"
          class="img-fluid rounded border cursor img-size"
        />
      </a>
    </div>
    <div class="col-12 col-md-6 text-white">
      <h3>Friendzone</h3>
      <p>This app...</p>
      <a href="https://friendzone-capstone.herokuapp.com">
        <img
          src="@/assets/Friendzone.png"
          alt="Friendzone"
          class="img-fluid rounded border cursor img-size"
        />
      </a>
    </div>
  </div>
</template>


<script>
export default {
  name: "Projects",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {},
};
</script>


<style scoped>
.img-size {
  min-width: 705px;
  min-height: 342px;
  max-width: 705px;
  max-height: 342px;
}
</style>