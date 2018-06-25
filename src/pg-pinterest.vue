<template>
  <div class="paragraph paragraph--pinterest">
    <div class="paragraph__field-media">
      <slot name="field_media">
        <a
          data-pin-do="embedPin"
          :href="dataPinterestUrl"></a>
      </slot>
      <slot />
    </div>
  </div>
</template>
<script>
  export default {
    name: 'PgPinterest',
    props: {
      dataPinterestUrl: { type: String, default: () => '' },
    },
  };
</script>
