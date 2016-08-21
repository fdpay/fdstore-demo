# fd-cart demo example

Start your free e-Commerce website in just 3 mint. 
No coding just few settings to start your own store on your own brand name. You can try sample code and start your own website.

![preview](https://github.com/fdpay/fdstore-demo/blob/master/images/full-screen.PNG)

## fd cart 

![preview](https://github.com/fdpay/fdstore-demo/blob/master/images/cart.PNG)

## <a href="http://fdpay.in/cart/index.html" target="_blank">Live Demo</a>

## How to use this sample code 

It's very simple just download [index.html](https://github.com/fdpay/fdstore-demo/blob/master/index.html) and update your token.

## Get your token 

Just login to [fdpay.in](http://fdpay.in"), verify your email id and phone number > Go to your profile section and just activate your account, you will get your token.

## Why token is required ?

Every account is associated with secure token, which will lead orders asscoaited to that token will be reflected on fdpay.in account, there are complete functionality to view, process and update your orders.

### NOTE: This is very important to always use your token to start with your website.

## How to add products?

Every "Add to Cart" button is a product, So you can use your own style to show your product but you need to add fd-attributes to every product button.

             <div class="col s6 m4">
                <div class="card">
                    <div class="card-image">
                        <img src="http://images.abofcdn.com/catalog/images/2015/LEVIA16AMDMTE9000309/Front_Large.jpg" class="prdImg" />

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



### We don't recommended to change settings as many users are using the same account for demo app so don't change settings.
