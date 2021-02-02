<template>
    <b-tabs content-class="mt-3">
        <b-tab :title="$t('home')" active>
            <b-container fluid>
                <Homepage/>
            </b-container>
        </b-tab>
        <b-tab :title="$t('second')">
            <b-container fluid>
                <p>I'm the second tab</p>
            </b-container>
        </b-tab>
        <b-tab :title="$t('third')">
            <b-container fluid>
                <p>I'm a disabled tab!</p>
            </b-container>
        </b-tab>
    </b-tabs>
</template>

<script>
    import Homepage from "@/components/Homepage/Homepage";
    export default {
        name: "Navbar",
        components: {Homepage}
    }
</script>

<style scoped>

</style>
