<template>
    <div>
        <div class="hero">
            <h2>{{ title }}</h2>
            <p>{{ subtitle }}</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Hero',
    props: {
        title: String,
        subtitle: String
    }
}
</script>

<style>
    .hero {
        text-align: center;
        margin-top: 50px;
    }
</style>