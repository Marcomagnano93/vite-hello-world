<script>

</script>

<template>
    <div class="hero">
        <h2 class="hero-title">Una volta dipingevo miniature</h2>
        <img class="hero-img" src="../components/qg.JPG" alt="">
    </div>
</template>

<style>
* {    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

.hero {
    width: 100%;
    position: relative;
    display: flex;
    justify-content: center;

}

.hero-title {
    font-size: 38px;
    color: white;
    position: absolute;
    z-index: 1;
    margin-top: 80px;
    
    
}

.hero-img {
    width: 100%;
    object-fit: cover;   
}
</style>