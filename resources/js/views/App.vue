<template>
    <div class="page-container">
        <md-app>
            <md-app-toolbar class="md-primary">
                <router-link :to="{ name: 'home' }">
                    <md-button>Darkwoolf blog</md-button>
                </router-link>
                <router-link :to="{ name: 'hello' }">
                    <md-button>Hello</md-button>
                </router-link>

            </md-app-toolbar>
            <md-app-content class="posts">
                <router-view></router-view>
            </md-app-content>
        </md-app>
    </div>
</template>

<script>
    export default {
        name: "App"
    }
</script>

<style lang="scss" scoped>
</style>