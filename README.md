# Seller Templates

**Free, ready-to-fill templates for people who sell online. Copy one, fill it in, and list faster.**

All examples use a made-up demo brand (Fernmoor). Swap in your own products.

## Contents
1. [Shopify product CSV import template](#1-shopify-product-csv-import-template)
2. [Etsy listing planner](#2-etsy-listing-planner)
3. [eBay item specifics checklist for clothing](#3-ebay-item-specifics-checklist-for-clothing)
4. [Vinted and Depop listing checklist](#4-vinted-and-depop-listing-checklist)

More templates are coming soon: a resale photo checklist and an AEO FAQ block for product pages.

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

## 3. eBay item specifics checklist for clothing

**File:** [ebay-clothing-item-specifics.csv](ebay-clothing-item-specifics.csv)

On eBay, buyers narrow clothing search with filters like **Size**, **Brand**, **Colour** and **Department**. Those filters read your **item specifics**. If a field is empty, your item can drop out when a buyer uses that filter. This checklist covers every field a clothing listing needs, with a filled demo (a linen shirt from the made-up brand Fernmoor).

### How to use it
1. **Open** the file in Google Sheets (File > Import) or Excel.
2. **Fill in** the **Your value** column with the garment in your hand: label first, then the tape measure.
3. **Mark** each row **Y** in the **Done** column.
4. **Copy** the values into the eBay listing form. eBay shows which fields are required for your category, so check those first.

### The fields that matter most
| Field | What to write |
|---|---|
| **Title (80 characters)** | Brand, department, item type, size, colour, material, then 1 or 2 style words. Check the length with the free [title checker](https://legacyroar7-maker.github.io/shop-tools/). |
| **Condition** | Pick the closest option, then name every flaw in the condition description. |
| **Brand** | Exactly as on the label. Use Unbranded if there is none. |
| **Department** | Women, Men, Unisex Adults, Girls, Boys. |
| **Size + Size Type** | The size on the label, plus Regular, Petite, Plus or Tall. |
| **Colour** | The main colour buyers would call it. |
| **Material** | Main fabric from the care label. |
| **Measurements** | Flat measurements in cm and inches. Sizes differ between brands, so buyers trust numbers more than labels. |

### Quick checklist before you list
- [ ] Title is 80 characters or less and starts with brand and item type
- [ ] Condition picked and every flaw written down
- [ ] Brand, Department, Size, Size Type, Colour filled in
- [ ] Style, Material, Fit, Sleeve Length, Pattern filled in where they fit
- [ ] Measurements added (tops: pit to pit, length, sleeve; bottoms: waist, inseam, rise)
- [ ] Photos: front, back, label, care label, fabric close-up, flaws, tape measure

### Common mistakes
- **Size only in the title.** The Size filter reads the item specific, not the title. Fill in both.
- **Writing "see photos" for flaws.** Buyers want flaws in words too. It also helps if there is a return dispute.
- **Guessing the material.** Copy it from the care label. If the label is gone, say so.
- **Measuring with the garment on a hanger or a person.** Lay it flat on a table and smooth it out first.
- **Using "Vintage" for anything old-looking.** Only use it when the item is truly old.

---

## 4. Vinted and Depop listing checklist

**File:** [vinted-depop-listing-checklist.csv](vinted-depop-listing-checklist.csv)

On Vinted and Depop, most buyers do not scroll the whole app. They pick a **category**, then filter by **size**, **brand**, **condition**, **colour** and **price**. If a field is empty or wrong, your item can drop out of those results. This checklist covers photos, text, the fields buyers filter by, pricing and shipping, with a filled demo (a wool cardigan from the made-up brand Fernmoor).

### How to use it
1. **Open** the file in Google Sheets (File > Import) or Excel.
2. **Look** at the **App** column. Rows marked **Both** are for Vinted and Depop. The rest are for one app only.
3. **Fill in** the **Your value** column with the item in your hand: labels first, then the tape measure.
4. **Mark** each row **Y** in the **Done** column, then copy the values into the app.

### Photos: the 8 shots
| # | Shot | Why |
|---|---|---|
| 1 | **Whole item, front** | This is the photo buyers see in the feed. |
| 2 | **Back** | Buyers want to see both sides. |
| 3 | **Brand label** | Shows the brand is real. |
| 4 | **Size and care label** | Size and fabric in one photo. |
| 5 | **Fabric close-up** | True colour and texture. |
| 6 | **Each flaw** | One clear photo per flaw. |
| 7 | **Tape measure** | Pit to pit or waist, laid flat. |
| 8 | **Worn (optional)** | Shows the fit. |

Use daylight, a plain background and no filters. Square photos look best on Depop.

### Title and description
| App | What buyers see first | What to write |
|---|---|---|
| **Vinted** | The title | Short: brand + item type + key detail + size. Vinted also uses these words to suggest a category. |
| **Depop** | The first words of the description | Start with brand, item type, size and colour. Add up to 5 hashtags with words that are not already in your text. |

Then, in the description on both apps: fit, measurements in cm, fabric, how often it was worn, and every flaw with where it is.

### The fields buyers filter by
| Field | Rule |
|---|---|
| **Category** | Pick the most exact one, all the way down. It decides which other fields you see. |
| **Brand** | Exactly as on the label. No label? Pick the no-brand option. Never guess a famous brand. |
| **Size** | The size on the label. Real measurements go in the description. |
| **Condition** | Pick the closest option and read its short definition in the app. If unsure, pick the lower one. |
| **Colour** | The main colour a buyer would call it. |
| **Material (Vinted)** | Main fabric from the care label. |
| **Source, age and style (Depop)** | Fill in every one that fits, for example preloved, modern, minimal. |

### Pricing tips
- **Check sold items, not live ones.** Search the same brand and item, then look at what really sold.
- **Leave a little room for offers.** Decide your lowest price before you list.
- **Turn on bundle discounts** if you sell many items.
- **Price by condition.** A worn item with flaws should sit below the same item in better condition.

### Quick checklist before you list
- [ ] Main photo shows the whole item, in daylight, on a plain background
- [ ] Brand label, size and care label, and every flaw photographed
- [ ] Title (Vinted) or first line (Depop) has brand, item, size and colour
- [ ] Category, brand, size, condition and colour filled in
- [ ] Measurements in cm and every flaw written in the description
- [ ] Price checked against sold items
- [ ] Parcel size picked from the item packed, not guessed

### Common mistakes
- **Dark or filtered photos.** Buyers cannot see the true colour, so they scroll past or ask and wait.
- **Size only in the text.** The size filter reads the size field. Fill in both.
- **"Good condition" with a hidden flaw.** It leads to returns and bad ratings. Show it and say it.
- **Pricing from live listings.** Live prices are what people hope for. Sold prices are what buyers paid.
- **Picking a parcel size too small.** The parcel can be refused or cost more to send.

---

Want this done for your shop or deck? I do it as a fixed-price project on Upwork: [Hire me on Upwork](https://www.upwork.com/freelancers/~01c18d191d6a95988c)

Built by **Tuli, Satin & Scale**.
