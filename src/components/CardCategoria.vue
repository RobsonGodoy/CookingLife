<script lang="ts">
export default {
    props: {
        categoria: { type: Object, required: true }
    }
}
</script>

<template>
    <article class="categoria">
        <header class="categoria__cabecalho">
            <img :src="`/imagens/icones/categorias_ingredientes/${categoria.imagem}`" alt="" class="categoria__imagem">
        </header>
    </article>
</template>
