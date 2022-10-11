<template>
    <div class="container-section-3">
        <div class="row">
            <div class="col-8">
                <div class="row mt-5 mb-5 position-relative eros-height">
                    <div id="bg-eros-green" class="col-6">
                        <img class="opacity-eros" src="./img/busy-architect-PYVKWM4-1024x872.jpg" alt="architect">
                    </div>
                    <div class="col-6 eros-absolute">
                        <img src="./img/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="business-woman">
                    </div>
                      
                </div>           
            </div>
            <div class="col-4 eros-p-100">
                <h2>Lear more about our <span class="eros-green">missions</span></h2>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora odio omnis natus iusto. Ea velit nam asperiores molestiae nesciunt dicta, dolorem possimus enim tempora nemo. Tempore vitae itaque architecto cumque.</p>
                <button id="eros-p-button" type="button" class="btn btn-success mt-4 mb-4 rounded-pill ">Success</button>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss">
    img{
        height: 20rem;
    }

    .opacity-eros{
        opacity: 0.3;
    }

    #bg-eros-green{
    // background: linear-gradient(45deg, #00d916, transparent);
    border-top-right-radius: 5%
    }

    .container-section-3{
        margin: 20px 0px;
        background-color: #f5f5f5;
    }

    .eros-absolute{
    position: absolute;
    top: 50px;
    left: 280px;
    }

    .eros-height{
        height: 400px;
    }

    .eros-p-100{
        padding: 100px 0px;
    }

    #eros-p-button{
        padding: 10px 30px;
       background-color: #00d9a6;
       border: none
    } 
</style>