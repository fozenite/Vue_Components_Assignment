<template>
    <div class="container">
        <app-header></app-header>
        <hr>
        <div class="row">
            <app-server-list></app-server-list>
            <app-server-details></app-server-details>
        </div>
        <hr>
        <app-footer></app-footer>
    </div>
</template>

<script>
    import ServerList from './components/ServerList.vue';
    import ServerDetails from './components/ServerDetails.vue';
    export default {
        components: {
            'app-server-list': ServerList,
            'app-server-details': ServerDetails
        }
    }
</script>

<style>

</style>
