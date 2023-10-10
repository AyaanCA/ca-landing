<template>
    <div>
        <nav class="navbar navbar-light">
            <img src="@/assets/img/Rectangle 2.png" alt="">
        </nav>
        <header class="main-header">
            <div class="header">
                <img class="logo-img" src="@/assets/img/codearrayLogo.png" alt="">
            </div>
            <div class="hamburger" @click="openMenu">
                <div class="line"></div>
                <div class="line"></div>
                <div class="line"></div>
            </div>
            <nav class="nav-bar">
                <ul class="main-list">
                    <li>
                        <p class="phone-number" style="color: rgb(8, 15, 46);">+91 84337 41455</p>
                    </li>
                    <li class="call-btn">
                        <a href="https://www.codearray.tech/contact-us" class="active"><img src="@/assets/img/phone.png">
                            Schedule Call</a>
                    </li>
                </ul>

            </nav>
        </header>
        <div class="main-wrapper">
            <div class="mask-group">
                <div class="background">
                    <div class="container">
                        <div class="title-section">
                            <div style="display: flex; align-items: center; justify-content: center;">
                                <p class="heading1" style="text-shadow: 0px 2px 5px rgb(72, 72, 72);">L<img class="eye-img"
                                        src="@/assets/img/Eye 2.gif">KING FOR A</p>
                            </div>
                            <p class="heading2" style="text-shadow: 0px 2px 5px rgb(72, 72, 72);">SOFTWARE DEVELOPMENT
                                AGENCY
                            </p>
                            <p class="heading3" style="text-shadow: 0px 2px 5px rgb(72, 72, 72);">TO BUILD YOUR NEXT DREAM
                                APPLICATION?</p>
                        </div>
                    </div>
                    <div class="schedule">
                        <a href="https://www.codearray.tech/contact-us" class="cta">
                            <span>Schedule Call With Us</span>
                            <svg width="13px" height="10px" viewBox="0 0 13 10">
                                <path d="M1,5 L11,5"></path>
                                <polyline points="8 1 12 5 8 9"></polyline>
                            </svg>
                        </a>
                    </div>
                </div>
                <div class="tablet">
                    <div>
                        <img class="tablet-img" src="@/assets/img/tablet-img.gif" alt="">
                    </div>
                </div>
            </div>
            <div class="card-row">
                <div class="card1">
                    <img class="card1-img" src="@/assets/img/card1.png" alt="">
                    <div class="card1-content">
                        <h3 style="color: #1F2D5C; font-family: 'system-ui;">We design and develop</h3>
                        <p>scalable, high-performing applications with a seamless user experience
                            to achieve maximum value for your business and define your brand in the market.</p>
                    </div>
                </div>
                <div class="card2">
                    <img class="card2-img" src="@/assets/img/card2.png" alt="">
                    <div class="card1-content">
                        <h3 style="color: #1F2D5C; font-family: 'system-ui;">42% of small businesses</h3>
                        <p>said they developed a mobile app to improve sales and increase revenue, and 61% of startups
                            planned
                            to develop a mobile app, as reported by Statistica.</p>
                    </div>
                </div>
                <div class="card3">
                    <img class="card3-img" src="@/assets/img/card3.png" alt="">
                    <div class="card1-content">
                        <h3 style="color: #1F2D5C; font-family: 'system-ui;">Codearray</h3>
                        <p>is one of the leading companies in app development, where we have worked with some of the best
                            innovative ideas and brands in the world across industries.</p>
                    </div>
                </div>
            </div>
            <div class="app-info">
                <img class="app-icon" src="@/assets/img/app-icon.png" alt="">
                <div class="app-content">
                    <p>App Solution</p>
                    <p>for All Kinds of Industries</p>
                </div>
                <div class="app-card-row1">
                    <div class="appcard">
                        <img class="app-img" src="@/assets/img/appcard1.png" alt="">
                        <div class="app-content">
                            <p>Food Delivery</p>
                            <p>App</p>
                        </div>
                    </div>
                    <div class="appcard">
                        <img class="app-img" src="@/assets/img/appcard2.png" alt="">
                        <div class="app-content">
                            <p>Grocery Delivery</p>
                            <p>App</p>
                        </div>
                    </div>
                    <div class="appcard">
                        <img class="app-img" src="@/assets/img/appcard3.png" alt="">
                        <div class="app-content">
                            <p>Telemedicine</p>
                            <p>App</p>
                        </div>
                    </div>
                    <div class="appcard">
                        <img class="app-img" src="@/assets/img/appcard4.png" alt="">
                        <div class="app-content">
                            <p>Ticket Booking</p>
                            <p>App</p>
                        </div>
                    </div>
                </div>
                <div class="app-card-row2">
                    <div class="appcard">
                        <img class="app-img5" src="@/assets/img/appcard5.png" alt="">
                        <div class="app-content">
                            <p>Taxi Booking</p>
                            <p>App</p>
                        </div>
                    </div>
                    <div class="appcard">
                        <img class="app-img" src="@/assets/img/appcard6.png" alt="">
                        <div class="app-content">
                            <p>Transportation Management</p>
                            <p>App</p>
                        </div>
                    </div>
                    <div class="appcard">
                        <img class="app-img" src="@/assets/img/appcard7.png" alt="">
                        <div class="app-content">
                            <p>Travel Planning</p>
                            <p>App</p>
                        </div>
                    </div>
                    <div class="appcard">
                        <img class="app-img" src="@/assets/img/appcard8.png" alt="">
                        <div class="app-content">
                            <p>Fitness & Health</p>
                            <p>App</p>
                        </div>
                    </div>
                </div>
                <div class="schedule" style="margin-bottom: 17px;">
                    <a href="https://www.codearray.tech/contact-us" class="cta">
                        <span style="font-family: system-ui;">Schedule Call With Us</span>
                        <svg width="13px" height="10px" viewBox="0 0 13 10">
                            <path d="M1,5 L11,5"></path>
                            <polyline points="8 1 12 5 8 9"></polyline>
                        </svg>
                    </a>
                </div>
            </div>
            <div class="app-info" style="background-color: white !important;">
                <img class="app-icon" src="@/assets/img/globe-icon.png" alt="">
                <div class="app-content">
                    <p>Web Solution</p>
                    <p>for All Kinds of Industries</p>
                </div>
                <div class="web-main">
                    <div class="web-row">
                        <div class="webcard1">
                            <div class="web-content">
                                <p>Custom application development</p>
                            </div>
                            <img class="web-img" src="@/assets/img/web1.png" alt="">
                        </div>
                        <div class="webcard1">
                            <div class="web-content">
                                <p>Portal development</p>
                            </div>
                            <img class="web-img" src="@/assets/img/web2.png" alt="">
                        </div>
                        <div class="webcard1">
                            <div class="web-content">
                                <p>E-commerce development</p>
                            </div>
                            <img class="web-img" src="@/assets/img/web3.png" alt="">
                        </div>
                        <div class="webcard1">
                            <div class="web-content">
                                <p>Saas products</p>
                            </div>
                            <img class="web-img" src="@/assets/img/web4.png" alt="">
                        </div>
                    </div>
                    <div class="web-row1">
                        <div class="webcard1-custom">
                            <div class="web-content">
                                <p>Web application support and maintenance</p>
                            </div>
                            <img class="web5" src="@/assets/img/web5.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
            <div class="schedule" style="margin-bottom: 17px;">
                <a href="https://www.codearray.tech/contact-us" class="cta">
                    <span class="schedule-call" style="font-family: system-ui;">Schedule Call With Us</span>
                    <svg width="13px" height="10px" viewBox="0 0 13 10">
                        <path d="M1,5 L11,5"></path>
                        <polyline points="8 1 12 5 8 9"></polyline>
                    </svg>
                </a>
            </div>
            <div class="comp-info">
                <div class="comp-card">
                    <p class="para">10+</p>
                    <p class="para-details">years in the industry.</p>
                </div>
                <div class="comp-card">
                    <p class="para">600+</p>
                    <p class="para-details">successfully delivered projects.</p>
                </div>
                <div class="comp-card">
                    <p class="para">100%</p>
                    <p class="para-details">customer satisfaction.</p>
                </div>
            </div>
            <div class="service-info">
                <div class="services">
                    <p>Why Choose CodeArray for Application Development Services?</p>
                </div>
            </div>
            <div class="service">
                <img class="service-img" src="@/assets/img/newservice.png" alt="">
            </div>
            <div class="carousel-main">
                <div class="service-info">
                    <div class="services">
                        <p>What Our Client Says</p>
                    </div>
                </div>
                <div class="image-gallery">
                    <VueSlickCarousel class="carousel" :arrows="false" :dots="true" v-bind="settings">
                        <img src="@/assets/img/testi1.png" class="case_study_img" alt="" />
                        <img src="@/assets/img/testi2.png" class="case_study_img" alt="" />
                        <img src="@/assets/img/testi3.png" class="case_study_img" alt="" />
                        <img src="@/assets/img/testi4.png" class="case_study_img" alt="" />
                    </VueSlickCarousel>
                </div>
            </div>
        </div>
        <div class="footer">
            <div class="footer-text">
                <p>© 2023 Codearray Technologies Pvt Ltd. All rights reserved. <a
                        href="https://www.codearray.tech/privacy-policy"
                        style="text-decoration: underline; color: white;">Privacy Policy</a></p>
            </div>
        </div>
    </div>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
import settings from '../../src/common/carousel-settings.js'
export default {
    components: { VueSlickCarousel },
    data() {
        return {
            settings: {}
        };
    },
    methods: {
        openMenu() {
            let navBar = document.querySelector(".nav-bar");
            navBar.classList.toggle("active")
        }
    },
    created() {
        this.settings = settings;
    }
}

</script>
<style scoped></style>
<style src="../components/landingPage.css"></style>

