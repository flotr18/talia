<template>
  <div class="container-fluid">
    <div class="row">
      <div class="dropdown">
  <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
    Dropdown button
  </button>
  <ul class="dropdown-menu">
    <li><a class="dropdown-item" href="#">ChatGPT</a></li>
    <li><a class="dropdown-item" href="#">Gemini</a></li>
    <li><a class="dropdown-item" href="#">Mistral</a></li>
  </ul>
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