<template>
<section class="spam">
    <div class="container">
        <img src="" alt="">
        <p>"We have worked with Avada Law for the past 15 years. As we have grown and evolved, what i have valued most about our relationship is that Avada Law know us and our business"</p>
        <p>Nigel Rawlinson . Senior Partner </p>
    </div>
</section>
<section class="background">
    <div class="container-container-card">
        <div class="card"></div>
        <div class="card"></div>
        <div class="card"></div>
    </div>
</section>
<section class="work">
    <h1></h1>
    <div class="line"></div>
    <p></p>
    <button></button>
</section>

</template>
<script>
export default {
    name: 'AppMain'
}
</script>
<style lang="scss" scoped>
    @use '../styles/partials/mixins' as*;
    @use '../styles/partials/variables' as*;

    section.spam{
        width: 100%;
        background-color: blue;
        height: 120px;
        
    }

    section.background{
        background-color: $sixColor;
        width: 100%;
        height: 400px;
    }
    div.container-container-card{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 500px;
    }
    div.card{
        width: 375px;
        height: 300px;
        background-color: red;
        border: 1px solid black;
        margin-bottom: 4rem;
    }
    section.work{
        width: 100%;
        height: 300px;
        background-color: blue;
    }
</style>