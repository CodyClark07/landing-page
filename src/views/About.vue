 <template>
  <div class="about container-fluid bg-image">
    <div class="row justify-content-center bg-image">
      <div class="col-12 col-md-6 fade-in">
        <img src="@/assets/profile.jpg" class="img-thumbnail profile" />
      </div>
      <div class="col-12 col-md-6 mt-2 fade-in align-self-center">
        <p class="text-white bg-gradient">
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
    </div>
    <div class="row">
      <div id="div1" class="col-1">
        <img
          src="https://www.freeiconspng.com/uploads/w3c-html5-logo-0.png"
          class="icon"
        />
      </div>

      <div id="div1" class="col-1 mt-5">
        <img
          src="https://img2.pngio.com/filecss3svg-wikimedia-commons-css-logo-png-1200_1682.png"
          class="icon"
        />
      </div>

      <div id="div1" class="col-1">
        <img
          src="https://www.freepnglogos.com/uploads/javascript/javascript-wysiwyg-editor-and-reusable-assets-coherent-editor-5.png"
          class="icon"
        />
      </div>

      <div id="div1" class="col-1 mt-5">
        <img
          src="https://3lhowb48prep40031529g5yj-wpengine.netdna-ssl.com/wp-content/uploads/2019/10/logo-vuejs-min.png"
          class="icon"
        />
      </div>

      <div id="div1" class="col-1">
        <img
          src="https://seeklogo.com/images/C/c-sharp-c-logo-02F17714BA-seeklogo.com.png"
          class="icon"
        />
      </div>

      <div id="div1" class="col-1 mt-5">
        <img
          src="https://cdn.auth0.com/blog/postman-integration/logo.png"
          class="icon"
        />
      </div>

      <div id="div1" class="col-1">
        <img
          src="https://infinapps.com/wp-content/uploads/2018/10/mongodb-logo.png"
          class="icon"
        />
      </div>
      <div id="div1" class="col-1 mt-5">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ee/.NET_Core_Logo.svg/1200px-.NET_Core_Logo.svg.png"
          class="icon"
        />
      </div>
      <div id="div1" class="col-1">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/590px-Node.js_logo.svg.png"
          class="icon"
        />
      </div>
      <div id="div1" class="col-1 mt-5">
        <img
          src="https://cdn.worldvectorlogo.com/logos/mysql-7.svg"
          class="icon"
        />
      </div>
      <div id="div1" class="col-1">
        <img
          src="https://3di-info.com/wp-content/uploads/2017/12/3di-casestudy-600x401-auth0.png"
          class="icon"
        />
      </div>
      <!-- <div id="div1" class="col-1 mt-5">
        <img
          src="https://4.bp.blogspot.com/-HrdDNxWpN30/UUobCj5EzsI/AAAAAAAAA4o/Q1B29GzHDoc/s1600/mvc_logo.gif"
          class="icon"
        />
      </div> -->
    </div>
  </div>
</template>


<script>
export default {
  name: "about",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {},
};
</script>


<style scoped>
#div1 {
  -webkit-animation: fadein 3s;
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
.icon {
  height: 5rem;
  width: 5rem;
  margin: 0rem !important;
}
.profile {
  margin-top: 1rem;
  height: 29.5rem;
  width: 23rem;
  background-color: transparent;
}
.align {
  flex-direction: row;
}
.bg-image2 {
  background-image: url("~@/assets/InletWinter.jpeg");
  background-size: cover;
  min-height: 60rem;
  background-repeat: no-repeat;
}
</style>
