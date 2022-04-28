<template lang="pug">
  v-row(justify="center" align="center")
    v-col(cols="12" sm="8" md="6")
      v-card.logo.py-4.d-flex.justify-center
        NuxtLogo
        VuetifyLogo
      v-card
        v-card-title.headline Welcome to the Vuetify + Nuxt.js template
        v-card-text
          p Vuetify is a progressive Material Design component framework for Vue.js. It was designed to empower developers to create amazing applications.
          p For more information on Vuetify, check out the
            a(
              href="https://vuetifyjs.com"
              target="_blank"
              rel="noopener noreferrer"
            ) documentation
            span .
          p If you have questions, please join the official
            a(
              href="https://chat.vuetifyjs.com/"
              target="_blank"
              rel="noopener noreferrer"
              title="chat"
            ) discord
            span .
        v-card-actions
          v-spacer
          v-btn(
            color="primary"
            nuxt
            to="/inspire"
          ) Continue
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
