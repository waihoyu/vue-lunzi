<template>
<div>
    <button class="g-button">按钮</button>
</div>
</template>

<script>
export default {
data(){
    return {
        
    }
}
}
</script>

<style lang="scss" scoped>
.g-button {
    font-size: var(--font-size);
    height: var(--button-height);
    background: var(--button-bg);
    border: 1px solid var(--button-color);
    border-radius: var(--border-radius);
    font: inherit;
}

.g-button:hover {
    border-color: var(--border-color-hover);
}

.g-button:active {
    background-color: var(--button-active-bg);
}
</style>
