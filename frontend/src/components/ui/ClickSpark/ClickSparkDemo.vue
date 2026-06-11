<template>
    <ClickSpark
        spark-color="#12A7E6"
        :spark-radius="20"
        :spark-length="4"
        :spark-thickness="2"
        :spark-count="8"
        :duration="320"
    />
    <h1 class="text-3xl">Click around</h1>
</template>

<script setup>
import ClickSpark from '../ClickSpark/ClickSpark.vue'
</script>