<template>
  <div class="app">
    <deni/>
    <juzent/>
    <smart-bridge/>
    <jForum/>
    <office/>
    <strayple/>
    <calendario/>
    <soyleu/>
    <tenge/>
    <sdu/>
    <hajj/>
    <xten/>
    <qos/>
    <bi/>
  </div>
</template>

<script>
import juzent from './views/juzent.vue'
import deni from './views/deni.vue'
import SmartBridge from './views/SmartBridge.vue'
import jForum from './views/jForum.vue'
import office from './views/office.vue'
import strayple from './views/strayple.vue'
import calendario from './views/calendario.vue'
import soyleu from './views/soyleu.vue'
import tenge from './views/tenge.vue'
import sdu from './views/sdu.vue'
import hajj from './views/hajj.vue'
import xten from './views/xten.vue'
import qos from './views/qos.vue'
import bi from './views/bi.vue'

export default {
  components: {
    juzent, 
    deni, 
    SmartBridge, 
    jForum, 
    office,
    strayple,
    calendario,
    soyleu,
    tenge,
    sdu,
    hajj,
    xten,
    qos,
    bi
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
p {
  margin: 0;
}
</style>
