<template>
    <div>
        Comp 2
    </div>
</template>

<script>
    import eventMixin from './mixin'

    export default{
        name: 'component2',
        mixins: [eventMixin],
        created(){
            console.log('event Comp 2 outside mixin');
        }
    }
</script>
