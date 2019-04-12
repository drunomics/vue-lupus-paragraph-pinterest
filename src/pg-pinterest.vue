<template>
  <div class="paragraph paragraph--pinterest">
    <slot :name="$slots.title ? 'title': 'default'" />
    <div class="pinterest-post">
      <a
        data-pin-do="embedPin"
        :href="src"
      />
    </div>
  </div>
</template>
<script>
// <script async defer src="//assets.pinterest.com/js/pinit.js">
export default {
  name: 'PgPinterest',
  props: {
    src: { type: String, default: () => '' }
  },
  created () {
    if (this.src !== '') {
      // Via v-html <script> does not get executed so we need to add this element here manually.
      const script = document.createElement('script')
      script.src = '//assets.pinterest.com/js/pinit.js'
      script.async = true
      script.defer = true
      document.head.appendChild(script)
    }
  }
}
</script>
