<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div class="text-center">
        <logo />
        <vuetify-logo />
      </div>
      <v-card>
        <v-card-title class="headline">
          Добро пожаловать в шаблон Vuetify + Nuxt.js
        </v-card-title>
        <v-card-text>
          <p>Vuetify - это компонентный фреймворк прогрессивного дизайна материалов для Vue.js. Он был разработан, чтобы дать разработчикам возможность создавать потрясающие приложения.</p>
          <p>
              Для получения дополнительной информации о Vuetify ознакомьтесь с <a
              href="https://vuetifyjs.com"
              target="_blank"
              rel="noopener noreferrer"
            >
              документацией
            </a>.
          </p>
          <p>
              Если у вас есть вопросы, присоединяйтесь к официальному <a
              href="https://chat.vuetifyjs.com/"
              target="_blank"
              rel="noopener noreferrer"
              title="chat"
            >
              discord
            </a>.
          </p>
          <p>
              Нашли ошибку? Сообщите об этом на github <a
              href="https://github.com/vuetifyjs/vuetify/issues"
              target="_blank"
              rel="noopener noreferrer"
              title="contribute"
            >
              Перейти на github
            </a>.
          </p>
          <p>Спасибо за разработку с Vuetify, и я с нетерпением жду возможности предложить больше интересных функций в будущем.</p>
          <div class="text-xs-right">
            <em><small>&mdash; John Leider</small></em>
          </div>
          <hr class="my-3">
          <a
            href="https://nuxtjs.org/"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt Документация
          </a>
          <br>
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt GitHub
          </a>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Продолжить
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
