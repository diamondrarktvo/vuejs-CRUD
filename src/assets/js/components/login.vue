<template>
    
    <form>
  <!-- Email input -->
    <div id="login">
            <h1>Login</h1>
        </div>
    <div class="form-outline mb-4">
        <input type="email" id="form2Example1" class="form-control" />
        <label class="form-label" for="form2Example1">Email address</label>
    </div>

    <!-- Password input -->
    <div class="form-outline mb-4">
        <input type="password" id="form2Example2" class="form-control" />
        <label class="form-label" for="form2Example2">Password</label>
    </div>

    <!-- Submit button -->
    <button type="button" class="btn btn-primary btn-block mb-4">Login</button>

  
</form>
</template>

<script>

    export default{
        data(){
            return{
                test: []
            }
        },

        // created: function()
        // {
            
        // },

        // methods: {
        //     // fetchProductData: function()
        //     // {
        //     //     this.$http.get('http://localhost:3000/api/products').then((response) => {
        //     //         this.products = response.body;
        //     //         this.originalProducts = this.products;
        //     //     }, (response) => {

        //     //     });
        //     // },

        //     // searchProducts: function()
        //     // {
        //     //     if(this.productSearch == '')
        //     //     {
        //     //         this.products = this.originalProducts;
        //     //         return;
        //     //     }

        //     //     var searchedProducts = [];
        //     //     for(var i = 0; i < this.originalProducts.length; i++)
        //     //     {
        //     //         var productName = this.originalProducts[i]['name'].toLowerCase();
        //     //         if(productName.indexOf(this.productSearch.toLowerCase()) >= 0)
        //     //         {
        //     //             searchedProducts.push(this.originalProducts[i]);
        //     //         }
        //     //     }

        //     //     this.products = searchedProducts;
        //     // }
        // }
    }
</script>
