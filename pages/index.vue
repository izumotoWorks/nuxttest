<template lang="pug">
  .wrap
    .head
      header
        img(src="" alt="")
        
    .index--wrap
      .contents--index--wrap
        .section--wrap
          main
            section
              h1 記事タイトル
              h2 コンテンツタイトル
    .footer--wrap
      footer
        h1 フッターロゴ
    //- メニューコンポーネント
    GlobalMenu
  
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'
import GlobalMenu from '~/components/GlobalMenu.vue'

export default {
  components: {
    Logo,
    VuetifyLogo,
    GlobalMenu
  }
}
</script>

<style lang="scss">
  .head {
    h1 {
      color :#f0f;
      overflow:hidden;
      white-space:nowrap;
    }
  }
</style>