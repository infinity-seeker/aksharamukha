<template>
  <q-page padding>
    If you would like to know how to access the backend python API via REST, send a request to vinodh@virtualvinodh.com.
  </q-page>
</template>

<script>
import { QTooltip, QPageSticky } from 'quasar'
import { ScriptMixin } from '../mixins/ScriptMixin'
import Controls from '../components/Controls'
import Transliterate from '../components/Transliterate'

export default {
  // name: 'PageName',
  mixins: [ScriptMixin],
  components: {
    QTooltip,
    Controls,
    Transliterate,
    QPageSticky
  },
  data () {
    return {
      options: {script: 'IAST', sourcePreserve: false}
    }
  }
}
</script>

<style scoped>
.invoc {
  display:inline;
}
.invoc-img {
  margin-top: -30px;
  display:inline-block;
}
@font-face {
  font-family: Adinatha Tamil Brahmi;
  src: url('../statics/AdinathaTamilBrahmi2.otf');
}
@font-face {
  font-family: e-Brahmi T;
  src: url('../statics/e-Brahmi-T.ttf');
}
@font-face {
  font-family: e-Velvi;
  src: url('../statics/e-Velvi.ttf');
}
.quote {
  text-align: left;
  margin-right: 140px;
  --q-color-primary: #777;
}
</style>
