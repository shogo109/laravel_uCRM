<script setup>
import { Link } from "@inertiajs/vue3";
</script>

<template>
    <div>
        <h1>Inertia Test</h1>
    </div>
    <a href="/">aタグ経由</a>
    <Link href="/">Linkコンポーネント経由</Link>
    <Link :href="route('inertia.index')">Inertia経由</Link>
</template>
