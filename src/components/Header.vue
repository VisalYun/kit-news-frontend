<template>
    <header>
        <div class="logo"></div>
        <h1>Kirirom News</h1>
    </header>
</template>

<script>
export default {
    name: 'Header',
    setup(){

    }
}
</script>

<style scoped>
header {
    padding: 6px 50px;
    box-shadow: 0px 5px #eee;
    display: flex;
    align-items: center;
}

.logo{
    width: 100px;
    height: 100px;
    background: url("https://www.rarejob.co.jp/wp-content/uploads/2022/04/KIRIROM-INSTITUTE-OF-TECHNOLOGY_logo.png") no-repeat center center;
    background-size: cover;
    margin-right: 25px;
}
</style>