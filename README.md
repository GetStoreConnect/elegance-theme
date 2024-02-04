# Elegance Theme

The StoreConnect Elegance Theme is a multi-purpose theme and clean theme ideal for cosmetic, clothing, or fashion industries. 

This versatile design can be easily repurposed or readjusted to suit any store, offering a sophisticated and clean layout. It is specifically tailored to emphasize upsell products, encouraging customers to seamlessly navigate through your offerings. 


## Directory Structure

This theme has a specific folder structure containing new and customised templates.

Also, it has been developed using the [Base Theme](https://github.com/GetStoreConnect/base-theme) as a boilerplate. The Elegance theme doesn't contain all the base theme structure, we only include those customised, modified and new templates, snippets, variables or translations. Feel free to create a brand new theme using the base theme or extending the templates and functionalities on this theme.

## Theme Installer

The theme installer is in your Salesforce org, where you must upload this theme as a zip file.

## Features

- New card carousels for featured categories, products, or filtered products
- New cart sidebar containing 'continue' and 'view cart' action buttons
- Cart modal on product page, it displays upsell products related the current product just added to cart
- Expandable search bar
- Cart page upsell products (you can now manually set what's you upsell category on the cart page section)
- Image swapper on product cards if your product contain more than 1 image
- Image zoom in effect on product card images

### New Content Blocks

- Image slider

### Modified Content Blocks

- featured_categories
- featured_products
- image_text_overlay

## How to Add Content Blocks to Picklist

You can follow the instructions in this document to [add content blocks to the picklist](https://help.getstoreconnect.com/documentation/adding-templates-to-content-template-picklist.html).

## Configuration

The first step is to download this repository as a `zip` folder and then upload it to your StoreConnect app via the theme importer located in the StoreConnect CMS.

### Troubleshooter

If you got an error while importing your theme you should "unzip" your folder and follow these instructions:

- Ensure that your root directory does not contain any `.git` hidden folders or files
- Compress it to a zip file
- Upload it via the theme importer


### Recommended Help Articles

- StoreConnect [Theme Builder Reference](https://help.getstoreconnect.com/documentation/themes/theme-reference.html)
- StoreConnect [Liquid Reference](https://help.getstoreconnect.com/documentation/liquid/liquid-reference.html)
