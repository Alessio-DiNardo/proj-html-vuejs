<template>
<div class="background">
    <section class="text">
        <h1>
            Lawyerrs with a global reputation
        </h1>
        <h3>Contantly challenging ourselves to delive moe to our clients</h3>
        <button>
            Let's get started
        </button>
    </section>
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
        height: 460px;
        background-image: url('../assets/img/video_law_home_preview.jpg');
    }

    section.text{
        color: white;
        text-align: center;
        padding-top: 10rem;
        
        h1{
            padding-bottom: .8rem;
            font-size: 2.5rem;
            text-transform: uppercase;
        }

        h3{
            font-size: 1rem;
            text-transform: uppercase;
            padding-bottom: 3rem
        }
    }

    button{
        border: none;
        background-color: $firstColor;
        padding: 1.2rem 5rem 1.2rem 5rem;
        color: white;
        text-transform: uppercase;
        font-size: 1rem;
    }
</style>