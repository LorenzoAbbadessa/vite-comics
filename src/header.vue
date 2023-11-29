<script>

</script>
<template>
    <header>
        <div class="img">
            <img src="vue-dc-comics-1\img\dc-logo.png">
        </div>

        <ul class="list">
            <li><a href="#">CHARACTERS</a></li>
            <li><a href="#">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">CONNECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>
        </ul>

    </header>
</template>
<style scoped>
header {
    background-color: white;
    color: grey;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 100px;
    margin-top: 20px;
}

a {
    text-decoration: none;
    color: darkslategrey;
}

li {
    margin: 10px;
    text-decoration: none;
}

ul {
    list-style: none;
    display: flex;
}
</style>