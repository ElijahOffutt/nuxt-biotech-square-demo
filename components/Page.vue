<template>
    <div class="wrap">
        <header>
            {{heading}}
        </header>
        <v-container fluid>
            <slot />
        </v-container>
    </div>
</template>

<script>
export default {
    props: ['heading']
}
</script>