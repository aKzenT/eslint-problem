<template functional>
    
</template>

<script lang="ts">
    import { Component } from 'vue-property-decorator';
    import B from './B.vue';

    @Component({
        name: 'A',
        components: { B },
    })
    export default class A {
    }
</script>