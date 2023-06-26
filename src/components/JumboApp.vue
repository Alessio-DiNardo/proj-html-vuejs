<template>
<div class="background">

</div>
</template>
<script>
export default {
    name: 'JumboApp'
}
</script>
<style lang="scss" scoped>
    @use '../styles/partials/mixins' as*;
    @use '../styles/partials/variables' as*;

    div.background{
        width: 100%;
        height: 600px;
        background-color: blue;
    }
</style>