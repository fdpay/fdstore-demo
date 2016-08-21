# fd-cart demo example

Start your free e-Commerce website in just 3 mint. 
No coding just few settings to start your own store on your own brand name. You can try sample code and start your own website.

![preview](https://github.com/fdpay/fdstore-demo/blob/master/images/full-screen.PNG)

## fd cart 

![preview](https://github.com/fdpay/fdstore-demo/blob/master/images/cart.PNG)

## <a href="http://fdpay.in/cart/index.html" target="_blank">Live Demo</a>

## How to use this sample code 

It's very simple just download [index.html](https://github.com/fdpay/fdstore-demo/blob/master/index.html) and update your token.

## Including files

        <link rel="stylesheet" type="text/css" href="jquery.pagepiling.css" />
        
        <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
        <script type="text/javascript" id="fd-pay" src="http://cdn.fdpay.in/scripts/v1/fd-cart.js" 
        fd-token="****YOUR TOKEN GOES HERE****"></script>

## Get your token 

Just login to [fdpay.in](http://fdpay.in"), verify your email id and phone number > Go to your profile section and just activate your account, you will get your token.

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

## Conclusion

You website is ready to launch, You can add as many product you want, It is just an extension of Jquery(Javascript Framework), with preintegrated payment gateway so you no need to worry about payment solution, No need to hire any developer and no need to invest any single penny, 

You will be getting awesome and cool website in just few mints. 

## Who is using fdpay.in

![namkeenvilla] (http://namkeenvilla.com)
![nafinternational] (http://nafinternational.com)

### Now next can be you :) 

## Resources

- Jquery by Google (Jquery Extension)
- Material Design (Style and Effects)

