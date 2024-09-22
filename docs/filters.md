# Filters

Loess themes are built with an optimized filtering user experience. Below is a quick overview for you to have the basic understanding of that feature and to start exploring it in your online store. Filters are a feature of the Shopify Platform. We recommend that you visit the [Shopify support docs](https://help.shopify.com/en/manual/online-store/search-and-discovery/filters) if you need complete and detailed information about filters.

#### Customizing filters

**1- Create your filters in the Admin**

From the Shopify Admin, open the **Navigation** tab under **Online store**. From there, you will be able to use the **Shopify Search & Discovery** app to manage your filters:

![image](https://github.com/user-attachments/assets/9d355082-82c5-4b9f-aa19-73d351462677)


**2- Enable the filters in your store**

Once you created your filters, you need to open the Theme Editor and enable the filters on your online store. To do so, go to the collection page, and edit the **Collection grid** settings. From there, you will be able to toggle *on* the **Enable filtering** setting.

#### Quick tips

You may have specific needs regarding your filters. For example, you may need your customers to use filters that do not correspond to product variants (product options), and need to have them organized into different categories. If this is the case, you can use product metafields instead (more info in the [metafield article](https://loess.ticksy.com/article/18634/)). Once you edit your filters with the **Search & Discovery** app to include the product metafields, each product metafield will output a **filter category** in the sidebar of your store. And then each value that has been created for those metafields will become a selectable **filter** within the categories. Please remember that filters within a category can be combined as an "or" (example: red **OR** green), but filters across categories as combined as an "and" (example "red" **AND** shirt). If you wish to make a category of filters that allow only one check box to be selected, the Shopify platform doesn't work that way, and this is not a feature themes can provide. Depending on your needs, a workaround may be to use separate collections for those, instead of relying on filters.

![image](https://github.com/user-attachments/assets/0d9b8648-51e9-426b-94a2-d0fcb01769df)


#### Color swatches

If your filters include colors and you want those colors to be displayed as swatches instead of just labels and checkboxes, you need to go to the **Theme Settings** and open the **Color swatches** tab. In the **Configuration** input field, you need to type in the color *hex* code for each existing color filter (Hex codes are a 6 digits number, as per the screen shot below). There are plenty of online tool (such as [this page](https://htmlcolorcodes.com/color-picker/)) for you to find color hex codes you can copy and paste. The important thing to remember for this to work is to avoid typos and to follow the right syntax in the Theme Editor. For example:

**Black:#000000<br>Night blue:#000080**

![image](https://github.com/user-attachments/assets/14b93727-d607-420d-a314-53025a365932)


#### Replacing color swatches with images

It can be useful to replace a color swatch by an image instead. This feature allows you to showcase patterns and textures instead of plain colors. Follow these steps:

1- Create a small image and give it a name (ex: **blue-stripes.jpg**)

2- Go to the Shopify admin, go to the **Content** tab (left side of the screen), and open the **Files** tab.

3- Upload your image

4- Now open the Theme Editor and go to the **Theme Settings**. Open the **Color swatches** tab. In the Configuration input field, you need to type in the exact name of the filter, add a colon, and add the name of your image (without spaces). Make sure to include the image file extension. For example:

**Blue stripes:blue-stripes.jpg**

\_\_\_

## \* Attention \*

**If your store is translated in multiple languages**, make sure you don't translate the content where your color swatches are named and associated to a hex code. For example, if you're using the Translate and Adapt app provided by Shopify, you might translate this content by mistake if you hit the "Auto-translate" button. This would create a conflict and your color swatches won't be outputted properly. You can easily fix this by going to the **General** tab under **Theme assets** and remove the translation in the **General: Color Swatch Configuration field**:

![image](https://github.com/user-attachments/assets/44f00747-a124-4e7d-92bc-044258b458fe)


## Color swatches in the product variant selector

You can also showcase the color swatches as variant selectors instead of color names in a product page. In order to do that, click the **Variant picker** block in the product section. Inside the block, select **Swatch** from the "Color" option type setting.

> Keep in mind that you’ll need to update this setting for any product section that is added to the page, like for the Featured product section or Quick View popup.
>
> ![image](https://github.com/user-attachments/assets/8ad2ad5f-036d-4757-a4db-75b15e2c901c)


#### Filter sidebar

On a large screen, the filters in collection and search result pages are displayed in a sidebar. To provide the best user experience to your customers, that sidebar has many functionality options. For example, if your store has a lot of categories that each contain a large number of filters, collapsing tabs may prevent long scrolling. This would also improve discoverability because the categories at the bottom of the sidebar could otherwise be hidden outside the viewport by default. On the other hand, a store with fewer filters and categories might benefit from having all the filters exposed by default. With the theme, this is a decision you are free to make, using the ‘Sidebar functionality on large screen’ setting located both in the Collection template and the Search template. To customize those templates in the Theme Editor, navigate to them or use the dropdown in the middle of the top bar (Search is located under “Others”).

\*Note that if a category has more than 15 filters, it will truncate after the 10th filter to shorten the scroll length. A ‘+ More’ link below the 10th filter will allow the customers to view them all.

### Automatic formatting

The ‘Auto formatting’ option is a great feature. When enabled, the theme will optimize the sidebar dynamically based on the number of filters and tabs. The layout will adapt according to the following algorithm:

1.  If the number of filter categories is greater than 5, the first tab is expanded by default and the other tabs are collapsed.

2.  If the number of filter categories is 5 or less, the tabs are expanded and non collapsible.

#### Enabling the color swatches in your store

Color swatches are supported in the following components of the theme:

- Collection filters

- Featured collection section

- Featured product

- Product page

- Product recommendations

- Quick view popup

For each of those sections and pages, you must enable the color swatches by going into their corresponding settings. Note that the Quick View popup is customizable by using the dropdown in the middle of the top bar in the Theme Editor. **Go to Products > quick-view**
