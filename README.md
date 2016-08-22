# fd-cart demo example

Start your free e-Commerce website in just 3 mins. 
No coding required, just few settings to start your own store with your own brand name. You can try sample code and start your own website.

![preview](https://github.com/fdpay/fdstore-demo/blob/master/images/full-screen.PNG)

## <a href="http://fdpay.in/cart/index.html" target="_blank">Live Demo</a>

## How to use this sample code 

It's very simple, just download [index.html](https://github.com/fdpay/fdstore-demo/blob/master/index.html) and update your token, or you can also follow the below steps to start with your own html file.

## Including files

        <link rel="stylesheet" type="text/css" href="http://cdn.fdpay.in/scripts/v1/fd-cart.css" />
        
        <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
        <script type="text/javascript" id="fd-pay" src="http://cdn.fdpay.in/scripts/v1/fd-cart.js" 
        fd-token="****YOUR TOKEN GOES HERE****"></script>

## Get your token 

Register at [fdpay.in](http://fdpay.in) and get your email & contact number verified. Go to your profile section and activate your account, you will get a token.If you have already registered, simply login and get your token from the profile.

Every account is associated with a secure token and orders associated to that token will be reflected in your fdpay.in account. There is complete functionality available to view, process and update your orders.

### NOTE: It is very important to use your token to start with your website.

## Button Simple Settings 

         <button class="fd-button" 
         fd-id="SKU000001" 
         fd-name="Puma Round Neck"
         fd-description="Brand new T-Shirt for Sale only for fake buyers" 
         fd-wt="250"
         fd-price="1099" 
         fd-qty="1" >Add To Cart</button>
         

## Button Complex Settings

         <button class="fd-button" 
         fd-id="SKU000001" 
         fd-name="Puma Round Neck"
         fd-description="Brand new T-Shirt for Sale only for fake buyers" 
         fd-wt="250"
         fd-price="1099" 
         fd-qty="1" 
         fd-image="http://img5a.flixcart.com/image/t-shirt/v/5/2/57190303-puma-xl-275x340-imaee3abzye53hew.jpeg" 
         fd-size="M" 
         fd-color="Grey"
         fd-width="200"
         fd-height="600">Add To Cart</button>
         

## How to add products?
Every "Add to Cart" button is a product, So you can use your own style to show your product but you need to add fd-attributes to every product button.

             <div class="col s6 m4">
                <div class="card">
                    <div class="card-image">
                        <img src="http://images.abofcdn.com/catalog/images/2015/LEVIA16AMDMTE9000309/Front_Large.jpg"/>
                    </div>
                    <div class="card-content">
                        I love this tshirt.
                    </div>
                    <div class="card-action">
                        <button class="fd-button btn waves-effect waves-light" fd-color="red"
                            fd-description="I love this tshirt" fd-id="2454323"
                            fd-image="http://images.abofcdn.com/catalog/images/2015/LEVIA16AMDMTE9000309/Front_Large.jpg" fd-name="Levis Tees"
                            fd-price="1" fd-qty="1" fd-size="xl" fd-wt="500" name="action" type="submit">
                            Add To Cart
                <i class="material-icons right">send</i>
                        </button>
                    </div>
                </div>
            </div>

![preview](https://github.com/fdpay/fdstore-demo/blob/master/images/product.PNG)

## Congratulations, Website is ready 

You website is ready to launch, You can add as many product you want. fdpay plugin is a Jquery(Javascript Framework) extension with preintegrated payment gateway so  no need to worry about payment solution. No need to invest a single penny on a developer. 

You will be getting an awesome website in just few mins. 

In case, if you don't have your own domain or server, you can contact us(fdpay.in@gmail.com) we will provide you with free space on our server so that you can host there or  you can also use any of the open source platforms available online(ex. Wordpress,Blogspot).Just copy paste your code and you are all set.

- Host on BlogSpot [sample app](http://fdpay.blogspot.in/2016/08/demo.html)
- Host on wordpress [sample app] (http://fdpay.my-style.in/wordpress/sample-page/)
- [own free website](http://www.own-free-website.com/) here is fdpay demo app [sample app](http://fdpay.page.tl/)
- [Free Website](http://www.n.nu/) here is fdpay demo app [sample app](http://www.fdpay.n.nu/)


## Features 

- Readymade Cart (No Programming required)
- Cart Manipulation
  - Add Product 
  - Delete Product
  - Update Product Quantity
- Login Feature : Register once and shop from all partner sites(websites wth fdpay plugin integrated) without registration.
  - Guest Checkout (Auto registration of user on fdpay.in in case of new user)
  - Login (Your fdpay.in account which will be valid across all our partner sites, so shop from everywhere with one account.)
  - Forgot Password
- Address Feature : Add your address once on any partner site, it will be available on all our partner sites.
  - Use any of your added addresses.
  - Add new address (Simple and Quick)
  - Delete the non existing address
- Cart Preview : User can preview cart before shop and validate to avoid false payment or false order.
- Pre Intergated Payment Gateway
  - Netbanking (All public and private banks of India)
  - Credit Card, Debit Card, American Express (We accept all kind of cards)
  - Wallet (paytm, payumoney, freecharge, mobikwik, olamoney)

We secure the payments using razorpay, easebuzz, payumoney, instamojo and lot more payment solution.

Store owners can update there store settings from there panel at fdpay.in 
- Update Cart Icon Color and Position 
  - "top-right" corner position and "red" color is the default value for cart icon.
- Shipping Cost
  - Specify Avg Shipping Cost (Rs.50 per 500grm is default value.)
  - Free Shipping feature (if specifed cost is 0 then there will be no shipping on website)
  - Custom shipping (for ex-if store wants to specify free shipping on purchase of Rs.2000)
- Global Discount on Cart (always in percentage)
  -  for ex -if you want to specify 5% discount on website
  -  for ex -if you want to specify 10% discount when cart value more than 2000 Rs.
- Extra Charges on cart (always in percentage). Store owner can specify miscellaneous deductions like service charges, payment gateway charges etc.
- Tax Deduction settings on Store
- Secure your token, so no one can use your token.
- Order Management
  - Update Order Status (SHIPPED, REJECT, CANCEL, READY TO SHIP, DELIVERED, COMPLETE)
  - Reject Orders (refund on the fly)
  - Auto Generated Invoice (integrated with QR Code, to scan and view on mobile phone.)
  - Auto Generated Shipping Label for every order.
  - Pre Integrated courier companies for tracking.
- All your order settlement will go to your bank account.

### Plugin is mobile optimized (responsive) and supports angular
- Additioal setting to do -In the Angular App, where you are loading  products from your api, make a call to `angularAddToCart();` function at the end of controller which binds your products to view, rest you are all set to go.

many more features to come ... 

## fd cart 
![preview](https://github.com/fdpay/fdstore-demo/blob/master/images/cart.PNG)

## Who is using fdpay.in

- [namkeenvilla] (http://namkeenvilla.com)
- [nafinternational] (http://nafinternational.com)

### Next can be you :) 

## Resources

- Jquery by Google (Jquery Extension)
- Material Design (Style and Effects)

