<template>
    <div>
        <div class="hero">
            <h2>{{ title }}</h2>
            <p>{{ subtitle }}</p>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ0giye6b65OcnCQAUbbkTsgK7OxT4ytFa75eNxU6P3UYNHcUgTqM06eZf4w4Wy3e7HH6M&usqp=CAU" alt="Vue.js CLI">
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