<template>
    <header>

        <div class="container">

            <div class="logo">
                <img :src="require('../assets/images/logotype.png')" alt="">
            </div>

            <div class="menu">
                <ul>
                    <li v-for="element,index in menuItems" :key='index'>{{element}}</li>
                </ul>
            </div>

        </div>

    </header>
</template>


<script>
export default {

    name: 'Header',

    props: {
        menuItems: Array,

    }
}
</script>


<style lang="scss" scoped>

@import "../styles/general.scss";

header{
    height: 50px;    
    width: 100%;
    position: absolute;
    z-index: 1;
    
    .container{
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;

        .logo {
            width: 100px;

            img{
                display: block;
            }
        }

        .menu {
            color: white;
            width: 60%;
            height: 100%;
            display: flex;
            align-items: flex-end;

            ul {
                display: flex;
                width: 100%;
                
            
                li {
                    margin: auto;
                    text-transform: uppercase;
                    line-height: 50px;

                    &:hover {
                        border-top: 4px solid white ;
                        line-height: 46px;
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
    }
}

</style>