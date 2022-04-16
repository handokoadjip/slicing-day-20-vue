<template>
  <Content1Component />
  <Content2Component />
  <Content3Component />
</template>

<script>
import Content1Component from "@/components/Content1Component.vue";
import Content2Component from "@/components/Content2Component.vue";
import Content3Component from "@/components/Content3Component.vue";

export default {
  name: "HomePage",
  components: {
    Content1Component,
    Content2Component,
    Content3Component,
  },
  mounted() {
    document.title = "Designspiration | Valdama"
  }
}
</script>
