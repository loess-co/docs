# Product Page

To customize the product page in the Theme Editor, navigate to that template or use the dropdown in the middle of the top bar.

The Product page comes with a lot of features and blocks. You can access the blocks from the sidebar under “Product information”. They’re designed to serve specific purposes, and can be reordered from the left sidebar, or customized using their block settings. Note that the “Product information” element in the sidebar also has its own settings to customize the main layout of the page.

**Pro tip**

Remember that when you customize a product page, you are actually customizing a **template**. This means that the information that is not determined by the product data from the Shopify admin (like when you add a section) will be the same across all product pages. You can avoid that and make the content dynamic based on the product featured on the page that uses that template. This is done by connecting the content to product [metafields](https://loess.ticksy.com/article/18634). It is also possible to create multiple [templates](https://loess.ticksy.com/article/18633/) with different sets of sections.

## Blocks overview

**Title, Price, Description, and Variant picker**

The information in those blocks is determined by the product data in the Shopify Admin. It’s in the “Variant picker” settings that you can define whether you want variants to be laid out as buttons, or as a dropdown. It is also from there that you can enable color swatches.

**Text**

This is probably the most useful block. You can, for example, connect it to a metafield to dynamically display the vendor for each product. Remember that the product description comes rather from the “Description block”, and its content is determined by the product data in the Shopify Admin.

**Image**

This block can be useful to include one or more images as blocks near the product description. Trust badges are a common use case. No need for an app!

**Related products / Complementary products**

If you are using a version of Upscale that is older than 2.0.0, follow those guidelines to showcase one or more products in the product details:

In the theme editor, add the Related product block. To connect the featured product(s) to a dynamic source using metafields, you must create a **Product metafield**, set up with a **Product content type**. Make sure to choose **List of products** (instead of One product), otherwise it will not work. Once this is done, at the bottom of every product page in the Shopify admin, you should find the metafield form field that you create where you can connect the desired featured products. Learn more about metafields in [this article](https://loess.ticksy.com/article/18634/).

If you are using Champion or a version of Upscale that is 2.0.0 or newer, follow those guidelines to showcase one or more products in the product details:

Install the **Search & Discovery** free app, and go to the **Recommendations** tab. Select products, and assign them Complementary products. Then, in the Theme Editor, add the Complementary products block to your product page.

**Collapsible tab**

This block is a great way to display more information about your products without bloating the page. Especially useful for the mobile experience. You can stack this block multiple times to create an accordion menu.

**Labels and icons**

That block leverages the icon library that’s built-in in the theme. It’s a great way to draw attention on product specifications customers are usually looking for. For example, you could include the truck icon and connect the label to a product metafield so that each product can show its own shipping information. Another great example is the ruler icon that could have the label “size chart”. The settings allow you to then add a link to a page that features the proper size chart, which can be opened as a popup.

**Stock availability**

Yes, the theme does have this built-in widget! It’s easy to use. Define the low inventory threshold and customize the messages and icons. The three icons are the following: In stock (green check mark), Low inventory (yellow question mark), Back order (red question mark).

**Line item property**

This block allows you to get some extra information from the customer when they purchase their product. For instance, you could display a check box for the customer to specify whether they want their product to be gift wrapped before they add to cart.

**Share**

This block displays a “Share” button so your customers can share the product page on their preferred social media.

**Custom liquid**

That section is there to give more freedom to advanced users with the Shopify platform, and to position the content as a reorderable block on the page.

**Product rating & reviews**

Star ratings and product reviews are not default features in themes. But the good news is that it’s easy to install the feature *as an app*… and Shopify provides one for free! All you need to do is go to the Shopify app store and install the [Product Reviews app](https://apps.shopify.com/product-reviews?surface_detail=product+reviews&surface_inter_position=1&surface_intra_position=12&surface_type=search). Once done, you can go to the Theme Editor and customize the product page. In the settings sidebar on the left, select “Add section”. You should see the “Reviews” app block at the bottom. You may also want to display the star rating near the product title or price. Add the “Star rating” block, under “Product information”, and drag it to change its position on the page. Customize the layout and features of the reviews from the settings attached to each block, and from your Shopify Admin, under the “App” tab. [Learn more](https://help.shopify.com/en/manual/products/product-reviews).
