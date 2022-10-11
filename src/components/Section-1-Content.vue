<template>
    <div class="Section-1-container">
        <div class="row">
            <div id="eros-padding" class="col-4">
                <p class="eros-green">17 Years of experience</p>
                <h1>Focus on Your <span class="eros-green">Business</span></h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod fuga aut consequuntur nisi, optio debitis tempore nobis molestias, facilis modi voluptatum dolorem id, voluptate corrupti repellat eaque! Unde, adipisci voluptatem.</p>
                <button id="eros-p-button" type="button" class="btn btn-dark m-5 rounded-pill">Dark</button>
                <p class="eros-font-size">FACEBOOK - INSTAGRAM - YOU TUBE - TWITTER</p>
            </div>
            <div class="col-8 section-1-photo-bg">
                
            </div>

        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss">
    h1 {
        overflow: hidden;
    }
    .Section-1-container{
        margin: 5px;
        background-color: #f5f5f5;
       
        
    }
    .section-1-photo-bg{
        background-image: url(./img/Group-35-2x.png);
        width: 100%;
        background-size: cover;
        background-repeat: no-repeat;
    }

    #eros-padding{
        padding-left: 80px;
        margin-top: 50px;
        
    }

    .eros-green{
       color: #00d9a6
    }
    
    #eros-p-button{
        padding: 10px 30px;
       background-color: #00d9a6;
       border: none
    } 
    

    .eros-font-size{
        font-size: 12px
    }
</style>