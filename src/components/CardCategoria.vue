<script lang="ts">
export default {
  props: {
     categoria: { type: Object as PropType<ICategoria>, required: true}
  }
}
</script>

<template>
    <article class="categoria">
        <header class="categoria__cabecalho">
            <img src="" alt="" class="acategoria__imagem">
        </header>
    </article>
  </template>