<template>
    <div class="green-line"></div>
    <div class="background">
        <div class="container">
            <section class="header-top">
                <div>
                    <p>
                        Avada & Associates legal team announce deal to open up oil & gas
                    </p>
                </div>
                <div>
                    <ul class="icons">
                        <li><i class="fa-brands fa-square-facebook"></i></li>
                        <li><i class="fa-brands fa-square-twitter"></i></li>
                        <li><i class="fa-brands fa-square-instagram"></i></li>
                        <li><i class="fa-brands fa-square-youtube"></i></li>
                    </ul>
                </div>
            </section>
        </div>
        <section class="header-bot">
            <div class="container">
                <div class="bar">
                    <img src="" alt="">
                    <nav class="menù">
                        <ul>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                        </ul>
                    </nav>
                </div>
            </div>
            </section>
    </div>
</template>
<script>
export default {
    name: 'AppHeader'
}
</script>
<style lang="scss" scoped>
    @use '../styles/partials/mixins' as*;
    @use '../styles/partials/variables' as*;

    section.header-top{
        display: flex;
        justify-content: space-between;
        padding-top: 0.75rem;
    }

    section.header-bot{
        background-color: orange;
        width: 100%;
        height: 300px;
    }

    div.background{
        background-color: $secondColor;
        width: 100%;
        height: 50px;
    }

    ul.icons{
        display: flex;
        color: $firstColor;
        font-size: 1.5rem;
    }
    
    div.green-line{
        background-color: $firstColor;
        width: 100%;
        height: 5px;
    }
</style>