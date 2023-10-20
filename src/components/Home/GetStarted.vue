<script>
 import image from "../../assets/gstart_shape.png"

 export default {
    data: () => {
        return {
            image: image,
        }
    }
 }
</script>

<template>
    <div class="section">
        <img class="shape" :src="image" alt="Bicolor lines">

        <div class="gStarted_intro">        
            <h1>
                Meaningful investments in <br>
                Main Street businesses
            </h1>

            <p>
                Browse vetted investment offerings in <br>
                communities all over the US.
            </p>

            <a href="#">GET STARTED</a>
        </div>

        <div class="circle"></div>
    </div>
</template>

<style scoped>
    .section {
        display: flex;
        align-items: center;
        position: relative;
        height: 780px;
        border: 1px solid black;
        background-image: url("../../assets/getStarted_bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
    }

    .shape {
        position: absolute;
        bottom: 0;
        right: 0;
        background-color: transparent;
    }

    .gStarted_intro {
        display: flex;
        flex-direction: column;
        gap: 40px;
        margin-left: 375px;
        color: #ffffff;
    }

    .circle {
        position: absolute;
        left: 230px;
        top: 71px;
        width: 558px;
        height: 558px;
        border-radius: 50%;
        opacity: 50%;
        background-color: #5c82cc;
    }

    .gStarted_intro > h1 {
        z-index: 5;
        font-size: 60px;
        font-weight: bold;
    }

    .gStarted_intro > p {
        z-index: 5;
        font-size: 24px;
        font-weight: normal;
    }   

    .gStarted_intro > a {
        z-index: 5;
        display: block;
        width: 270px;
        height: 70px;
        background-color: #128C76;
        padding: 24px 80px;
        font-size: 16px;
        font-weight: bold;
        color: #ffffff;
        text-decoration: none;
    }

    .gStarted_intro > a:visited {
        text-decoration: none;
    }
</style>