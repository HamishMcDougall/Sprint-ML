<template>
  <div>
    <navbar/>
      <div class="container navbaroffset">
              <div class="columns">
          <div class="column">
            First column
          </div>
          <div class="column">
            Second column
          </div>
          <div class="column">
            Third column
          </div>
          <div class="column">
            Fourth column
          </div>
    </div>
      </div>
    <pageFooter/>
  </div>
</template>

<script>
  import navbar from '~/components/navbar.vue'
  import pageFooter from '~/components/footer.vue'
  
  export default {
    components: {
      navbar,
      pageFooter
    }
  }
</script>

<style>
.navbaroffset{
  padding-top: 52px;
}
</style>
