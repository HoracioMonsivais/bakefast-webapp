<template>
    <div class="Header__container">
        <div class="Hero__content" >
            <h1 class="Hero__tittle" >Delicious cakes for your cravings</h1>
            <p class="Hero__paragraph" >Create your perfect cake with our options that we have for you.</p>
            <button class="Hero__button" >View menu</button>
        </div>
        <figure class="Hero__img" >
            <img class="img_Hero" src="../assets/Img/Hero_img.png" alt="Hero_img">
        </figure>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
.Header__container {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    padding: 80px 60px;
}

.Hero__tittle {
    font-style: normal;
    font-weight: 600;
    font-size: 60px;
    line-height: 70px;
    color: #9600FF;
}

.Hero__paragraph {
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 23px;
    color: #000000;
    margin-top: 24px;
}

.Hero__button {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 20px 40px;
    border: none;
    color: #fff;

    background: #CB80FF;
    border-radius: 8px;
    margin-top: 40px;
}

.img__Hero {
    width: 100%;
    display: block;
}
</style>