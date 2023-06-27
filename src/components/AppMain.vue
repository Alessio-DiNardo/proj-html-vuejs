<template>
<section class="spam">
    <div class="container">
        <div class="text">
            <img src="../assets/img/envato-logo.png" alt="Envato logo">
            <p>"We have worked with Avada Law for the past 15 years. As we have grown and evolved, what i have valued most about our relationship is that Avada Law know us and our business"</p>
            <span><strong>Nigel Rawlinson . Senior Partner</strong></span>
        </div>
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
        background-image: url('../assets/img/showeare-parallax.jpg');
        height: 400px;
        background-image: bottom;
        
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

    div.text{
        text-align: center;
        color: white;
        font-size: 1.1rem;
        padding-top: 7rem;

        img{
            padding-bottom: 1.5rem;
        }

        p{
            padding-bottom: 1.8rem;
            line-height: 30px;
            font-size: 19px;
            text-align: center;
            letter-spacing: 2px;
            font-style: italic;
        }
    }
    
</style>