# Custom Product Badges

Loess themes allow you to create custom product badges like “New”, “Trendy now”, “Staff pick”, etc…. You do so by using [metafields](https://loess.ticksy.com/article/18634/).

**1- Create a metafield definition**

In the Shopify Admin, select **Settings** at the bottom left of your screen. Go to the **Custom data** tab, and then create a **Product** definition. Select “Add definition” at the top right of the page and create the metafield using the “Single line text” content type. The name of that metafield must be “**Custom badge**”. Make sure to select **One value**, and **Single line text**. the Namespace and key is *custom.custom_badge.* Close the page (the X at the top right).

**2- Add a value to the metafield**

Once the product metafield definition is created, it will be visible in the Shopify Admin when you edit your products. Select a product and scroll down to “Metafields” at the bottom of the page. Your metafield definition should be visible in the “Metafield” section. This is where you attribute the value specific to your product or variant. (Ex: Staff pick). It’s recommended to keep the label short.

**3- Customize the design of the badge**

The theme will detect when custom badges are created and will display them on the store when applicable. As long as the metafield name is “Custom badge” and the Namespace and key is unchanged. To customize the color and style of the badge, open the Theme Editor, and go to the “Theme Settings” tab on the left. Open the “Product” tab and change the relevant settings under “Product badges”. These settings may be located on the right side of your screen if you're using a large display.

![image](https://github.com/user-attachments/assets/f02267e2-e58f-4352-b661-c566fabf22a5)
