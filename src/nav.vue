<script>

</script>
<template>
    <nav>
        <ul>
            <li>
                <img src="vue-dc-comics-1/img/buy-comics-digital-comics.png">
                <h3>DIGITAL COMICS</h3>
            </li>
            <li>
                <img src="vue-dc-comics-1/img/buy-comics-merchandise.png">
                <h3>DC MERCHANDISE</h3>
            </li>
            <li>
                <img src="vue-dc-comics-1/img/buy-comics-subscriptions.png">
                <h3>SUBSCRIPTION</h3>
            </li>
            <li>
                <img src="vue-dc-comics-1/img/buy-comics-shop-locator.png">
                <h3>COMIC SHOP LOCATOR</h3>
            </li>
            <li>
                <img src="vue-dc-comics-1/img/buy-dc-power-visa.svg">
                <h3>DC POWER VISA</h3>
            </li>
        </ul>
    </nav>
</template>
<style scoped>
nav {
    background-color: blue;
    height: 100px;
}

ul {
    display: flex;
    justify-content: space-around;
    list-style: none;
    margin: 0;
    height: 100%;
    align-items: center;
}

li {
    display: flex;
    align-items: center;
    color: white;
}

li img {
    height: 50px;
    margin: 7px;

}
</style>