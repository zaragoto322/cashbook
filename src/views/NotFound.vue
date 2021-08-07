<template>
    <div>
        <div>
            404 Not Found
        </div>
        <div>
             <router-link to="/">返回首页</router-link>
        </div>
    </div>
</template>

<script>
import Nav from '@/components/Nav.vue'
    export default {
        name: 'NotFound',
        components: {Nav}
    }
</script>

<style lang="scss" scoped>

</style>