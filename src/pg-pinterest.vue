<template>
  <div class="paragraph paragraph--pinterest">
    <div class="paragraph__field-media">
      <a
        data-pin-do="embedPin"
        :href="dataPinterestUrl"></a>
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
