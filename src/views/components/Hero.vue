<template>
  <div>
    <div class="position-relative">
      <!-- shape Hero -->
      <section class="section-shaped my-0">
        <div
          style="right: -3%; top: 10%"
          class="shape shape-style-1 shape-primary shape-skew"
        >
          <img
            id="bg-sec1"
            src="img/brand/image/bg-tran/Group 1154_0.png"
            alt="logo"
          />
        </div>
        <div class="shape-container">
          <div class="container">
            <div class="row row-sec1" style="align-items: center">
              <div class="col-lg-6">
                <div>
                  <h2 class="hero-title text-dark">
                    <span> Full-Service Positioning Platform Solutions</span>
                  </h2>
                  <p class="lead text-dark">
                    Location-based solutions increase quality, productivity and
                    better environment.
                  </p>
                  <div class="btn-wrapper">
                    <base-button
                      tag="a"
                      href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
                      class="mb-3 mb-sm-0 button-css"
                    >
                      Wave Me
                    </base-button>
                  </div>
                </div>
              </div>
              <div class="col-md-6">
                <img
                  style="margin: 0 5%"
                  src="img/brand/image/Group 116.png"
                  class="card-img-top"
                />
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- 1st Hero Variation -->
    </div>

    <section class="section section-shaped my-0">
      <div class="shape shape-style-11 shape-skew bg-sec2">
        <img
        
          src="img/brand/image/bg-tran/Group 1155.png"
          alt="logo" class="img-sec3"
        />
      </div>
      <div class="container py-0">
        <div class="row row-grid align-items-center">
          <div class="col-md-5 order-lg-1 ml-lg-auto">
            <div class="position-relative pl-md-5">
              <img
                style="width: 279px; height: 484.36px"
                src="img/brand/image/4.png"
                class="img-center img-fluid"
              />
            </div>
          </div>
          <div class="col-lg-7 order-lg-2">
            <div class="ml-3 mr-5">
              <h4 class="display-3 text-dark">
                Full-Service Platform Solutions for Enterprises
              </h4>
              <p class="text-dark">
                Set have great you male grass yielding an yielding first their
                you're have called the abundantly fruit were man.
              </p>
            </div>
            <div class="row row-grid mt-5 ml-1 mr-1">
              <div class="col-lg-4 col-md-4 col-sm-4 al-center">
                <div class="bg-card-1 card-sec2 p-1">
                  <img
                    class="mt-2"
                    style="width: 88px; height: 88px"
                    src="img/brand/image/Group 354.png"
                  />
                  <div>
                    <h6 style="font-size: 13px" class="text-white mt-3">
                      Certified in compliance with STCW standards.
                    </h6>
                  </div>
                </div>
              </div>
              <div class="col-lg-4 col-md-4 col-sm-4 al-center">
                <div class="bg-card-2 card-sec2 p-1">
                  <img
                    class="mt-2"
                    style="width: 88px; height: 88px"
                    src="img/brand/image/Group 354.png"
                  />
                  <div>
                    <h6 style="font-size: 13px" class="text-white mt-3">
                      Medically fit for service.
                    </h6>
                  </div>
                </div>
              </div>
              <div class="col-lg-4 col-md-4 col-sm-4 al-center">
                <div class="bg-card-3 card-sec2 p-1">
                  <img
                    class="mt-2"
                    style="width: 88px; height: 88px"
                    src="img/brand/image/Group 355.png"
                  />
                  <div>
                    <h6 style="font-size: 13px" class="text-white mt-3">
                      Adequately experienced to operate in assigned vessels.
                    </h6>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section section-shaped my-0">
      <div class="row row-grid bg-a align-items-center">
        <div class="col-md-12 col-lg-5 col-sm-12 order-lg-1 ml-lg-auto">
          <div class="position-relative pl-md-5">
            <!-- <h4 class="display-3 text-dark">
                Full-Service Platform Solutions for Enterprises
              </h4> -->
            <h2 class="hero-title-2 text-dark">
              <span> Full-Service Platform Solutions for Enterprises</span>
            </h2>
          </div>
        </div>
        <div style="margin-top: 0" class="col-lg-7 order-lg-2">
          <div class="row row-grid ml-3 mr-5">
            <div v-for="i in section3_1" :key="i" class="col-lg-4 col-sm-4  al-center">
              <img
                style="width: 95px; height: 95px"
                src="img/brand/image/bg-tran/12.png"
              />
              <h5 class="text-brown mt-3">{{ i.name }}</h5>
              <p class="text-white-to-brown mt-3">
                {{ i.detail }}
              </p>
            </div>
          </div>
          <div class="row row-grid mt-1 ml-3 mr-5">
            <div v-for="i in section3_2" :key="i" class="col-lg-4 col-sm-4  al-center">
              <img
                style="width: 95px; height: 95px"
                src="img/brand/image/bg-tran/12.png"
              />
              <h5 class="text-brown mt-3">{{ i.name }}</h5>
              <p class="text-white-to-brown mt-3">
                {{ i.detail }}
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container">
        <div class="row justify-content-center text-center mb-lg">
          <div class="col-lg-8">
            <h2 class="display-3">Our Featured Works</h2>
          </div>
        </div>

        <div class="row">
          <div class="col-md-6 col-lg-4 mb-5 mb-lg-4">
            <div class="px-4">
              <img
                v-lazy="'img/theme/team-2-800x800.jpg'"
                class="img-center img-fluid shadow shadow-lg--hover"
                style="width: 250px"
              />
            </div>
          </div>
          <div class="col-md-6 col-lg-4 mb-5 mb-lg-4">
            <div class="px-4">
              <img
                v-lazy="'img/theme/team-3-800x800.jpg'"
                class="img-center img-fluid shadow shadow-lg--hover"
                style="width: 250px"
              />
            </div>
          </div>
          <div class="col-md-6 col-lg-4 mb-5 mb-lg-4">
            <div class="px-4">
              <img
                v-lazy="'img/theme/team-4-800x800.jpg'"
                class="img-center img-fluid shadow shadow-lg--hover"
                style="width: 250px"
              />
            </div>
          </div>
          <div class="col-md-6 col-lg-4 mb-5 mb-lg-4">
            <div class="px-4">
              <img
                v-lazy="'img/theme/team-2-800x800.jpg'"
                class="img-center img-fluid shadow shadow-lg--hover"
                style="width: 250px"
              />
            </div>
          </div>
          <div class="col-md-6 col-lg-4 mb-5 mb-lg-4">
            <div class="px-4">
              <img
                v-lazy="'img/theme/team-3-800x800.jpg'"
                class="img-center img-fluid shadow shadow-lg--hover"
                style="width: 250px"
              />
            </div>
          </div>
          <div class="col-md-6 col-lg-4 mb-5 mb-lg-4">
            <div class="px-4">
              <img
                v-lazy="'img/theme/team-4-800x800.jpg'"
                class="img-center img-fluid shadow shadow-lg--hover"
                style="width: 250px"
              />
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section section-shaped my-0 overflow-hidden">
      <div class="shape shape-style-3 bg-b shape-skew">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
      <div class="container pb-100">
        <div class="row text-center justify-content-center">
          <div class="col-lg-10">
            <h2 class="display-3 mt-3 text-brown">Free White Papers</h2>
            <p class="lead mb-3 text-white">
              Would you like to learn more about indoor positioning, sensor
              technology, and possible applications? The infsoft whitepaper
              offers a comprehensive overview including industry highlights and
              is accessible for free, without registration.
            </p>
            <base-button
              tag="a"
              href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
              class="mb-1 mb-sm-0"
            >
              Download Now
            </base-button>
            <base-button
              tag="a"
              type="secondary"
              href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
              class="mb-1 mb-sm-0"
            >
              Discover Our White Paper
            </base-button>
          </div>
        </div>
      </div>
    </section>

    <section class="section mt-5">
      <div class="container">
        <div class="row justify-content-center text-center">
          <div class="col-lg-8 mb-5">
            <h2 class="display-3">Sponser</h2>
          </div>
        </div>

        <div class="img-spon">
          <img
            src="img/brand/image/bg-tran/SC line.png"
            class="img-fluid"
            style="width: 200px"
          />
          <img
            src="img/brand/image/bg-tran/KMITL eng.png"
            class="img-fluid"
            style="width: 200px"
          />
          <img
            src="img/brand/image/bg-tran/MH.png"
            class="img-fluid"
            style="width: 200px"
          />
          <img
            src="img/brand/image/bg-tran/KRIS - LOGO.png"
            class="img-fluid"
            style="width: 200px"
          />
          <img
            src="img/brand/image/bg-tran/SiBB.png"
            class="img-fluid"
            style="width: 200px"
          />
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <div class="row justify-content-center text-center mb-lg">
          <div class="col-lg-8">
            <h2 class="display-3">Latest Use Cases & Blog Posts</h2>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
            <div class="px-4">
              <img
                v-lazy="
                  'img/brand/image/bg-tran/infsoft-use-case_Asset-Tracking-Manufacturing.png'
                "
                class="img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <span class="d-block mb-1"
                    >Asset Tracking in a Manufacturing Facility</span
                  >
                </h5>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
            <div class="px-4">
              <img
                v-lazy="
                  'img/brand/image/bg-tran/infsoft-use-case_Demand-Oriented-Cleaning-of-Workspaces.png'
                "
                class="img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <span class="d-block mb-1"
                    >Demand-Oriented Cleaning of Workspaces</span
                  >
                </h5>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
            <div class="px-4">
              <img
                v-lazy="'img/brand/image/bg-tran/Scroll Group 3.png'"
                class="img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <span class="d-block mb-1"
                    >Occupancy Analytics in Offices</span
                  >
                </h5>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
            <div class="px-4">
              <img
                v-lazy="'img/brand/image/bg-tran/Scroll Group 4.png'"
                class="img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <span class="d-block mb-1">Temperature Monitoring</span>
                </h5>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section section-lg">
      <div class="container">
        <div class="row row-grid align-items-center">
          <div class="col-md-7 order-md-2 order-ms-1">
            <form class="row g-3">
              <div class="col-md-6">
                <base-input
                  alternative
                  placeholder="Your name"
                  addon-left-icon="ni ni-single-02"
                ></base-input>
              </div>
              <div class="col-md-6">
                <base-input
                  alternative
                  placeholder="Email address"
                  addon-left-icon="ni ni-email-83"
                >
                </base-input>
              </div>
              <div class="col-12 mt-4">
                <base-input
                  alternative
                  placeholder="Phone number"
                  addon-left-icon="ni ni-mobile-button"
                ></base-input>
              </div>
              <div class="col-12 mt-4">
                <base-input class="mb-4">
                  <textarea
                    class="form-control form-control-alternative"
                    name="name"
                    rows="4"
                    cols="80"
                    placeholder="Type a message..."
                  ></textarea>
                </base-input>
              </div>
              <div class="col-md-8 mt-4">
                Use Bootstrap’s custom button styles for actions in forms,
                dialogs, and more with support for multiple sizes, states, and
                more.
              </div>
              <div class="col-md-4 mt-4">
                <button type="submit" class="btn btn-primary button-css">
                  Send Message
                </button>
              </div>
            </form>
          </div>
          <div class="col-md-5 order-md-1 order-ms-2">
            <div class="pr-md-5">
              <h3>Visit our studio at</h3>
              <p>
                3280 Thompson Drive Oakland <br />
                CA California 94621
              </p>
              <h3 class="mt-5">Massage us</h3>
              <p>
                mike101050@omtecha.com <br />
                (+66) 510-430-6581
              </p>
              <div class="mt-5">
                <base-button
                  tag="a"
                  href="#"
                  type="info"
                  icon="fa fa-twitter"
                  rounded
                  icon-only
                ></base-button>
                <base-button
                  tag="a"
                  href="#"
                  type="info"
                  icon="fa fa-facebook"
                  rounded
                  icon-only
                ></base-button>
                <base-button
                  tag="a"
                  href="#"
                  type="info"
                  icon="fa fa-dribbble"
                  rounded
                  icon-only
                ></base-button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "home",
  components: {},
  data: () => ({
    section3_1: [
      {
        id: 1,
        name: "Imployee Tracking",
        detail:
          "Create new user experiences with location-aware AR navigation and virtual content.",
      },
      {
        id: 2,
        name: "Wayfinding & POIs",
        detail:
          "Enable navigation from point A to point B and add metadata to your indoor maps.",
      },
      {
        id: 3,
        name: "Asset Tracking",
        detail:
          "Enable navigation from point A to point B and add metadata to your indoor maps.",
      },
    ],
    section3_2: [
      {
        id: 4,
        name: "Augmented Reality",
        detail:
          "Set have great you male grass yielding an yielding first their you're have called the abundantly fruit were man",
      },
      {
        id: 5,
        name: "Geofencing",
        detail:
          "Show relevant content at the right time in the right place and adapt your app’s logic based on device's location.",
      },
      {
        id: 6,
        name: "Wayfinding & POIs",
        detail:
          "Enable navigation from point A to point B and add metadata to your indoor maps.",
      },
    ],
  }),
};
</script>
<style scoped>


.al-center {
  text-align: center;
}
.text-brown {
  color: #534d4d;
  font-weight: 600;
}
.list-out {
  display: flex;
  margin-top: 0;
  margin-bottom: 1rem;
  flex-direction: column;
  list-style: none;
  align-items: center;
}

.bg-card-1 {
  /* background: linear-gradient(180deg, #fbba77 0%, #dfa871 100%); */
  background: linear-gradient(
    180deg,
    rgba(255, 195, 113, 1) 0%,
    rgba(245, 75, 48, 1) 100%
  );
}
.bg-card-2 {
  background: linear-gradient(180deg, #00f88d 0%, #00c570 100%);
}
.bg-card-3 {
  background: linear-gradient(180deg, #38f0f2 0%, #00c2ff 100%);
}
.img-spon {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  gap: 30px;
}
</style>
