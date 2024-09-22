# Product Size Chart

Adding a size chart to a product page is a common need. Size charts may vary depending on the product, and can go from very simple (few lines of text), to very complex (long tables, visual references, etc.). There are a few ways you can include size charts on your store, and you should choose the way that works best for your own needs. That said, here are two basic examples with *Upscale* that don’t require you to install an app, and that may work for you.

**Pro tip**

Remember that when you customize a product page, you are actually customizing a **template**. This means that the information that is not determined by the product data from the Shopify admin (like the added blocks) will be the same across all products using that template. You can avoid that and make the content dynamic based on the product featured on the page. This is done by connecting the content to product [metafields](https://loess.ticksy.com/article/18634). It is also possible to create multiple [templates](https://loess.ticksy.com/article/18633/) with different sets of sections.

### 1- Page in a popup

With this technique, you will first create a page that contains a size chart. It will then be referenced in a popup from the relevant product page.

In the Shopify Admin, go to **Pages**, under **Online Store**. Select **Add page** and use the text editor to build your size chart. Note that you can insert a table. Then go to the Theme Editor, navigate to the relevant product template or use the dropdown in the middle of the top bar. Once there, from the left sidebar, add the **Labels and icons** block. You can customize that block from its setting sidebar which may be located on the right side of your screen if you're using a large display. Add an icon (for example a ruler, shirt, shoe…), and/or a label. Create a link by selecting your size chart page, under **Pages**. You can define the link behaviour and select **Popup**.

![image](https://github.com/user-attachments/assets/9ad3fdd1-4500-4021-8d77-258edfa4f151)


If you have different products that require different size charts, you can create multiple size chart pages in your Shopify Admin. But you will then have to connect the popup link to a metafield. For that, you will need to have previously created a **Product metafield** definition with a **Page** content type (One page). Note that if a product is featured in a template using a dynamic source (metafield), and that dynamic source has no property, that product page will display the size chart button but without any link. [Learn more about metafields](https://loess.ticksy.com/article/18634/).

![image](https://github.com/user-attachments/assets/c269351b-ae35-4fca-a45b-16c6ca1dcd81)


### 2- Content in a collapsible tab

From the Theme Editor, navigate to the relevant product template or use the dropdown in the middle of the top bar. Once there, from the left sidebar, add the **Collapsible Tab** block. You can customize that block from its setting sidebar which may be located on the right side of your screen if you're using a large display. Add a heading and create your size chart using the text field. You can also reference a page instead, but it’s recommended to not use long text inside a collapsible tab for better usability. Pages can be created in your Shopify Admin. Either way, both content sources can be connected to a metafield if you have different products that require different size charts.

![image](https://github.com/user-attachments/assets/b4a159af-18dc-4e18-8187-abde14a5de9e)

