<template>
  <i-frame :src="url" />
</template>

<script>
import  iFrame from "@/components/iFrame/index"
export default {
  name: "Nacos",
  components: { iFrame },
  data() {
    return {
      // url : '/nacos' + "/nacos/#"
      url: 'http://localhost:8848/nacos/#'
    }
  }
}
</script>

<style scoped>

</style>
