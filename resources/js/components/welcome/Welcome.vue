<template>
<div class="container">
    <div class="jumbotron">
        <h1 class="display-4">Employee Management System(EMS)</h1>
        <SubHeader/>
    </div>
</div>
</template>

<script>
import SubHeader from "./partials/SubHeader";

export default {
    name: 'Welcome',
    components: {SubHeader}
}
</script>

<style scoped>

</style>
