<template>
    <div class="footer-container">
        <siteWidgets />
        <div class="footer-main">
            <div class="footer-content">
                <aside>
                    <div class="dc-comics">
                        <h2>DC COMICS</h2>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                    </div>
                    <div class="shop">
                        <h2>SHOP</h2>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>
                </aside>
                <aside>
                    <div class="dc">
                        <h2>DC</h2>
                        <ul>
                            <li><a href="#">Terms Of Use</a></li>
                            <li><a href="#">Privacy policy(New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>
                </aside>
                <aside>
                    <div class="sites">
                        <h2>SITES</h2>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Vista</a></li>
                        </ul>
                    </div>
                </aside>
            </div>
            <div class="footer-logo">
            </div>
        </div>
        <div class="sing-up-container">
            <button>SING UP</button>
        </div>
    </div>    
</template>

<script>
import siteWidgets from "./siteWidgets.vue";

export default {
    name: "siteFooter",
    components:{
        siteWidgets,
    }
};
</script>

<style>

</style>
