<template>
    <div class="container">
        <p>Call our experrts today 1.800.555.6789</p>
        <section class="footer">
                <div>
                    <p>
                        <i class="fa-regular fa-copyright"></i>Copyright 2012-2023 | <span class="green">Avada Website Builder</span> by <span class="green">ThemFusion</span> | All Rights reserrved | Powererd by <span class="green">WordPress</span>
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
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
    @use '../styles/partials/mixins' as*;
    @use '../styles/partials/variables' as*;

    p{
        color: $fourColor;
        font-size: 1.2rem;
        text-transform: uppercase;
        padding-top: 1.5rem;
    }
    section.footer{
        height: 130px;
        display: flex;
        justify-content: space-between;
        padding-top: 3rem;

        p{
            font-size: 0.8em;
            color: grey;

            i{
                padding: 0.2rem;
                font-size: 0.7rem;
            }
            span{
                color: $firstColor;
            }
        }
    }

    ul.icons{
        display: flex;
        color: $firstColor;
        font-size: 1.7rem;
    }
</style>