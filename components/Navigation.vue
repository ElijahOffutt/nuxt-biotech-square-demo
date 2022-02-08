<template>
    <header>
        <div :style="`background-color: ${blue}`" class="banner">
            <a href="">Schedule a Demo</a>
        </div>
        <nav>
            <img height="100%" src="https://biotechsquare.com/wp-content/uploads/2019/07/biotech_logo_website.jpg" />
        </nav>
    </header>
</template>

<script>
export default {
    data(){return{
        blue: require('../assets/colors.json').blue,
        bannerFont: require('../assets/fonts.json').link,
        links: [
            {
                text: 'about',
                path: ''
            },
            {
                text: 'technology',
                path: ''
            },
            {
                text: 'contact',
                path: ''
            }
        ]
    }}
}
</script>

<style lang="scss">
.banner{
    a{
        width: 1120px;
        display: inline-block;
        text-align: right;
        color: white !important;
        text-decoration: none;
        font-weight: 600;
    }
}

header{
    nav{
        height: 60px;
        background-color: white;;
    }
}
</style>