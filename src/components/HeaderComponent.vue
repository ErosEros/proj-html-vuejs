<template>
    <div class="container-header">
        <div class="header-top">
            HeaderComponent 
        </div>
        <div class="header-bottom">
            <div class="row">
                <div class="col-3 text-center">
                    <span><strong>Flox | Business</strong></span>
                </div>
                <div class="col-6">
                    <ul class="d-flex justify-content-around">
                        <li v-for="(link, index) in links" :key="index">
                        <a :class="{active: link.current }" :href="link.url">
                        {{ link.text }}
                        </a>
                    </li>

                    

                        <!-- <li>HOME</li>
                        <li>ABOUT</li>
                        <li>SERVICE</li>
                        <li>SHOWCASE</li>
                        <li>BLOG</li>
                        <li>CONTACT</li> -->
                    </ul>
                </div>
                <div class="col-3 text-center">
                    <button class="btn btn-primary" type="button">Button</button>
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
        border: 1px solid black
    }

    .li {
        list-style: none
    }
</style>