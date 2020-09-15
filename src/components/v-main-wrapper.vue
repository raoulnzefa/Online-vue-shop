<template>
    <div class="v-main-wrapper">
        <p>{{title}}</p>
        <vCatalog></vCatalog>
        <vCart></vCart>
    </div>
</template>

<script>
import vCatalog from './v-catalog'
import vCart from './v-cart'
export default {
    name: 'v-main-wrapper',
    data: () => ({
        title: 'Main wrapper'
    }),
    components: {
       vCatalog,
       vCart
    }
}
</script>

<style lang="scss">
.v-main-wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
    max-width: 900px;
    width: 100%;
    margin: 0 auto;
}
</style>