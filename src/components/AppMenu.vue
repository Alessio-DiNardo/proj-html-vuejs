<template>
<div class="background">
    <div class="container-container-card">
        <div class="card">
            <div class="line"></div>
            <div class="text">
                <h1>Who we are</h1>
                <p>
                    Nullam fringilla tristique elit id varius. Nulla lacinia quam nec venenatis dignissim. Vivamus volutpat tempus semper. Cras feugiat mi sit amet risus consectetur.
                </p>
                <button>
                    about us
                </button>
            </div>
        </div>
        <div class="card">
            <div class="line"></div>
            <div class="text">
                <h1>What we do</h1>
                <p>
                    Nullam fringilla tristique elit id varius. Nulla lacinia quam nec venenatis dignissim. Vivamus volutpat tempus semper. Cras feugiat mi sit amet risus consectetur.
                </p>
                <button>
                    our work
                </button>
            </div>
        </div>
        <div class="card">
            <div class="line"></div>
            <div class="text">
                <h1>where we work</h1>
                <p>
                    Nullam fringilla tristique elit id varius. Nulla lacinia quam nec venenatis dignissim. Vivamus volutpat tempus semper. Cras feugiat mi sit amet risus consectetur.
                </p>
                <button>
                    our offices
                </button>
            </div>
        </div>
    </div>
</div>
<section class="check">
    <div class="container-container-check">
        <div class="show">
            <div class="content">
                <span class="check">
                    <i class="fa-solid fa-check"></i>
                </span>
                <h2>
                    a global view
                </h2>
                <p>
                    Nullam fringilla tristique elit id varius ipsums. Lorem lacinia quam nec venenatis sadips dignissim.
                </p>
            </div>
        </div>
        <div class="show">
            <div class="content">
                <span class="check">
                    <i class="fa-solid fa-check"></i>
                </span>
                <h2>
                    a global view
                </h2>
                <p>
                    Nullam fringilla tristique elit id varius ipsums. Lorem lacinia quam nec venenatis sadips dignissim.
                </p>
            </div>
        </div>
        <div class="show">
            <div class="content">
                <span class="check">
                    <i class="fa-solid fa-check"></i>
                </span>
                <h2>
                    a global view
                </h2>
                <p>
                    Nullam fringilla tristique elit id varius ipsums. Lorem lacinia quam nec venenatis sadips dignissim.
                </p>
            </div>
        </div>
        <div class="show">
            <div class="content">
                <span class="check">
                    <i class="fa-solid fa-check"></i>
                </span>
                <h2>
                    a global view
                </h2>
                <p>
                    Nullam fringilla tristique elit id varius ipsums. Lorem lacinia quam nec venenatis sadips dignissim.
                </p>
            </div>
        </div>
        
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
        height: 180px;

        p{
            color: white;
            text-transform: uppercase;
            font-size: 1.8rem;
            margin-right: 8rem;
        }

        button{
            border: none;
            background-color: #3a8a82;
            padding: 1.2rem 2.5rem 1.2rem 2.5rem ;
            color: white;
            text-transform: uppercase;
            font-size: 1.2rem;
            
            // font-family: var(--button_typography-font-family);
            // font-style: var(--button_typography-font-style,normal);

        }

    }

    div.card{
        width: 375px;
        height: 300px;
        background-color: white;
        border: 1px solid $secondColor;
        text-align: center;
    }

    div.text{
        padding-top: 3rem;

        h1{
            font-size: 1.2rem;
            text-transform: uppercase;
            line-height: 1rem;
            color: $fourColor;
        }

        p{
            font-size: 1.1rem;
            padding: 1.8rem;
            line-height: 1.8rem;
            color: grey;
        }

        button{
            border: none;
            background-color: $fourColor;
            padding: 1rem 2.5rem 1rem 2.5rem;
            color: white;
            text-transform: uppercase;
            transition: all 0.2s ease-in-out
        }

        button:hover{
            background-color: $firstColor;
        }
    }
    section.check{
        background-color: $sixColor;
        width: 100%;
        height: 350px;
    }

    section.green{
        background-color: $firstColor;
        width: 100%;
        height: 180px;
    }

    div.show{
        width: 375px;;
        margin-bottom: 9rem;
    }

    div.content{
        text-align: center;
        padding-top: 1rem;
        padding-left: 3rem;
        padding-right: 3rem;

        span.check{
            color: $firstColor;
            font-size: 1.4rem;
            padding-bottom: 0.9rem;

        }

        h2{
            color: $fourColor;
            text-transform: uppercase;
            font-size: 1.2rem;
            padding-top: 0.7rem;
            padding-bottom: 0.7rem;
        }

        p{
            color: grey;
            font-size: 1.1rem;

        }
    }

    div.line{
        height: 2px;
        width: 100%;
        background-color: $firstColor;
    }
</style>