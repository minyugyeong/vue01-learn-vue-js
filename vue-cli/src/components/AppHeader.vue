<template>
  <header>
    <h1>{{ propsdata }}</h1>
    <button v-on:click="sendEvent">send</button>
  </header>
</template>

<script>
export default {
  props: ['propsdata'],

  data() {
    return {
      
    };
  },

  mounted() {
    
  },

  methods: {
    sendEvent: function(){
      this.$emit('renew')
    }
  },
};
</script>

<style lang="scss" scoped>

</style>