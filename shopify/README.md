# Sniperform Shopify Import

This folder contains a Shopify OS 2.0 product-template slice for the Sniperform LevelUp product page rebuild.

## Files

- `sections/sniperform-levelup-product.liquid`
- `templates/product.sniperform-levelup.json`

## How to use

1. Copy `sections/sniperform-levelup-product.liquid` into your Shopify theme `sections/` directory.
2. Copy `templates/product.sniperform-levelup.json` into your Shopify theme `templates/` directory.
3. In Shopify admin, assign the `product.sniperform-levelup` template to the `LevelUp Performance Grips` product.

## Notes

- The template is designed to live inside the existing Shopify header/footer/navigation.
- Product title, price, variant, and add-to-cart actions come from the Shopify `product` object.
- Some supporting visuals and proof clips still point at the existing Sniperform CDN assets so the section can work immediately on the current store.
- If you upload new imagery to Shopify, replace the hardcoded media URLs in the section with your preferred theme settings or product metafields.
