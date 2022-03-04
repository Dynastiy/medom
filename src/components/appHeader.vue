<template>
  <div>
    <div class="appNav d-flex justify-content-between content">
      <div>
        <img src="@/assets/logo.png" width="150" alt="" srcset="" />
      </div>
      <ul class="list-unstyled d-flex" style="gap: 30px">
        <li><a href="#how-it-works">How it Works</a></li>
        <li><a href="#health-care-provider">Health Care Provider</a></li>
      </ul>
      <div>
        <a href="#waitlist"
          ><button class="join__waitlist">Join Waitlist</button></a
        >
      </div>
    </div>

    <div class="sticky-top">
      <div class=" mobile-nav">
      <nav class="navbar navbar-expand-lg navbar-light bg-light content">
        <router-link to="" class="navbar-brand">
          <img src="@/assets/logo.png" width="150" alt="" srcset="" />
        </router-link>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <a class="nav-link text-dark" href="#how_it_works">Home </a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-dark" href="#health-care-provider"
                >Health Care Provider</a
              >
            </li>
          </ul>
          <form class="form-inline my-2 my-lg-0">
            <a href="#waitlist"
              ><button class="join__waitlist">Join Waitlist</button></a
            >
          </form>
        </div>
      </nav>
    </div>
    </div>
  </div>
</template>