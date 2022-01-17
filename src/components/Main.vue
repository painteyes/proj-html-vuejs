<template>
<main>
    <div class="jumbotron">

        <div class="explore">
            
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

main{

    



}

.jumbotron {


    
    height: 900px;
    display: flex;

    img{
        width: 70%;
    }

    .explore {
        background-color: #1f1e38;
        width: 30%;
        height: 100%;
    }



}





</style>