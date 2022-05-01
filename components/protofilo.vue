<template>
    <v-container>
        <div id='component-protofile' class="d-flex flex-column justify-center align-center">
            <img src="~/assets/resorces/download (1).jpg" alt="">
            <h1>{{name}}</h1>
            <p>{{description}}</p>
            <div class="d-felx">
                <a href="https://github.com/ali-en-2000" title="github" target="blank"><i class="fa-brands fa-github mx-2"/></a>
                <a href="https://t.me/ali_Frontend_developer" title="telegram" target="blank"><i class="fa-brands fa-telegram mx-2"/></a>
                <a href="https://www.linkedin.com/" title="linkedin" target="blank"><i class="fa-brands fa-linkedin mx-2"/></a>

            </div>
        </div>
    </v-container>

</template>

<script>
export default {
    data() {
        return {
            name:'ali reza mohmmadi',
            description: 'im future of web programming'
        }
    },

};
</script>

<style lang="scss" scoped>
    #component-protofile{
        height: 100vh;
        margin: 0;
    }
    img{
        border-radius: 150px;
        max-height: 100px;
        max-width: 100px;
    }
    i{
        font-size: 34px ;
    }
</style>