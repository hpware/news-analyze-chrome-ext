<script setup lang="ts">
import { ref } from "vue";
const serverInput = ref();
</script>

<template>
    <div class="justify-center align-center text-center p-4">
        <div class="flex flex-row">
            <span>Current: </span><span>{{ serverInput }}</span>
        </div>
        <h3 class="text-2xl text-bold">Change your server url:</h3>
        <div class="flex flex-row">
            <input type="text" v-model="serverInput" />
            <button>Submit</button>
        </div>
    </div>
</template>
