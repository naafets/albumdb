<template>
  <div class="container">
    <section class="section">
      <div class="columns">
        <div class="column">
          <b-message :active.sync="isActive" class="has-text-weight-normal message-red is-white">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id fermentum quam. Proin sagittis, nibh id hendrerit imperdiet, elit sapien laoreet elit
          </b-message>
        </div>
        <div class="column">
          <b-message :active.sync="isActive" class="has-text-weight-normal message-orange is-white">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id fermentum quam. Proin sagittis, nibh id hendrerit imperdiet, elit sapien laoreet elit
          </b-message>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  components: {}
}
</script>

<style>
.message-red {
  border: 0.02rem solid gray;
  border-left: 3px solid #917e7e !important;
}
.message-orange {
  border: 0.02rem solid gray;
  border-left: 3px solid #8b3c3c !important;
}
</style>
