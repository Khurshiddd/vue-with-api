<template>
    <div>
        <h1>Home: {{ $store.state.count }}</h1>
        <div class="w-25">
            <Button @click="increaseHandler">
                Increase
            </Button>
        </div>
        <div class="w-25">
            <Button @click="decreaseHandler">
                Decrease
            </Button>
        </div>
    </div>
</template>
<script>
export default {
    methods: {
        increaseHandler(){
        this.$store.commit('increment')
        },
        decreaseHandler(){
        this.$store.commit('decrement')
        }
    }
}
</script>
<style>
    
</style>