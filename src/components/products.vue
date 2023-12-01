<template>
    <div>
        
        <h1>Product Details</h1>
        <slot name="Product1">p1</slot>
        <slot name="Product2">p2</slot>

    </div>
</template>

<script>
export default {
    components:['products'],
    setup (props) {
      

    
    }
}
</script>

<style lang="scss" scoped>

</style>