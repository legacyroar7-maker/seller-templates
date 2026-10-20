# Seller Templates

**Free, ready-to-fill templates for people who sell online. Copy one, fill it in, and list faster.**

All examples use a made-up demo brand (Fernmoor). Swap in your own products.

## Contents
1. [Shopify product CSV import template](#1-shopify-product-csv-import-template)
2. [Etsy listing planner](#2-etsy-listing-planner)
3. [eBay item specifics checklist for clothing](#3-ebay-item-specifics-checklist-for-clothing)
4. [Vinted and Depop listing checklist](#4-vinted-and-depop-listing-checklist)
5. [AEO FAQ block for product pages](#5-aeo-faq-block-for-product-pages)
6. [Resale clothing photo checklist](#6-resale-clothing-photo-checklist)

More templates are coming soon: a product description structure and a product photo shot list for Etsy and Shopify.

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

Use daylight, a plain background and no filters. Square photos look best on Depop. For set-up, label close-ups and photo limits, see the [resale clothing photo checklist](#6-resale-clothing-photo-checklist).

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

## 5. AEO FAQ block for product pages

**File:** [product-faq-block.html](product-faq-block.html)

Buyers now ask search engines and AI tools full questions, like "Is this mug dishwasher safe?" These tools answer from text they can read on your product page. A short FAQ with clear questions and direct answers gives them that text. This is the AEO part of SEO and AEO: write the answer buyers are looking for, in words a machine can quote. It makes your page easier to read and quote. It does not guarantee you will show up.

The file has two parts, with a filled demo (a mug from the made-up brand Fernmoor):
- **Part 1: the visible FAQ.** Plain HTML that buyers see on the page.
- **Part 2: the same FAQ as JSON-LD.** Structured data (`FAQPage` from schema.org) that labels each question and answer for machines.

### The 6 question types buyers ask
| # | Type | Example question | The answer must include |
|---|---|---|---|
| 1 | **Size and fit** | What size is the Fernmoor Speckled Mug? | Real numbers: cm, ml, size chart or how it fits. |
| 2 | **Materials** | What is it made of? | The main material, plus anything buyers check for (food-safe, allergy, vegan). |
| 3 | **Who it is for** | Is it a good gift for a coffee lover? | Yes or no first, then the reason. |
| 4 | **Care and use** | Can it go in the dishwasher? | What is fine, what to avoid. |
| 5 | **Delivery** | When will it arrive? | Processing time in days. Made to order, if it is. |
| 6 | **Problems and returns** | What if it arrives broken? | What the buyer does and what you do, with a time limit. |

### Rules for good answers
- **Answer in the first sentence.** "Yes, both are fine." Then add detail.
- **Keep it to 1 to 3 sentences.** Short answers are easier to quote.
- **Name the product in the question.** Then the answer still makes sense when it is quoted on its own.
- **Use real numbers.** "350 ml", "3 to 5 working days". Not "large" or "fast".
- **Only true facts.** No sales lines or promo codes in the answers. Write only what you can keep.
- **Match the two parts word for word.** The JSON-LD must say exactly what the visible FAQ says.

### Add it to Shopify in 5 steps
1. **Edit** the file: change the questions and answers in Part 1, then copy the same text into Part 2.
2. **Paste Part 1:** Products > open the product > in the description editor, click **Show HTML** (the `<>` button) > paste at the end > Save.
3. **Make a template** for this product: Online Store > Themes > Customize > Products > Create template. Then set the product to use it (product page > Theme template).
4. **Paste Part 2:** in that template, add a **Custom Liquid** block or section and paste Part 2 into it > Save. A Custom Liquid block shows on every product that uses the template, so keep one template per product, or ask a developer to load the FAQ from a metafield.
5. **Test** the live page URL in the [Schema Markup Validator](https://validator.schema.org/). It should find one `FAQPage` with 6 questions and no errors.

**Etsy, eBay, Vinted and Depop** do not allow code in listings. Copy only the questions and answers from Part 1 as plain text at the end of your description.

### Common mistakes
- **Expecting FAQ dropdowns in Google.** Google now shows FAQ rich results only for a small group of government and health sites. The value is clear answers on your page, not a special search look.
- **JSON-LD with no visible FAQ.** The structured data must describe text that is really on the page.
- **Two FAQPage blocks on one page.** Some themes and apps add one already. Check with the validator and keep one.
- **The same FAQ on every product.** "What size is it?" needs a different answer for each product.
- **Vague answers.** "It depends" or "Contact us" gives a buyer and an AI tool nothing to use.

---

## 6. Resale clothing photo checklist

**File:** [resale-photo-checklist.csv](resale-photo-checklist.csv)

On eBay, Vinted, Depop and Vestiaire Collective, buyers cannot touch the item. Your photos have to show what it looks like, what brand and size it is, and what is wrong with it. This checklist walks you through set-up, the 8 shots and the checks after, with a filled demo (a denim jacket from the made-up brand Fernmoor).

### How to use it
1. **Open** the file in Google Sheets (File > Import) or Excel.
2. **Do the set-up rows first** (light, background, phone). They take 5 minutes and fix most bad photos.
3. **Take the 8 shots** in order and mark each row **Y** in the **Done** column.
4. **Do the after rows** before you upload: check, light edits, photo order.

### Set-up: light, background, phone
| What | Do this | Not this |
|---|---|---|
| **Light** | Daylight from a big window. Turn off ceiling lights. | Flash, direct sun, yellow room lights at night. |
| **Background** | Plain and light: a white sheet, a white wall or a light grey board. | Bed covers with patterns, carpets, mirrors with a messy room. |
| **Item** | Steamed, lint rolled, pockets empty, buttons and zips done up. | Creases, pet hair, a crumpled item. |
| **Style** | One style for all main shots: flat lay, hanger on a plain wall, or worn. | Mixing styles and backgrounds in one listing. |
| **Phone** | Clean lens, normal 1x lens, grid on, tap to focus, phone held level. | Digital zoom, beauty filters, shooting at an angle. |

### The 8 shots
| # | Shot | How | Check |
|---|---|---|---|
| 1 | **Whole item, front** | Fill most of the frame. Straight above (flat lay) or straight in front. | Nothing cut off, item straight. This is the photo buyers see first. |
| 2 | **Back** | Same distance and angle as shot 1. | Matches shot 1 from the other side. |
| 3 | **Brand label** | Close-up, label flat, fill the frame. | Every letter can be read. Buyers use it to check the brand is real. |
| 4 | **Size and care label** | Unfold the label so the text is flat. | Size and fabric can be read. |
| 5 | **Fabric close-up** | Close to the fabric, in daylight. | Colour on screen matches the item in your hand. |
| 6 | **Details** | Buttons, zips, pockets, prints, hardware. | Each one is sharp. |
| 7 | **Each flaw** | One photo per flaw. Point to it with a finger or a pen. | Every flaw in your description has a photo. |
| 8 | **Measurement or fit** | Tape measure on the item laid flat, or a worn photo. | Numbers on the tape can be read. |

### Label close-ups: 4 quick rules
- **Get close, then step back a little** until the phone can focus. Tap the label on the screen.
- **Hold the label flat** with one finger at the edge, not over the text.
- **No flash.** It makes shiny labels white and hard to read.
- **Shoot every label:** brand, size, care and fabric. If a label was cut out, take a photo of where it was and say so in the text.

### What each app asks for
| App | Photos | Notes |
|---|---|---|
| **eBay** | Up to 24 | At least 500 x 500 pixels, about 1600 x 1600 is best. No logos, badges or watermarks on photos. |
| **Vinted** | Up to 20 | Show every flaw in photos and in the description. For the same item in other sizes, photograph each size label. |
| **Depop** | Only a few slots, plus 1 video | Most sellers had 4 photo slots when this was written. Square photos look best. Use shots 1, 3, 7 and 8, and show the rest in the video. |
| **Vestiaire Collective** | The form tells you | The listing form asks for set shots in a set order. Proof of origin (receipt, certificate or serial number) is uploaded on its own and is not shown to buyers. No stock photos. |

Limits change. Check the app when you list.

### Quick checklist before you upload
- [ ] Daylight, no flash, plain light background
- [ ] Item steamed, lint rolled, pockets empty
- [ ] Shots 1 and 2: whole item front and back, nothing cut off
- [ ] Shots 3 and 4: brand, size and care labels can be read
- [ ] Shot 5: colour on screen matches the real item
- [ ] Shot 7: one photo for every flaw
- [ ] Shot 8: tape measure numbers can be read
- [ ] No filters, no text or logos on photos, shot 1 is first

### Common mistakes
- **Photos at night under room lights.** Colours turn yellow, and buyers get a different colour than they saw.
- **Stock photos or photos from the brand's website.** Buyers want this item, not a new one. Some apps do not allow it.
- **Hiding flaws in the last photo or leaving them out.** It leads to returns and "not as described" claims. Show them and say them.
- **Labels that cannot be read.** Buyers then ask and wait, or move on.
- **A busy background.** The item gets lost, and the first photo looks messy in the feed.

---

Want this done for your shop or deck? I do it as a fixed-price project on Upwork: [Hire me on Upwork](https://www.upwork.com/freelancers/~01c18d191d6a95988c)

Built by **Tuli, Satin & Scale**.
