<template>
    <div>
        <multiselect v-model="value" :options="options"></multiselect>

    </div>
</template>
<script>
    import Multiselect from 'vue-multiselect'
    export default {
        name: "Layout",
        components: {Multiselect},
        data(){
            return {
                value: null,
                options: ['list', 'of', 'options']
            }
        }
    }
</script>
<style src="vue-multiselect/dist/vue-multiselect.min.css"></style>
<style lang="scss">

</style>