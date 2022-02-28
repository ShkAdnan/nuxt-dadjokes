<template>
    <nuxt-link :to="'jokes/'+ id">
        <div class="jokes">
            {{ joke }}
        </div>
    </nuxt-link>
</template>

<script>

export default {
    name : "Jokes",
    props : ['joke', 'id']
}
</script>

<style>
.jokes{
    padding: 1rem;
    border: 1px dotted #ccc;
    margin: 1rem 0;
}
</style>
