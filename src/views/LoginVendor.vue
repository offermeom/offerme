<template>
    <v-app>
        <v-container class="d-block my-auto">
            <v-card
            elevation="2"
            >
            <V-card-title>
                Login as Vendor
            </V-card-title>
            <v-card-text>
                <v-form>
                    <v-text-field
                    prepend-icon="mdi-account"
                    name="login"
                    label="Login"
                    type="text"
                    ></v-text-field>
                    <v-text-field
                    id="password"
                    prepend-icon="mdi-lock"
                    name="password"
                    label="Password"
                    type="password"
                    ></v-text-field>
                        </v-form>             
            </v-card-text>
            <v-card-actions class="d-flex justify-center">
                <v-spacer></v-spacer>
                <v-btn color="#379AFF" class="white--text" to="/">Login</v-btn>
            </v-card-actions>
            </v-card>
        </v-container>
    </v-app>
</template>

<script>
export default {
}
</script>