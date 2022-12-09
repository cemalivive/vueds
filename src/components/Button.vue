<template>
    <button :class="[dark ? 'dark' : 'light', 'baseButton']"> {{ buttonText }}</button>
</template>


<script>

export default ({
props: {
    buttonText: {
        type: String,
        default: () => 'Button!',
    },
    light:{
        type: Boolean,
        default: () => true,
    },
    dark:{
        type: Boolean,
        default: () => false,
    },
},
})
</script>



<style scoped>
.baseButton {
padding: 10px;
border:1px solid gray;
border-radius: 4px;
cursor: pointer;

}

.light {
background-color: white;
color: black;
}
.dark {
background-color: black;
color: white;
}

</style>