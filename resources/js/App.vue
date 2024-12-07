<script setup>
import { ref } from "vue";

const count = ref(0);
</script>

<template>
    <div>
        <h2>Welcome to Laravel & VueJS app!</h2>
        <div>
            <div>{{ count }}</div>
            <button type="button" @click="count++">Add</button>
            <button type="button" @click="count--">Minus</button>
        </div>
    </div>
</template>