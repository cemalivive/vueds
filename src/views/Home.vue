<script>
import AppButton from '../components/Button.vue'

export default {
    name: 'Home',
    components: { 
        AppButton
        },
}
</script>

<template>
    <div id="buttons">
    <AppButton buttonText="Dark" :dark="true" />
    <AppButton buttonText="Light" />
    </div>

</template>

<style scoped>
#buttons {
    display: flex;
    flex-direction: column;
}
</style>