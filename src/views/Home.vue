<template>
  <div class="home h-screen ">
    
     <heading/>
     <featured/>
     <interesting/>
     <choose/>
     <story/>
     <foot/>
     <footing/>


  </div>
</template>

<script>
// @ is an alias to /src
import choose from "@/components/choose.vue"
import featured from  "@/components/featured.vue"
import  heading from "@/components/heading.vue"
import interesting from "@/components/interesting.vue"
import story from "@/components/story.vue"
import foot from "@/components/foot.vue"
import footing from "@/components/footing.vue"
export default {
  name: "Home",
  components: {
    heading,
    featured,
    interesting,
    choose,
    story,
    foot,
    footing

    
  }
};
</script>
