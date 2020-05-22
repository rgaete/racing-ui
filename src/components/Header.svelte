<script>

  export let indexClass = "";
  export let teamClass = "";
  export let scheduleClass = "";
  export let stadingsClass = "";
  export let newsClass = "";

</script>

<div class="custom-header">
  <div class="header-mobile clearfix" id="header-mobile">
    <div class="header-mobile__logo">
      <a href="/">
        <img
          src="assets/images/soccer/logo.png"
          srcset="assets/images/soccer/logo@2x.png 2x"
          alt="Alchemists"
          class="header-mobile__logo-img" />
      </a>
    </div>
    <div class="header-mobile__inner">
      <a id="header-mobile__toggle" class="burger-menu-icon">
        <span class="burger-menu-icon__line" />
      </a>
      <span
        class="header-mobile__search-icon"
        id="header-mobile__search-icon" />
    </div>
  </div>
  <header class="header">
    
    <div class="header__top-bar clearfix">
      <div class="container">
          <ul class="nav-account">
          <li class="nav-account__item">
            <a
              data-toggle="modal"
              data-target="#modal-login-register-tabs"
              href="/login">
              Tu Perfil
            </a>    
          </li>
          <li class="nav-account__item nav-account__item--logout">
            <a href="/login">Salir</a>
          </li>
        </ul>
      </div>
    </div>
    
    <div class="header__secondary">
      <div class="container">
        <ul class="info-block info-block--header">
          <li class="info-block__item info-block__item--contact-secondary">
            <svg role="img" class="df-icon df-icon--soccer-ball">
              <use xlink:href="assets/images/icons-soccer.svg#soccer-ball" />
            </svg>
            <h6 class="info-block__heading">Contáctanos</h6>
            <a class="info-block__link" href="mailto:info@racingfc.cl">
              info@racingfc.cl
            </a>
          </li>
        </ul>
      </div>
    </div>
    <div class="header__primary">
      <div class="container">
        <div class="header__primary-inner">
          <div class="header-logo">
            <a href="/">
              <img
                src="assets/images/soccer/logo.png"
                srcset="assets/images/soccer/logo@2x.png 2x"
                alt="Racing"
                class="header-logo__img" />
            </a>
          </div>
          <nav class="main-nav clearfix">
            <ul class="main-nav__list">
              <li class={indexClass}>
                <a href="/">Inicio</a>
              </li>
              <li class={teamClass}>
                <a href="/team">Nuestro Equipo</a>
              </li>
              <li class={stadingsClass}>
                <a href="/">Estadísticas</a>
                <!--
                <ul class="main-nav__sub">
                  <li>
                    <a href="_soccer_game-overview.html">Programación</a>
                  </li>
                  <li>
                    <a href="_soccer_team-overview.html">Overview</a>
                  </li>
                  <li>
                    <a href="_soccer_team-roster.html">Roster</a>
                    <ul class="main-nav__sub-2">
                      <li>
                        <a href="_soccer_team-roster.html">Roster - 1</a>
                      </li>
                      <li>
                        <a href="_soccer_team-roster-2.html">
                          Roster - 2 &nbsp;
                          <span class="label label-danger">New</span>
                        </a>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <a href="_soccer_team-standings.html">Standings</a>
                  </li>
                  <li>
                    <a href="_soccer_team-last-results.html">Latest Results</a>
                  </li>
                  <li>
                    <a href="_soccer_team-schedule.html">Schedule</a>
                  </li>
                  <li>
                    <a href="_soccer_team-gallery.html">Gallery</a>
                    <ul class="main-nav__sub-2">
                      <li>
                        <a href="_soccer_team-gallery-album.html">
                          Single Album
                        </a>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <a href="_soccer_player-overview.html">Player Pages</a>
                    <ul class="main-nav__sub-2">
                      <li>
                        <a href="_soccer_player-overview.html">Overview</a>
                      </li>
                      <li>
                        <a href="_soccer_player-stats.html">
                          Full Estadísticas
                        </a>
                      </li>
                      <li>
                        <a href="_soccer_player-bio.html">Biography</a>
                      </li>
                      <li>
                        <a href="_soccer_player-news.html">Related Noticias</a>
                      </li>
                      <li>
                        <a href="_soccer_player-gallery.html">Gallery</a>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <a href="_soccer_staff-single.html">Staff Member</a>
                  </li>
                </ul>
                -->
              </li>
              <li class={scheduleClass}>
                <a href="/">Programación</a>
              </li>
              <li class={newsClass}>
                <a href="/">Noticias</a>
              </li>
            </ul>
            <a href="/" class="pushy-panel__toggle">
              <span class="pushy-panel__line" />
            </a>
          </nav>
        </div>
      </div>
    </div>
  </header>
</div>
