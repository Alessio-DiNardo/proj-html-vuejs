<template>
    <div class="green-line"></div>
    <div class="background">
        <div class="container">
            <section class="header-top">
                <div>
                    <p class="avada">
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
    </div>
    <section class="header-bot">
            <div class="container">
                <div class="bar">
                    <img src="../assets/img/avada-law-logo.png" alt="Logo">
                    <nav class="menù">
                        <ul class="list">
                            <li>Home</li>
                            <li>Who We Are</li>
                            <li>What We Do</li>
                            <li>Where We Work</li>
                            <li>Careers</li>
                            <li>News</li>
                            <li>Contact</li>
                        </ul>
                    </nav>
                </div>
            </div>
        </section>
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
        background-color: white;
        width: 100%;
        height: 110px;
    }

    div.background{
        background-color: $secondColor;
        width: 100%;
        height: 50px;
    }

    ul.icons{
        display: flex;
        color: $firstColor;
        font-size: 1.7rem;
    }
    
    div.green-line{
        background-color: $firstColor;
        width: 100%;
        height: 5px;
    }

    div.bar{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-top: 2rem;
    }

    ul.list{
        display: flex;

        li{
            padding: 0 1rem 0 2.6rem;
        }
    }

    p.avada{
        font-size: 0.9rem;
        padding-top: 0.2rem;
        color: grey;
    }
</style>