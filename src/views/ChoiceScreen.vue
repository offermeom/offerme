<template>
    <v-app class="c-screen d-flex justify-center">
        <v-container>
            <v-btn
            depressed
            color="#379AFF"
            class="d-block mx-auto my-auto white--text"
            width="150px"
            @click="goToVendorLogin()"
            >
            Vendor
            </v-btn>
            <div class="d-flex justify-center">
             <div class="my-4 d-inline-flex align-center">
                <v-divider width="55px"></v-divider>
                  <h4 class="text-center grey--text mx-2">Or</h4>
                <v-divider width="55px"></v-divider>
             </div>
            </div>
            <v-btn
            depressed
            color="#379AFF"
            outlined
            class="d-block mx-auto my-auto"
            width="150px"
            @click="goToCustomerLogin()"
            >
            Customer
            </v-btn> 
        </v-container>
    </v-app>

    

</template>

<script>
export default {
    methods:{
    goToVendorLogin(){
    this.$router.push('/loginvendor'); 
    },
    goToCustomerLogin(){
    this.$router.push('/logincustomer'); 
    },
  }
}
</script>

<style>
.c-screen .v-application--wrap {
    justify-content: center;
}
</style>