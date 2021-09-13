<template>
    <div class="picture">
        <img src="@/assets/moi.jpg" alt="">
    </div>
    <ul class="picture-info">
        <li class="name"><strong>Tom Lemelle</strong></li>
        <li class="name"><div>Développeur web</div></li>
        <li>tom.lemelle@hotmail.fr</li>
        <li>Rouen, Haute-Normandie, France</li>
        <li>Né le 21/02/2000</li>
        <li>https://www.linkedin.com/in/tom-lemelle/</li>
        <li>https://github.com/TomLemelle</li>
        <li>07 67 33 83 65</li>
    </ul>
</template>

<script>
export default {

}
</script>

<style lang="scss">

.picture {
    width: 50%;
    margin: 30px auto;

    img {
        width: 100%;
        border-radius: 50%;
        border: 5px solid #fff;
    }
}

.picture-info {
    list-style: none;
    padding: 0;
    margin: 0 45px;

    strong {
        font-weight: 500;
        font-size: 35px;
        color: #03bcff;
    }

    div {
        font-weight: 500;
        font-size: 28px;
        letter-spacing: 1px;
        color: #03bcff;
        margin-bottom: 20px;
    }

    li:not(.name){
        margin: 7px 0;
        font-size: 16px;
        font-weight: bold;
    }
}

</style>