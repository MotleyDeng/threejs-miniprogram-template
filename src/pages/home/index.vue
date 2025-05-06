<template>
    <div>
        <LoadModel></LoadModel>
    </div>
</template>
<script setup>
    import LoadModel from '@/components/LoadModel.vue';
    import { onMounted } from 'vue';
    onMounted(() => {
        console.log('TODO1');
    });
</script>