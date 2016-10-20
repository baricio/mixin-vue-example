<template>
    <div>
        Comp 1
    </div>
</template>

<script>
    import eventMixin from './mixin'

    export default{
        name: 'component1',
        mixins: [eventMixin]
    }
</script>
