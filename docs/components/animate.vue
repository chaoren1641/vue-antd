<template lang="md">
<demo>
  <example title="通知信息">
    <div style="position: fixed; width: 100%; top: 50; z-index: 9999">
      <v-animate transition-name="fade">
        <p key="1">1</p>
        <p key="2">2</p>
      </v-animate>
    </div>
    <v-button @click="_show1">显示</v-button>
  </example>
</demo>
</template>

<script>
import vAnimate from '../../components/base/animate'
import vButton from '../../components/button'

export default {

  components: { vAnimate, vButton },

  methods: {
    _show1 () {

    }
  }

}

</script>
