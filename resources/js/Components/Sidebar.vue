<script setup>
    export default {
        name: 'Sidebar'
    }
</script>

<template>
    <div class="sidebar">
        <div class="sidebar-item" :class="{active: route().current('home')}">
            <inertia-link href="route('home')">Home</inertia-link>
        </div>
        <div class="sidebar-item" :class="{active: route().current('trending')}">
            <inertia-link href="route('trending')">Trending</inertia-link>
        </div>
        <div class="sidebar-item" :class="{active: route().current('subscriptions')}">
            <inertia-link href="route('subscriptions')">Subscriptions</inertia-link>
        </div>
        <div class="sidebar-item" :class="{active: route().current('library')}">
            <inertia-link href="route('library')">Library</inertia-link>
        </div>
    </div>
</template>

<style scoped>

</style>
