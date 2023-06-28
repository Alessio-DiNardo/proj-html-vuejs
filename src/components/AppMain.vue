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
        <div class="card">
            <img src="../assets/img/law_7.jpg" alt="img">
            <h2>international</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incidunt ut labore. Sadips ipsums et dolores ficilis ametis uns etras.</p>
        </div>
        <div class="card">
            <img src="../assets/img/law_8.jpg" alt="img">
            <h2>international</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incidunt ut labore. Sadips ipsums et dolores ficilis ametis uns etras.</p>
        </div>
        <div class="card">
            <img src="../assets/img/law_3.jpg" alt="img">
            <h2>international</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incidunt ut labore. Sadips ipsums et dolores ficilis ametis uns etras.</p>
        </div>
    </div>
</section>
<section class="work">
    <div class="content">
        <h1>let's work together</h1>
        <div class="line"></div>
        <p>We work as a single united team with market leading firms around the world and give our clients the highest quality advice possible.</p>
        <button>make enquiry</button>
    </div>
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
        height: 800px;
    }
    div.container-container-card{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 580px;
    }
    div.card{
        width: 375px;
        height: 580px;
        background-color: white;
        border: 1px solid rgb(211, 203, 203);
        text-align: center;
        margin-top: 12rem;

        img{
            width: 270px;
            text-align: center;
            padding-top: 2rem;

            img:hover{
            transform: scale(1.3);
            z-index: 2;
        }
        }

        h2{
            color: $fourColor;
            text-transform: uppercase;
            font-size: 1.3rem;
            padding: 1.3rem 1.3rem
        }

        p{
            padding-right: 2.3rem;
            padding-left: 2.3rem;
            font-size: 1.2rem;
        }
    }
    
    section.work{
        width: 100%;
        height: 500px;
        background-image: url('../assets/img/where-we-work-parallax.jpg');
        background-position: bottom;
        background-size: cover;


        div.content{
            color: white;
            text-align: center;
            padding-top: 10rem;
        }

        h1{
            font-size: 1.7rem;
            text-transform: uppercase;
            padding-bottom: 2rem;
        }

        p{
            font-size: 1.2rem;
            padding: 2rem 
        }

        button{
        border: none;
        background-color: $firstColor;
        padding: 1rem 2rem 1rem 2rem;
        color: white;
        text-transform: uppercase;
        font-size: 0.9rem;
        font-weight: bold;
        }

        button:hover{
            background-color: $sevenColor;
        }
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