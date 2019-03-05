<template>
  <div>
    <v-layout column justify-center align-center mb-5>
      <v-flex xs12 sm8 md6>
        <div class="text-xs-center">
          <img src="/Johannes-Berggren.jpeg" alt="Johannes Berggren portrait" class="mb-2 portrait" />
        </div>
        <h1>Johannes Berggren</h1>
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center align-center my-5>
      <v-flex xs12 my-2>
        <h2>Find me at</h2>
        <v-divider />
      </v-flex>
      <v-flex xs3 sm3>
        <a href="https://www.goodreads.com/user/show/53628610-johannes-berggren">Goodreads</a>
      </v-flex>
      <v-flex xs3 sm3>
        <a href="https://soundcloud.com/johannes-berggren">Soundcloud</a>
      </v-flex>
      <v-flex xs3 sm3>
        <a href="https://www.linkedin.com/in/johannesberggren/">LinkedIn</a>
      </v-flex>
      <v-flex xs3 sm3>
        <a href="https://github.com/Johannes-Berggren">GitHub</a>
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center align-center my-5>
      <v-flex xs12 my-2>
        <h2>What I'm up to</h2>
        <v-divider />
      </v-flex>
      <v-flex xs6 sm3>
        <h3>Learnlink</h3>
        <p>CTO, Co-founder</p>
      </v-flex>
      <v-flex xs6 sm3>
        <h3>ChartCo</h3>
        <p>IT Operations Engineer</p>
      </v-flex>
      <v-flex xs6 sm3>
        <h3>KOK</h3>
        <p>DJ, Co-founder</p>
      </v-flex>
      <v-flex xs6 sm3>
        <h3>KOK Ventures</h3>
        <p>Founding partner</p>
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center align-center my-5>
      <v-flex xs12 my-2>
        <h2>What people are writing</h2>
        <v-divider />
      </v-flex>
      <v-flex xs12 sm12 md6 mb-5 px-3>
        <h4>In Norwegian</h4>
        <p>Digi.no:
          <a href="https://www.digi.no/artikler/mokk-lei-php-og-sql-na-lager-johannes-23-en-moderne-webapp-nesten-uten-a-kode/397937">
            Møkk lei PHP og SQL: Nå lager Johannes (23) en moderne webapp nesten uten å kode
          </a>
        </p>
        <p>Dagens Næringsliv:
          <a href="https://www.dn.no/forskning/grundervirksomhet/grunder/taper-pa-a-droppe-studier-for-grunderdrommen/1-1-5711026">
            Taper på å droppe studier for gründerdrømmen
          </a>
        </p>
        <p>Universitas:
          <a href="https://universitas.no/sak/63569/angst-grunderens-rad-ikke-ta-imot-rad-pa-vors/">
            Angst-gründerens råd: –⁠ Ikke ta imot råd på vors
          </a>
        </p>
      </v-flex>
      <v-flex xs12 sm12 md6 mb-5 px-3>
        <h4>In Spanish</h4>
        <p>TicBeat:
          <a href="http://www.ticbeat.com/entrevistas/johannes-berggren-learnlink-queremos-acercar-las-tutorias-online-a-personas-con-dislexia-y-profesionales-tic/">
            Johannes Berggren (LearnLink): “Queremos acercar las tutorías online a personas con dislexia y profesionales TIC”
          </a>
        </p>
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center align-center>
      <v-flex xs12 my-2>
        <h2>I'm also DJing</h2>
        <v-divider />
      </v-flex>
      <v-divider />
      <v-flex xs12 sm12 md6 mb-5 px-3>
        <h4>March 2019</h4>
        <h3>Progressive Mix</h3>
        <iframe
                width="100%"
                height="300"
                scrolling="no"
                frameborder="no"
                allow="autoplay"
                src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/584966655&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
      </v-flex>
      <v-flex xs12 sm12 md6 mb-5 px-3>
        <h4>January 2019</h4>
        <h3>Progressive Mix</h3>
        <iframe
                width="100%"
                height="300"
                scrolling="no"
                frameborder="no"
                allow="autoplay"
                src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/565553181&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
      </v-flex>
      <v-flex xs12 sm12 md6 mb-5 px-3>
        <h4>December 2018</h4>
        <h3>Progressive Mix</h3>
        <iframe
                width="100%"
                height="300"
                scrolling="no"
                frameborder="no"
                allow="autoplay"
                src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/551018304&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
      </v-flex>
    </v-layout>
  </div>
</template>

<style scoped>
  * {
    text-align: center;
  }

  .portrait {
    border-radius: 100%;
    width: 150px;
    height: 150px;
  }
</style>
