<template>
    <div class="bar">
        <h1 class="header">Barコンポーネント</h1>
        <p>これはBarコンポーネントです。</p>
        <foo/>
    </div>
</template>

<script>
import Foo from './foo'
export default {
    components: {
        Foo
    }
}
</script>
<style>
p { text-decoration: underline; }
</style>

<style scoped>
.bar {
    border: solid 1px red;
    margin: 4px;
    padding: 4px;
}
.header { font-size: 125%; }
</style>
