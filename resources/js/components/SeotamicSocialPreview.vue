<template>
  <SocialPreview
    :domain="meta.seotamic.preview_domain"
    :title="meta.seotamic.social_title"
    :image="meta.seotamic.social_image"
    :description="meta.seotamic.social_description"
  />
</template>

<script>
import Fieldtype from "./Fieldtype.vue";
import SocialPreview from "./seotamic/SocialPreview.vue";

export default {
  components: {
    SocialPreview,
  },

  mixins: [Fieldtype],

};
</script>
