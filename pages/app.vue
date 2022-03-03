<template>
    <div>
        <div :key="n" v-for="n in 100">
        {{n}}
        </div>
    </div>
</template>
<script>
export default {
    layout: 'app'
}
</script>