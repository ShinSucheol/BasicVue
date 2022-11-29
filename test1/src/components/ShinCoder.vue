<template>
    <div>
        <p>{{ name }}</p>
        <button @click="updateName">Change Name</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: 'Shin Coder',
        }
    },

    methods: {
        updateName() {
            this.name = 'Shin Coder Updated';
        }
    }
}
</script>
