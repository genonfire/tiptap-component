# tiptap-component
Vue.js component for TipTap (Based on tiptap.dev examples)


![screenshot](./sample.png?raw=true "screenshot")


# Install
tiptap and tiptap-extensions required (if not installed)

    npm install tiptap tiptap-extensions


# How to

    Copy assets/images/icons, assets/sass and src/components/TipTap.vue to your repository


# Example
Please refer src/components/SampleEditor.vue
```vue
<template>
  <TipTap
    :options="options"
  />
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
        content: 'default text',
        editable: true
      }
    }
  }
}
</script>
```


# Demo

https://genonfire.github.io/tiptap-component/
