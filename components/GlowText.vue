<template>
    <span
        class="inline text-primary-content transition-all underline hover:decoration-transparent hover:drop-shadow-[0_0_10px_#fff] duration-1000">
        <slot />
    </span>
</template>

<style>
@keyframes glow {
    from {
        text-shadow: 0 0 0px #fff, 0 0 0px #fff;
    }

    to {
        text-shadow: 0 0 20px #fff, 0 0 30px #fff;
    }
}
</style>