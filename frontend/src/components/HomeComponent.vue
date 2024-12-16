<template>
    <div>
        <h1><router-link to="/">Home Page</router-link></h1>
        <router-link to="/theme1">Theme 1</router-link>
    </div>
</template>

<script>
export default {
    name: 'HomeComponent',
    props: {}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
