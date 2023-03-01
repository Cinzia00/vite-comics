<template>
    <footer>
        <div>
            <ul class="header-footer">
                <li>
                    <div class="icon-box">
                        <img src="/buy-comics-digital-comics.png" alt="">
                    </div>
                    <div>
                        <a href="">DIGITAL COMICS</a>
                    </div>
                </li>
                <li>
                    <div class="icon-box">
                        <img src="/buy-comics-merchandise.png" alt="">
                    </div>
                    <div>
                        <a href="">DC MERCHANDISE</a>
                    </div>
                </li>
                <li>
                    <div class="icon-box">
                        <img src="/buy-comics-subscriptions.png" alt="">
                    </div>
                    <div>
                        <a href="">SUBSCRIPTION</a>
                    </div>
                </li>
                <li>
                    <div class="icon-box">
                        <img src="/buy-comics-shop-locator.png" alt="">
                    </div>
                    <div>
                        <a href="">COMIC SHOP LOCATOR</a>
                    </div>
                </li>
                <li>
                    <div class="icon-box">
                        <img src="/buy-dc-power-visa.svg" alt="">
                    </div>
                    <div>
                        <a href="">DC POWER VISA</a>
                    </div>
                </li>
            </ul>
        </div>
        <div class="main-footer">
            <img class="big-logo" src="/dc-logo-bg.png" alt="">
            <div class="list-item">
                <ul>
                    <li>
                        <h3>DC COMICS</h3>
                    <li>
                        <a href="">Characters</a>
                    </li>
                    <li>
                        <a href="">Comics</a>
                    </li>
                    <li>
                        <a href="">Movies</a>
                    </li>
                    <li>
                        <a href="">TV</a>
                    </li>
                    <li>
                        <a href="">Games</a>
                    </li>
                    <li>
                        <a href="">Videos</a>
                    </li>
                    <li>
                        <a href="">News</a>
                    </li>
                </li>
                <li>
                    <h3>SHOP</h3>
                </li>
                <li>
                    <a href="">Shop DC</a>
                </li>
                <li>
                    <a href="">Shop DC Collectibles</a>
                </li>

            </ul>
            <ul>
                <li>
                    <h3>DC</h3>
                <li>
                    <a href="">Terms Of Use</a>
                </li>
                <li>
                    <a href="">Privacy policy (New)</a>
                </li>
                <li>
                    <a href="">Ad Choices</a>
                </li>
                <li>
                    <a href="">Advertising</a>
                </li>
                <li>
                    <a href="">Jobs</a>
                </li>
                <li>
                    <a href="">Subscriptions</a>
                </li>
                <li>
                    <a href="">Talent Workshops</a>
                </li>
                <li>
                    <a href="">CPSC Certificates
                    </a>
                </li>
                <li>
                    <a href="">Ratings</a>
                </li>
                <li>
                    <a href="">Shop Help</a>
                </li>
                <li>
                    <a href="">Contacts Us</a>
                </li>

                </li>
            </ul>
            <ul>
                <li>
                    <h3>SITES</h3>
                <li>
                    <a href="">DC</a>
                </li>
                <li>
                    <a href="">MAD Magazine</a>
                </li>
                <li>
                    <a href="">DC Kids</a>
                </li>
                <li>
                    <a href="">DC Universe</a>
                </li>
                <li>
                    <a href="">DC Power Visa</a>
                </li>

                </li>
            </ul>
            </div>
        </div>
        <div class="footer-sing-up">
            <div class="box-sign-up">
                <a>SIGN-UP NOW!</a>
            </div>
            <div class="icon-social">
                <h3>FOLLOW US</h3>
                <div><i class="fa-brands fa-facebook"></i></div>
                <div><i class="fa-brands fa-twitter"></i></div>
                <div><i class="fa-brands fa-youtube"></i></div>
                <div><i class="fa-brands fa-pinterest"></i></div>
                <div><i class="fa-solid fa-location-dot"></i></div>
            </div>

        </div>
    </footer>
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
// @use '../partials/general' as *;


footer {
    color: white;

    .header-footer {
        display: flex;
        justify-content: center;
        gap: 20px;
        line-height: 60px;
        padding: 50px;
        background-color: #0282F9;
    }

    li {
        display: flex;
        gap: 10px;
    }

    .icon-box {
        width: 50px;
        height: 50px;

        img {
            height: 100%;
        }
    }
    


}

.main-footer {
    background-image: url('/footer-bg.jpg');
    padding: 40px;
    position: relative;
    overflow: hidden;

    .big-logo {
        position: absolute;
        right: 10%;
        bottom: -25%;
    }

    .list-item {
        display: flex;
        gap: 8px;
        color: gray;
        margin-left: 100px;
    }
    h3 {
        color: white;
        padding: 10px 0;
    }

    li {
        padding: 4px 0;
        font-size: 13px;
    }
}

.footer-sing-up {
    display: flex;
    justify-content: space-between;
    background-color: #303030;
    padding: 35px;
    .icon-social{
        display: flex;
        gap: 10px;
    }

    .box-sign-up {
        border-color: #0282F9;
    }
}
</style>
  