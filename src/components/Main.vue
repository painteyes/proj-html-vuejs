<template>
<main>

    <div class="jumbotron ">
        
        <div class="container">

            <div class="wrapper">

                <TitleArea
                    :sectionName="'Always the best wayt you need it'" 
                    :sectionTitle="'The best business consulting'" 
                    :titleSize="'font-size:80px;'" 
                />

                <div class="buttons">
                    <a class="btn btn-bluegreen" href="#">Read more </a>
                    <i id='play' class="fas fa-play"></i>
                </div>
            </div>
        </div>
        
        <img :src="require('../assets/images/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg')" alt="">

    </div>

    <div class="services">

        <div class="wrapper">

            <div class="title">
                <h3>Our consultant can help you</h3>
                <div class="line"></div>
            </div>

            <ul>
                <li>
                    <div  class="icon">
                        <i class="fas fa-chart-pie"></i>
                    </div>

                    <div class="text-area">
                        <h4>Statistical Consulting</h4>
                        <p>When, while lovely valley teems vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a..</p>
                    </div>
                </li>
                 <li>
                    <div  class="icon">
                        <i class="fas fa-chalkboard"></i>
                    </div>

                    <div class="text-area">
                        <h4>Digital Consulting</h4>
                        <p>When, while lovely valley teems vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a..</p>
                    </div>
                </li> 
                <li>
                    <div  class="icon">
                        <i class="fas fa-piggy-bank"></i>
                    </div>

                    <div class="text-area">
                        <h4>Banking Consulting</h4>
                        <p>When, while lovely valley teems vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a..</p>
                    </div>
                </li> 
                <li>
                    <div  class="icon">
                        <i class="fas fa-building"></i>
                    </div>

                    <div class="text-area">
                        <h4>Enterprise Consulting</h4>
                        <p>When, while lovely valley teems vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a..</p>
                    </div>
                </li>
            </ul>
        </div>
    </div>

    <section class="bg">

        <div class="about-us">

            <img :src="require('../assets/images/business-people-working-together-on-project-and-5FHSKBL.jpg')" alt="">

            <div class="wrapper">

                <TitleArea 
                :sectionName="'About us'" 
                :sectionTitle="'We make your strategy work'" 
                :titleSize="'font-size:50px;'"
                :wrapper="'width: 50%;'" />

                <p>When, while lovely valley teems vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore ex sint facilis animi expedita eius fuga perferendis fugiat quo vel cumque magni, quis vero molestiae veritatis sapiente quaerat ipsam. Perferendis!</p>
                
            </div>
        </div>

        <div class="get-started">
            <h5>We Help to deliver the business case</h5>
            <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam voluptatem sapiente quaerat, inventore nesciunt vel esse! Vitae itaque odit iure ipsa, nulla autem aliquid enim distinctio blanditiis voluptas, ratione molestiae?</p>
            <a class="btn btn-red" href="#">Get Started</a>
        </div>

    </section>


</main>    
</template>


<script>

import TitleArea from "./TitleArea.vue";

export default {

    name: 'Main',

    components: {
        TitleArea,
    },

}
</script>


<style lang="scss" scoped>

@import "../styles/general.scss";
@import "../styles/variables.scss";


.jumbotron {
 
    height: 900px;
    background-color: $brand_primary_color ;

    display: flex;
    align-items: center;

    position: relative;
    
    .container{

        z-index: 1;
        
        .wrapper{

            width: 50%;

            .buttons {
                display: flex;
                align-items: center;
            }

            #play{
                margin-left: 20px ;    
                color: #39febe;
                width: 40px;
                height: 40px;
                border: 3px solid white;
                border-radius: 50%;
                display: flex;
                justify-content: center;
                align-items: center;  
                cursor: pointer;     
            }
        }
    }

    img{
        width: 65%;
        height: 100%;

        position: absolute;
        right: 0;
        top: 0;
        
        object-fit:cover;
        object-position:top ;
    }

}

.services{
    margin: 80px 0;
    background-color: white;
    color: black;

    position: relative;

    .wrapper{

        width: 70%;
        margin: auto;

        .title{

            display: flex;

            h3{
                min-width: 410px;
                display: inline-block;
                text-transform: uppercase;
                font-size: 25px;
                margin-bottom: 70px ;
            }

            .line{
                width: 100%;
                border-top: 3px solid #39febe;
                margin-top: 15px;
                
            }

            &::after {                
                display: inline-block;
                content: "";
                border-top: 3px solid #39febe;
                position: absolute; 
                right: 0;
                left: 85%; 
                margin-top: 15px;       
            }
        }

        ul{ 
            display: flex;
            flex-wrap: wrap;
            
            li{
                width: calc((100% /2) );
                margin-bottom: 60px; 
                display: flex; 

                .icon { 
                    background-color: #f81d39;
                    color: white;
                    width: 50px;
                    height: 50px;
                    border-radius: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;  
                    cursor: pointer;
                }

                .text-area {
                    width: calc((100% - 50px) - 30px);
                    margin-left: 30px;

                    h4 {
                        font-size: 20px;
                        text-transform: uppercase;
                        margin: 10px 0 ;
                    }

                    p {
                        color: #1f1e38b3;
                        font-size: small;
                        width: 50%;
                    }
                }
            }
        }
    } 
}

.about-us{

    height: 500px;
    display: flex;
    align-items: center;

    img{
        height: 100%;
        width: 50%;
        object-fit:cover;
        object-position:top ;
    }

    .wrapper{
        width: 27%;
        margin: 0 70px;

        p {
            color: #8a8999;
        }
    }
}

.get-started{
    width: 85%;
    height: 200px;
    background-color: #39febe;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    position: relative;
  
    .btn{
        position: absolute;
        bottom: 0;
        right: 0;
    }

    p {
        font-size: small;
        width: 30%;
    }

    h5{
        // width: 50%;

        text-align: center;
    }
}



</style>