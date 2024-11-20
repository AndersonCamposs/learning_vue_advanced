<script setup>

</script>

<template>
    <div class="nav_container">
        <h1>Nav</h1>
        <nav>
            <RouterLink to="/">Home</RouterLink>
            <RouterLink to="/props">Props</RouterLink>
        </nav>
    </div>
    
</template>

<style scoped>
.nav_container {
    width: 100%;
    height: 10vh;
    color: #fff;
    background-color: #000; 
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav_container * {
    margin: 0 5px;
    padding: 5px;
}
</style>