<template>
  <div class="home">
    <div class="row bg-image justify-content-center">
      <div
        class="col-12 col-lg-4 col-md-5 col-sm-6 mt-2 text-center fade-in"
        data-aos="fade-up"
      >
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
        <!-- <img
          v-if="BwVisible"
          src="@/assets/profile-2.jpg"
          class="img-thumbnail profile"
          @mouseover="BwVisible = !BwVisible"
        /> -->
        <img src="@/assets/profile-3.jpg" class="profile rounded shadow-lg" />
        <h1 class="text-white text-center">Software Developer</h1>
      </div>
    </div>
    <div id="about" class="row bg-image2">
      <div
        data-aos="fade-right"
        data-aos-offset="300"
        data-aos-easing="ease-in-sine"
        class="col-12 col-lg-6 align-self-center"
      >
        <h3 class="">A Little About Me</h3>
      </div>
      <div
        data-aos="fade-left"
        data-aos-offset="300"
        data-aos-easing="ease-in-sine"
        class="col-12 col-md-6 align-self-center"
      >
        <img src="@/assets/profile.jpg" class="profile rounded shadow-lg" />
      </div>
      <div
        data-aos="fade-up"
        data-aos-offset="200"
        data-aos-easing="ease-in-sine"
        class="col-12 col-lg-6 col-md-6 align-self-center"
      >
        <p class="text-white bg-gradient mr-2 ml-2 text-center shadow-lg">
          "Don't save what you can do today, for tomorrow" Was a saying my
          father told me numerous times while growing up, and has stuck with me
          since. I have always been GO-GO-GO since I was a kid and it overlapped
          into my work ethic. For 16 years I worked in the family business,
          starting as a fish processor, after several years of maintaining the
          fish processing plant, I decided to take on a bigger role of store
          management and product development. But as time moved on I realized I
          yearned for more mental stimulation and learning. I was always working
          in technology, from building inventory databases in excel and
          formatting Point of Sale systems, to using GIS and radio telemetry
          along with population dynamics for data analysis using excel and other
          software. Realizing how much I enjoyed coding and its ability to not
          only mentally stimulate me but provide me with endless educational
          opportunities, I felt I finally found where I was meant to be.
        </p>
      </div>
      <div
        data-aos="zoom-in-left"
        class="col-12 col-lg-6 col-md-6 align-self-center"
      >
        <img
          src="https://www.freeiconspng.com/uploads/w3c-html5-logo-0.png"
          class="icon"
        />
        <img
          src="https://img2.pngio.com/filecss3svg-wikimedia-commons-css-logo-png-1200_1682.png"
          class="icon"
        />
        <img
          src="https://www.freepnglogos.com/uploads/javascript/javascript-wysiwyg-editor-and-reusable-assets-coherent-editor-5.png"
          class="icon"
        />
        <img
          src="https://3lhowb48prep40031529g5yj-wpengine.netdna-ssl.com/wp-content/uploads/2019/10/logo-vuejs-min.png"
          class="icon"
        />
        <img
          src="https://seeklogo.com/images/C/c-sharp-c-logo-02F17714BA-seeklogo.com.png"
          class="icon"
        />
        <img
          src="https://cdn.auth0.com/blog/postman-integration/logo.png"
          class="icon"
        />
        <img
          src="https://infinapps.com/wp-content/uploads/2018/10/mongodb-logo.png"
          class="icon"
        />
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ee/.NET_Core_Logo.svg/1200px-.NET_Core_Logo.svg.png"
          class="icon"
        />
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/590px-Node.js_logo.svg.png"
          class="icon"
        />
        <img
          src="https://cdn.worldvectorlogo.com/logos/mysql-7.svg"
          class="icon"
        />
        <img
          src="https://3di-info.com/wp-content/uploads/2017/12/3di-casestudy-600x401-auth0.png"
          class="icon"
        />
        <img
          src="https://4.bp.blogspot.com/-HrdDNxWpN30/UUobCj5EzsI/AAAAAAAAA4o/Q1B29GzHDoc/s1600/mvc_logo.gif"
          class="icon"
        />
      </div>
    </div>
    <div id="projects" class="row justify-content-center bg-image3">
      <div
        data-aos="fade-up"
        data-aos-duration="3000"
        class="col-12 col-lg-6 col-md-6 align-self-center"
      >
        <div
          class="card bg-gradient border shadow-lg text-white text-center h-25 p-4"
          style="overflow: auto"
        >
          <h1 class="text-warning"><b>MY PROJECTS</b></h1>
          <div>
            <h3><u>Friendzone</u></h3>
            <p class="">
              Application built with Vue.js, Node.js, JavaScript and API's,
              along with Auth0. Product owner, maintained Scrum principles. This
              App was designed to be a social media platform for gamers across
              all consoles. Where they can follow their favorite games and chat
              with other gamers, as well as maintain a ranking system based off
              of a Rep score.
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
          <hr class="rounded" />
          <div>
            <h3><u>Kanban</u></h3>
            <p class="text-center">
              Application built with Vue.js front-end, Node.js back-end and
              integrated Auth0. Variation of a Trello Board to allow users to
              create and organize lists and tasks.
            </p>
            <a href="https://kanban-app-clone.herokuapp.com/">
              <img
                src="@/assets/Kanban.png"
                alt="Kanban"
                class="img-fluid rounded border cursor img-size shake"
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
          <hr class="rounded" />
          <div>
            <h3><u>Bug-Report</u></h3>
            <p class="">
              Application built with Vue.js, JavaScript and integrated Auth0.
              Designed to allow a user to log individual bug reports. Bugs
              report created by, and the timestamp it was created. Users can
              also add notes to the bug report providing detailed steps towards
              the bugs resolution.
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
        </div>
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
.icon {
  height: 5rem;
  width: 5rem;
  margin: 0rem !important;
}
hr.rounded {
  border-top: 8px solid #bbb;
  border-radius: 5px;
}
.h-25 {
  min-height: 40rem;
  max-height: 40rem;
  /* min-width: 50rem; */
  max-width: 50rem;
}
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

  background-color: transparent;
}
.bg-image {
  background-image: url("~@/assets/MossTree.jpeg");
  background-size: cover;
  min-height: 60rem;
  max-height: 50rem;
  background-repeat: no-repeat;
}
.bg-image2 {
  background-image: url("~@/assets/InletWinter.jpeg");
  background-size: cover;
  min-height: 60rem;
  background-repeat: no-repeat;
}
.bg-image3 {
  background-image: url("~@/assets/seward.jpeg");
  background-size: cover;
  min-height: 60rem;
  background-repeat: no-repeat;
}
hr.rounded {
  border-top: 8px solid #bbb;
  border-radius: 5px;
}

/* .img-size {
  min-width: 660px;
  min-height: 342px;
} */
.github {
  min-width: 50px;
  min-height: 50px;
  max-width: 50px;
  max-height: 50px;
}
</style>
