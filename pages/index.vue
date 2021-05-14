<template>
  <v-container>
    <v-layout
      align-center
      justify-center
      mt-3
    >
      <v-flex
        xs12
        sm4
        md6
        style="text-align: right; margin-right: 20px"
      >
        <img
          src="/Johannes-Berggren.jpeg"
          alt="Johannes Berggren portrait"
          class="mb-2 portrait"
        />
      </v-flex>

      <v-flex
        xs12
        sm8
        md6
        class="intro"
      >
        <v-layout
          wrap
          justify-center
          mt-4
          mb-5
        >
          <v-flex xs12>
            <h1>Johannes Berggren</h1>
          </v-flex>
        </v-layout>
      </v-flex>
    </v-layout>

    <!--    <v-layout justify-center my-3>-->
    <!--      <v-flex xs12 sm8>-->
    <!--        <p>-->
    <!--          <i>Johannes is a Norwegian internet entrepreneur, software engineer and angel investor.</i>-->
    <!--        </p>-->
    <!--        <p>-->
    <!--          <i>"Having started his first company at age 12, Johannes has years of first hand business development-->
    <!--             experience.-->
    <!--             Johannes currently serves as CTO at Learnlink, the first and fastest growing online tutoring platform in-->
    <!--             Northern Europe."-->
    <!--          </i>-->
    <!--        </p>-->
    <!--      </v-flex>-->
    <!--      <v-flex xs6>-->
    <!--        <h3>I help companies </h3>-->
    <!--      </v-flex>-->
    <!--    </v-layout>-->

    <v-layout
      wrap
      justify-center
      my-5
      follow
    >
      <v-flex
        xs12
        my-2
      >
        <h2>Connect</h2>
        <v-divider />
      </v-flex>
      <v-flex
        xs4
        sm4
        first
      >
        <a href="https://www.linkedin.com/in/johannesberggren/">LinkedIn</a>
      </v-flex>
      <v-flex
        xs4
        sm4
        first
      >
        <a href="https://github.com/Johannes-Berggren">GitHub</a>
      </v-flex>
      <v-flex
        xs4
        sm4
        first
      >
        <a href="https://soundcloud.com/johannes-berggren">Soundcloud</a>
      </v-flex>
      <v-flex
        xs3
        sm3
        mt-3
        mb-3
        second
      >
        <a href="https://www.goodreads.com/user/show/53628610-johannes-berggren">Goodreads</a>
      </v-flex>
      <v-flex
        xs3
        sm3
        mt-3
        mb-3
        second
      >
        <a href="https://www.crunchbase.com/person/johannes-berggren">Crunchbase</a>
      </v-flex>
      <v-flex
        xs3
        sm3
        mt-3
        mb-3
        second
      >
        <a href="https://www.shareville.no/medlemmer/j-b/wall">Shareville</a>
      </v-flex>
    </v-layout>

    <v-layout
      wrap
      justify-center
      my-5
      follow
    >
      <v-flex
        xs12
        my-2
      >
        <h2>Investments</h2>
        <v-divider />
      </v-flex>
      <v-flex
        xs12
        sm6
        md4
        mt-3
        mb-3
        investment-logos
      >
        <a href="https://accountflow.no">
          <img src="/accountflow_logo.png" />
        </a>
      </v-flex>
      <v-flex
        xs12
        sm6
        md4
        mt-3
        mb-3
        investment-logos
      >
        <a href="https://sharebox.no">
          <img src="/sharebox_logo.png" />
        </a>
      </v-flex>
      <v-flex
        xs12
        sm6
        md4
        mt-3
        mb-3
        investment-logos
      >
        <a href="https://www.visualyst.co">
          <img
            style="max-height: 120px"
            src="/visualyst_logo.png"
          />
        </a>
      </v-flex>
      <v-flex
        xs12
        sm6
        md4
        mt-3
        mb-3
        investment-logos
      >
        <a href="https://luado.no">
          <img src="/luado_logo.png" />
        </a>
      </v-flex>
    </v-layout>

    <v-layout
      wrap
      justify-center
      my-5
    >
      <v-flex
        xs12
        my-2
      >
        <h2>What people are writing</h2>
        <v-divider />
      </v-flex>
      <v-flex
        xs12
        sm6
        md6
        mb-5
        px-3
      >
        <p>Shifter:
          <a href="https://shifter.no/nyheter/johannes-solgte-leiligheten-og-tjente-millioner-pa-bitcoin-na-investerer-han-gevinsten-i-startups/210946">
            Johannes solgte leiligheten og tjente millioner på Bitcoin: Nå investerer han gevinsten i startups
          </a>
        </p>
        <p>Startup Norway @ Medium:
          <a href="https://medium.com/startup-norway/investorkollektivet-seedstage-vil-bygge-ressursmilj%C3%B8-for-investeringer-6d750fcf5b82">
            Investorkollektivet Seedstage vil bygge ressursmiljø for investeringer
          </a>
        </p>
        <p>Digi.no:
          <a href="https://www.digi.no/artikler/mokk-lei-php-og-sql-na-lager-johannes-23-en-moderne-webapp-nesten-uten-a-kode/397937">
            Møkk lei PHP og SQL: Nå lager Johannes (23) en moderne webapp nesten uten å kode
          </a>
        </p>
      </v-flex>
      <v-flex
        xs12
        sm6
        md6
        mb-5
        px-3
      >
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
        <p>TicBeat:
          <a href="http://www.ticbeat.com/entrevistas/johannes-berggren-learnlink-queremos-acercar-las-tutorias-online-a-personas-con-dislexia-y-profesionales-tic/">
            Johannes Berggren (LearnLink): “Queremos acercar las tutorías online a personas con dislexia y profesionales
            TIC”
          </a>
        </p>
      </v-flex>
    </v-layout>

    <!-- <v-layout wrap justify-center>
      <v-flex xs12 my-2>
        <h2>Favorites</h2>
        <v-divider />
      </v-flex>
      <v-divider />
      <v-flex xs6 mb-5 px-3>
        <h3>Books</h3>
        <p>
          <a href="https://www.goodreads.com/book/show/82256.The_Sovereign_Individual">
            The Sovereign Individual
          </a>
        </p>
        <p>
          <a href="https://www.goodreads.com/book/show/18050143-zero-to-one?from_search=true&qid=nm30TkPUO1&rank=1">
            Zero to One: Notes on Startups, or How to Build the Future
          </a>
        </p>
        <p>
          <a href="https://www.goodreads.com/book/show/32600757-angel?ac=1&from_search=true&qid=Q4G5QmotcW&rank=1">
            Angel:
            How to Invest in Technology Startups
          </a>
        </p>
        <p>
          <a href="https://www.goodreads.com/book/show/28815.Influence?ac=1&from_search=true&qid=r5e1AgOsoL&rank=3">
            Influence: The Phychology of Persuasion
          </a>
        </p>
        <p>
          <a href="https://www.goodreads.com/book/show/18176747-the-hard-thing-about-hard-things?ac=1&from_search=true&qid=hCBFXdOXMO&rank=1">
            The Hard Thing About Hard Things
          </a>
        </p>
        <p>Surely You're Joking, Mr. Feynman!</p>
        <p>Sapiens: A Brief History of Humankind</p>
        <p>The Innovator's Dilemma</p>
        <p>Thinking, Fast and Slow</p>
      </v-flex>
      <v-flex xs6 mb-5 px-3>
        <h3>Podcasts</h3>
        <p>
          <a href="https://thisweekinstartups.com/">
            This Week in Startups
          </a>
        </p>
        <p>
          <a href="http://ocdevel.com/mlg">
            Machine Learning Guide
          </a>
        </p>
        <p>
          <a href="https://www.kevinrose.com/">
            The Kevin Rose Show
          </a>
        </p>
        <p>
          <a href="https://tim.blog/podcast/">
            The Tim Ferriss Show
          </a>
        </p>
        <p>
          <a href="https://podcasts.voxmedia.com/show/recode-decode">
            Recode Decode
          </a>
        </p>
        <p>
          <a href="https://podcasts.voxmedia.com/show/pivot">
            Pivot
          </a>
        </p>
        <p>
          <a href="https://dataskeptic.com/">
            Data Sceptic
          </a>
        </p>
      </v-flex>
    </v-layout> -->
  </v-container>
</template>

<style scoped lang="stylus">
* {
  text-align: center;
}

.portrait {
  border-radius: 100%;
  width: 175px;
  height: 175px;
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

.investment-logos {
  display: flex;
}

.investment-logos a {
  align-self: center;
  margin: auto;
}

.investment-logos a img {
  max-width: 200px;
}
</style>
