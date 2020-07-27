<template>
    <div>
        home
        <nav-header></nav-header>   <!--下面是驼峰，这边是转为-形式-->
        <router-view></router-view>  <!--这里放子路由-->
        <nav-footer></nav-footer>
    </div>
</template>

<script>
    import NavHeader from '../components/NavHeader.vue'
    import NavFooter from '../components/NavFooter.vue'
    export default {
        name:'nav-home',
        components:{
            NavHeader,
            NavFooter
        }
    }
</script>