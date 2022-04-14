<template>
    <div id="headerdiv">
        <img 
            src="https://image.shutterstock.com/shutterstock/photos/1283829169/display_1500/stock-vector-fantasy-sport-logo-1283829169.jpg" 
            alt="">
        <span>reDraft Fantasy Sports</span>
    </div>
</template>

<script>
    export default {
        name: 'PageHeader'
        
        }
</script>

<style scoped>
    #headerDiv{
        display: flex;
    }
    span {
        font-size: 3rem;
        color: #383838;
    }
    img {
        float: left;
        max-height: 65px;
        max-width: 65px;
    }
    
</style>