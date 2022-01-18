<template>
    <footer class="bg-color">

        <div class="container">

            <section> 

                <div class="logo">
                    <img :src="require('../assets/images/logotype-2-150x25.png')" alt="">
                </div>

                <div class="menu">
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



            </section>

            

            <div class="copyright">
                <span>Terms of use</span>
                <br>
                <span>Privacy Environmental Policy</span>
            </div>


        </div>

        
    </footer>
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



.container {

    section{
        display: flex;
        justify-content: space-between;
        align-items: center;

        padding: 70px 0;

    }

    .menu {
        color: #6e6d7e;
        width: 60%;
        height: 100%;
        display: flex;
        
        // align-items: flex-end;

        // .logo {
        //     width: 100px;

        //     img{
        //         display: block;
        //     }
        // }

        ul {
            display: flex;
            justify-content: center;
            width: 100%;
        
            li {
                margin: 0 15px;
                text-transform: uppercase;
                line-height: 50px;

                &:hover {
                    cursor: pointer;
                }
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


//     .section::after {                
//         display: inline-block;
//         content: "";
//         border-top: 3px solid #6e6d7e;
//         width: 100%;
//         // display: block;
//         // position: absolute; 
//         // right: 0;
//         // left: 85%; 
//         // margin-top: 15px;       
//     }
}

</style>