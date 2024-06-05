<!-- home -->
<template>
  <div>
    <div>首页</div>
    <foot-bar :active="tabActive"></foot-bar>
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {
    footBar: () => import('@/components/footBar')
  },
  data() {
    return {
      tabActive: 0
    }
  },
  created() {

  },
  computed: {},

  mounted() {},

  methods: {

  }
}
</script>
