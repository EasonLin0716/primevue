<template>
    <DocSectionText v-bind="$attrs">
        <p>ProgressBar is used with the <i>value</i> property.</p>
    </DocSectionText>
    <div class="card">
        <ProgressBar :value="50"></ProgressBar>
    </div>
    <DocSectionCode :code="code" />
</template>

<script setup lang="ts">
import ProgressBar from '@/volt/ProgressBar.vue';
import { ref } from 'vue';

const code = ref(`
<template>
    <div class="card">
        <ProgressBar :value="50"></ProgressBar>
    </div>
</template>

<script setup lang="ts">
import ProgressBar from '@/volt/ProgressBar.vue';
<\/script>
`);
</script>
