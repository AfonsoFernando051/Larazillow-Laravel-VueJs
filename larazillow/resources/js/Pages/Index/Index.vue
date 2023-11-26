<template>
    <div>
        Index
    </div>
    <Link href="/hello">
        show
    </Link>
    <div>
        The message is {{ message }}
    </div>
</template>

<script setup>
    import {Link} from '@inertiajs/vue3'
    defineProps({
        message: String
    })
</script>