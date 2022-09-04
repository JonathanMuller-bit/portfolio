<template>
    <div class="logo">
        <h1 class="principal-logo"><span>&lt;</span>JonathanMuller.dev.br<span>/&gt;</span></h1>
        <p class="text">Coming soon...</p>
    </div>
</template>
<script>

export default {
    name: 'LogoComponent', 
}
</script>
<style>
.logo{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100%;
    font-size: 2rem;
    flex-direction: column;
}
.principal-logo{
    color: #f8f8f8;
    /* font-family: 'Londrina Sketch', cursive; */
        font-family: 'Tourney', cursive;

    display: flex;
    align-items: center;
    
}

.text {
    color: #f8f8f8;
    font-size: 2rem;
    font-family: 'Tourney', cursive;
}


span {
    font-size: 10rem;
    padding: 30px;
}

</style>