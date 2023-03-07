<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="/dc-logo.png" alt="">
            </div>
            <ul class="list-item-header">
                <li>
                    <a href="">CHARACTERS</a>
                </li>
                <li>
                    <a href="">COMICS</a>
                </li>
                <li>
                    <a href="">MOVIES</a>
                </li>
                <li>
                    <a href="">TV</a>
                </li>
                <li>
                    <a href="">GAMES</a>
                </li>
                <li>
                    <a href="">COLLECTIBLES</a>
                </li>
                <li>
                    <a href="">VIDEOS</a>
                </li>
                <li>
                    <a href="">FANS</a>
                </li>
                <li>
                    <a href="">NEWS</a>
                </li>
                <li>
                    <a href="">SHOP</a>
                </li>
            </ul>

        </div>
       
    </header>
</template>
  
<script>
export default {
    data() {
        return {
        }
    }
}
</script>

<style lang="scss" scoped>
@use '../partials/reset' as *;

.container {
    display: flex;
    justify-content: space-between;
    padding: 22px 0;
    font-size: 12px;
    font-weight: bold;


    .logo {
        width: 80px;
        flex-shrink: 0;
    }
    .list-item-header {
        display: flex;
        line-height: 60px;
        padding: 0 20px;
        gap: 25px;
    
    }
}

li:hover {
    color: #0282F9;
}


</style>
  