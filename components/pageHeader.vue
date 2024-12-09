<template>
    <div class="Header">
        <logo />
        <HeaderTitle />
    </div>
    <HeaderHr />
</template>

<style scoped lang="scss">
@import '@/styles/variables';

.Header {
    width: 100%;
    height: 5em;
    background-color: $primary-black;
    display: flex;
    align-items: center;
    gap: 1vh;
}
</style>