<template >
  <!-- Our Blogs -->
  <div data-type="Group" data-name="Our Blogs" class="Our_Blogs_Class">
    <div data-type="Group" data-name="Our Blo" class="Our_Blo_Class">
      <svg datatype="Line" data-name="Line 3" class="Line_3" viewBox="0 0 140 2">
        <path
          fill="transparent"
          stroke="rgba(120,59,9,1)"
          stroke-width="2px"
          stroke-linejoin="miter"
          stroke-linecap="butt"
          stroke-miterlimit="4"
          shape-rendering="auto"
          class="Line_3_Class"
          d="M 0 0 L 140 0"
        />
      </svg>
      <div data-type="Text" data-name="title-our" class="title_our_Class">
        <span>Our Blogs</span>
      </div>
      <div data-type="Text" data-name="text-our" class="text_our_Class">
        <span>An insight to the incredible experiences in the world</span>
      </div>
    </div>
	
    <div data-type="Group" data-name="Group-our-1" class="Group_our_1_Class">
      <div data-type="Text" data-name="title-our-1" class="title_our_1_Class">
       <span>{{posts[1].header}}</span>
      </div>
      <div data-type="Text" data-name="text-our-1" class="text_our_1_Class">
         <span>{{posts[1].content}}</span>
      </div>

      <div data-type="Group" data-name="read-more-1" class="read_more_1_Class">
        <div data-type="Text" data-name="Read More-our-1" class="Read_More_our_1_Class">
          <span>Read More</span>
        </div>
        <svg
          datatype="Path"
          data-name="Icon-arrow-1"
          class="Icon_arrow_1"
          viewBox="11.246 6.196 8.105 14.176"
        >
          <path
            fill="rgba(205,104,20,1)"
            class="Icon_arrow_1_Class"
            d="M 16.90829658508301 13.28146743774414 L 11.54403114318848 7.921422004699707 C 11.14730262756348 7.524694442749023 11.14730262756348 6.883176803588867 11.54403114318848 6.490669727325439 C 11.94075775146484 6.098162651062012 12.582275390625 6.098162651062012 12.97900390625 6.490669727325439 L 19.0565357208252 12.5639820098877 C 19.44060134887695 12.94804763793945 19.44904327392578 13.56424140930176 19.08607864379883 13.96096801757813 L 12.9832239151001 20.07648658752441 C 12.7848596572876 20.27485084533691 12.52318859100342 20.37192153930664 12.26573753356934 20.37192153930664 C 12.00828647613525 20.37192153930664 11.74661540985107 20.27485084533691 11.54825115203857 20.07648658752441 C 11.15152359008789 19.67975807189941 11.15152359008789 19.03824234008789 11.54825115203857 18.64573287963867 L 16.90829658508301 13.28146743774414 Z"
          />
        </svg>
      </div>
      <img
        data-type="Rectangle"
        data-name="Rectangle 31"
        class="Rectangle_31_Class"
      :src="posts[1].image"
      />
    </div>

    <div data-type="Group" data-name="Group-our-4" class="Group_our_4_Class">
      <div data-type="Text" data-name="title-our-4" class="title_our_4_Class">
         <span>{{posts[4].header}}</span>
      </div>
      <div data-type="Text" data-name="text-our-4" class="text_our_4_Class">
        <span>
        {{posts[4].content}}
        </span>
      </div>
      <img
        data-type="Rectangle"
        data-name="Rectangle 34"
        class="Rectangle_34_Class"
        :src="posts[4].image"
      />
      <div data-type="Group" data-name="read-more-4" class="read_more_4_Class">
        <div data-type="Text" data-name="Read More-our-4" class="Read_More_our_4_Class">
          <span>Read More</span>
        </div>
        <svg
          datatype="Path"
          data-name="Icon-arrow-4"
          class="Icon_arrow_4"
          viewBox="11.246 6.196 8.105 14.176"
        >
          <path
            fill="rgba(205,104,20,1)"
            class="Icon_arrow_4_Class"
            d="M 16.90829658508301 13.28146743774414 L 11.54403114318848 7.921422004699707 C 11.14730262756348 7.524694442749023 11.14730262756348 6.883176803588867 11.54403114318848 6.490669727325439 C 11.94075775146484 6.098162651062012 12.582275390625 6.098162651062012 12.97900390625 6.490669727325439 L 19.0565357208252 12.5639820098877 C 19.44060134887695 12.94804763793945 19.44904327392578 13.56424140930176 19.08607864379883 13.96096801757813 L 12.9832239151001 20.07648658752441 C 12.7848596572876 20.27485084533691 12.52318859100342 20.37192153930664 12.26573753356934 20.37192153930664 C 12.00828647613525 20.37192153930664 11.74661540985107 20.27485084533691 11.54825115203857 20.07648658752441 C 11.15152359008789 19.67975807189941 11.15152359008789 19.03824234008789 11.54825115203857 18.64573287963867 L 16.90829658508301 13.28146743774414 Z"
          />
        </svg>
      </div>
    </div>
    <div data-type="Group" data-name="Group-our-3" class="Group_our_3_Class">
      <div data-type="Text" data-name="title-our-3" class="title_our_3_Class">
         <span>{{posts[4].header}}</span>
      </div>
      <div data-type="Text" data-name="text-our-3" class="text_our_3_Class">
        <span>
           {{posts[4].content}}
        </span>
      </div>
      <img
        data-type="Rectangle"
        data-name="Rectangle 33"
        class="Rectangle_33_Class"
        :src="posts[3].image"
      />
      <div data-type="Group" data-name="read-more-3" class="read_more_3_Class">
        <div data-type="Text" data-name="Read More-our-3" class="Read_More_our_3_Class">
         <span>{{posts[2].header}}</span>
        </div>
        <svg
          datatype="Path"
          data-name="Icon-arrow-3"
          class="Icon_arrow_3"
          viewBox="11.246 6.196 8.105 14.176"
        >
          <path
            fill="rgba(205,104,20,1)"
            class="Icon_arrow_3_Class"
            d="M 16.90829658508301 13.28146743774414 L 11.54403114318848 7.921422004699707 C 11.14730262756348 7.524694442749023 11.14730262756348 6.883176803588867 11.54403114318848 6.490669727325439 C 11.94075775146484 6.098162651062012 12.582275390625 6.098162651062012 12.97900390625 6.490669727325439 L 19.0565357208252 12.5639820098877 C 19.44060134887695 12.94804763793945 19.44904327392578 13.56424140930176 19.08607864379883 13.96096801757813 L 12.9832239151001 20.07648658752441 C 12.7848596572876 20.27485084533691 12.52318859100342 20.37192153930664 12.26573753356934 20.37192153930664 C 12.00828647613525 20.37192153930664 11.74661540985107 20.27485084533691 11.54825115203857 20.07648658752441 C 11.15152359008789 19.67975807189941 11.15152359008789 19.03824234008789 11.54825115203857 18.64573287963867 L 16.90829658508301 13.28146743774414 Z"
          />
        </svg>
      </div>
    </div>
    <div data-type="Group" data-name="Group-our-2" class="Group_our_2_Class">
      <div data-type="Text" data-name="title-our-2" class="title_our_2_Class">
         <span>{{posts[4].header}}</span>
      </div>
      <div data-type="Text" data-name="text-our-2" class="text_our_2_Class">
        <span>
          {{posts[2].content}}
        </span>
      </div>
      <img
        data-type="Rectangle"
        data-name="Rectangle 32"
        class="Rectangle_32_Class"
        :src="posts[2].image"
      />
      <div data-type="Group" data-name="read-more-2" class="read_more_2_Class">
        <div data-type="Text" data-name="Read More-our-2" class="Read_More_our_2_Class">
          <span>Read More</span>
        </div>
        <svg
          datatype="Path"
          data-name="Icon-arrow-2"
          class="Icon_arrow_2"
          viewBox="11.246 6.196 8.105 14.176"
        >
          <path
            fill="rgba(205,104,20,1)"
            class="Icon_arrow_2_Class"
            d="M 16.90829658508301 13.28146743774414 L 11.54403114318848 7.921422004699707 C 11.14730262756348 7.524694442749023 11.14730262756348 6.883176803588867 11.54403114318848 6.490669727325439 C 11.94075775146484 6.098162651062012 12.582275390625 6.098162651062012 12.97900390625 6.490669727325439 L 19.0565357208252 12.5639820098877 C 19.44060134887695 12.94804763793945 19.44904327392578 13.56424140930176 19.08607864379883 13.96096801757813 L 12.9832239151001 20.07648658752441 C 12.7848596572876 20.27485084533691 12.52318859100342 20.37192153930664 12.26573753356934 20.37192153930664 C 12.00828647613525 20.37192153930664 11.74661540985107 20.27485084533691 11.54825115203857 20.07648658752441 C 11.15152359008789 19.67975807189941 11.15152359008789 19.03824234008789 11.54825115203857 18.64573287963867 L 16.90829658508301 13.28146743774414 Z"
          />
        </svg>
      </div>
    </div>
  </div>
</template>



<script>

export default {
    name: 'OurBlogs',
    components: {  },
    data() {
        return {
       posts: []
        }
	},
	 async  fetch() {
		this.posts =  await this.$axios.$get(process.env.URL_DEFAULT + '/Blog')

 	 },
}
</script>
<style lang="css">
</style>