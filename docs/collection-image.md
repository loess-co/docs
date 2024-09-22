# Collection Image

[![Alt text for the image](https://ticksy_attachments.s3.amazonaws.com/7061512107.png)](https://youtu.be/zUSAtWy3Sp8)
_Video tutorial about collection images_

To add a collection cover image, you must go to your Shopify Admin, and then from the left sidebar go to **Products > Collections.**

From there, you can assign each collection a **Collection image**. The theme will be able to leverage this image in the following instances:

1.  Collection list section (as individual cards)

2.  Collections list page (as individual cards)

3.  Collection page (as a collection header)

One common issue though is that an image that is perfect when used as an individual card (for instance with a portrait aspect ratio) may not provide the desired result when used as a collection header. In the example below, the head of the model is cut off and the cropping is awkward:

![image](https://github.com/user-attachments/assets/88c70a4e-28b9-43ba-8ea8-4c2c06dc8dab)


To overcome this issue, from the Theme Editor, you can **go into each collection and connect its header image to a dynamic source** using metafields. But first, your Collection metafields must be created following these steps:

1.  Open the Shopify admin, and click on **Settings** located at the bottom left corner of the screen.

2.  Open the **Metafields** tab, and click on **Collection.** Then select **Add a definition.**

3.  Name it "Cover image", and select the **File** content type (one file, images & videos). Hit **Save** and close the page (the X at the top right corner of the screen).

4.  Now go to your collections from the Shopify Admin. If you scroll down, you should see a section titled **Metafields** with an image picker labeled **Cover image**.

5.  You guessed it. This is where you can assign a different image for each collection that you will then be able to select using the dynamic source button from the Theme Editor. Like in the example above, you could either use the same image with a different cropping more suited for your desired layout, or just use a completely different image.

\**More info about how to customize the collection header in* [_this article_](https://loess.ticksy.com/article/18632/)_._
