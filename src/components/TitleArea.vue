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

    span {
        font-size: 17px;
        color: #c2c2c9;
    }

    span::before{
        display: inline-block;
        content: "";
        border-top: 3px solid #39febe;
        width: 40px;
        margin-right: 15px ;
        height: 5px;         
    }

    h3{
        color: white;
        font-weight: bold ;
        margin: 25px 0;
    }
}

</style>