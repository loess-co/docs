# Linkable Variant

The linkable variant block is available in the product page. This advanced feature is applicable when color swatches are displayed. It will load a different product page when the user clicks on a color swatch from a product page.

## This feature is useful when:

- your store displays color swatches

- you have a big catalog with color variants that are set up as **individual products**.

## 1- Set up your color swatch 

Make sure you follow the steps for setting up the color swatches, as explained in [this article](https://loess.ticksy.com/article/19047/).

## 2- Set up the 1st product metafield.

Click on **Settings**, on the bottom left corner of the screen in your admin, and open the **Metafields** tab. Create a product metafield that you can name, for example, "Color". Just make sure the namespace and key is  **custom.color_value** and that you set its content type to **Single line text**, **One value**.

\*Note: The namespace **custom.color_value** must be written exactly as is, otherwise the feature won't work. This text won't be visible to your customers, so there's no need to use translation if your store is in another language than english.

## 3- Set up your 2nd product metafield

Create a second product metafield that you can name, for example, "Color variant". Select **Product** as the content type, and **List of products**.

## 4- Edit your product information properly

Once your 2 product metafields are set up, you should see them at the bottom of your product pages in the Shopify admin:

![image](https://github.com/user-attachments/assets/7c87b16f-a2bb-4a90-bd85-b05bca42822a)


1.  In the color metafield, enter the name of **the color swatch related to that specific product** page.

2.  In the color variant metafield, select **all the products that qualify as a color variant of that product**.

3.  Repeat this operation for each product that is related to the group

Here's an example of the proper set up:

![image](https://github.com/user-attachments/assets/3cbf7a7b-135d-4e67-926a-7e055b1ba872)


## 5- Customize your store's product page

Finally, go to the Theme Editor and edit the Product page. In the left sidebar, find the Product information. Click **Add block**, and select **Linkable variant**. In the block's settings, connect the products to a dynamic source and select the "Color variants" metafield that you previously created.

![image](https://github.com/user-attachments/assets/069861ef-645b-4ab2-b936-2df4a4e1e5a5)


### Important notes

- If the color variants of products from the same group are not selected in the same order, the color swatches displayed in a product page will shift position between pages as the user clicks on them. Improve the user experience by maintaining the same order.

- If your products have other variants than just colors, know that using this method resets the user's variant selection when they click on a color swatch because a new product page is loaded each time. For example, if the user selects a **Size** option first and a color next, the size will reset to the default. One way to improve the experience is to put the linkable variant block below the variant picker in the product page layout.
