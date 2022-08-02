<template>

<main>

    <div class="text-top">Videos Novos toda <b>quinta</b> às <b>20 horas</b></div>

    <a href="https://www.youtube.com" target="_blank">
    <img alt="Inscreva-se" id="subscribe" src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg"/>
    </a>

    <div class="text-bottom">youtube.com/scorpionsistemas</div>

</main>

</template>

<script>
export default{
    name: 'Home'
}
</script>

<style scoped>

main{
    background-color: #ffffff;
    justify-content: center;
    align-items: center;
}

#subscribe{
    width: 340px;
}

.text-top{
    color: black;
    font-size: 20px;
    margin-bottom: 20px;
}

.text-bottom{
    color: black;
    font-size: 18px;
    margin-top: 20px;
}

@media (min-width: 700px) {
    #subscribe{
     width: 470px;   
    }
}
</style>