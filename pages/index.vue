<template>
  <v-container style="max-width: 960px">
    <v-row
      justify="center"
      align="center"
      class="mb-8"
    >
      <v-col
        cols="8"
        sm="2"
      >
        <v-img
          src="/Johannes-Berggren.jpeg"
          alt="Johannes Berggren portrait"
          style="border-radius: 100%"
        />
      </v-col>

      <v-col>
        <h1>Johannes Berggren</h1>

        <v-divider class="my-2" />

        <a
          class="mr-8"
          href="https://www.linkedin.com/in/johannesberggren/"
          target="blank"
        >LinkedIn</a>
        <a
          class="mr-8"
          href="https://github.com/Johannes-Berggren"
          target="blank"
        >GitHub</a>
        <a
          class="mr-8"
          href="https://soundcloud.com/johannes-berggren"
          target="blank"
        >Soundcloud</a>
        <a
          class="mr-8"
          href="https://www.goodreads.com/user/show/53628610-johannes-berggren"
          target="blank"
        >Goodreads</a>
        <a
          class="mr-8"
          href="https://www.crunchbase.com/person/johannes-berggren"
          target="blank"
        >Crunchbase</a>
        <a
          class="mr-8"
          href="https://www.shareville.no/medlemmer/j-b/wall"
          target="blank"
        >Shareville</a>
      </v-col>
    </v-row>

    <v-row justify="center">
      <v-col
        cols="12"
        md="6"
      >
        <h3>What people are writing</h3>

        <v-divider class="mt-2 mb-4" />

        <v-row>
          <v-col>
            <p>
              <a
                href="https://shifter.no/nyheter/johannes-solgte-leiligheten-og-tjente-millioner-pa-bitcoin-na-investerer-han-gevinsten-i-startups/210946"
                target="blank"
              >
                Johannes solgte leiligheten og tjente millioner på Bitcoin: Nå investerer han gevinsten i startups
              </a>
              <i style="color: grey; text-align: right">Shifter</i>
            </p>
            <p>
              <a
                href="https://medium.com/startup-norway/investorkollektivet-seedstage-vil-bygge-ressursmilj%C3%B8-for-investeringer-6d750fcf5b82"
                target="blank"
              >
                Investorkollektivet Seedstage vil bygge ressursmiljø for investeringer
              </a>
              <i style="color: grey; text-align: right">Startup Norway @ Medium</i>
            </p>
            <p>
              <a
                href="https://www.digi.no/artikler/mokk-lei-php-og-sql-na-lager-johannes-23-en-moderne-webapp-nesten-uten-a-kode/397937"
                target="blank"
              >
                Møkk lei PHP og SQL: Nå lager Johannes (23) en moderne webapp nesten uten å kode
              </a>
              <i style="color: grey; text-align: right">Digi.no</i>
            </p>

            <p>
              <a
                href="https://www.dn.no/forskning/grundervirksomhet/grunder/taper-pa-a-droppe-studier-for-grunderdrommen/1-1-5711026"
                target="blank"
              >
                Taper på å droppe studier for gründerdrømmen
              </a>
              <i style="color: grey; text-align: right">Dagens Næringsliv</i>
            </p>
            <p>
              <a
                href="https://universitas.no/sak/63569/angst-grunderens-rad-ikke-ta-imot-rad-pa-vors/"
                target="blank"
              >
                Angst-gründerens råd: –⁠ Ikke ta imot råd på vors
              </a>
              <i style="color: grey; text-align: right">Universitas</i>
            </p>
            <p>
              <a
                href="http://www.ticbeat.com/entrevistas/johannes-berggren-learnlink-queremos-acercar-las-tutorias-online-a-personas-con-dislexia-y-profesionales-tic/"
                target="blank"
              >
                Johannes Berggren (LearnLink): “Queremos acercar las tutorías online a personas con dislexia y profesionales
                TIC”
              </a>
              <i style="color: grey; text-align: right">TicBeat</i>
            </p>
          </v-col>
        </v-row>
      </v-col>

      <v-col
        cols="12"
        md="6"
      >
        <h3>Investments</h3>

        <v-divider class="mt-2 mb-4" />

        <v-row>
          <v-col
            cols="6"
            sm="4"
            md="6"
          >
            <v-card
              class="pa-4"
              height="80"
            >
              <a
                href="https://accountflow.no"
                target="blank"
              >
                <v-img src="/accountflow_logo.png" />
              </a>
            </v-card>
          </v-col>

          <v-col
            cols="6"
            sm="4"
            md="6"
          >
            <v-card
              class="pa-4"
              height="80"
            >
              <a
                href="https://sharebox.no"
                target="blank"
              >
                <v-img src="/sharebox_logo.png" />
              </a>
            </v-card>
          </v-col>

          <v-col
            cols="6"
            sm="4"
            md="6"
          >
            <v-card
              class="pa-4"
              height="80"
            >
              <a
                href="https://www.visualyst.co"
                target="blank"
              >
                <v-img src="/Visualyst_Logo_Blue_Landscape.png" />
              </a>
            </v-card>
          </v-col>

          <v-col
            cols="6"
            sm="4"
            md="6"
          >
            <v-card
              class="pa-4"
              height="80"
            >
              <a
                href="https://luado.no"
                target="blank"
              >
                <v-img
                  src="/luado_logo.png"
                  height="50"
                />
              </a>
            </v-card>
          </v-col>

          <v-col
            cols="6"
            sm="4"
            md="6"
          >
            <v-card
              class="pa-4"
              height="80"
            >
              <a
                href="https://www.getlivly.com/"
                target="blank"
              >
                <v-img
                  src="/livly_logo.svg"
                  height="50"
                  width="95"
                  class="mx-auto"
                />
              </a>
            </v-card>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped lang="scss">
a {
  font-family: sans-serif;
  text-decoration: none;
}
</style>
