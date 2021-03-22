<template>
  <div class="card">
    <div class="card-content">
      <div class="row valign-wrapper">
        <grid-vue tamanho="4">
          <img
            src="http://materializecss.com/images/yuna.jpg"
            alt=""
            class="circle responsive-img"
          />
          <!-- notice the "circle" class -->
        </grid-vue>
        <grid-vue tamanho="8">
          <span class="black-text">
            <h5>Maria</h5>
            This is a square image. Add the "circle" class to it to make it
            appear circular.
          </span>
        </grid-vue>
      </div>
    </div>
    <div class="card-action">
      <a href="#">This is a link</a>
      <a href="#">This is a link</a>
    </div>
  </div>
</template>

<script>
import GridVue from "@/components/layouts/GridVue";
export default {
  name: "CardConteudoVue",
  props: [],
  data() {
    return {};
  },
  components: {
    GridVue,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>