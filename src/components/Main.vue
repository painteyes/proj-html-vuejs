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
                <a id='read-more' class="btn btn-bluegreen" href="#">Read more </a>
                <a id='play' href="#">
                    <i class="fas fa-play"></i>
                </a>
                
            </div>
        </div>
        
        <img :src="require('../assets/images/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg')" alt="">

    </section>

    <section class="services">

        <div class="wrapper">

            <div class="title-area">
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
        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam voluptatem sapiente quaerat, inventore nesciunt vel esse! Vitae itaque odit iure ipsa.</p>
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

                <div class="client">
                    <img :src="require('../assets/images/DRY-1-790x592.jpg')" alt="">
                    <div class="overlay">

                        <div class="client-name">
                            Purinky Products 
                            <br>
                            <span>uncategorized</span> 
                        </div>

                        <i class="fas fa-plus-square"></i>
                    </div>
                </div>

                <div class="client">
                    <img :src="require('../assets/images/221bf0b7-8134-43bb-936a-5acbe42db64a-790x592.jpg')" alt="">
                    <div class="overlay">

                        <div class="client-name">
                            Purinky Products 
                            <br>
                            <span>uncategorized</span> 
                        </div>

                        <i class="fas fa-plus-square"></i>
                    </div>
                </div>

                <div class="client">
                    <img :src="require('../assets/images/z1el4c4p-790x592.jpg')" alt="">
                    <div class="overlay">

                        <div class="client-name">
                            Purinky Products 
                            <br>
                            <span>uncategorized</span> 
                        </div>

                        <i class="fas fa-plus-square"></i>
                    </div>
                </div>

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

            <div class="customer">

                <div class="overlay">
                    <img :src="require('../assets/images/oliver-ragfelt-488196-2.jpg')" alt="">
                </div>

                <div class=" text-area">
                    <p class="content">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aspernatur ut mollitia, quibusdam at sapiente soluta id exercitationem error consequuntur laboriosam perferendis tenetur provident, enim ratione commodi necessitatibus omnis maiores repellendus!</p>
                    <span class="person-name"> Vera Duncan</span> 
                    <br> 
                    <span class="company-name">Amazon Inc.</span>
                </div>

            </div>

            <div class="customer">

                <div class="overlay">
                    <img :src="require('../assets/images/oliver-ragfelt-488196-2.jpg')" alt="">
                </div>

                <div class=" text-area">
                    <p class="content">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aspernatur ut mollitia, quibusdam at sapiente soluta id exercitationem error consequuntur laboriosam perferendis tenetur provident, enim ratione commodi necessitatibus omnis maiores repellendus!</p>
                    <span class="person-name"> Vera Duncan</span> 
                    <br> 
                    <span class="company-name">Amazon Inc.</span>
                </div>

            </div>

            <div class="customer">

                <div class="overlay">
                    <img :src="require('../assets/images/oliver-ragfelt-488196-2.jpg')" alt="">
                </div>

                <div class=" text-area">
                    <p class="content">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aspernatur ut mollitia, quibusdam at sapiente soluta id exercitationem error consequuntur laboriosam perferendis tenetur provident, enim ratione commodi necessitatibus omnis maiores repellendus!</p>
                    <span class="person-name"> Vera Duncan</span> 
                    <br> 
                    <span class="company-name">Amazon Inc.</span>
                </div>

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
                    
                    <div class="content">

                        <div class="date">
                            <span>July 4, 2019</span>
                            <span>by Paul</span>
                        </div>

                        <div class="title">
                            Canadian Consulting Firm acquired by UK Giant
                        </div>

                        <div class="text">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse incidunt amet eligendi sunt aliquid corporis, ad a enim possimus ...
                        </div>
                    </div>
                </div>

                <div class="article">

                    <img :src="require('../assets/images/business-people-working-together-on-project-and-5FHSKBL-1390.jpg')" alt="">
                    
                    <div class="content">

                        <div class="date">
                            <span>July 4, 2019</span>
                            <span>by Paul</span>
                        </div>

                        <div class="title">
                            Canadian Consulting Firm acquired by UK Giant
                        </div>

                        <div class="text">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse incidunt amet eligendi sunt aliquid corporis, ad a enim possimus ...
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="contact">

        <img :src="require('../assets/images/business-people-working-together-on-project-and-B3MZ4TX.jpg')" alt="">
        
        <div class="content">

            <h4>Let's talk about work</h4>
            <span>A wonderful serenity has taken possession far far away, behind the word mountains.</span>
            
            <div class="button">
                <a class="btn btn-dark" href="#">Get started</a>
            </div>

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

            #read-more:hover{
                background-color: #f71e3a;
                color: white ;
            }

            #play{
                width: 45px;
                height: 45px;
                font-size: 10px ;
                margin-left: 25px ;    
                color: #39febe;
                border: 2px solid white;
                border-radius: 50%;
                cursor: pointer; 
                position: relative;

                i {
                    position: absolute;
                    left: 50%;
                    top: 50%;
                    transform: translate(-50%,-50%);
                }   
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
    padding: 100px 0;
    background-color: #FFFFFF;
    color: black;
    position: relative;

    .wrapper{
        width: 85%;
        margin-left: auto;

        .title-area{
            display: flex;

            h3{
                min-width: 410px;
                display: inline-block;
                text-transform: uppercase;
                font-size: 25px;
            }

            .line{
                width: 100%;
                border-top: 3px solid #39ffbf;
                margin-top: 15px;  
            }
        }

        ul{ 
            margin-top: 100px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;

            li{
                width: calc((100% / 2) - 20px);
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
                    cursor: pointer;

                    h4 {
                        font-size: 20px;
                        text-transform: uppercase;
                        margin: 10px 0 ;
                    }

                    p {
                        color: #888888;
                        font-size: small;
                        width: 50%;
                    }
                }
            }
        }
    } 
}

