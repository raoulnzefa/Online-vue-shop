<template>
    <div class="v-catalog">
        <h1>Каталог</h1>
        <vCatalogItem></vCatalogItem>
    </div>
</template>

<script>
    import vCatalogItem from './v-catalog-item'
    export default {
        name: 'v-catalog',
        components: {
            vCatalogItem,
        }
    }
</script>

<style lang="scss" scoped>

</style>