<script setup lang="ts">

import DocumentSvg from "@/components/svgs/DocumentSvg.vue";
</script>

<template>
<header class = "header">
    <div class="logo">
        <DocumentSvg class="icon"/>
        <h1>かんたんメモ</h1>
    </div>
    <p>思いついたことをサッと記録しよう</p>
</header>
</template>

<style scoped>
.header{
    background: white;
    padding: 16px;
    flex-direction: column;
    display: flex;
    align-items: center;
    justify-content: center;
}
.logo{
    display: flex;
    gap: 12px;
    color: coral;
    font-size: 40px;
}
.header .logo .icon{
    width: 56px;
    height: 56px;
}
.header p{
    color: dimgray;
    font-size: 19px;
}
</style>
