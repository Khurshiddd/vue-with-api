<template>
    <div class="d-flex flex-column flex-md-row align-items-center py-3 mb-4 border-bottom">
        <a class="d-flex align-items-center text-dark text-decoration-none">
            <img src="../image/10138abac57d4a8c90198e5798c14e83.png" alt="logo" style="width: 90px; height: 60px; cursor: pointer;" @click="toHomeHandler">
        </a>
        
        <nav class="d-inline-flex mt-2 mt-md-0 ms-md-auto">
            <a>
                <RouterLink :to="{name: 'login'}" class="me-3 py-2 text-dark text-decoration-none">Login</RouterLink>
            </a>
            <a>
                <RouterLink :to="{name: 'register'}" class="me-3 py-2 text-dark text-decoration-none">Register</RouterLink>
            </a>
        </nav>
    </div>
</template>
<script>
export default {
    methods:{
        toHomeHandler(){
            return this.$router.push('/')
        }
    }
}
</script>
<style>

</style>