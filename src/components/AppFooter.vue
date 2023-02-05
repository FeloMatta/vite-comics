<script>
import AppLogo from './AppLogo.vue';

export default {
    name: 'AppFooter',
    components: {
        AppLogo
    }
}
</script>

<template>

    <footer>
        <div class="shop">
            <ul>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics"> <span>DIGITAL COMICS</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="DC MERCHANDISE"> <span>DC MERCHANDISE</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="SUBSCRIPTION"> <span>SUBSCRIPTION</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="COMIC SHOP LOCATOR"> <span>COMIC SHOP LOCATOR</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="DC POWER VISA"> <span>DC POWER VISA</span>
                    </a>
                </li>
            </ul>

        </div>

        <div class="info">
            <div class="container">
                <div  class="card">
                    <h3>
                        DC COMICS
                    </h3>
                    <ul>
                        <li><a href=#>Characters</a></li>
                        <li><a href=#>Comics</a></li>
                        <li><a href=#>Movies</a></li>
                        <li><a href=#>TV</a></li>
                        <li><a href=#>Games</a></li>
                        <li><a href=#>Videos</a></li>
                        <li><a href=#>News</a></li>
                    </ul>

                    
                    <h3>
                        SHOP
                    </h3>
                    <ul>
                        <li><a href=#>Shop DC</a></li>
                        <li><a href=#>Shop DC Collectibles</a></li>
                    </ul>
                
                </div>
                <div  class="card">
                    <h3>
                        DC
                    </h3>
                    <ul>
                        <li><a href=#>Terms Of Use</a></li>
                        <li><a href=#>Privacy policy (new)</a></li>
                        <li><a href=#>Ad Choices</a></li>
                        <li><a href=#>Advertising</a></li>
                        <li><a href=#>Jobs</a></li>
                        <li><a href=#>Subscriptions</a></li>
                        <li><a href=#>Talent Workshops</a></li>
                        <li><a href=#>CPSC Certificates</a></li>
                        <li><a href=#>Ratings</a></li>
                        <li><a href=#>Shop Help</a></li>
                        <li><a href=#>Contact Us</a></li>
                    </ul>
                </div>
                <div  class="card">
                    <h3>
                        SITES
                    </h3>
                    <ul>
                        <li><a href=#>DC</a></li>
                        <li><a href=#>MAD Magazine</a></li>
                        <li><a href=#>DC Kids</a></li>
                        <li><a href=#>DC Universe</a></li>
                        <li><a href=#>DC Power Visa</a></li>
                    </ul>
                </div>
            </div>

            <div class="bgdc">

            </div>
        </div>

        <div class="contact">
            <div class="btn">
                <button>
                    SIGN-UP NOW!
                </button>
            </div>
            <div class="follow">
                <a href="#">FOLLOW US</a>
                <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a>
            </div>
        </div>
    </footer>

</template>

<style lang="scss" scoped>
// footer{
    
// }
.shop{
    height: 150px;
    padding-left: 170px;
    padding-right: 170px;
    background-color: #0282F9;
    display: flex;
    justify-content: center;
    align-items: center;
    ul{
        display: flex;
        justify-content: space-around;
        align-items: center;
        list-style: none;

        li{
            
            a{
                
                display: inline-block;
                text-decoration: none;
                color: white;
                font-size: 12px;

                img{
                    vertical-align: middle;
                    padding: 25px;
                    width: 100px;
                    height: 100px;
                    object-fit: contain;
                }
                
            }
        }
    }
}
.info{
    background-image: url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    width: 100%;
    height: auto;
    max-width: 100%;
    background-position: center;
    background-size: cover;

    padding-left: 170px;
    padding-right: 170px;
    
    width: 100%;
    display: flex;
    justify-content: space-between;
    
    .container{
        display: flex;
        padding-top: 30px;
        padding-bottom: 30px;
        .card{
            flex-wrap: wrap;
            padding: 10px;
            padding-right: 30px;
            max-width: 100%;
            h3{
                color: white;
                margin-bottom: 10px;
                width: max-content;
            }
            ul{
                list-style: none;
                margin-bottom: 10px;

                li{
                    padding-top: 5px;
                    width: max-content;
                }

                a{
                display: inline-block;
                text-decoration: none;
                color: white;
                font-size: 12px;
                }
            }
            
        }
    }
    .bgdc{
        background-image: url(../assets/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        width: 100%;
        height: auto;
        max-width: 100%;
        background-position: right;
    }

    

}
.contact{
        padding-left: 170px;
        padding-right: 170px;
        background-color: #303030;
        height: 144px;
        display: flex;
        justify-content: space-between;
        align-items: center;

        button{
            background-color: transparent;
            color: white;
            font-weight: bold;
            font-size: 1rem;
            border: 2px solid #1168B9;
            padding: 17px;
        }

        a{
            text-decoration: none;
            color: #0281F9;
            font-weight: bold;
            font-size: 1.3rem;
        }
        .follow{
            display: flex;
            justify-content: center;
            align-items: center;

            img{
                padding: 8px;

            }
        }


    }
</style>