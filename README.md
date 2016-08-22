# fd-cart demo example

Start your free e-Commerce website in just 3 mint. 
No coding just few settings to start your own store on your own brand name. You can try sample code and start your own website.

![preview](https://github.com/fdpay/fdstore-demo/blob/master/images/full-screen.PNG)

## <a href="http://fdpay.in/cart/index.html" target="_blank">Live Demo</a>

## How to use this sample code 

It's very simple just download [index.html](https://github.com/fdpay/fdstore-demo/blob/master/index.html) and update your token, or you can also follow the below steps, to start your own html file.

## Including files

        <link rel="stylesheet" type="text/css" href="jquery.pagepiling.css" />
        
        <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
        <script type="text/javascript" id="fd-pay" src="http://cdn.fdpay.in/scripts/v1/fd-cart.js" 
        fd-token="****YOUR TOKEN GOES HERE****"></script>

## Get your token 

Just login to [fdpay.in](http://fdpay.in), verify your email id and phone number > Go to your profile section and just activate your account, you will get your token.

Every account is associated with secure token, which will lead orders asscoaited to that token will be reflected on fdpay.in account, there are complete functionality to view, process and update your orders.

### NOTE: This is very important to always use your token to start with your website.

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

## Congratulations, Website is ready to launch

You website is ready to launch, You can add as many product you want, It is just an extension of Jquery(Javascript Framework), with preintegrated payment gateway so you no need to worry about payment solution, No need to hire any developer and no need to invest any single penny, 

You will be getting awesome and cool website in just few mints. 

In Case, If you don;t have your own domain or your own server, you can contact us we will provide you free space on our server so that you can host there or else you can use any of the below open source platform and just copy paste your code and you are all done.

- Host on BlogSpot [sample](http://fdpay.blogspot.in/2016/08/demo.html)
- Host on wordpress
- [own free website]http://www.own-free-website.com/ here is fdpay demo app [sample app](http://fdpay.page.tl/)

You are free to use any online free website provider and do your setting and start selling your products.

## Features 

- Readymade Cart (No Coding)
- Cart Manipulation
  - Add Product 
  - Delete Product
  - Update Product Quantity
- Login Feature : register one time and shop from all partner site without registration.
  - Guest Checkout (Auto registration of user on fdpay.in in case of new user)
  - Login (Login will your fdpay.in login which will be valid accorss all our partner sites, So one login and shop from every where.)
  - Forgot Password
- Address Feature : add your address one time on any partner site it will be avaible to all our partner site those how are using our plugin
  - View all your previous address
  - Add new address (Simple and Quick)
  - Delete the non existing address
- Cart Preview : user can preview cart before shop and validate to avoid false payment or false order.
- Pre Intergated Payment Gateway
  - Netbanking (All major banks of India)
  - Credit Card, Debit Card, American Express (We except all kind of cards)
  - Wallet (paytm, payumoney, freecharge, mobikwik, olamoney)

We secure our payment using razorpay, easebuzz, payumoney, instamojo and lot more payment solution.

Store owner can update there store settings from there panel at fdpay.in 
- Update Cart Icon Color and Position 
  - "top-right" corner position and "red" color is the default value for cart icon.
- Shipping Cost
  - Specify Avg Shipping Cost (50 Rs. per 500grm is default value.)
  - Free Shipping feature (if Specifed cost is 0 then there will be no shipping on website)
  - Custom shipping (if Store want to specify free shipping on purchase of 2000 Rs. something like this.)
- Global Discount on Cart (always in percentage)
  -  for example if you want to specify 5% discount on website
  -  for example if you want to specify 10% discount when cart value more than 2000 Rs.
- Extra Charges on Cart (always in percentage), Store owner can specify deduction like service charges, payment gateway charges etc.
- Tax Deduction settings on Store
- Secure your token, so no one can use your token.
- Orders Management
  - Update Orders Status (SHIPPED, REJECT, CANCEL, READY TO SHIP, DELIVERED, COMPLET)
  - Reject Orders (refund on the fly)
  - Auto Generated Invoice (integrated with QR Code, to scan and view on mobile phone.)
  - Auto Generated Shipping Label for each orders.
  - Pre Integrated Shipping Tracking System with top 22 Shipping brands.
- All your order settelment will goes to your bank accounts.

many more features yet to come ... 

## fd cart 
![preview](https://github.com/fdpay/fdstore-demo/blob/master/images/cart.PNG)

## Who is using fdpay.in

- [namkeenvilla] (http://namkeenvilla.com)
- [nafinternational] (http://nafinternational.com)

### Now next can be you :) 

## Resources

- Jquery by Google (Jquery Extension)
- Material Design (Style and Effects)

