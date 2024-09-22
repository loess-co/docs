# Color Swatches

[![Alt text for the image](https://ticksy_attachments.s3.amazonaws.com/9447151937.png)](https://youtu.be/Dl3q8qnaLD8)
_Video tutorial about setting up color swatches on your store_

If your filters include colors and you want those colors to be displayed as swatches instead of just labels and checkboxes, you need to go to the **Theme Settings** and open the **Color swatches** tab. In the **Configuration** input field, you need to type in the color *hex* code for each existing color filter (Hex codes are a 6 digits number, as per the screen shot below). There are plenty of online tool (such as [this page](https://htmlcolorcodes.com/color-picker/)) for you to find color hex codes you can copy and paste. The important thing to remember for this to work is to avoid typos and to follow the right syntax in the Theme Editor. For example:

**Black:#000000<br>Night blue:#000080**
![image](https://github.com/user-attachments/assets/deb003b1-e9e1-4ce4-a593-30ee32d1e9be)


Please note that the theme relies on a variant that is specifically the one from the Shopify options that is called **Color**. Because of that, it can't support multiple color swatch groups (for example: eyeglasses for which customers can choose a lens color and a frame color). This ensures that the swatches displayed in filters and product cards are accurate and consistent across the board. I your products are composed of different components that each come in multiple colors, you would have to choose 1 dominant color for leveraging the swatches, and then the other color options would be displayed either as buttons, or options in a dropdown menu.

![image](https://github.com/user-attachments/assets/51a28fd4-d56c-4aa7-ac2a-e9118f33c967)


#### Replacing color swatches with images

It can be useful to replace a color swatch by an image instead. This feature allows you to showcase patterns and textures instead of plain colors. Follow these steps:

1- Create a small image and give it a name (ex: blue-stripes.jpg)

2- Go to the Shopify admin, go to the **Content tab** (left side of the screen), and open the **Files** tab

3- Upload your image

4- Now open the Theme Editor and go to the **Theme Settings**. Open the **Color swatches** tab. In the **Configuration** input field, you need to type in the exact name of the filter, add a colon, and add the name of your image (without spaces). Make sure to include the image file extension. For example:

**Blue stripes:blue-stripes.jpg**

\_\_\_

## \* Attention \*

For color swatches to appear in product cards, each variant must be associated to a product image.

![image](https://github.com/user-attachments/assets/a8406891-5605-49f9-919c-0a7acd168163)


## \* Attention \*

**If your store is translated in multiple languages**, make sure you don't translate the content where your color swatches are named and associated to a hex code. For example, if you're using the **Translate and Adapt** app provided by Shopify, you might translate this content by mistake if you hit the "Auto-translate" button. This would create a conflict and your color swatches won't be outputted properly. You can easily fix this by going to the **General** tab under **Theme assets** and remove the translation in the **General: Color Swatch Configuration** field:

![image](https://github.com/user-attachments/assets/d59a7d05-d49a-4276-8aff-0fde84857e7b)
