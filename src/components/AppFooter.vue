<template>
    <footer>
        <div class="container">
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
            <div class="container">

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
        </div>
        <div class="footer-sing-up">
            <div class="container">
                <div class="box-sign-up">
                    <a href="">SIGN-UP NOW!</a>
                </div>
                <div class="icon-social">
                    <h3>
                        <a href="">FOLLOW US</a>
                    </h3>
                    <ul class="list-item-social">
                        <li>
                            <a href="">
                                <img src="/footer-facebook.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <img src="/footer-twitter.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <img src="/footer-youtube.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <img src="/footer-pinterest.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <img src="/footer-periscope.png" alt="">
                            </a>
                        </li>
                    </ul>
                </div>
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
    background-color: #0282F9;
    color: white;

    .header-footer {
        display: flex;
        flex-wrap: nowrap;
        justify-content: center;
        gap: 20px;
        line-height: 60px;
        padding: 50px 0;
        font-size: 14px;

        li {
            display: flex;
            gap: 10px;
            line-height: 50px;
        }
    }


    .icon-box {
        width: 50px;
        height: 50px;
        font-size: 12px;

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
        gap: 30px;
        color: gray;
    }
    h3 {
        font-size: 18px;
        color: white;
        padding: 10px 0;
    }

    li {
        padding: 4px 0;
        font-size: 13px;
    }
}

.footer-sing-up {
    background-color: #303030;
    padding: 35px;
    .icon-social{
        display: flex;
        gap: 35px;

        h3 {
            color: #0282F9;
            line-height: 45px;
        }
    }

    .container {
        display: flex;
        justify-content: space-between;
    }
    
    .box-sign-up {
        border: 1px solid #0282F9;
        padding: 15px;
        font-weight: bold;
    }
}

.list-item-social {
    display: flex;
    gap: 10px;
}
</style>
  