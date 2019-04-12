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
export default {
  name: 'PgPinterest',
  props: {
    src: { type: String, default: () => '' }
  }
}
</script>
