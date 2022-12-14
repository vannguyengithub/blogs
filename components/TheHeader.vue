<template>
    <header id="header">
      <div class="tcl-container">
        <div class="tcl-row tcl-no-gutters header">
          <div class="tcl-col-2">
            <!-- Logo -->
            <div class="header-logo">
              <a href="/">
                <img src="/assets/images/logo.png" alt="Go to homepage">
              </a>
            </div>
          </div>
          <div class="tcl-col-4">
            <!-- Header Search -->
            <form action="/search.html" method="get">
              <div class="header-search">
                <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512" height="1em"
                  width="1em" xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0;">
                  <path
                    d="M505 442.7L405.3 343c-4.5-4.5-10.6-7-17-7H372c27.6-35.3 44-79.7 44-128C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c48.3 0 92.7-16.4 128-44v16.3c0 6.4 2.5 12.5 7 17l99.7 99.7c9.4 9.4 24.6 9.4 33.9 0l28.3-28.3c9.4-9.4 9.4-24.6.1-34zM208 336c-70.7 0-128-57.2-128-128 0-70.7 57.2-128 128-128 70.7 0 128 57.2 128 128 0 70.7-57.2 128-128 128z">
                  </path>
                </svg>
                <input class="header-search__input" type="text" placeholder="Search articles here ..."
                  aria-label="Search" name="query">
              </div>
            </form>

          </div>
          <div class="tcl-col-6">
            <!-- Nav -->
            <div class="header-nav">
              <ul class="header-nav__lists">
                <li><a href="#">Home</a></li>
                <li>
                  <a href="#">Our Team</a>
                  <ul>
                    <li><a href="#">Our Team 1</a></li>
                    <li><a href="#">Our Team 2</a></li>
                    <li><a href="#">Our Team 3</a></li>
                  </ul>
                </li>
                <li>
                  <a href="#">Contact</a>
                  <ul>
                    <li><a href="#">Contact 1</a></li>
                    <li><a href="#">Contact 2</a></li>
                    <li>
                      <a href="#">Contact 3</a>
                      <ul>
                        <li><a href="#">Contact 11</a></li>
                        <li><a href="#">Contact 12</a></li>
                        <li><a href="#">Contact 13</a></li>
                      </ul>
                    </li>
                  </ul>
                </li>
              </ul>
              <ul class="header-nav__lists">
                <li class="user"><a href="login.html"><i class="icons ion-person"></i> Tài khoản</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </header>
</template>
<script>
export default {

}
</script>
<style>
    @import url('~/assets/css/header.css');
</style>