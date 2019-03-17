<template>
  <div>
    <v-layout column justify-center my-3>
      <v-flex xs12 sm8 md6>
        <div class="text-xs-center">
          <img src="/Johannes-Berggren.jpeg" alt="Johannes Berggren portrait" class="mb-2 portrait" />
        </div>
        <h1>Johannes Berggren</h1>
      </v-flex>
    </v-layout>

    <!--<v-layout wrap justify-center my-5 mb-5>-->
    <!--<v-flex xs12 mb-3>-->
    <!--<v-divider />-->
    <!--</v-flex>-->
    <!--<v-flex xs6 sm3>-->
    <!--<h3>Learnlink</h3>-->
    <!--<p>CTO, Co-founder</p>-->
    <!--</v-flex>-->
    <!--<v-flex xs6 sm3>-->
    <!--<h3>KOK Ventures</h3>-->
    <!--<p>Founding partner</p>-->
    <!--</v-flex>-->
    <!--<v-flex xs6 sm3>-->
    <!--<h3>ChartCo</h3>-->
    <!--<p>IT Operations Engineer</p>-->
    <!--</v-flex>-->
    <!--<v-flex xs6 sm3>-->
    <!--<h3>KOK</h3>-->
    <!--<p>DJ, Co-founder</p>-->
    <!--</v-flex>-->
    <!--<v-flex xs12 my-1>-->
    <!--<v-divider />-->
    <!--</v-flex>-->
    <!--</v-layout>-->

    <!--<v-layout column justify-center my-3>-->
    <!--<p>-->
    <!--<i>"Johannes is a Norwegian internet entrepreneur, software engineer and angel investor.<br />He has deep-->
    <!--technical expertise, and is currently one of Norways top full stack software engineers."-->
    <!--</i>-->
    <!--</p>-->
    <!--<p>-->
    <!--<i>"Having started his first company at age 12, Johannes has years of first hand business development-->
    <!--experience.-->
    <!--Johannes currently serves as CTO at Learnlink, the first and fastest growing online tutoring platform in-->
    <!--Northern Europe."-->
    <!--</i>-->
    <!--</p>-->
    <!--</v-layout>-->

    <v-layout column justify-center my-2 mb-5>
      <!--<h3>Ask Johannes:</h3>-->
      <h4>johannes@berggren.co</h4>
    </v-layout>

    <v-layout wrap justify-center my-5 follow>
      <v-flex xs12 my-2>
        <h2>Connect with me</h2>
        <v-divider />
      </v-flex>
      <v-flex xs4 sm4 first>
        <a href="https://www.linkedin.com/in/johannesberggren/">LinkedIn</a>
      </v-flex>
      <v-flex xs4 sm4 first>
        <a href="https://github.com/Johannes-Berggren">GitHub</a>
      </v-flex>
      <v-flex xs4 sm4 first>
        <a href="https://soundcloud.com/johannes-berggren">Soundcloud</a>
      </v-flex>
      <v-flex xs3 sm3 mt-3 mb-3 second>
        <a href="https://www.goodreads.com/user/show/53628610-johannes-berggren">Goodreads</a>
      </v-flex>
      <v-flex xs3 sm3 mt-3 mb-3 second>
        <a href="https://www.crunchbase.com/person/johannes-berggren">Crunchbase</a>
      </v-flex>
      <v-flex xs3 sm3 mt-3 mb-3 second>
        <a href="https://www.shareville.no/medlemmer/j-b/wall">Shareville</a>
      </v-flex>
      <v-flex xs3 sm3 mt-3 mb-3 second>
        <a href="https://learnlink.no/profil/bPVgZ3f1pjhrN7esErZ4Q4gX5wy1/">Learnlink</a>
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center my-5 follow>
      <v-flex xs12 my-2>
        <h2>Investments</h2>
        <v-divider />
      </v-flex>
      <v-flex xs6 mt-3 mb-3>
        <a href="https://sharebox.no">
          <img src="/sharebox_logo.png" />
        </a>
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center my-5 follow>
      <v-flex xs12 my-2>
        <h2>Open source projects</h2>
        <v-divider />
      </v-flex>
      <v-flex xs6 first>
        <a href="https://www.npmjs.com/package/firestore-to-bigquery-export" style="margin-bottom: 5px">
          Firestore to BigQuery Export
        </a>
        <p>An automatic tool for copying and converting Cloud Firestore data to BigQuery.</p>
      </v-flex>
      <v-flex xs6 first>
        <a href="http://marketflow-d6822.firebaseapp.com">MarketFlow</a>
        <p>Lets you see the stock market sentiment and volatility for any period of time.</p>
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center my-5>
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
            Johannes Berggren (LearnLink): “Queremos acercar las tutorías online a personas con dislexia y profesionales
            TIC”
          </a>
        </p>
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center>
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

    <v-layout wrap justify-center>
      <v-flex xs12 my-2>
        <h2>Favorites</h2>
        <v-divider />
      </v-flex>
      <v-divider />
      <v-flex xs6 mb-5 px-3>
        <h3>Books</h3>
        <p>Influence: The Phychology of Persuasion</p>
        <p>Zero to One: Notes on Startups, or How to Build the Future</p>
        <p>Surely You're Joking, Mr. Feynman!</p>
        <p>Angel: How to Invest in Technology Startups</p>
        <p>The Hard Thing About Hard Things</p>
        <p>Sapiens: A Brief History of Humankind</p>
        <p>The Innovator's Dilemma</p>
        <p>Thinking, Fast and Slow</p>
      </v-flex>
      <v-flex xs6 mb-5 px-3>
        <h3>Podcasts</h3>
        <p>This Week in Startups</p>
        <p>Maching Learning Guide</p>
        <p>The Kevin Rose Show</p>
        <p>Pivot</p>
        <p>Recode Decode</p>
        <p>The Tim Ferriss Show</p>
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

  a {
    font-family: sans-serif;
    text-decoration: none;
  }

  .first a {
    font-size: 18px;
  }

  .second a {
    font-size: 16px;
  }
</style>
