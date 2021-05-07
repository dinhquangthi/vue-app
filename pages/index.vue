<template>
<div>
<PopularPost/>
<Offers/>
<OurBlogs/>
</div>
</template>

<script>
import PopularPost from '@/components/PopularPost/PopularPost.vue'
import Offers from '@/components/Offers/Offers.vue'
import OurBlogs from '@/components/OurBlogs/OurBlogs.vue'
export default {
  components: {
    PopularPost,
    Offers,
    OurBlogs
  }

}
</script>
