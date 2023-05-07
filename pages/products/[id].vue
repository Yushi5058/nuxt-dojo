<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Fugiat nobis laborum modi ut illum eos aspernatur harum? Tenetur, facilis veniam!</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
    definePageMeta({
layout: 'products'
})


</script>

<style scoped>

</style>
