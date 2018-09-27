<template>
  <div id="div">
    hahaha
  </div>
</template>

<script>
export default {
    name: "",
    data() {
        return {};
    },
    methods: {},
    watch: {
        asyncArray: function() {
            this.$nextTick(function() {
                //////方法
                console.log($("#div").text());
            });
        }
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
