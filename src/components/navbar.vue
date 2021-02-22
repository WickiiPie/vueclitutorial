<template>
    <nav>
        <!-- flat removes drop shadow -->
        <v-toolbar flat app>
            <v-toolbar-title class="text-lowercase purple--text">
                <span class="font-weight-light">ProjectName</span>
                <span> todo </span>
            </v-toolbar-title>
            <!-- space between title and button -->

            <v-spacer></v-spacer>
            <v-btn flat color="grey">
                <span>Signout</span>
                <v-icon>mdi-exit-to-app</v-icon>
            </v-btn>
        </v-toolbar>
    </nav>
</template>
<script>
export default {

}
</script>