.about-us {

    height: 550px;
    display: flex;
    align-items: center;

    img{
        height: 100%;
        width: 50%;
        object-fit:cover;
        object-position:top ;
    }

    .wrapper{
        width: 30%;
        margin: 0 70px;

        p {
            color: #aaaaaa;
        }
    }
}

.get-started {

    @include side-container;

    height: 220px;
    background-color: #39ffbf;
    display: flex;
    align-items: center;
    position: relative;
  
    .btn{
        position: absolute;
        bottom: 0;
        right: 0;
    }

    p {
        font-size: small;
        width: 25%;
        width: calc(100% / 2);
        padding-right: 25%;
        color: #444444;
    }

    h5{
        padding: 0 13%;
        font-size: 30px;
        text-transform: uppercase;
        text-align: center;
        width: calc(100% / 2);

    }
}

.project {
    margin: 130px 0;

    .wrapper{
        width: 40%;
    }

    .previews {
        width: 100%;

        .client{
            display: inline-block;
            width: calc((100% / 3) - 30px);
            margin: 0 15px;
            position: relative;

            img{
                display: block;
            }
        }

        .client:first-child {
            margin-left: auto;
            margin-right: 30px;
        }

        .client:last-child {
            margin-right: auto;
            margin-left: 30px;
        }
    }

    .overlay{
        display: none;

        .client-name{
            color: white;
            font-size: 20px;
            font-weight: bold ;

            span{
               color: #c2c2c9; 
                font-weight: lighter ;
                font-size: smaller;
            }  
        }

        i{
            font-size: 45px;
        }

        *{
            display: none;
        }

        &:hover{
            *{
                display: block;
            }
        }
    }

    .client:hover{

        .overlay {
            display: flex;    
            justify-content: space-between;
            align-items: flex-end;
            padding: 20px;
            position: absolute; 
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba($brand_secondary_color, 0.8);
            cursor: pointer; 
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
        color: #AAAAAA;
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
        height: 300px;
        background-color: #FFFFFF;
        margin-left: auto;
        margin-top: 35px;

        display: flex;

        .customer {
            position: relative;
            width: calc(100% / 3);
            
            .overlay{
                height: 100%;
                opacity: 0;

                img {
                    height: 100%;
                    width: 100%;
                    display: block;
                    object-fit: cover;                    
                }
            }

            .text-area {
                display: block;    
                position: absolute; 
                top: 0;
                left: 0;
                right: 0;
                bottom: 0;
                cursor: pointer; 
                z-index: 0;

                display: flex;
                justify-content: flex-start;
                align-items: flex-start;
                flex-direction: column;
                
                padding: 50px;

                .content {
                    font-size: 14px;
                    color: #888888;
                    margin-bottom: 30px;
                }

                .person-name{
                    color: black;
                    font-weight: bold ;
                }

                .company-name{
                    color: #888888;
                    font-size: small;
                } 
            }

            &:hover{

                .overlay {
                    opacity: 1;
                }
                
                .text-area .person-name{
                    color: white;
                }

                .text-area .content,
                .text-area .company-name{
                    color: #aaaaaa;
                }
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
            position: relative;
            cursor: pointer; 

            
            .content{
                background-color: #FFFF;
                width: 80%;
                margin-left: auto ;
                margin-top: -50px ;
                position: absolute;
                right: 0;
                bottom: -60px;
                z-index: 1;
                padding: 50px;

                .date{
                    color: $brand_secondary_color;
                    margin-bottom: 10px ;

                    span{
                        margin-right: 15px ;
                    }
                }

                .title{
                    font-size: 26px ;
                    margin-bottom: 20px;
                }

                .text{
                    color: #888888;
                }                
            }

            // &:hover::after{
            //     content: "";
            //     position: absolute; 
            //     top: 0;
            //     left: 0;
            //     right: 0;
            //     bottom: 0;
            //     background-color: rgba($brand_secondary_color, 0.5);
            // }
        }

        .article:first-child {
            margin-left: 0;
            margin-right: 20px;
        }

        .article:last-child {
            margin-right: 0;
            margin-left: 20px;

        }
    }
}

.contact {
    position: relative;

    img{
        width: 100%;
        height: 400px;
        object-fit: cover;
    }

    .content{
        color: white;
        text-align: center;
        position: absolute;
        left: 50%;
        top:50%;
        transform: translate(-50%,-50%);
        margin: auto;

        h4{
            font-size: 40px;
            text-transform: uppercase;
            margin-bottom: 15px;
        }
        span{
            display: inline-block;
            width: 60%;
            margin-bottom: 25px;
        }
    }
}

</style>