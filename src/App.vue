<template>
    <div id="app">
        <h1>{{msg}}</h1>
        <comp1></comp1>
        <comp2></comp2>
        <comp3></comp3>
    </div>
</template>

<script>
    import Comp1 from './Comp1.vue'
    import Comp2 from './Comp2.vue'
    import Comp3 from './Comp3.vue'
    import eventMixin from './mixin'

    export default{
        name: 'root',
        data(){
            return{
                msg: 'Vue Mixin'
            }
        },
        components:{
            Comp1, Comp2, Comp3
        },
        mixins: [eventMixin]
    }
</script>
