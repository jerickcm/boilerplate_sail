<script>
import { Head, Link } from '@inertiajs/vue3'
import PublicLayout from '../Layouts/PublicLayout.vue'

export default {
    components: {
        Head,
        PublicLayout
    },
    setup () {
        return {}
    }
}
</script>

<template>
    <Head title="Homepage" />
    <PublicLayout>
        <div>
            <div class="max-w-7xl mx-auto p-6 lg:p-8">
                <h1>Homepage</h1>
            </div>
        </div>
    </PublicLayout>
</template>