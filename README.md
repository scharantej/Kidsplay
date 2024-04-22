## Flask Application Design for a Toy Shopping Website

**HTML Files**

- **index.html (Homepage):**
  - Displays a welcome message and a list of featured products.
  - Provides a search bar and navigation to different product categories.

- **categories.html (Categories):**
  - Displays a list of all product categories available on the website.
  - Allows users to filter products by category.

- **products.html (Products):**
  - Displays a list of products belonging to a specific category.
  - Provides product details, including images, descriptions, and prices.

- **product_details.html (Product Details):**
  - Displays the details of a specific product, including its description, price, and images.
  - Allows users to add the product to their shopping cart.

- **cart.html (Shopping Cart):**
  - Displays the contents of the user's shopping cart.
  - Allows users to remove items from the cart or proceed to checkout.

- **checkout.html (Checkout):**
  - Contains a form where users can enter their shipping and payment information.
  - Redirects to a confirmation page once the order is placed.

**Routes**

- **'/' (Homepage):** Displays the homepage (index.html).

- **'/categories' (Categories):** Displays the categories page (categories.html).

- **'/products/<category_name>' (Products):** Displays the products page (products.html) for a specific category.

- **'/product/<product_id>' (Product Details):** Displays the product details page (product_details.html) for a specific product.

- **'/add_to_cart/<product_id>' (Add to Cart):** Adds a product to the user's shopping cart.

- **'/cart' (Shopping Cart):** Displays the shopping cart page (cart.html).

- **'/remove_from_cart/<product_id>' (Remove from Cart):** Removes a product from the user's shopping cart.

- **'/checkout' (Checkout):** Displays the checkout page (checkout.html).

- **'/place_order' (Place Order):** Receives the checkout form submission and processes the order.