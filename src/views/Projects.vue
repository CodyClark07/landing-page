<template>
  <div class="Projects row justify-content-center">
    <div
      class="col-12 col-lg-8 col-md-6 col-sm-4 text-white text-center mx-auto mt-2"
    >
      <h3>Bug-Report</h3>
      <p>
        Application built with Vue.js, JavaScript and integrated Auth0. Designed
        to allow a user to log individual bug reports. Bugs report created by,
        and the timestamp it was created. Users can also add notes to the bug
        report providing detailed steps towards the bugs resolution.
      </p>
      <a href="http://buggreport.herokuapp.com">
        <img
          src="@/assets/Bug-Report.png"
          alt="Bug-Report"
          class="img-fluid rounded border cursor img-size"
          data-toggle="tooltip"
          data-placement="top"
          title="Click to open"
        />
      </a>
    </div>
    <div
      class="col-12 col-lg-8 col-md-6 col-sm-4 text-white text-center mx-auto mt-2"
    >
      <h3>Kanban</h3>
      <p class="text-center">
        Application built with Vue.js front-end, Node.js back-end and integrated
        Auth0. Variation of a Trello Board to allow users to create and organize
        lists and tasks.
      </p>
      <a href="https://kanban-app-clone.herokuapp.com/">
        <img
          src="@/assets/Kanban.png"
          alt="Kanban"
          class="img-fluid rounded border cursor img-size mt-4"
          data-toggle="tooltip"
          data-placement="top"
          title="Click to open"
        />
      </a>
    </div>
    <div
      class="col-12 col-lg-8 col-md-6 col-sm-4 text-white text-center mt-2 mb-2"
    >
      <h3>Friendzone</h3>
      <p>
        Application built with Vue.js, Node.js, JavaScript and API's, along with
        Auth0. Product owner, maintained Scrum principles. This App was designed
        to be a social media platform for gamers across all consoles. Where they
        can follow their favorite games and chat with other gamers, as well as
        maintain a ranking system based off of a Rep score.
      </p>
      <a href="https://friendzone-capstone.herokuapp.com">
        <img
          src="@/assets/Friendzone.png"
          alt="Friendzone"
          class="img-fluid rounded border cursor img-size"
          data-toggle="tooltip"
          data-placement="top"
          title="Click to open"
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
  mounted() {
    $('[data-toggle="tooltip"]').on("click", function () {
      $(this).tooltip("hide");
    });
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