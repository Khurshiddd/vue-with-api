<template>
    <div class="text-center">
        <main class="form-signin w-25 m-auto">
            <form>
                <img src="../image/10138abac57d4a8c90198e5798c14e83.png" alt="logo" style="width: 90px;">
                <h1 class="h3 mb-3 fw-normal">Register</h1>
                <Input :label="'Email'" :type="'email'" :placeholder="'example@gmail.com'"/>
                <Input :label="'Password'" :type="'password'" :placeholder="''"/>
                
                <Button type="submit">Register</Button>
            </form>
        </main>
    </div>
</template>
<script>

export default {
    
}
</script>
<style>

</style>