<template>
    <div>
        <MyItem 
            v-for="item in this.$store.state.myRentals"
            :key="item.id"
            :item="item"
        />
    </div>
</template>

<script>
    export default {
        layout: "no-nav",
    }
</script>