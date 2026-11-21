# Shopify content applied (21 Nov 2026)

- `publish/` holds the exact HTML pushed to Shopify (product description, collection intro, collection guide metafield `custom.seo_guide`).
- `backup/product-live-before.html` is the product description as it was before the update. The collection description and SEO fields were empty before.
- Collection uses template `collection.kids`; the guide renders via section `collection-seo-guide` (theme change, needs publishing).
