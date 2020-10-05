<template>
  <div class="home bg-image">
    <div class="row">
      <div class="col-12 mt-2">
        <a
          href="https://drive.google.com/file/d/1hv-fTSX-_9B9q4i0HPvDcz0Um-GkOVm7/view?usp=sharing"
          target="_blank"
        >
          <i
            class="fa fa-file-text-o fa-2x mx-2 text-warning cursor"
            data-toggle="tooltip"
            data-placement="top"
            title="Click to view Resume"
          ></i>
        </a>
        <a href="mailto:cclarkbar7@gmail.com">
          <i
            class="fa fa-envelope-o fa-2x mx-2 text-danger cursor"
            data-toggle="tooltip"
            data-placement="top"
            title="Click to email"
          ></i>
        </a>
        <i
          type="button"
          id="dropdownMenuButton"
          class="dropdown fa fa-phone-square fa-2x mx-2 text-success cursor"
          data-toggle="dropdown"
          aria-haspopup="true"
          aria-expanded="false"
        >
          <div
            class="dropdown-menu bg-warning"
            aria-labelledby="dropdownMenuButton"
          >
            <h3 class="text-center">
              <a href="tel:2089604422"
                ><i
                  class="fa fa-mobile text-success"
                  data-toggle="tooltip"
                  data-placement="top"
                  title="Click to call"
                ></i
              ></a>
            </h3>
            <a class="">
              <h5 class="text-dark text-center">
                <u>Phone</u>
              </h5>
              <h4 class="text-dark text-center">208-960-4422</h4>
            </a>
          </div>
        </i>
        <a href="https://www.linkedin.com/in/codyclark07/" target="_blank">
          <i
            class="fa fa-linkedin-square fa-2x mx-2 text-primary cursor"
            data-toggle="tooltip"
            data-placement="top"
            title="Click to view LinkedIn"
          ></i>
        </a>
        <a href="https://github.com/CodyClark07" target="_blank">
          <i
            class="fa fa-github fa-2x mx-2 text-dark cursor"
            data-toggle="tooltip"
            data-placement="top"
            title="Click to view GitHub"
          ></i>
        </a>
      </div>
    </div>
    <div class="col-12 fade-in">
      <img
        v-if="BwVisible"
        src="@/assets/profile-2.jpg"
        class="img-thumbnail profile"
        @mouseover="BwVisible = !BwVisible"
      />
      <img
        v-if="!BwVisible"
        src="@/assets/profile-3.jpg"
        class="img-thumbnail profile"
        @mouseleave="BwVisible = true"
      />
    </div>
    <div class="row justify-content-center">
      <div class="col-12 col-lg-4 col-md-4 col-sm-4">
        <h1 class="text-white bg-gradient fade-in">Software Developer</h1>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  data() {
    return {
      BwVisible: true,
      cell: "2089604422",
    };
  },
  mounted() {
    $('[data-toggle="tooltip"]').on("click", function () {
      $(this).tooltip("hide");
    });
  },
  components: {},
};
</script>
<style>
.fade-in {
  -webkit-animation: fadein 3s; /* Safari, Chrome and Opera > 12.1 */
  -moz-animation: fadein 3s; /* Firefox < 16 */
  -ms-animation: fadein 3s; /* Internet Explorer */
  -o-animation: fadein 3s; /* Opera < 12.1 */
  animation: fadein 3s;
}
@keyframes fadein {
  from {
    opacity: 0;
    transform: scale(0.5);
  }
  to {
    opacity: 1;
    transform: scale(1);
  }
}
.bg-gradient {
  background: rgb(38, 38, 38);
  background: linear-gradient(
    0deg,
    rgba(38, 38, 38, 0.671) 0%,
    rgba(55, 55, 55, 0.671) 50%,
    rgba(33, 32, 32, 0.671) 100%
  );
}
.profile {
  margin-top: 1rem;
  height: 29.5rem;
  width: 23rem;
  background-color: transparent;
}
.bg-image {
  background-image: url("~@/assets/MossTree.jpeg");
  background-size: cover;
  min-height: 60rem;
  max-height: 50rem;
  background-repeat: no-repeat;
}
</style>
