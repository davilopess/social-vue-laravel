<template>

<span>

  <div class="row">
        <grid-vue class="input-field" tamanho="12">
          <textarea id="textarea1" class="materialize-textarea"></textarea>
          <label for="textarea1">Textarea</label>
        </grid-vue>

        <p>
          <grid-vue class="btn waves-effect waves-light" tamanho="2 offset-s10">Publicar</grid-vue>
        </p>
  </div>

  <card-conteudo-vue
    perfil="http://materializecss.com/images/yuna.jpg"
    nome="Maria"
    data="12/08/2021 13:00"
  >

    <card-detalhe-vue 
      img="http://materializecss.com/images/sample-1.jpg" 
      titulo = ""
      txt="I am a very simple card. I am good at containing small bits of
        information. I am convenient because I require little markup to use
        effectively."      
      />
  </card-conteudo-vue>
</span>
</template>

<script>
import CardConteudoVue from "@/components/social/CardConteudoVue";
import CardDetalheVue from "@/components/social/CardDetalheVue";
import GridVue from "@/components/layouts/GridVue";

export default {
  name: "Home",
  data() {
    return {};
  },
  components: {
    CardConteudoVue,
    CardDetalheVue,
    GridVue
  },
};
</script>

<!-
    CardConteudoVue- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
