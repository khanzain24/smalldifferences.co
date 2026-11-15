# smalldifferences.co

A wall of NARCISSISMOFSMALLDIFFERENCES with product names hidden in it.

## Files

- `index.html` is the wall. Product names are the `PRODUCTS` list near the top of the script.
- `product.html` is every product page. Each product is one entry in the `P` list: name, price, sizes, Shopify variant IDs, pictures and spec rows.
- `img/` holds the product photos.

## Change the shop address

`product.html` has one line near the top of the script: `var SHOP = "https://sterntao.com";`
Change it if the Shopify store's primary domain changes, or carts will break.

## Add a product

1. Publish it from Printful and set it Active, with Online Store ticked, in Shopify.
2. Get its variant IDs from `https://sterntao.myshopify.com/products.json`.
3. Add its photos to `img/`, an entry to the `P` list in `product.html`, and its name to `PRODUCTS` in `index.html`.
