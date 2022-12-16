<template>
    <div class="container-fluid text-center p-4">
        <div class="row">
            <!-- Kiri -->
            <div class="col-3 border-end border-1 border-danger" style="padding-right: 0">
                <div class="border-bottom border-2 border-danger" style="height: 6rem">Jacob's Breakfast</div>
                <div class="border-bottom border-2 border-danger overflow-scroll" style="height: 24rem">Invoice Body</div>
                <div class="" style="height: 6rem">Commands</div>
            </div>

            <!-- Kanan -->
            <div class="col-9 border-start border-1 border-danger">
                <!-- Content -->
                <div class="row" style="height: 478px">
                    <!-- Category Tab -->
                    <nav>
                        <div class="nav nav-tabs" id="nav-tab" role="tablist">
                            <button class="nav-link active" id="nav-appetizer-tab" data-bs-toggle="tab" data-bs-target="#nav-appetizer" type="button" role="tab" aria-controls="nav-appetizer" aria-selected="true">Appetizer</button>
                            <button class="nav-link" id="nav-maincourse-tab" data-bs-toggle="tab" data-bs-target="#nav-maincourse" type="button" role="tab" aria-controls="nav-maincourse" aria-selected="false">Main Course</button>
                            <button class="nav-link" id="nav-dessert-tab" data-bs-toggle="tab" data-bs-target="#nav-dessert" type="button" role="tab" aria-controls="nav-dessert" aria-selected="false">Dessert</button>
                            <button class="nav-link" id="nav-soup-tab" data-bs-toggle="tab" data-bs-target="#nav-soup" type="button" role="tab" aria-controls="nav-soup" aria-selected="false">Soup</button>
                            <button class="nav-link" id="nav-drink-tab" data-bs-toggle="tab" data-bs-target="#nav-drink" type="button" role="tab" aria-controls="nav-drink" aria-selected="false">Drink</button>
                            <!-- <button class="nav-link" id="nav-others-tab" data-bs-toggle="tab" data-bs-target="#nav-others" type="button" role="tab" aria-controls="nav-others" aria-selected="false">Others</button> -->
                        </div>
                    </nav>

                    <!-- Isi category -->
                    <div class="tab-content pt-3" id="nav-tabContent">
                        <div class="tab-pane fade show active" id="nav-appetizer" role="tabpanel" aria-labelledby="nav-appetizer-tab" tabindex="0">
                            <div class="row row-cols-1 row-cols-md-3 g-4">
                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Appetizer/savoury party bread.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Savory Party Bread</h5>
                                            <p class="card-text">It’s impossible to stop nibbling on warm pieces of this cheesy, oniony bread. The sliced loaf fans out for a fun presentation. It’s one of the best savory appetizers I’ve found. —Kay Daly, Raleigh, North Carolina</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Appetizer/teriyaki meatballs.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Teriyaki Pineapple Meatballs</h5>
                                            <p class="card-text">These teriyaki pineapple meatballs appetizer changed so many times because of my family’s suggestions that it eventually became a main course. I think the homemade sauce sets these meatballs apart. —Evette Nowicki, Oak Harbor, Washington</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Appetizer/fruit and cheese.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Fruit Charcuterie Board</h5>
                                            <p class="card-text">Who says cheese and sausage get to have all the fun? Make this fruit charcuterie board a party go-to with any that are in season. —Taste of Home Test Kitchen</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Appetizer/Hot spinach.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Hot Spinach Artichoke Dip</h5>
                                            <p class="card-text">One taste of this outrageously delicious hot spinach artichoke dip and your guests will not stop eating it until it’s gone. The savory blend of artichokes, spinach and Parmesan cheese is positively addictive! It tastes even better if you make it the night before and chill it in the fridge before baking. —Michelle Krzmarzick, Torrance, California</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Appetizer/Orange-Glazed Meatballs.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Orange-Glazed Meatballs</h5>
                                            <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Appetizer/chicken-parmesan-sliders.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Chicken Parmesan Slider Bake</h5>
                                            <p class="card-text">Sliders are the perfect finger food for any get-together, and this flavorful chicken Parmesan version won’t disappoint. —Nick Iverson, Denver, Colorado</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="tab-pane fade" id="nav-maincourse" role="tabpanel" aria-labelledby="nav-maincoursec" tabindex="0">
                            <div class="row row-cols-1 row-cols-md-3 g-4">
                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Main Course/Spaghetti-Lamb-Bolognese-by-PictureTheRecipe.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Lamb Bolognese With Feta & Mint</h5>
                                            <p class="card-text">A hearty and traditional pasta sauce favorite with a ground lamb makeover. Served with a twist of feta and mint, this is the perfect stick to your ribs comfort dish!</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Main Course/Chicken-Cordon-Bleu-pinterest-2-683x1024.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Skinny Skillet Chicken Cordon Bleu</h5>
                                            <p class="card-text">TThis lightened up version of Cordon Bleu packs all the flavors of the classic dish but cooks in one-pan, takes less than 30 minutes to make and is under 350 calories a serving…but who’s counting right?</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Main Course/Chicken-Masala-Curry-by-PictureTheRecipe.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Indian Style Chicken Masala</h5>
                                            <p class="card-text">Learn how to make a basic Indian aromatic curry paste and turn it into a restaurant-style Indian chicken dish that pairs perfectly with Naan or rice.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Main Course/Sticky-Tamarind-Roasted-Chicken-PictureTheRecipe.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Sticky Tamarind Chicken</h5>
                                            <p class="card-text">Sweet, tangy and spicy…the perfect oven roasted chicken for a quick weeknight dinner!</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Main Course/Almond-crusted-chicken-breast-6-819x1024.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Almond Crusted Chicken With Maple Dijon Sauce (Gluten Free)</h5>
                                            <p class="card-text">A gluten free and healthy chicken dinner that will become weeknight favorite!</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Main Course/PictureTheRecipe-Cuban-Mojo-Roast-Chicken.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Cuban Mojo Roast Chicken</h5>
                                            <p class="card-text">This isn’t your typical roast chicken! With fresh bright flavors of orange, lime, cumin, cilantro and mint this Cuban inspired Mojo Roast is zesty and fresh!</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="tab-pane fade" id="nav-dessert" role="tabpanel" aria-labelledby="nav-dessert" tabindex="0">
                            <div class="row row-cols-1 row-cols-md-3 g-4">
                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Dessert/apple-cherry-strudel-80661-1.jpeg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Apple & cherry strudel</h5>
                                            <p class="card-text">Nothing tops a festive feast like a homemade strudel - try this elegant version with apple and cherries.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Dessert/affogato-16835-1.jpeg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Affogato</h5>
                                            <p class="card-text">For a decadent and soul-warming dessert, look no further than this traditional Italian affogato.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Dessert/snickers-rolls-26145-1.jpeg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Snickers rolls</h5>
                                            <h5 class="card-title">Love Snickers? Make them the star of this decadent treat.</h5>
                                            <p class="card-text"></p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Dessert/maltesers-tiramisu-74785-1.jpeg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Maltesers tiramisu</h5>
                                            <p class="card-text">For a twist on the classic Italian dessert, try our Maltesers tiramisu.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Dessert/chocolate-baubles-5626-1.jpeg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Chocolate baubles</h5>
                                            <p class="card-text">Here is a Christmas decoration that tastes delicious too. Get into the festive spirit with these simple and tasty chocolate baubles.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Dessert/black-forest-trifles-30666-1.jpeg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Black forest trifles</h5>
                                            <p class="card-text">This is a fuss-free version of Germany's famous layered cherry-chocolate dessert.</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="tab-pane fade" id="nav-soup" role="tabpanel" aria-labelledby="nav-soup" tabindex="0">
                            <div class="row row-cols-1 row-cols-md-3 g-4">
                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Soup/butternut-squash-soup.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Butternut Squash Soup</h5>
                                            <p class="card-text">Ginger, rosemary, and sage fill this soup with cozy autumn flavor. Lightly creamy, warming, and nourishing, it’s my go-to recipe for a cool fall night.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Soup/wild-rice-soup-1-806x1024.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Creamy Wild Rice Soup</h5>
                                            <p class="card-text">It might not look like it, but this soup’s base isn’t made with dairy. Instead, it gets its creamy texture from blended white beans, cashews, and savory miso paste.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Soup/cream-of-mushroom-soup.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Cream of Mushroom Soup</h5>
                                            <p class="card-text">Don’t even think about adding this cream of mushroom soup to your next green bean casserole! Brimming with rich, savory flavor, it’s meant to be enjoyed all on its own.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Soup/potato-leek-soup-1.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Potato Leek Soup</h5>
                                            <p class="card-text">If you see a bunch of beautiful fall leeks at the farmers market or store, snatch them up to make this recipe. It’s a lighter version of the classic soup, made with blended white beans instead of heavy cream.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Soup/vegetarian-chili.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Easy Vegetarian Chili</h5>
                                            <p class="card-text">Do we count chili as a soup? I’m on the fence, but I still had to include this recipe here. It’s super quick and easy to make, and on a cold night, its smoky/spicy flavor will warm you up in no time.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Soup/IMG_14144-807x1024.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Yellow Split Pea Soup</h5>
                                            <p class="card-text">Yellow split peas mingle with the fresh corn kernels in this vegan riff on corn chowder, making it extra-hearty and super fun to eat. It’s delicious on its own, but I like it even more with crispy, smoky coconut bacon on top!</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="tab-pane fade" id="nav-drink" role="tabpanel" aria-labelledby="nav-drink" tabindex="0">
                            <div class="row row-cols-1 row-cols-md-3 g-4">
                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Drinks/water.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Water</h5>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Drinks/orange.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Orange Juice</h5>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Drinks/sprite.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Sprite</h5>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Drinks/coca.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Coca Cola</h5>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Drinks/fanta.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Fanta</h5>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="./icons/Drinks/teh.jpg" class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Tea</h5>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- <div class="tab-pane fade" id="nav-others" role="tabpanel" aria-labelledby="nav-others" tabindex="0">
                            <div class="row row-cols-1 row-cols-md-3 g-4">
                                <div class="col">
                                    <div class="card h-100">
                                        <img src="..." class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Others</h5>
                                            <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="..." class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Card title</h5>
                                            <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="..." class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Card title</h5>
                                            <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="..." class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Card title</h5>
                                            <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="..." class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Card title</h5>
                                            <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="col">
                                    <div class="card h-100">
                                        <img src="..." class="card-img-top" alt="Alt-Image" />
                                        <div class="card-body">
                                            <h5 class="card-title">Card title</h5>
                                            <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div> -->

                        <div class="tab-pane fade" id="nav-profile" role="tabpanel" aria-labelledby="nav-profile-tab" tabindex="0">...</div>
                        <div class="tab-pane fade" id="nav-contact" role="tabpanel" aria-labelledby="nav-contact-tab" tabindex="0">...</div>
                        <div class="tab-pane fade" id="nav-disabled" role="tabpanel" aria-labelledby="nav-disabled-tab" tabindex="0">...</div>
                    </div>
                </div>

                <!-- Report Sale -->
                <div class="row border-top border-2 border-danger">
                    <h1>Report Sale</h1>
                </div>
            </div>
        </div>
    </div>
</template>
