<template>
    <div>
        <Header />
        <Section1 />
        <Section2 />
        <Section4 />
    </div>
</template>

<script>

import Header from './Header.vue';
import Section1 from './Section1.vue';
import Section2 from './Section2.vue';
import Section4 from './Section4.vue';

    export default 
    {
        name: 'Home',
        components:
        {
            Header,
            Section1,
            Section2,
            Section4
        }
    }

</script>
