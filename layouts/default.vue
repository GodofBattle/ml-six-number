<template>
    <div>
        <Menubar :model="menuItems"></Menubar>
        <slot/>
    </div>
</template>

<script setup>
const menuItems = [
    { label: 'Home', icon: 'pi pi-fw pi-home', to: '/' },
    { label: 'History', icon: 'pi pi-fw pi-desktop', to: '/history' },
    { label: 'Compute', icon: 'pi pi-fw pi-plus', to: '/compute' },
]
</script>