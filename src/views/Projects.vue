<template>
  <div class="Projects row justify-content-center">
    <div class="col-12 text-white text-center mx-auto mt-2">
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
          class="img-fluid rounded border cursor img-size shake"
          data-toggle="tooltip"
          data-placement="top"
          title="Click to open"
        />
      </a>
      <a href="https://github.com/CodyClark07/Bug-Report">
        <img
          src="https://image.flaticon.com/icons/png/512/25/25231.png"
          alt="GitHub"
          class="rounded border cursor shake github ml-2"
          data-toggle="tooltip"
          data-placement="top"
          title="Click for source code"
        />
      </a>
    </div>
    <div class="col-12 text-white text-center mx-auto mt-2">
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
          class="img-fluid rounded border cursor img-size mt-4 shake"
          data-toggle="tooltip"
          data-placement="top"
          title="Click to open"
        />
      </a>
      <a href="https://github.com/JohnDLund/Kanban-Group-Project">
        <img
          src="https://image.flaticon.com/icons/png/512/25/25231.png"
          alt="GitHub"
          class="rounded border cursor shake github ml-2"
          data-toggle="tooltip"
          data-placement="top"
          title="Click for source code"
        />
      </a>
    </div>
    <div class="col-12 text-white text-center mt-2 mb-2">
      <h3>Friendzone</h3>
      <p class="">
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
          class="img-fluid rounded border cursor img-size shake"
          data-toggle="tooltip"
          data-placement="top"
          title="Click to open"
        />
      </a>
      <a href="https://github.com/HarrisonWheeler/friendzone-capstone">
        <img
          src="https://image.flaticon.com/icons/png/512/25/25231.png"
          alt="GitHub"
          class="rounded border cursor shake github ml-2"
          data-toggle="tooltip"
          data-placement="top"
          title="Click for source code"
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
@keyframes shake {
  0% {
    transform: translate(1px, 1px) rotate(0deg);
  }
  10% {
    transform: translate(-1px, -2px) rotate(-1deg);
  }
  20% {
    transform: translate(-3px, 0px) rotate(1deg);
  }
  30% {
    transform: translate(3px, 2px) rotate(0deg);
  }
  40% {
    transform: translate(1px, -1px) rotate(1deg);
  }
  50% {
    transform: translate(-1px, 2px) rotate(-1deg);
  }
  60% {
    transform: translate(-3px, 1px) rotate(0deg);
  }
  70% {
    transform: translate(3px, 1px) rotate(-1deg);
  }
  80% {
    transform: translate(-1px, -1px) rotate(1deg);
  }
  90% {
    transform: translate(1px, 2px) rotate(0deg);
  }
  100% {
    transform: translate(1px, -2px) rotate(-1deg);
  }
}
.shake:hover {
  /* Start the shake animation and make the animation last for 0.5 seconds */
  -webkit-animation-name: shake;
  -webkit-animation-duration: 0.5s;

  /* When the animation is finished, start again */
  -webkit-animation-iteration-count: infinite;
}
.img-size {
  min-width: 705px;
  min-height: 342px;
  max-width: 705px;
  max-height: 342px;
}
.github {
  min-width: 50px;
  min-height: 50px;
  max-width: 50px;
  max-height: 50px;
}
</style>