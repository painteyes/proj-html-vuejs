<template>

    <div class="title-area">
        <span>{{sectionName}}</span>
        <h3 :style="titleSize">{{sectionTitle}}</h3>        
    </div>

</template>


<script>




export default {

    name: 'TitleArea',

    props: {
        sectionName: String,
        sectionTitle: String,
        titleSize: String,
    }
}
</script>


<style lang="scss" scoped>

.title-area{

    text-transform: uppercase;
    margin-bottom: 30px;


    span {
        font-size: 15px;
        color: #aaaaaa;
    }

    span::before{
        display: inline-block;
        content: "";
        border-top: 3px solid #39ffbf;
        width: 40px;
        margin-right: 15px ;
        height: 5px;         
    }

    h3{
        color: white;
        font-weight: bold ;
        margin-top: 20px;
    }
}

</style>