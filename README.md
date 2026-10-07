# Seller Templates

**Free, ready-to-fill templates for people who sell online. Copy one, fill it in, and list faster.**

All examples use a made-up demo brand (Fernmoor). Swap in your own products.

## Contents
1. [Shopify product CSV import template](#1-shopify-product-csv-import-template)
2. [Etsy listing planner](#2-etsy-listing-planner)

More templates for eBay, Vinted and Depop are coming soon.

---

## 1. Shopify product CSV import template

**File:** [shopify-product-import-template.csv](shopify-product-import-template.csv)

One demo product (a t-shirt) with 3 colour variants: Sand, Olive and Charcoal. It uses the current Shopify column names, so you can see exactly how a product with variants is laid out.

### How the rows work
| Row | What goes in it |
|---|---|
| **Row 1** | The header. Do not change these names. |
| **Row 2** | The product + its first variant. Fill in Title, Description, Vendor, Tags, SEO title and SEO description here. |
| **Rows 3 and 4** | One row per extra variant. Repeat the **URL handle**. Leave Title, Description, Vendor and Tags **blank**. Fill in the variant: colour, SKU, price, stock. |

### Key columns
| Column | What to write |
|---|---|
| **Title** | Product name buyers see. |
| **URL handle** | Lowercase, dashes, no spaces. Same on every row of one product. |
| **Description** | Product text. Simple HTML is fine (`<p>`, `<ul>`, `<li>`). |
| **Status** | `draft` (hidden, safe to check first) or `active` (live). |
| **Option1 name / value** | For example `Color` and `Sand`. Name only on the first row. |
| **Price / Cost per item** | Numbers only, with a dot: `29.00`. No currency sign. |
| **Inventory quantity** | Stock number. Works for shops with one location. |
| **Weight value (grams)** | Weight in grams, used for shipping rates. |
| **Product image URL** | A public image link that opens in a browser. Leave blank and add photos later if you do not have links. |
| **SEO title** | Aim for about 60 characters or less. |
| **SEO description** | Aim for about 155 characters or less. |

You can leave out columns you do not need. Only **Title** is required for a new product.

### Import it in 5 steps
1. **Open** the file in Google Sheets (File > Import) or Excel.
2. **Replace** the demo rows with your product. Keep one row per variant and the same URL handle on each.
3. **Save** as CSV with UTF-8 encoding (Google Sheets: File > Download > CSV). The file must be under 15 MB.
4. **Import** in Shopify: Products > Import > Add file > choose your CSV > Upload and continue.
5. **Check** the preview, press Import products, then open the product and check variants, prices and stock before you set it to active.

### Common mistakes
- **Sorting the sheet.** Rows of one product get split up and images can be lost. Do not sort.
- **Different handles on variant rows.** Shopify then makes separate products instead of variants.
- **Image links that do not open.** The import skips them or fails. Test each link in a browser first.
- **Commas or currency signs in prices.** Write `29.00`, not `29,00` or `$29`.
- **Saving in the wrong encoding.** Odd symbols in the text usually mean the file was not UTF-8.

---

## 2. Etsy listing planner

**File:** [etsy-listing-planner.csv](etsy-listing-planner.csv)

Plan a full Etsy listing in one sheet before you open Etsy: title, 13 tags, core details, category, attributes, materials, description start, photos, price and shipping. One row per field, with the limit, a tip and a filled demo example (a handmade mug from the made-up shop Fernmoor).

### How to use it
1. **Open** the file in Google Sheets (File > Import) or Excel.
2. **Write** your text in the **Your text** column. The **Characters used** column counts it for you.
3. **Check** every count is inside the **Limit** column.
4. **Copy** each field into your Etsy listing.

### The rules that matter most
| Field | Limit | Rule |
|---|---|---|
| **Title** | 140 characters | Put the main words first: what it is, then key details. Keep it short and easy to read. `%`, `:`, `&` and `+` can each be used only once. |
| **Tags** | 13 tags, 20 characters each | Use all 13. Use phrases buyers type ("ceramic coffee mug"), not single words. No repeats. |
| **Category** | Pick from list | Pick the most exact one. It decides which attributes you can fill in. |
| **Attributes** | Change by category | Colour, size, occasion and more. They work like extra search words, so fill in every one that fits and do not waste tags on them. |
| **Materials** | Letters, numbers, spaces | Say what it is made of. |
| **Description** | First lines show first | Start with what it is, who it is for and the key facts. Size, care and shipping come after. |
| **Photos** | Main photo first | Your first photo is the thumbnail in search. Show the item clearly. |

### Common mistakes
- **Stuffing the title.** A long list of keywords is hard to read. Buyers skip it.
- **Tags that are almost the same.** "mug", "mugs" and "the mug" use up three tags for one search. Mix what it is, who it is for, the style and the occasion.
- **Leaving attributes empty.** Empty attributes mean fewer ways to be found in filters.
- **Wrong "When was it made?"** If you make it after the order comes in, pick made to order.
- **Promising a processing time you cannot keep.** Late orders hurt your shop.

---

Want this done for your shop or deck? I do it as a fixed-price project on Upwork: [Hire me on Upwork](https://www.upwork.com/freelancers/~01c18d191d6a95988c)

Built by **Tuli, Satin & Scale**.
