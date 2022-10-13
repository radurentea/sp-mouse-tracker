<template>
    <div>
        Your mouse is at position: {{ x }}, {{ y }}
    </div>
</template>

<script setup>
import { useMouse } from '../composables/mouse.js';

const { x, y } = useMouse()

</script>