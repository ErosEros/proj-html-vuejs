<template>
    <div class="container-header">
        <div class="header-top">
            <div id="eroseros" class="row d-flex justify-content-between">
                <div class="col-3">
                    <span class="text-white">(001)88451234 88455438</span>
                </div>
                <div class="col-3 text-end">
                    <span class="text-white">icon social</span>
                </div>
            </div>
        </div>
        <div class="header-bottom">
            <div class="row eros-flex">
                <div class="col-3 text-center">
                    <div>
                        <img class="img-logo" src="./img/cropped-Group-39-2x.png" alt="logo">
                    </div>
                </div>
                <div class="col-6">
                    <ul class="d-flex justify-content-around">
                        <li v-for="(link, index) in links" :key="index">
                            <a id="eros-text" :class="{active: link.current }" :href="link.url">
                                {{ link.text }}
                            </a>
                        </li>
                    </ul>
                </div>
                <div class="col-3 text-center">
                    <button id="eros-green" class="btn btn-primary rounded-pill " type="button">Button</button>
                </div>
                
            </div>
        </div>
    </div>

</template>
<script>
export default {
    name: "HeaderComponent",
    props: ["links"],
}
</script>
<style lang="scss">
    .header-top{
        background-color: #4c4c4c;
        height: 5vh;
    }
    .header-bottom {
        height: 10vh;
        // border: 1px solid black;
        padding: 1rem;
        overflow: hidden;
    }

    li{
        list-style: none
    }

   #eros-text{
    text-decoration: none;
    color: black;
   }

    .img-logo{
        width: 175px;
    height: 50px;
}

.eros-flex{
    display: flex;
    align-items: baseline;
}
#eros-green{
       background-color: #00d9a6;
       border: none
    } 
</style>