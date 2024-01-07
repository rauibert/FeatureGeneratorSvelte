<script>
  import Formulario from "./formulario.svelte";
  let name = "Svelte";
  let cod_feature = "";
</script>




<h1>Feature Generator Svelte</h1>

<h2>Hola {name}</h2>
<div class="formulario">
  <Formulario />
</div>


<main>
  Feature: {cod_feature}
  
</main>


<style>
.formulario{
    width: 80%;
    margin: 0 auto;
  }
</style>