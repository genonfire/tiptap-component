<template>
  <div>
    <div
      style="margin:10px;text-align:center;"
    >
      <h2>TipTap Component</h2>
    </div>

    <TipTap
      :options="options"
    />
  </div>
</template>

<script>
import TipTap from '@/components/TipTap'

export default {
  components: {
    TipTap
  },
  data () {
    return {
      options: {
        content: '<blockquote><p>Testing...</p></blockquote><ul><li><p><b>bold</b></p></li><li><p><i>italic</i></p></li><li><p><u>underline</u></p></li></ul>',
        editable: true
      }
    }
  }
}
</script>
