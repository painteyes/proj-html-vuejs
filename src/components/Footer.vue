<template>

    <section>

        <div class="container">

            <footer> 

                <div class="logo">
                    <img :src="require('../assets/images/logotype-2-150x25.png')" alt="">
                </div>

                <div class="list-menu">
                    <ul>
                        <li v-for="element,index in menuItems" :key='index'>{{element}}</li>
                    </ul>
                </div>

                <div class="social-icons">
                    <i class="fab fa-instagram"></i>
                    <i class="fab fa-linkedin-in"></i>
                    <i class="fab fa-facebook-f"></i>
                    <i class="fab fa-twitter"></i>
                </div>

            </footer>

            <hr>
            
            <div class="copyright">

                <div class="col-left">
                    <span>Terms of use</span>
                    <br>
                    <span>Privacy Environmental Policy</span>
                </div>

                <div class="col-right">
                    <span>Copyright 2020 Phlox Consulting. All rights Reserved.</span>
                </div>
 
            </div>
        </div>

        <div class="support">

            <div class="back-to-top">
                <i class="fas fa-arrow-circle-up"></i>
            </div>

            <div class="chat">
                <i class="fas fa-comment-dots"></i>
            </div>
    
        </div>

    </section>
    
</template>


<script>
export default {

    name: 'Footer',

    props: {
        menuItems: Array,
    }
}
</script>


<style lang="scss" scoped>

@import "../styles/general.scss";

section{
    position: relative;

    footer{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 70px 0;

        .list-menu {
            width: 60%;
            height: 100%;
            display: flex;

            ul {
                display: flex;
                justify-content: center;
                width: 100%;
            
                li {
                    margin: 0 15px;
                    line-height: 50px;
                }

                :first-child {
                    margin-left: 0;
                }

                :last-child {
                    margin-right: 0;
                }
            }
        }

        .social-icons{
            color: white;
            i{ margin: 10px;}
        }   
    }

    .copyright {

        display: flex;
        justify-content: space-between;
        align-items: flex-end;
        color: #aaaaaa;
        padding: 20px 0;

        span{
            font-size: small;
        }
    }

    .support{

        position: absolute;
        bottom: 10px;
        right: 10px;

        >*{
            margin-right: 20px;
            display: inline-block;
            cursor: pointer;
        }

        .back-to-top{
            color: #aaaaaa ;
            font-size: 30px;
        }

        .chat{
            color: #527ceb;
            font-size: 50px;
        }
    }
}

</style>