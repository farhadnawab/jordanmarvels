<template>
    <b-container>
    <b-row>
        <b-col cols = "8">
            <b-row class = "img-bubble">
                <b-img :src = "require(`../../assets/png/bubble-up.png`)" />
                <b-img class = "img-review-text-up" :src = "require(`../../assets/png/laura-text.png`)" />
            </b-row>
        </b-col>
    </b-row>
    <b-row>
        <b-col cols = "8">
            <b-row align-v = "center">
                <b-col cols = "3">
                    <b-img rounded = "circle" :src = "require(`../../assets/svg/laura.svg`)"/>
                </b-col>
                <b-col cols = "3">
                    <img :src = "require(`../../assets/svg/laura-name.svg`)" />
                </b-col>
                    <b-col cols = "3">
                    <b-img rounded = "circle" :src = "require(`../../assets/svg/rene.svg`)"/>
                </b-col>
                <b-col cols = "3">
                    <img :src = "require(`../../assets/svg/rene-name.svg`)" />
                </b-col>
            </b-row>
        </b-col>
    </b-row>
    <b-row  align-h="end">
        <b-col cols = "8" >
            <b-row class = "img-bubble">
                <b-img :src = "require(`../../assets/png/bubble-down.png`)" />
                <b-img class = "img-review-text-down" :src = "require(`../../assets/png/rene-text.png`)" />
            </b-row>
        </b-col>
    </b-row>
    </b-container>
</template>
<script>

export default {
    name: "Profile",
    props: {
        svg_photo_img: String, 
        svg_name_img: String,
        png_bubble_img: String,
        png_text_img: String
    }  
}
</script>
<style>
.img-bubble{
    position: relative;
}
.img-review-text-up{
    position: absolute;
    left: 50px;
    top: 50px;
}
.img-review-text-down{
    position: absolute;
    left: 50px;
    top: 100px;
}
</style>