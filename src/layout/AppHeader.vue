<template>
  <header class="header-global">
    <base-nav class="navbar-main" transparent type="" effect="light" expand>
      <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
        <div style="position: relative">
          <img
            style="width: 188px; height: 65px"
            src="img/brand/image/8.png"
            alt="logo"
          />
          <img
            class="floating"
            style="
              width: 30px;
              height: 30px;
              position: absolute;
              top: -5px;
              right: 32px;
            "
            src="img/brand/image/9.png"
            alt="logo"
          />
        </div>
      </router-link>

      <div class="row" slot="content-header" slot-scope="{ closeMenu }">
        <div class="col-6 collapse-brand">
          <a
            href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
          >
            <img src="img/brand/blue.png" />
          </a>
        </div>
        <div class="col-6 collapse-close">
          <close-button @click="closeMenu"></close-button>
        </div>
      </div>

      <ul class="navbar-nav align-items-lg-center ml-lg-auto">
        <base-dropdown class="nav-item" menu-classes="dropdown-menu-xxl">
          <a
            slot="title"
            href="#"
            class="nav-link"
            data-toggle="dropdown"
            role="button"
          >
            <i class="ni ni-ui-04 d-lg-none"></i>
            <span class="nav-link-inner--text">HOME</span>
          </a>
          <div class="dropdown-menu-inner">
            <div class="row">
              <div class="col col-sm-4">
                <div style="display: flex" class="menu-box">
                  <div
                    style="min-width: 120px; margin-right: -8px"
                    class="icon"
                  >
                    <img
                      src="https://cdn2.hubspot.net/hubfs/5493376/6M%20Templates/services-menu-icon.png"
                    />
                  </div>
                  <div>
                    <span
                      style="font-size: 16px; margin-top: 5px; display: block"
                      >Location Based</span
                    >
                    <h5
                      style="
                        font-weight: 700;
                        margin: 5px 0px;
                        transition: 0.2s color;
                      "
                    >
                      Services
                    </h5>
                    <p
                      style="
                        font-size: 13px;
                        white-space: normal;
                        margin-bottom: 0px;
                      "
                    >
                      Provide the finest location experience for your visitors.
                    </p>
                  </div>
                </div>

                <div
                  style="
                    position: static;
                    margin-left: 115px;
                    opacity: 1;
                    color: #17191c;
                  "
                >
                  <div><a href="#">Smart Workplace</a></div>
                  <div><a href="#">Smart Hospital</a></div>
                  <div><a href="#">Retail</a></div>
                  <div><a href="#">Aviation</a></div>
                  <div><a href="#">Hospitadivty</a></div>
                  <div><a href="#">Other Sectors</a></div>
                </div>
              </div>
              <div class="col col-sm-4">
                <div style="display: flex" class="menu-box">
                  <div
                    style="min-width: 120px; margin-right: -8px"
                    class="icon"
                  >
                    <img
                      src="https://cdn2.hubspot.net/hubfs/5493376/6M%20Templates/services-menu-icon.png"
                    />
                  </div>
                  <div>
                    <span
                      style="font-size: 16px; margin-top: 5px; display: block"
                      >Location Based</span
                    >
                    <h5
                      style="
                        font-weight: 700;
                        margin: 5px 0px;
                        transition: 0.2s color;
                      "
                    >
                      Services
                    </h5>
                    <p
                      style="
                        font-size: 13px;
                        white-space: normal;
                        margin-bottom: 0px;
                      "
                    >
                      Provide the finest location experience for your visitors.
                    </p>
                  </div>
                </div>

                <div
                  style="
                    position: static;
                    margin-left: 115px;
                    opacity: 1;
                    color: #17191c;
                  "
                >
                  <div><a href="#">Smart Workplace</a></div>
                  <div><a href="#">Smart Hospital</a></div>
                  <div><a href="#">Retail</a></div>
                  <div><a href="#">Aviation</a></div>
                  <div><a href="#">Hospitadivty</a></div>
                  <div><a href="#">Other Sectors</a></div>
                </div>
              </div>
              <div class="col col-sm-4">
                <div style="display: flex" class="menu-box">
                  <div
                    style="min-width: 120px; margin-right: -8px"
                    class="icon"
                  >
                    <img
                      src="https://cdn2.hubspot.net/hubfs/5493376/6M%20Templates/services-menu-icon.png"
                    />
                  </div>
                  <div>
                    <span
                      style="font-size: 16px; margin-top: 5px; display: block"
                      >Location Based</span
                    >
                    <h5
                      style="
                        font-weight: 700;
                        margin: 5px 0px;
                        transition: 0.2s color;
                      "
                    >
                      Services
                    </h5>
                    <p
                      style="
                        font-size: 13px;
                        white-space: normal;
                        margin-bottom: 0px;
                      "
                    >
                      Provide the finest location experience for your visitors.
                    </p>
                  </div>
                </div>

                <div
                  style="
                    position: static;
                    margin-left: 115px;
                    opacity: 1;
                    color: #17191c;
                  "
                >
                  <div><a href="#">Smart Workplace</a></div>
                  <div><a href="#">Smart Hospital</a></div>
                  <div><a href="#">Retail</a></div>
                  <div><a href="#">Aviation</a></div>
                  <div><a href="#">Hospitadivty</a></div>
                  <div><a href="#">Other Sectors</a></div>
                </div>
              </div>
            </div>
          </div>
        </base-dropdown>
        <base-dropdown tag="li" class="nav-item">
          <a
            slot="title"
            href="#"
            class="nav-link"
            data-toggle="dropdown"
            role="button"
          >
            <i class="ni ni-collection d-lg-none"></i>
            <span class="nav-link-inner--text">SOLUTION</span>
          </a>
          <router-link to="/landing" class="dropdown-item">Landing</router-link>
          <router-link to="/profile" class="dropdown-item">Profile</router-link>
          <router-link to="/login" class="dropdown-item">Login</router-link>
          <router-link to="/register" class="dropdown-item"
            >Register</router-link
          >
        </base-dropdown>
        <base-dropdown class="nav-item" menu-classes="dropdown-menu-xl">
          <a
            slot="title"
            href="#"
            class="nav-link"
            data-toggle="dropdown"
            role="button"
          >
            <i class="ni ni-ui-04 d-lg-none"></i>
            <span class="nav-link-inner--text">INDUSTRIES</span>
          </a>
          <div class="dropdown-menu-inner">
            <a
              href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
              class="media d-flex align-items-center"
            >
              <div
                class="
                  icon icon-shape
                  bg-gradient-primary
                  rounded-circle
                  text-white
                "
              >
                <i class="ni ni-spaceship"></i>
              </div>
              <div class="media-body ml-3">
                <h6 class="heading text-primary mb-md-1">Getting started</h6>
                <p class="description d-none d-md-inline-block mb-0">
                  Get started with Bootstrap, the world's most popular framework
                  for building responsive sites.
                </p>
              </div>
            </a>
            <a
              href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
              class="media d-flex align-items-center"
            >
              <div
                class="
                  icon icon-shape
                  bg-gradient-warning
                  rounded-circle
                  text-white
                "
              >
                <i class="ni ni-ui-04"></i>
              </div>
              <div class="media-body ml-3">
                <h5 class="heading text-warning mb-md-1">Components</h5>
                <p class="description d-none d-md-inline-block mb-0">
                  Learn how to use Argon compiling Scss, change brand colors and
                  more.
                </p>
              </div>
            </a>
          </div>
        </base-dropdown>
        <base-dropdown tag="li" class="nav-item">
          <a
            slot="title"
            href="#"
            class="nav-link"
            data-toggle="dropdown"
            role="button"
          >
            <i class="ni ni-collection d-lg-none"></i>
            <span class="nav-link-inner--text">RESOUCES</span>
          </a>
          <router-link to="/landing" class="dropdown-item">Landing</router-link>
          <router-link to="/profile" class="dropdown-item">Profile</router-link>
          <router-link to="/login" class="dropdown-item">Login</router-link>
          <router-link to="/register" class="dropdown-item"
            >Register</router-link
          >
        </base-dropdown>
        <base-dropdown class="nav-item" menu-classes="dropdown-menu-xl">
          <a
            slot="title"
            href="#"
            class="nav-link"
            data-toggle="dropdown"
            role="button"
          >
            <i class="ni ni-ui-04 d-lg-none"></i>
            <span class="nav-link-inner--text">CONTACT</span>
          </a>
          <div class="dropdown-menu-inner">
            <a
              href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
              class="media d-flex align-items-center"
            >
              <div
                class="
                  icon icon-shape
                  bg-gradient-primary
                  rounded-circle
                  text-white
                "
              >
                <i class="ni ni-spaceship"></i>
              </div>
              <div class="media-body ml-3">
                <h6 class="heading text-primary mb-md-1">Getting started</h6>
                <p class="description d-none d-md-inline-block mb-0">
                  Get started with Bootstrap, the world's most popular framework
                  for building responsive sites.
                </p>
              </div>
            </a>
            <a
              href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
              class="media d-flex align-items-center"
            >
              <div
                class="
                  icon icon-shape
                  bg-gradient-warning
                  rounded-circle
                  text-white
                "
              >
                <i class="ni ni-ui-04"></i>
              </div>
              <div class="media-body ml-3">
                <h5 class="heading text-warning mb-md-1">Components</h5>
                <p class="description d-none d-md-inline-block mb-0">
                  Learn how to use Argon compiling Scss, change brand colors and
                  more.
                </p>
              </div>
            </a>
          </div>
        </base-dropdown>
        <li class="nav-item d-none d-lg-block ml-lg-4">
          <!-- <span
            style="color: white; position: absolute; left: 25%; top: 25%;"
            class="nav-link-inner--text"
            >Get Started</span
          > -->
          <!-- <img
            style="width: 205px; height: 63px"
            src="img/brand/image/Group 354.png"
            alt="logo"
          /> -->
          <base-button
            tag="a"
            href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
            class="mb-3 mb-sm-0 button-css"
          >
            Get Started
          </base-button>
        </li>
      </ul>
    </base-nav>
  </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown,
  },
};
</script>
<style scoped>
.container{
  
}
</style>
