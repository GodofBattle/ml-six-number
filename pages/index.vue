<template>
    <div>
        <h1>HoME</h1>
        {{ data }}
    </div>
</template>

<script setup>
const { data } = await useFetch('https://dhlottery.co.kr/common.do?method=getLottoNumber&drwNo=100');
</script>
