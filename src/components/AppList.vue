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
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
            </div>
            <div class="column">
                <h2>OUR PRRACTICE AERAS</h2>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
            </div>
            <div class="column">
                <h2>OU PUBLICATION</h2>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
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
        height: 800px;
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
        
        border: 1px solid black;
    }

    div.column{
        border: 1px solid black;
        
    }

    div.card{
        width: 180px;
        height: 50px;
        background-color: red;
        border: 1px solid black;
        margin: 1rem 0 1rem 0;
    }
</style>