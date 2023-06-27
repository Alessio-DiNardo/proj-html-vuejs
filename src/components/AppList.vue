<template>
<section class="background">
    <div class="container">
        <h1>
            GLOBAL CHALLENGE. WORLD CLASS RESPONSE
        </h1>
        <div class="line"></div>
        <div class="table">
            <div class="column">
                <h2>OUR PEOPLE</h2>
                <div class="card">
                    <img src="../assets/img/column1-image1.jpg" alt="Image">
                    <p>Deborah Brown</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column1-image2.jpg" alt="Image">
                    <p>Allen Lucas</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column1-image3.jpg" alt="Image">
                    <p>Muriel Potter</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column1-image4.jpg" alt="Image">
                    <p>Ken Douglas</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column1-image5.jpg" alt="Image">
                    <p>Loretta Harris</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column1-image6.jpg" alt="Image">
                    <p>Phil Russell</p>
                </div>
            </div>
            <div class="column">
                <h2>OUR PRRACTICE AERAS</h2>
                <div class="card">
                    <img src="../assets/img/column2-image1.jpg" alt="Image">
                    <p>Tax Litigation</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column2-image2.jpg" alt="Image">
                    <p>Aquisitions</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column2-image3.jpg" alt="Image">
                    <p>Financial Advice</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column2-image4.jpg" alt="Image">
                    <p>International</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column2-image5.jpg" alt="Image">
                    <p>Oil and Gas</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column2-image6.jpg" alt="Image">
                    <p>Capital Markets</p>
                </div>
            </div>
            <div class="column">
                <h2>OU PUBLICATION</h2>
                <div class="card">
                    <img src="../assets/img/column3-image1.jpg" alt="Image">
                    <p>Low Oil Prices</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column3-image2.jpg" alt="Image">
                    <p>Cost of Divorce</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column3-image3.jpg" alt="Image">
                    <p>2015 Tax Laws</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column3-image4.jpg" alt="Image">
                    <p>Surveys Matter</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column3-image5.jpg" alt="Image">
                    <p>In-House Work</p>
                </div>
                <div class="card">
                    <img src="../assets/img/column3-image6.jpg" alt="Image">
                    <p>Ana Thompson</p>
                </div>
            </div>
        </div>
    </div>

</section>
</template>
<script>
export default {
    name: 'AppList'
}
</script>
<style lang="scss" scoped>
    @use '../styles/partials/mixins' as*;
    @use '../styles/partials/variables' as*;

    section.background{
        background-color: $sixColor;
        width: 100%;
        height: 900px;
        
    }

    h1{
        text-align: center;
        padding-top: 6rem;
        font-size: 2rem;
    }

    div.line{
        width: 150px; 
        height: 1px;
        background-color: grey;
        margin: 1.5rem auto;
    }

    div.table{
        display: flex;
        justify-content: space-between;
        margin-bottom: 2rem;
        
    }

    div.column{
        

        h2{
            font-size: 1.2rem;
            color: $fourColor;
        }
    }

    div.card{
        
        
        background-color: $secondColor;
        margin: 1rem 0 1rem 0;
        display: flex;
        padding: 1rem 7rem 1rem .5rem;

        img{
            width: 50px;
        }

        p{
            color: rgb(78, 77, 77);
            padding-top: .8rem;
            padding-left: 1rem;
        }
    }
</style>