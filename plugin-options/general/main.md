# Main

The **Main** section includes the major plugin settings, such as displaying the Add to cart button and Notifications, Off-canvas settings, and others.

![](../../.gitbook/assets/main_page.png)

## &#x20; Slide-in Off-Canvas Cart Page

![](<../../.gitbook/assets/Screen Shot 2021-03-18 at 23.59.27.png>)

This option allows opening the side cart when adding the product to the cart.

**Enabled Slide-in Off-Canvas Cart Page:**

![](../../.gitbook/assets/Products.gif)

## Ajax add to Cart

![](<../../.gitbook/assets/Screen Shot 2021-03-18 at 23.59.38.png>)

By enabling this option, the item will be added to the cart without refreshing the page.

{% hint style="info" %}
**AJAX add to cart buttons on archives** option in WooCommerce Settings should be enabled for this option to work properly.
{% endhint %}

![](<../../.gitbook/assets/WooCommerce sett.png>)

**Enabled Ajax add to Cart:**

![](<../../.gitbook/assets/Basic Gray Jeans.gif>)

## Ajax remove from Cart

![](<../../.gitbook/assets/Screen Shot 2021-03-18 at 23.59.46.png>)

This option allows removing items from the cart without refreshing the page.

**Enabled Ajax remove from Cart:**

![](<../../.gitbook/assets/Products (1).gif>)

## Add to cart button

![](<../../.gitbook/assets/Screen Shot 2021-03-18 at 23.59.53.png>)

If the theme does not provide a button for adding a product to the cart on the main page of the store, after enabling this option, the plugin will add the **Add to cart** buttons on the store page:

![If option is disabled](<../../.gitbook/assets/image (111).png>)

![If option is enabled](<../../.gitbook/assets/image (110).png>)

## Fly to cart animation

![](../../.gitbook/assets/11684933-e9b92168681974c04aae64e54a2044ec.png)

When this option is enabled, the **Fly to cart** animation effect activates by adding an item to the cart.

{% hint style="info" %}
[Ajax add to Cart](main.md#ajax-add-to-cart) option should be enabled for this option to work.
{% endhint %}

![](<../../.gitbook/assets/Products (2).gif>)

## Show Related products slider

![](../../.gitbook/assets/11703087-60bb0df7d2e71d0ed4e61ffbccbb52b4.png)

This option allows showing related products to your chosen item. Related items will be displayed as sliders in the cart off-canvas.

{% hint style="info" %}
Related products will not be displayed if there is only one product in the store and you add it to the cart.
{% endhint %}

![](<../../.gitbook/assets/Products (1).png>)

## Apply coupons in Side cart

When this option is enabled, you will be able to add different promotion coupons to the items.

![](<../../.gitbook/assets/image - 2021-08-08T205413.986.png>)

After enabling this option, you can create the coupons in **Marketing > Coupons**.

![](<../../.gitbook/assets/image - 2021-08-08T205937.654.png>)

On the opened page, fill in all the required fields and click **Publish** button.

{% hint style="info" %}
You can get detailed information about the coupon creation process on the [Coupon Management page](https://docs.woocommerce.com/document/coupon-management/) of WooCommerce documentation.
{% endhint %}

![](../../.gitbook/assets/11703864-cbc675cce691eecf92fc1bda20b9a916.png)

The created promo code appears in the Coupons section.

![](<../../.gitbook/assets/Coupons ‹ — .png>)

The coupon will be applied to the selected items.

![](../../.gitbook/assets/Products.png)

## Show shipping methods in Side cart payout

![](../../.gitbook/assets/11725195-657ae5dec274889f50eb4f9a195e7845.png)

By enabling this option, the users can order delivery for their products by specifying the address of their location.

![](<../../.gitbook/assets/Products (2).png>)

By default, the shipping is free of charge, but you can change the shipping price and shipping zones in the WooCommerce settings.

{% hint style="info" %}
You can get detailed information about the shipping settings on the [Setting up Shipping Zones](https://docs.woocommerce.com/document/setting-up-shipping-zones/) page of WooCommerce documentation.
{% endhint %}

## Basket status

This setting will define whether to show the basket icon on the web page.

![](<../../.gitbook/assets/image (92).png>)

{% tabs %}
{% tab title="Always show" %}
If **Always show** option is selected, the basket icon will be visible on the entire website.

![](<../../.gitbook/assets/image (53).png>)
{% endtab %}

{% tab title="Always hide" %}
If **Always hide** option is selected, the basket icon will be hidden on the entire website.

{% hint style="info" %}
Side Cart automatically opens if the user adds a product to the cart.
{% endhint %}

![](<../../.gitbook/assets/image (85).png>)
{% endtab %}

{% tab title="Hide when cart is empty" %}
If **Hide when cart is empty** option is selected, the basket icon will be visible on the entire website when at least 1 product is in the cart.&#x20;

![](<../../.gitbook/assets/image (8).png>)
{% endtab %}
{% endtabs %}

## Basket counter status

This setting will define whether to display the counter under the basket icon on the web page.

{% tabs %}
{% tab title="Always show" %}
If **Always show** option is selected, the basket icon counter will be visible on the entire website.

{% hint style="info" %}
If the **Basket status** option is set to **Always hide**, the counter will be not visible.
{% endhint %}

![](<../../.gitbook/assets/image (11).png>)
{% endtab %}

{% tab title="Always hide" %}
If **Always hide** option is selected, the basket icon counter will be hidden on the entire website.

![](<../../.gitbook/assets/image (94).png>)
{% endtab %}

{% tab title="Hide when cart is empty" %}
If **Hide when cart is empty** option is selected, the side cart icon counter will be visible on the entire website when at least 1 product is in the cart.

{% hint style="info" %}
If the **Basket status** option is set to **Always hide**, the counter will be not visible.
{% endhint %}

![](<../../.gitbook/assets/image (5).png>)
{% endtab %}
{% endtabs %}

## Cart icon Counter

This setting determines whether to count only unique items in the cart or all selected items.

![](<../../.gitbook/assets/image (17).png>)

{% tabs %}
{% tab title="Total Unique products in a Cart" %}
If **Total Unique products in a Cart** option is selected, the side cart icon counter showing unique items count in the cart.

![](<../../.gitbook/assets/image (4).png>)
{% endtab %}

{% tab title="Total items in a Cart" %}
If **Total items in a Cart** option is selected, the side cart icon counter shows all items count in the cart.

![](<../../.gitbook/assets/image (145).png>)
{% endtab %}
{% endtabs %}

## Disable Cart on Selected Pages

![](<../../.gitbook/assets/image (27).png>)

This setting disables displaying the side cart icon on the selected pages. Page slugs should be written in the field, separated by commas.

{% hint style="info" %}
Side Cart will be automatically opened if the user adds a product to the cart.
{% endhint %}
