<template>
<div class="background">
    <div class="container-container-card">
        <div class="card"></div>
        <div class="card"></div>
        <div class="card"></div>
    </div>
</div>
<section class="check">
    <div class="container-container-check">
        <div class="show"></div>
        <div class="show"></div>
        <div class="show"></div>
        <div class="show"></div>
    </div>
</section>
<section class="green">
    <div class="container-container-green">
        <p>Questions abount a judicial issue? ask our experts</p>
        <button>
            ask an expert
        </button>
    </div>
</section>
</template>
<script>
export default {
    name: 'AppMenu'
}
</script>
<style lang="scss" scoped>
    @use '../styles/partials/mixins' as*;
    @use '../styles/partials/variables' as*;

    div.background{
        width: 100%;
        height: 500px;
        background-color: $secondColor;
    }

    div.container-container-check{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 500px;
    }

    div.container-container-card{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 500px;
    }

    div.container-container-green{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 150px;
    }

    div.card{
        width: 375px;
        height: 300px;
        background-color: red;
        border: 1px solid black;
    }

    section.check{
        background-color: $sixColor;
        width: 100%;
        height: 350px;
    }

    section.green{
        background-color: $firstColor;
        width: 100%;
        height: 160px;
    }

    div.show{
        width: 200px;
        height: 130px;
        background-color: blue;
        border: 1px solid black;
        margin-bottom: 9rem;

    }

</style>