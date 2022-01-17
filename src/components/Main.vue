<template>
<main>

    <div class="jumbotron ">
        
        <div class="text-area">

            <div class="container">

                <div class="wrapper">

                    <div class="text">
                        <span>Always the best way you need it</span>
                        <h2>The best business consulting</h2>
                    </div>

                    <div class="buttons">
                        <a class="btn" href="#">Read more </a>
                        <i id='play' class="fas fa-play"></i>
                    </div>
                
                </div>
            </div>
        </div>

        <img :src="require('../assets/images/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg')" alt="">

    </div>

</main>    
</template>


<script>
export default {
    name: 'Main',
}
</script>


<style lang="scss" scoped>

@import "../styles/general.scss";
@import "../styles/variables.scss";



.jumbotron {
 
    height: 900px;
    background-color: $brand_primary_color ;
    color: white;
    display: flex;
    align-items: center;
    position: relative;

    .text-area{
        position: absolute;
        width: 100%;

        .wrapper{
            width: 50%;
            text-transform: uppercase;

            span::before{
                display: inline-block;
                content: "";
                border-top: 3px solid #39febe;
                width: 40px;
                margin-right: 15px ;         
            }

            h2{
                font-size: 80px;
                margin: 25px 0;
            }

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
            }

        }
    }

    img{
        height: 100%;
        margin-left: auto; 
    }

}





</style>