# tiptap-component
Vue.js component for TipTap (Based on tiptap.dev examples)


![screenshot](./sample.png?raw=true "screenshot")
![screenshot](./insertimage.png?raw=true "screenshot")
![screenshot](./insertvideo.png?raw=true "screenshot")


# Demo

https://genonfire.github.io/tiptap-component/


# Install
tiptap and tiptap-extensions required (if not installed)

    npm install tiptap tiptap-extensions


# How to

    Copy assets/images/icons, assets/sass and src/components to your repository


# Usage
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
        editable: true,
        supportImage: true,
        supportVideo: true
      }
    }
  }
}
</script>
```

- based on vuetify
- File upload API should be implemented to support image upload
