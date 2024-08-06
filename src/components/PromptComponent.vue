<template>
  <div class="container">
    <div class="row">
      <div class="col-6 first">
          jack 
      </div>
      <div class="col-6 second">
        sparrow
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'PromptComponent',
    data() {
      return {
        message : ''
      }
    },
    computed: {},
    mounted() {},
    methods: {}
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

.first {
  background-color: blue;
}

.second {
  background-color: red;
}

</style>