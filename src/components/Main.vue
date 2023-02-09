<template>
    <div>
        <ElliminateFunction />
        <Solutions />
        <Industry />
        <OurClients />
        <Contact />
    </div>
</template>
<script>
import Contact from './contact.vue';
import Industry from './Industry.vue';
import Solutions from './Solutions.vue';
import OurClients from './OurClients.vue';
import ElliminateFunction from './ElliminateFunction.vue';

export default {
    components: { ElliminateFunction, Solutions, Industry, OurClients, Contact }
}
</script>
<style lang="">
    
</style>