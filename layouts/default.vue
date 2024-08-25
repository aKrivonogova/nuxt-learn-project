<template>
    <div>
        <header>
            <NavBar />
        </header>
        <main>
            <nuxt />
        </main>
        <footer>
            тут будет какой-то фуутер
        </footer>
    </div>
</template>

<script>

import NavBar from '@/components/NavBar.vue'
export default {
    name: 'layouts',
}

</script>

<style></style>