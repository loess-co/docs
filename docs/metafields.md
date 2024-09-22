# Metafields

Loess themes are built to unlock the full potential of metafields. Below is a quick overview for you to have the basic understanding of that feature and to start exploring it in your online store. Metafields are a feature of the Shopify Platform. We recommend that you visit the [Shopify support docs](https://help.shopify.com/en/manual/metafields) if you need complete and detailed information about metafields. Shopify also provides a great [video](https://www.youtube.com/watch?v=M4nCHMLjYCE&t=449s) if you are more of a visual type:

[![Alt text for the image](https://ticksy_attachments.s3.amazonaws.com/3780749011.png)](https://www.youtube.com/watch?v=M4nCHMLjYCE&t=449s)

### Understanding dynamic content

A metafield is what allows your content to be “dynamic”. This means that the content in a section or a block featured in a template can change per page. The most practical example is when you’re adding sections on the product page template, and you need the content in those sections to change based on the product featured on the page. To know if a content (a heading, an image, a product…) can be connected to a metafield, look for this icon from the settings sidebar.

![image](https://github.com/user-attachments/assets/5cc54182-e7da-4bc8-b075-ee00d6cf7484)


There are a few simple steps to follow in order for you to create dynamic content with metafields:

**1- Create a metafield definition**

In the Shopify Admin, select “Settings” at the bottom left of your screen. Then go to the “Metafields” tab (or "Custom data"). If, for example, you want a section on the product page to show dynamic content, you then need to create a “Product definition”. Select “Add definition” and create the metafield using the proper content type. You exit the settings page with the close button on the top right corner of your screen.

**2- Add a value to the metafield**

Once the product metafield definition is created, it will be visible in the Shopify Admin when you edit your products. Select a product and scroll down to the bottom of the page. Your metafield definition should be visible in the “Metafield” section. This is where you attribute the value specific to your products. (Ex: the dimensions of the box in which the product is shipped).

**3- Connect the content to the metafield so it references that value**

Now go to the theme editor and open the product page template. Go to the section or block where you want the dynamic content to be featured. For example the “Collapsible tab” block. You can add a heading that will be the same for all product pages, like “Box dimensions”, but don’t type in the dimensions in the “Tab content” field. This would actually make the content identical for every product using that template because it is data that is sourced by the Theme editor instead of being sourced by the product data from the Shopify Admin. What you do is connect that text field to the value of the metafield, by clicking on the metafield icon.

**Pro tips**

Note that a product using that template for which no value has been attributed to the metafield will display an empty tab. Remember that you can create multiple product templates if you need different sets of sections and blocks per product type.

Using the same 3 steps, you can customize the header of a collection page, for example, with more flexibility by overriding the collection cover image. You would then have to create a metafield that has a “Collection definition”.

### Custom product badges

Metafields are also used to create custom product badges like “New”, “Trendy now”, “Staff pick”, etc…. Learn more about it in the section named Custom product badges section.
