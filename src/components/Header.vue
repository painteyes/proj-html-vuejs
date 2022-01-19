<template>
    <header>

        <div class="container">

            <div class="logo">
                <img :src="require('../assets/images/logotype.png')" alt="">
            </div>

            <div class="menu">

                <!-- Expanded menu -->
                <ul class="list-menu">
                    <li class="item" v-for="element,index in menuItems" :key='index'>{{element}}</li>
                </ul>

                <!-- Burger menu -->
                <div class="burger-menu">
                    <i id="menu-icon" class="fas fa-bars" @click="clickMenu"></i>
                    <ul v-if="menuShow">
                        <li v-for="element,index in menuItems" :key='index'>{{element}}</li>
                    </ul>
                </div>
            </div>
        </div>

    </header>
</template>


<script>

export default {

    name: 'Header',

    props: {
        menuItems: Array,

    },

    data: function() {
        return{
            menuShow: false,
        }
    },

    methods: {
        clickMenu: function(){
            return this.menuShow = !this.menuShow;
        }
    }
}
</script>


<style lang="scss" scoped>

@import "../styles/general.scss";

header{
    width: 100%;
    height: 70px;    
    position: absolute;
    z-index: 1;

    .container{
        display: flex;
        align-items: flex-start;
        padding-top: 20px;

        .logo {
            width: 100px;
            margin-top: 4px;
            cursor: pointer;
            img{
                display: block;
            }
        }

        .menu {
            margin-left: auto;
            color: white;
            display: flex;
            align-items: center;

            .list-menu {
                display: flex;

                li {
                    line-height: 66px;
                    margin: 4px 25px 0;

                    &:hover {
                        line-height: 66px;
                        border-top: 4px solid white ;
                        margin-top: 0;                    
                    }
                }

                li:first-child {
                    margin-left: 0;
                }

                li:last-child {
                    margin-right: 0;
                }
            }

            // Burger menu
            .burger-menu{
                text-align: right;

                i{
                    display: none;
                    font-size: 40px;
                    cursor: pointer;
                }

                li {
                    margin: 25px 0;
                    cursor: pointer;
                }
            }
        }
    }
}


@media screen and (max-width: 920px) {

    .list-menu .item{
        display: none;
    }

    #menu-icon {
        display: inline-block;
    }
}

</style>