<template>
    <div>

        <h2>About</h2>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eaque rem perferendis similique dolores fugiat
            explicabo tenetur tempore officiis eligendi eveniet. Quae officiis ipsa consequatur exercitationem
            consectetur voluptatem modi praesentium commodi!</p>
        <div>{{ data }}</div>
    </div>
</template>

<script setup>
const { data } = await useFetch('/api/currency/GBP')
</script>

<style scoped>
h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

p {
    margin: 20px 0;
}
</style>