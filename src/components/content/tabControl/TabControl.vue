<template>
  <div class="tab-control">
      <div v-for="item in titles " :key="item.id">
          <span>{{item}}</span>
      </div>
  </div>
</template>

<script>
export default {
  name: 'TabControl',
  props: {
    titles:{
      type:Array,
      default(){
          return []
      }
    }
  },
  data() {
    return {
    };
  },
  computed:{
  },
  watch:{
  },
  methods: {},
};
</script>

<style scoped>

</style>
