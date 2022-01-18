<template>
<main>

    <section class="jumbotron ">
        
        <div class="container">

            <div class="wrapper">

                <TitleArea
                    :sectionName="'Always the best wayt you need it'" 
                    :sectionTitle="'The best business consulting'" 
                    :titleSize="'font-size:80px;'" 
                />

            </div>

            <div class="buttons">
                <a class="btn btn-bluegreen" href="#">Read more </a>
                <i id='play' class="fas fa-play"></i>
            </div>
        </div>
        
        <img :src="require('../assets/images/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg')" alt="">

    </section>

    <section class="services">

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
    </section>

    <div class="bg-color">

        <section class="about-us">

            <img :src="require('../assets/images/business-people-working-together-on-project-and-5FHSKBL.jpg')" alt="">

            <div class="wrapper">

                <TitleArea 
                :sectionName="'About us'" 
                :sectionTitle="'We make your strategy work'" 
                :titleSize="'font-size:50px;'"
                />

                <p>When, while lovely valley teems vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore ex sint facilis animi expedita eius fuga perferendis fugiat quo vel cumque magni, quis vero molestiae veritatis sapiente quaerat ipsam. Perferendis!</p> 
            </div>
        </section>

        <section class="get-started">
            <h5>We Help to deliver the business case</h5>
            <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam voluptatem sapiente quaerat, inventore nesciunt vel esse! Vitae itaque odit iure ipsa, nulla autem aliquid enim distinctio blanditiis voluptas, ratione molestiae?</p>
            <a class="btn btn-red" href="#">Get Started</a>
        </section>

        <section class="project">

            <div class="container">

                <div class="wrapper">

                    <TitleArea 
                    :sectionName="'Project'" 
                    :sectionTitle="'Our expert trusted consultants help clients'" 
                    :titleSize="'font-size:30px;'"
                    />

                </div>

                <div class="previews">
                    <img :src="require('../assets/images/DRY-1-790x592.jpg')" alt="">
                    <img :src="require('../assets/images/221bf0b7-8134-43bb-936a-5acbe42db64a-790x592.jpg')" alt="">
                    <img :src="require('../assets/images/z1el4c4p-790x592.jpg')" alt="">
                </div>
            </div>
        </section>

        <section class="testimonial">

            <div class="container">

                <div class="wrapper">

                    <div class="section-name">Testimonial</div>

                    <TitleArea 
                        :sectionName="''" 
                        :sectionTitle="'What\'s the customers say about our work'" 
                        :titleSize="'font-size:30px;'"
                    />

                </div>
            </div>

            <div class="references">

                <div class="text-area">
                    <p class="content">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aspernatur ut mollitia, quibusdam at sapiente soluta id exercitationem error consequuntur laboriosam perferendis tenetur provident, enim ratione commodi necessitatibus omnis maiores repellendus!</p>
                    <span class="person-name"> Vera Duncan</span> 
                    <br> 
                    <span class="company-name">Amazon Inc.</span>
                </div>

                <div class="text-area">
                    <p class="content">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aspernatur ut mollitia, quibusdam at sapiente soluta id exercitationem error consequuntur laboriosam perferendis tenetur provident, enim ratione commodi necessitatibus omnis maiores repellendus!</p>
                    <span class="person-name"> Vera Duncan</span> 
                    <br> 
                    <span class="company-name">Amazon Inc.</span>
                </div>

                <div class="text-area">
                    <p class="content">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aspernatur ut mollitia, quibusdam at sapiente soluta id exercitationem error consequuntur laboriosam perferendis tenetur provident, enim ratione commodi necessitatibus omnis maiores repellendus!</p>
                    <span class="person-name"> Vera Duncan</span> 
                    <br> 
                    <span class="company-name">Amazon Inc.</span>
                </div>            
            </div>
        </section>

        <section class="blog">

            <div class="container">

                <TitleArea 
                    :sectionName="'Blog'" 
                    :sectionTitle="'The recent news you must read it'" 
                    :titleSize="'font-size:30px;'"
                />

                <div class="previews">

                    <div class="article">

                        <img :src="require('../assets/images/startup-business-people-and-strategy-board-PAJ3P9K-1390x1042.jpg')" alt="">
                        
                        <!-- <div class="text-area">
                            
                        </div> -->
                    </div>

                    <div class="article">

                        <img :src="require('../assets/images/business-people-working-together-on-project-and-5FHSKBL-1390.jpg')" alt="">
                        
                        <!-- <div class="text-area">
                            
                        </div> -->
                    </div>
                    
                </div>

            </div>

        </section>

        <section class="contact">

            <img :src="require('../assets/images/business-people-working-together-on-project-and-B3MZ4TX.jpg')" alt="">
            
            <div class="text-content">

                <div class="wrapper">
                    <h4>Let's talk about work</h4>
                    <span>A wonderful serenity has taken possession far far away, behind the word mountains.</span>
                </div>

                <div class="button">
                    <a class="btn btn-dark" href="#">Get started</a>
                </div>

            </div>

        </section>

    </div>


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
@import "../styles/mixin.scss";


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
        }

        .buttons {
                
            display: flex;
            align-items: center;

            #play{
                font-size: 10px ;
                margin-left: 25px ;    
                color: #39febe;
                width: 45px;
                height: 45px;
                border: 2px solid white;
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

.services {
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

.about-us {

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

.get-started {

    @include side-container;

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
        width: 25%;
    }

    h5{
        width: 20%;
        font-size: 30px;
        text-transform: uppercase;
        text-align: center;
    }
}

.project {

    margin: 130px 0;

    .wrapper{
        width: 40%;
    }

    .previews {

        width: 100%;

        img{
            width: calc((100% / 3) - 30px);
            margin: 0 15px;
        }

        :first-child {
            margin-left: 0;
            margin-right: 30px;
        }

        :last-child {
            margin-right: 0;
            margin-left: 30px;

        }
    }
} 

.testimonial {

    position: relative;

    .section-name {
        font-size: 15px;
        text-transform: uppercase;
        left: 50%;
        transform: translate(-50%);
        color: #c2c2c9;
        position: absolute;
    }
              
    .wrapper{
        width: 35%;
        text-align: right;
        margin-left: auto;
        margin-bottom: 30px

    }

    .references {

        @include side-container;

        background-color: white;
        margin-left: auto;
        margin-top: 35px;

        display: flex;

        .text-area {

            width: calc(100% / 3);
            padding: 35px 50px;

            .content {
                font-size: 14px;
                color: #c2c2c9;
                margin-bottom: 30px;

            }

            .person-name{
                color: black;
                font-weight: bold ;
            }

            .company-name{
                color: #c2c2c9;
                font-size: small;
            }


            
            

            
        }

    }



}

.blog{
    margin-top: 130px;
    margin-bottom: 200px;

    .previews {

        display: flex;

        .article{
            width: calc((100% / 2) - 20px);
            margin: 0 10px; 
        }

        :first-child {
            margin-left: 0;
            margin-right: auto;
        }

        :last-child {
            margin-right: 0;
            margin-left: auto;

        }
    }
}

.contact {

    position: relative;

    .text-content{
        color: white;

        text-align: center;

        position: absolute;
        left: 50%;
        top:50%;
        transform: translate(-50%,-50%);

        .wrapper {
            width: 60%;
            margin: auto;
        }
    }

}

</style>