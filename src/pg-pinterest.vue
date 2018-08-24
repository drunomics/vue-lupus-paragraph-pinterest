<template>
  <div class="paragraph paragraph--pinterest">
    <div class="paragraph__field-media">
      <a
        data-pin-do="embedPin"
        :href="dataUrl"></a>
    </div>
  </div>
</template>
<script>
  export default {
    name: 'PgPinterest',
    props: {
      dataUrl: { type: String, default: () => '' },
    },
  };
</script>
