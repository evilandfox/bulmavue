<template>
  <b-footer>
    <b-content class="has-text-centered">
      <p>
        <strong>Bulma</strong> by <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is licensed
        <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The website content
        is licensed <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY NC SA 4.0</a>.
      </p>
    </b-content>
  </b-footer>
</template>

<script lang="ts">
import {defineComponent} from 'vue'
import {BFooter, BContent} from '/@lib/'

export default defineComponent({
  components: {BFooter, BContent}
})
</script>
