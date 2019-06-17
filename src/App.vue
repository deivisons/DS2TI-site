<template>
  <div
    id="page"
    class="site"
  >

    <section class="header-top-info-1">
      <div class="container">
        <div class="row">
          <div class="col-md-6 col-sm-7">
            <!-- Start Contact Info -->
            <ul class="info pull-left"></ul>
            <!-- /End Contact Info -->
          </div>

          <div class="col-md-6 col-sm-5">
            <!-- Start Social Media Icons -->

            <ul class="social pull-right"></ul>
            <!-- /End Social Media Icons-->
          </div>
        </div>
      </div>
    </section>

    <div class="clearfix"></div>

    <header role="banner">
      <div class="container">
        <div class="col-md-4 col-sm-4 col-xs-12 dss-header padding-top-25">
          <a
            class="navbar-brand"
            href="#"
          >
            DS2TI
            <p class="site-description">Soluções inteligentes</p>
          </a>
        </div>

        <div class="col-md-8 col-sm-8 col-xs-12 dss-header padding-top-25">
          <ul class="search-cart text-right">
            <li>
              <form
                class="searchbox"
                action="#"
                method="get"
              >
                <input
                  type="search"
                  name="s"
                  id="s"
                  placeholder="Search anything..."
                  class="searchbox-input"
                  onkeyup="buttonUp();"
                  required
                >
                <input
                  type="submit"
                  class="searchbox-submit"
                  value
                >
                <span class="searchbox-icon">
                  <i class="fa fa-search"></i>
                </span>
              </form>
            </li>

            <!-- <li>
              <div class="dss-cart">
                <a href class="cart-icon">
                  <i class="fa fa-cart-plus"></i>
                  <span class="count">0</span>
                </a>
              </div>
            </li>-->
            <!-- <li>
              <div class="dss-button">
                <a href>
                  <i class="fa fa-clock-o"></i> Book Now
                </a>
              </div>
            </li>-->
          </ul>
        </div>
      </div>
    </header>

    <div class="container">
      <div
        id="sticky-wrapper"
        class="sticky-wrapper"
        style="height: 69px;"
      >
        <div
          id="sticky-wrapper"
          class="sticky-wrapper"
          style="height: 69px;"
        >
          <nav
            class="navbar navbar-default dss-nav sticky-nav"
            role="navigation"
            style
          >
            <div class="container">
              <!-- Mobile Display -->
              <div class="navbar-header">
                <button
                  type="button"
                  class="navbar-toggle collapsed"
                  data-toggle="collapse"
                  data-target="#bs-example-navbar-collapse-1"
                >
                  <span class="sr-only">Toggle navigation</span>
                  <span class="icon-bar"></span>
                  <span class="icon-bar"></span>
                  <span class="icon-bar"></span>
                </button>
              </div>
              <!-- /Mobile Display -->

              <!-- Menu Toggle -->
              <div
                class="collapse navbar-collapse"
                id="bs-example-navbar-collapse-1"
              >
                <div
                  id
                  class
                >
                  <ul class="nav navbar-nav navbar-right">
                    <li class="current-menu-item active">
                      <a
                        href="#"
                        title="Home"
                      >Home</a>
                    </li>
                    <li
                      id=" menu-item-2 "
                      class="menu-item menu-item-2"
                    >
                      <a href="#">About</a>
                    </li>
                    <!-- <li id=" menu-item-46 " class="menu-item menu-item-46 dropdown">
                      <a href="#">
                        Parent Page
                        <i class="caret"></i>
                      </a>
                      <ul class="dropdown-menu">
                        <li id=" menu-item-49 " class="menu-item menu-item-49">
                          <a href="#">Sub-page</a>
                        </li>
                      </ul>
                    </li>-->
                  </ul>
                </div>
              </div>
              <!-- Menu Toggle -->
            </div>
          </nav>
        </div>
      </div>
    </div>
    <div class="clearfix"></div>
    <div
      id="content"
      class="site-content"
      role="main"
    >
      <section class="breadcrumb dss">
        <div class="background-overlay">
          <div class="container">
            <div class="row padding-top-60 padding-bottom-30">
              <div class="col-md-6 col-xs-12 col-sm-6">
                <h2>Worth A Thousand Words</h2>
              </div>

              <div class="col-md-6 col-xs-12 col-sm-6 breadcrumb-position">
                <ul class="page-breadcrumb">
                  <li>
                    <a href="#">Home</a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>

      <div class="clearfix"></div>
      <!-- Blog & Sidebar Section -->
      <section class="page-wrapper">
        <div id="app"></div>
        <div class="container">
          <div class="row padding-top-60 padding-bottom-60">
            <div id="app">
              <router-view />
            </div>

            <!--Blog Detail-->
            <!-- <div class="col-md-12">
              <article
                id="post-19"
                class="post-19 post type-post status-publish format-standard hentry category-uncategorized tag-boat tag-lake"
            >-->
            <!-- <a href="#" class="post-thumbnail"></a> -->
            <!-- <footer class="entry-footer">
                  <span class="byline">
                    <span class="author vcard">
                      <a class="url fn n" href="#">
                        <i class="fa fa-user"></i> Theme
                        Admin
                      </a>
                    </span>
                  </span>
                  <span class="cat-links">
                    <a href="#">
                      <i class="fa fa-folder-open"></i>
                    </a>
                    <a href="#" rel="category">Uncategorized</a>
                  </span>
                  <span class="tags-links">
                    <a href="#">
                      <i class="fa fa-tags"></i>
                    </a>
                    <a href="#" rel="tag">boat</a>,
                    <a href="#" rel="tag">lake</a>
                  </span>
            </footer>-->
            <!-- .entry-footer -->

            <!--  <header class="entry-header">
                  <h2 class="entry-title">
                    <a href="#" rel="bookmark">
                      Worth A Thousand
                      Words
                    </a>
                  </h2>
            </header>-->
            <!-- .entry-header -->

            <!-- <div class="entry-content">
                  <figure style="width: 435px" class="wp-caption alignnone">
                    <img
                      class="wp-image-59"
                      alt="Boat"
                      src="https://wpdotorg.files.wordpress.com/2008/11/boat.jpg"
                      width="435"
                      height="288"
                    >
                    <figcaption class="wp-caption-text">Boat</figcaption>
                  </figure>
                  <p>Boat.</p>
            </div>-->
            <!-- .entry-content -->
            <!-- </article> -->

            <!-- <div class="paginations"></div>
            </div>-->
            <!--/End of Blog Detail-->
          </div>
        </div>
      </section>
      <!-- End of Blog & Sidebar Section -->

      <div class="clearfix"></div>

      <!--======================================
      Footer Section
      ========================================-->
      <div class="clearfix"></div>

      <!--======================================
      Footer Copyright
      ========================================-->
      <section class="footer-copyright">
        <div class="container">
          <div class="row padding-top-20 padding-bottom-10">
            <div class="col-md-6 text-left">
              <p class="copyright">DS2TI - soluções inteligentes.</p>
            </div>
            <div class="col-md-6">
              <ul class="payment-icon"></ul>
            </div>
          </div>
        </div>
      </section>

      <!--======================================
      Top Scroller
      ========================================-->
      <a
        href="#"
        class="top-scroll"
      >
        <i class="fa fa-arrow-circle-o-up"></i>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #003366;
  margin-top: 0px;
}
</style>
