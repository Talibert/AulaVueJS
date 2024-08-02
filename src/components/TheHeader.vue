<template>
    <header class="header">
        <HeaderButton/>
        <HeaderButton/>
        <HeaderButton/>
    </header>
</template>

<script>
import HeaderButton from './HeaderButton.vue';

export default {
    setup() {
        
    },
    components: {
        HeaderButton
    }
}
</script>

<style>
    .header {
        background: #000;
        color: #fff;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        padding: 3px;
    }
</style>