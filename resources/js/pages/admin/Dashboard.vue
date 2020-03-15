<template>
    <div class="container">
        <div class="card card-default">
            <div class="card-header">Admin Dashboard</div>
            <div class="card-body">
                Bienvenue sur votre dashboard administrateur
            </div>
        </div>
        <div class="card card-default">
            <div class="card-header">Liste des utilisateur</div>
            <div class="card-body">
                <userList></userList>
            </div>
        </div>
    </div>
</template>

<script>
    import userList from '../../components/user-list';
    export default {
        components: {
            userList
        }
    }
</script>

<style scoped>

</style>
