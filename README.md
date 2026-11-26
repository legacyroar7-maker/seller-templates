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
7. [Product description structure](#7-product-description-structure)
8. [Product photo shot list for Etsy and Shopify](#8-product-photo-shot-list-for-etsy-and-shopify)
9. [Shopify collection page checklist](#9-shopify-collection-page-checklist)
10. [Shopify SEO and AEO fields checklist for every product](#10-shopify-seo-and-aeo-fields-checklist-for-every-product)
11. [Shopify product page checklist before you go live](#11-shopify-product-page-checklist-before-you-go-live)
12. [eBay and Vinted shipping and parcel size cheat sheet](#12-ebay-and-vinted-shipping-and-parcel-size-cheat-sheet)
13. [Etsy shop About and announcement template](#13-etsy-shop-about-and-announcement-template)
14. [Depop and Vinted offer and bundle message templates](#14-depop-and-vinted-offer-and-bundle-message-templates)
15. [Shopify size chart template for clothing](#15-shopify-size-chart-template-for-clothing)

More templates are coming soon: eBay condition notes for used items, Vinted and Depop measurement guide for clothing.

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
- **Ready replies for offers and bundles:** see the [offer and bundle message templates](#14-depop-and-vinted-offer-and-bundle-message-templates).

### Quick checklist before you list
- [ ] Main photo shows the whole item, in daylight, on a plain background
- [ ] Brand label, size and care label, and every flaw photographed
- [ ] Title (Vinted) or first line (Depop) has brand, item, size and colour
- [ ] Category, brand, size, condition and colour filled in
- [ ] Measurements in cm and every flaw written in the description
- [ ] Price checked against sold items
- [ ] Parcel size picked from the item packed, not guessed (see the [shipping and parcel size cheat sheet](#12-ebay-and-vinted-shipping-and-parcel-size-cheat-sheet))

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

## 7. Product description structure

**File:** [product-description-template.html](product-description-template.html)

A good product description answers the buyer's questions in the order they ask them: What is it? Why is it good for me? Will it fit? How do I look after it? This structure puts the answers in 5 blocks, so buyers find what they need fast and search engines and AI tools get clear text to read. That is the core of SEO and AEO for a product page. It makes your page easier to understand and quote. It does not guarantee rankings or sales.

The file has a blank template (Part 1) and a filled demo (Part 2): a waxed canvas tote from the made-up brand Fernmoor.

### The 5 blocks
| # | Block | Length | What to write |
|---|---|---|---|
| 1 | **Hook** | 1 or 2 sentences | What it is, who it is for, and the main reason to buy. Use the main search phrase once, the way a buyer would type it. |
| 2 | **3 benefits** | 3 bullet points | Start each one with what the buyer gets, then the fact that proves it. |
| 3 | **Specs** | 4 to 8 lines | Size, weight, material, colour, what is in the box. Real numbers with units. |
| 4 | **Care** | 2 or 3 sentences | How to clean it, what to avoid, how to keep it looking good. |
| 5 | **FAQ** | 2 or 3 questions | The questions buyers ask most. Answer in the first sentence. For a full FAQ with structured data, see [section 5](#5-aeo-faq-block-for-product-pages). |

### Feature or benefit? 3 before and after examples
A feature is what the product has. A benefit is what the buyer gets from it. Lead with the benefit, then prove it with the feature.

| Before (feature only) | After (benefit first, then the fact) |
|---|---|
| Padded laptop pocket. | **Your laptop stays safe.** A padded inside pocket fits most laptops up to 15 inches. |
| Waxed cotton canvas. | **Light rain runs off.** The cotton canvas is waxed, so drops bead up instead of soaking in. |
| 28 cm handle drop. | **Comfortable on your shoulder.** The 28 cm handle drop is long enough to wear over a coat. |

### The demo, as it reads on the page
> The Fernmoor Waxed Canvas Tote is a work bag for people who carry a laptop, lunch and a water bottle every day. It stays upright, closes with a zip and shrugs off light rain.
>
> - **Your laptop stays safe.** A padded inside pocket fits most laptops up to 15 inches.
> - **Light rain runs off.** The cotton canvas is waxed, so drops bead up instead of soaking in.
> - **Comfortable on your shoulder.** The leather handles have a 28 cm drop, long enough to wear over a coat.
>
> **Details:** 40 x 36 x 12 cm (15.7 x 14.2 x 4.7 in), about 17 litres. 850 g. Waxed cotton canvas, leather handles, cotton lining. Olive green. In the box: 1 tote and a care card.
>
> **Care:** Wipe with a damp cloth and let it dry in the air. Do not put it in the washing machine or tumble dryer.
>
> **Is the Fernmoor Waxed Canvas Tote waterproof?** No, it is water-resistant. It handles light rain, but it is not made for heavy rain.

### Plain-text template for Etsy, eBay, Vinted and Depop
Etsy and Vinted descriptions are plain text, and eBay does not allow scripts. Copy this and replace the [brackets]:

```text
[Product name] is a [what it is] for [who it is for]. [Main reason to buy].

- [Benefit 1]. [Fact behind it].
- [Benefit 2]. [Fact behind it].
- [Benefit 3]. [Fact behind it].

DETAILS
Size: [cm and inches]
Weight: [g]
Material: [main material]
Colour: [colour]
In the box: [what the buyer gets]

CARE
[How to clean it]. [What to avoid].

QUESTIONS
[Question 1]? [Answer].
[Question 2]? [Answer].
```

**Resale (Vinted, Depop, eBay pre-owned):** keep the hook short, skip the benefits, and add a **Condition** line with every flaw and where it is. Put measurements in the specs.

### Where to use it
| Platform | Tip |
|---|---|
| **Shopify** | Paste Part 1 or Part 2 in the description editor with **Show HTML** (the `<>` button). Keep headings small (`h3`), because your theme already uses a big heading for the product title. |
| **Etsy** | Buyers see the first lines first, so the hook matters most. Put shipping and shop policies in your shop settings, not in every description. |
| **eBay** | Many buyers read on a phone. Keep the specs as short lines, and fill in item specifics too, because filters read those, not your text. |
| **Vinted and Depop** | Use the short resale version. On Depop, the first words of the description show first, so start with brand, item, size and colour. |

### Quick checklist before you publish
- [ ] The first sentence says what it is and who it is for
- [ ] The main search phrase appears once in the hook, in natural words
- [ ] 3 benefits, each with a fact behind it
- [ ] Specs have real numbers and units, in cm and inches where it helps
- [ ] Care says what to do and what to avoid
- [ ] 2 or 3 FAQ answers that start with yes, no or a number
- [ ] Every claim is true for this exact product

### Common mistakes
- **A wall of text.** Buyers scan. Short blocks and bullet points are easier to read on a phone.
- **Only adjectives.** "Premium, stylish, high quality" tells a buyer nothing. Numbers and facts do.
- **Saying "waterproof" when it is water-resistant.** Use the exact word, or you get returns and complaints.
- **The same description on every product.** Each product needs its own hook, specs and answers. Copied text also helps no one in search.
- **Keyword stuffing.** Repeating the same phrase 5 times reads badly. Use it once in the hook and once more only if it fits.

---

## 8. Product photo shot list for Etsy and Shopify

**File:** [product-photo-shot-list.csv](product-photo-shot-list.csv)

Buyers cannot pick up your product. Your photos have to show what it is, how big it is, what it feels like and what arrives in the box. This shot list gives you 10 shots in the order buyers want them, with a tip for Etsy and Shopify on each one, and a filled demo (a ceramic vase from the made-up brand Fernmoor). For second-hand clothing, use the [resale clothing photo checklist](#6-resale-clothing-photo-checklist) instead.

### How to use it
1. **Open** the file in Google Sheets (File > Import) or Excel.
2. **Plan** all 10 shots before you start, and write your own idea for each one in the demo column.
3. **Shoot** them in one session, with the same light and background, and mark each row **Y** in the **Done** column.
4. **Upload** them in the same order. Shot 1 always goes first.

### The 10 shots
| # | Shot | What it shows the buyer |
|---|---|---|
| 1 | **Main photo** | What the product is, in one look. Plain light background, space on every side. |
| 2 | **Second angle** | The back, side or top. |
| 3 | **Scale** | How big it really is: in a hand or next to a mug, a book or a phone. |
| 4 | **Size with numbers** | Height, width and depth in cm and inches, written beside the product. |
| 5 | **Detail close-up** | Texture, finish, stitching or hardware. |
| 6 | **Colours and options** | Every colour or size side by side, then one photo of each. |
| 7 | **In use (lifestyle)** | The product in a real home or on a person. |
| 8 | **What is in the box** | Everything the buyer gets, laid out from above. |
| 9 | **Packaging or gift** | How it arrives. |
| 10 | **Made by hand or personal touch** | Hands at work, or a proof of the personalization. |

**Bonus:** a short video of the product turning or in use.

### Short rules
- **One look for the whole set.** Same light, same background, same shape (square or landscape) for every photo.
- **Daylight, no flash.** Shoot by a window and turn off ceiling lights so colours stay true.
- **Fill the frame, but leave a border.** Sites crop photos for thumbnails. Space around the product stops it getting cut off.
- **No text on the first photo.** Numbers and short labels are fine from shot 2 onward.
- **Real colours only.** Crop and brighten a little, but do not change colours. Buyers return items that look different.
- **Big, sharp files.** Aim for at least 2000 pixels on each side so zoom stays sharp.
- **Write alt text for every photo.** Say what is in it in plain words, for example "Fernmoor ribbed vase in sand, held in one hand to show size". It helps buyers who use screen readers and gives search engines and AI tools clear text about the image.

### Etsy and Shopify at a glance
| | Etsy | Shopify |
|---|---|---|
| **How many** | Up to 20 photos and 2 videos per listing | Many more than you need. 6 to 10 good photos cover most products. |
| **Shape** | First photo landscape or square. It sets the shape for the rest. | Square is the safe choice. Keep one shape for all photos. |
| **Size** | At least 2000 pixels wide and high is recommended | 2048 x 2048 is a common square size. Up to 20 MB per image. |
| **Options** | Link photos to variations (Variations > Link photos) | One image per variant, so the photo changes when the buyer picks it |
| **Video** | 5 to 15 seconds, sound is removed | MP4 or MOV, keep it short |
| **Alt text** | Add it in the photo editor of each listing | Add it on each image in the product page (Add alt text) |

Limits change. Check the site when you list.

### Quick checklist before you upload
- [ ] Shot 1 shows the whole product, on a plain light background, with no text
- [ ] One shot shows scale and one shows the size in numbers
- [ ] Close-up colour matches the real product
- [ ] Every colour or option has its own photo, linked to its variant
- [ ] What is in the box matches the description
- [ ] All photos share one light, one background and one shape
- [ ] Alt text written for every photo
- [ ] Photos uploaded in order, shot 1 first

### Common mistakes
- **A busy first photo.** Props, text or a dark room make the thumbnail hard to read in search.
- **No sense of size.** Without a scale shot, buyers guess, then return it when it is smaller than they thought.
- **Mixed backgrounds and shapes.** A gallery that jumps between square and tall photos looks messy.
- **Only lifestyle photos.** Mood is nice, but buyers still need a clear shot of the product itself.
- **Stock or AI-changed photos that do not match the real product.** Buyers get something different from what they saw. Show the real item.

---

## 9. Shopify collection page checklist

**File:** [shopify-collection-page-checklist.csv](shopify-collection-page-checklist.csv)

A collection page is a shelf in your shop: "Ceramic vases", "Linen shirts", "Gifts under 50". Buyers reach it from your menu, from search engines and from AI answers. It needs a clear name, a short intro, the right products, filters that help, and links to the next shelf. This checklist walks through every field in 5 parts, with a filled demo (a "Ceramic Vases" collection from the made-up brand Fernmoor).

### How to use it
1. **Open** the file in Google Sheets (File > Import) or Excel.
2. **Open** your collection in Shopify: Products > Collections.
3. **Go** row by row. Write your text in the **Your value** column and mark each row **Y** in the **Done** column.
4. **Preview** the live page on a phone before you share it.

### Part 1. Title and intro text
| Field | What to write |
|---|---|
| **Collection title** | The words buyers type. "Ceramic Vases", not "Our Lovely Pieces" or "Drop 7". It is usually the big heading on the page. |
| **Intro text** (Description box) | 2 to 4 short sentences, about 40 to 80 words. Long text above the products pushes them off a phone screen. |
| **Collection image** | One clear photo in the same style as your product photos, with alt text. Check it on a phone, some themes crop it. |

**Intro formula:** what is in it + who it is for + the choices (sizes, colours, materials) + one helpful fact + a link to a related collection.

> **Demo:** Handmade ceramic vases for dried flowers, fresh stems and shelves. Choose from 3 heights (12, 20 and 30 cm) and 4 glazes: sand, sage, chalk and charcoal. Every vase is glazed inside and holds water. Pair one with our **ceramic mugs** (a link to that collection) for a matching gift.

### Part 2. Products and sort order
| Field | What to set |
|---|---|
| **Collection type** | **Manual:** you add each product by hand. **Smart:** Shopify adds every product that matches your rules. You cannot switch the type after you save, so pick Smart for shelves that grow. |
| **Conditions** (Smart only) | One clear rule, for example **Product type is equal to Vase**. Write product type and tags the same way on every product, or products go missing. |
| **Sort** | Best selling, Newest, Price or Manually. Put your clearest, best-stocked products in the first row. |
| **Product count** | Enough products to compare. Merge shelves with only 1 or 2 products, and keep empty collections out of your menu. |

### Part 3. Filters
Filters let buyers narrow a shelf by colour, size or price. Set them up in the free **Search & Discovery** app from Shopify: Apps > Search & Discovery > Filters > Add filter. Your theme must show them. Most Online Store 2.0 themes, like Dawn, do.

| Filter | Why buyers use it | Comes from |
|---|---|---|
| **Availability** | Hide sold-out items | Stock levels |
| **Price** | Stay inside a budget | Variant prices |
| **Colour** | Match a room or an outfit | Variant option or metafield |
| **Size** | Find what fits | Variant option or metafield |
| **Material** | Check what it is made of | Metafield or tags |

4 to 6 filters is usually enough. Filters read your product data, so clean it first: if one product says "Grey" and another says "Gray", buyers see two options.

### Part 4. SEO and AEO fields
Find these on the collection page: **Search engine listing > Edit**.

| Field | Rule | Demo |
|---|---|---|
| **SEO title** (Page title) | About 60 characters or less. Main words first, then one key detail, then your brand. | Handmade Ceramic Vases in 4 Glazes \| Fernmoor (45) |
| **Meta description** | About 155 characters or less. What is on the shelf, one reason to look, the main choices. | Handmade ceramic vases in 3 sizes and 4 glazes, glazed inside to hold water. Shop sand, sage, chalk and charcoal vases from Fernmoor. (133) |
| **URL handle** | Short, lowercase, dashes. If you change it later, keep **Create a URL redirect** ticked so old links still work. | `/collections/ceramic-vases` |
| **Image alt text** | What is in the photo, in plain words. No keyword lists. | Three Fernmoor ceramic vases in sand, sage and charcoal on a white shelf |
| **FAQ block** (AEO) | 3 to 5 real buyer questions with short answers, below the products. Answer in the first sentence. | Do the vases hold water? Yes, every vase is glazed inside and holds water for fresh flowers. |

**About the FAQ block:** buyers ask AI tools full questions, and those tools answer from text they can read. Clear questions and direct answers on the page give them that text. Many themes have a **Collapsible content** section you can add to the collection template (Online Store > Themes > Customize). If each shelf needs its own questions, make a separate collection template and pick it under **Theme template** on the collection page. Answer rules are in the [AEO FAQ block](#5-aeo-faq-block-for-product-pages) section.

You can check title and meta lengths with the free [title checker](https://legacyroar7-maker.github.io/shop-tools/).

### Part 5. Internal links and menu
| Link | What to do | Demo |
|---|---|---|
| **Main menu** | Add the collection so buyers find it in one or two clicks: Content > Menus (older admins: Online Store > Navigation). | Home decor > Ceramic Vases |
| **Links in the intro** | Link 1 or 2 related collections. The link text says where it goes, never "click here". | ceramic mugs |
| **Links from products** | One line at the end of each product description that links back to the collection. | See all ceramic vases |
| **Related collections** | Add a **Collection list** section under the products with 2 to 4 shelves that make sense next. | Ceramic Mugs, Table Decor, Gifts under 50 |

### Quick checklist before you publish
- [ ] Title uses the words buyers type
- [ ] Intro is 2 to 4 sentences and the first products still show on a phone
- [ ] Right products are in, nothing empty or broken
- [ ] First row shows your clearest, in-stock products
- [ ] Filters show, and each value has one spelling
- [ ] SEO title about 60 characters, meta description about 155
- [ ] Short URL handle, redirect ticked if you changed it
- [ ] Image alt text written
- [ ] 3 to 5 FAQ answers, each one true
- [ ] Collection is in the menu and every link works

### Common mistakes
- **The same intro on every collection.** Each shelf needs its own words, or the pages look alike to buyers and search engines.
- **Names only you understand.** "Drop 7" or "Autumn vibes" tells a buyer nothing. Use the product words.
- **A wall of text above the products.** Put the short intro on top. Longer help goes in the FAQ below.
- **Messy filter values.** "Grey", "gray" and "GREY" become three options.
- **Changing the handle with no redirect.** Old links and saved bookmarks break.
- **Tiny or empty shelves in the menu.** Buyers click, find nothing, and leave.

These steps make the page clearer for buyers, search engines and AI tools. Nobody can promise a ranking.

---

## 10. Shopify SEO and AEO fields checklist for every product

**File:** [shopify-product-seo-aeo-fields-checklist.csv](shopify-product-seo-aeo-fields-checklist.csv)

Every Shopify product has a set of small fields that search engines, AI tools and your own shop filters read: SEO title, meta description, URL handle, image alt text, category, type and tags. They take a few minutes per product, and they are easy to skip. This checklist lists all of them in 16 rows, with where to find each one in Shopify admin, the rule, a live character count and a filled demo (the Speckled Mug from the made-up brand Fernmoor).

### How to use it
1. **Open** the file in Google Sheets (File > Import) or Excel. Make one copy per product.
2. **Open** the product in Shopify: Products > click the product.
3. **Go** row by row. Write your text in the **Your text** column. The **Characters used** column counts it for you on the rows with a limit.
4. **Paste** each value into Shopify, press **Save**, and mark the row **Y** in the **Done** column.

### Part 1. Search engine listing
Scroll to the bottom of the product page: **Search engine listing > Edit** (pencil icon).

| Field | Rule | Demo |
|---|---|---|
| **SEO title** (Page title) | About 60 characters or less. What it is, one key detail, then your brand. If you leave it blank, Shopify uses the product title. | Speckled Stoneware Mug, 350 ml, Sage Green \| Fernmoor (53) |
| **Meta description** | About 155 characters or less. What it is, 2 or 3 facts buyers check, one reason to click. Only true facts. | Handmade speckled stoneware mug in sage green. Holds 350 ml, dishwasher and microwave safe. Ships in a gift box in 3 to 5 working days. (135) |
| **URL handle** | Short, lowercase, dashes. Drop filler words like "the", "best" or "new". If you change it later, keep **Create a URL redirect** ticked so old links still work. | `/products/speckled-stoneware-mug` |

### Part 2. Images
| Field | Rule | Demo |
|---|---|---|
| **Image file name** | Rename the photo before you upload. Shopify keeps the name in the image link. | `speckled-stoneware-mug-sage.jpg`, not `IMG_4821.jpg` |
| **Main image alt text** | Media > click the photo > **Alt text**. Say what is in the photo in plain words. About 125 characters or less. No keyword lists, and do not start with "Image of". | Fernmoor speckled stoneware mug in sage green on a wooden table |
| **Alt text for every other photo** | Say what is different in this photo: the detail, the size, the use. | Close-up of the speckled glaze and curved handle of the sage green mug |

Alt text helps buyers who use screen readers, and it tells search engines and AI tools what the photo shows. What to shoot is in the [product photo shot list](#8-product-photo-shot-list-for-etsy-and-shopify).

### Part 3. Product organization
| Field | Where | Rule | Demo |
|---|---|---|---|
| **Category** | Product page > Category | Type the product word and pick the most exact match from Shopify's list. It decides which extra fields you can fill. | Mugs |
| **Category metafields** | Fields shown under Category | Fill every one that fits, with the same spelling on every product. They feed filters and some sales channels. | Color: Green. Material: Stoneware. |
| **Type** | Product organization > Type | Your own word for what it is, same spelling on every similar product. | Mug |
| **Vendor** | Product organization > Vendor | Your brand, or the maker's brand if you resell. | Fernmoor |
| **Collections** | Product organization > Collections | Every shelf it belongs on, usually 1 to 3. | Ceramic Mugs, Gifts under 50 |
| **Tags** | Product organization > Tags | About 3 to 8, lowercase, one spelling each. Tags help your own sorting, smart collections and filters. They are not a keyword list for Google. | stoneware, handmade, gift idea, dishwasher safe |

### Part 4. AEO content on the page
Buyers ask AI tools full questions, like "Can this mug go in the dishwasher?" Those tools answer from text they can read on your page. Give them clear facts.

| Field | Rule | Demo |
|---|---|---|
| **Key facts in the description** | Real numbers: size, capacity, material, care, delivery time. Not "large" or "fast". Full structure in [Product description structure](#7-product-description-structure). | 350 ml, 9.5 cm tall, stoneware, dishwasher and microwave safe, ships in 3 to 5 working days |
| **FAQ block** | 3 to 6 real buyer questions. Answer in the first sentence. HTML and JSON-LD in the [AEO FAQ block](#5-aeo-faq-block-for-product-pages). | Can the Fernmoor Speckled Mug go in the dishwasher? Yes, and in the microwave too. |
| **Barcode (GTIN)** | Variants > open the variant > Barcode. Only the real number from the packaging. Never make one up. Handmade items often have none. | None (handmade) |

### Part 5. Final check
Read the **Search engine listing** preview in Shopify, then open the live page on a phone. Title and description should not be cut off in a bad place, every photo should load, and each alt text should match its photo.

You can check SEO title and meta description lengths with the free [title checker](https://legacyroar7-maker.github.io/shop-tools/).

### Doing many products at once
Products > **Export** gives you a CSV with the SEO title and SEO description columns. Fill them in, then import the file back with **Overwrite products with matching handles** ticked. Test with 2 products first and keep the original export as a backup. The column layout is in the [Shopify product CSV import template](#1-shopify-product-csv-import-template).

### Quick checklist before you save
- [ ] SEO title about 60 characters, main words first
- [ ] Meta description about 155 characters, its own text, only true facts
- [ ] Short URL handle, redirect ticked if you changed it
- [ ] Photo file names say what the product is
- [ ] Every photo has its own alt text
- [ ] Category picked and its fields filled
- [ ] Type and vendor spelled the same as on your other products
- [ ] In 1 to 3 collections
- [ ] 3 to 8 clean tags
- [ ] Key facts with real numbers, plus a short FAQ

### Common mistakes
- **The same meta description on every product.** Each page needs its own words, or the pages look alike.
- **Keyword lists in alt text.** "mug cup coffee mug gift mug" does not describe a photo. Write one plain sentence.
- **Changing the URL handle with no redirect.** Old links, ads and bookmarks break.
- **Two spellings of one value.** "Grey" and "Gray", or "Mug" and "Mugs", split your filters and collections.
- **Leaving Category empty.** You lose the extra fields that filters and some sales channels read.
- **Made-up facts or barcodes.** Write only what is true for this product.

These fields make the page clearer for buyers, search engines and AI tools. Nobody can promise a ranking.

---

## 11. Shopify product page checklist before you go live

**File:** [shopify-product-page-go-live-checklist.csv](shopify-product-page-go-live-checklist.csv)

A product can look fine in Shopify admin and still break for buyers: a colour with no photo, a variant with 0 stock, a weight left at 0 kg, or a product that is Active but not on your Online Store. This checklist goes through the whole product page in 26 rows and 8 parts, with where to find each field in Shopify admin, the rule, and a filled demo (the Speckled Mug from the made-up brand Fernmoor, in 3 colours).

### How to use it
1. **Open** the file in Google Sheets (File > Import) or Excel. Make one copy per product.
2. **Keep** the product on **Draft** while you work.
3. **Go** row by row. Write what you set in the **Your value** column and mark **Done** with **Y**.
4. **Switch** the product to **Active** only after the final test in Part 8.

### Part 1. Product basics
| Check | Rule | Demo |
|---|---|---|
| **Title** | The plain name buyers search for, plus one key detail. No CAPITALS or emoji. | Speckled Stoneware Mug, 350 ml |
| **Description** | Hook, 3 benefits, specs with real numbers, care, short FAQ. Full structure in [Product description structure](#7-product-description-structure). | 350 ml, 9.5 cm tall, stoneware, dishwasher safe, 3 FAQs |
| **Photos** | At least 5, same light and background. What to shoot is in the [product photo shot list](#8-product-photo-shot-list-for-etsy-and-shopify). | 8 photos: main, in hand, glaze close-up, box and more |

### Part 2. Variants
| Check | Rule | Demo |
|---|---|---|
| **Options** | Variants > **Add options like size or color**. Same spelling as on your other products. | Color: Sage Green, Sand, Charcoal |
| **Every variant complete** | Open each variant. Each one needs its own price, SKU, stock, weight and photo. | 3 of 3 complete |
| **Variant photo** | Link a photo to each variant, so buyers see the colour they pick. | Each colour has its own main photo |

### Part 3. Prices
| Check | Rule | Demo |
|---|---|---|
| **Price** | Check every variant. Check your tax settings to see if prices include tax. | 24.00 |
| **Compare-at price** | Only a real earlier price that was higher. Otherwise leave it blank. In the EU the earlier price you show must be the lowest price of the last 30 days. | Blank |
| **Charge tax on this product** | Ticked for most physical products. Check **Settings > Taxes and duties**. | Ticked |
| **Cost per item** | What one unit costs you, with packaging. Buyers never see it. Shopify uses it to show profit and margin. | 9.50 (profit 14.50, margin 60.4%) |

### Part 4. Inventory
| Check | Rule | Demo |
|---|---|---|
| **SKU** | Your own short code, unique per variant. | FM-MUG350-SAGE |
| **Barcode** | Only the real number from the packaging. Never make one up. | None (handmade) |
| **Track quantity** | Ticked. Enter the stock you really have at each location. | 12 / 8 / 5 |
| **Continue selling when out of stock** | Off. Turn it on only for made to order items, and show the real delivery time on the page. | Off |

### Part 5. Shipping
| Check | Rule | Demo |
|---|---|---|
| **This is a physical product** | Ticked for anything you post. | Ticked |
| **Weight** | One unit packed, with box and filling. Round up. A weight of 0 gives wrong shipping rates. | 0.55 kg |
| **Shipping profile and rates** | **Settings > Shipping and delivery**. The product must be in a profile with rates for every country you sell to. Buyers in a country with no rate cannot check out. | General profile, home country and EU |
| **Customs information** | If you ship abroad: country or region of origin and HS code. Check the code with your carrier or the customs tariff. Do not guess. | Portugal, HS 6912.00 |

### Part 6. SEO and AEO fields
Fill the SEO title, meta description, URL handle, image alt text, category, type, vendor, collections and tags. Each field, with rules and a demo, is in the [Shopify SEO and AEO fields checklist](#10-shopify-seo-and-aeo-fields-checklist-for-every-product). You can check lengths with the free [title checker](https://legacyroar7-maker.github.io/shop-tools/).

### Part 7. Status and sales channels
| Check | Rule | Demo |
|---|---|---|
| **Status** | **Draft** while you work. **Active** only after Part 8. | Draft, then Active |
| **Sales channels and markets** | **Publishing > Manage**. Tick **Online Store** and every other channel you use. A product can be Active and still not show in your shop if Online Store is not ticked. | Online Store and Shop |
| **Theme template** | The right product template, if your theme has more than one. It decides which sections show, for example your FAQ block. | Default product |

### Part 8. Final test
1. **Open** the live page on a phone. Click every variant: the photo, price and stock message should change.
2. **Read** all text once more for typos and wrong numbers.
3. **Add** one variant to the cart and go to checkout with a test address. Check the shipping rate, tax and total before the payment step.
4. **For** a full test order, use your payment provider's test mode, then cancel the test order and turn test mode off.

### Doing many products at once
Products > tick the products > **Bulk edit**. Add the columns you need (price, compare-at price, SKU, weight, stock) and scan them side by side. Empty cells and 0 kg weights are easy to spot this way.

### Quick checklist before you go live
- [ ] Clear title and a description with real numbers
- [ ] At least 5 photos, each with alt text
- [ ] Every variant has price, SKU, stock, weight and its own photo
- [ ] Compare-at price blank, or a real earlier price
- [ ] Cost per item filled in
- [ ] Track quantity on, real stock counts entered
- [ ] Continue selling when out of stock off (unless made to order)
- [ ] Packed weight filled in for every variant
- [ ] Shipping rates for every country you sell to
- [ ] Customs information filled in if you ship abroad
- [ ] SEO and AEO fields done (section 10)
- [ ] Online Store ticked under sales channels
- [ ] Phone preview and checkout test done, then Status set to Active

### Common mistakes
- **Weight left at 0 kg.** Weight-based and carrier rates come out wrong, often too low.
- **Only the first variant checked.** The other colours go live with no photo, no SKU or 0 stock.
- **A fake compare-at price.** It misleads buyers, and in many countries it breaks consumer law.
- **Continue selling when out of stock left on.** You take orders you cannot send.
- **Active but not on Online Store.** The product exists in admin, but buyers never see it.
- **No shipping rate for a country you sell to.** Buyers from there reach checkout and cannot pay.

These checks help the page work for buyers on day one. Nobody can promise sales or a ranking.

---

## 12. eBay and Vinted shipping and parcel size cheat sheet

**File:** [ebay-vinted-shipping-cheat-sheet.csv](ebay-vinted-shipping-cheat-sheet.csv)

A wrong weight or parcel size costs you money. On eBay, the carrier can charge you the difference after the label is bought. On Vinted, a parcel that is too big can be refused, and the size cannot be changed after the buyer pays. This cheat sheet shows how to pack, weigh, measure and pick the right size, with a filled demo (a wool cardigan from the made-up brand Fernmoor).

### How to use it
1. **Open** the file in Google Sheets (File > Import) or Excel.
2. **Look** at the **App** column. Rows marked **Both** are for eBay and Vinted. The rest are for one app only.
3. **Pack the item first**, then weigh and measure it. Write your numbers in the **Your value** column.
4. **Mark** each row **Y** in the **Done** column, then enter the numbers in the app.

### The golden rule: pack first, then weigh and measure
Weigh and measure the parcel **as it will be sent**: item, bag or box, tissue, filling and any note. Then **round up**. Never round down.

| What | How | Rule |
|---|---|---|
| **Weight** | Put the sealed parcel on a kitchen or parcel scale. | Round up to the next 100 g, or the next whole unit your carrier uses. |
| **Length** | The longest side, at the widest point. | Round up to the next whole cm (or inch). |
| **Width** | The next longest side. Soft mailers bulge, so measure the middle. | Round up. |
| **Height** | From the table to the highest point. Press lightly. | Round up. Do not squash it to make it fit. |

### Dimensional weight in 1 minute
Many couriers charge the **bigger** of two numbers: the real weight, or the size turned into a weight.

**Length x width x height (cm) / the carrier's number = dimensional weight (kg)**

Many couriers use **5000** for cm and kg. Postal services often charge small soft parcels by real weight only. Check your carrier, because the number and the rules differ.

Demo: 31 x 26 x 6 cm = 4836. 4836 / 5000 = about **1 kg**. The real weight is **0.6 kg**. A courier using this rule would charge for 1 kg. A smaller, flatter parcel would cost less.

### Pick the size: eBay and Vinted side by side
| | **eBay** | **Vinted** |
|---|---|---|
| **Where you enter it** | The delivery part of the listing: packed weight, length, width, height and package type. | When you list, you pick a parcel size. The app shows the weight limit and example items for each size. |
| **Who pays** | You set it: free, flat cost, or calculated from your weight and size. | The buyer pays at checkout and picks the carrier and delivery option. |
| **How to choose** | A service whose size and weight limits your parcel fits, for example a large letter, small parcel or package option. | The smallest size where your packed weight and size are both under the limit. Close to the limit? Pick the next size up. |
| **If you get it wrong** | The carrier can charge you the difference after the label is bought. | The carrier can refuse the parcel or charge extra. The size cannot be changed after the buyer pays. |
| **Time to send** | The handling time you set. Pick one you can always meet. | The time Vinted shows after the sale (5 working days when this was written), with the label or code from Vinted. |
| **Bundles** | Add up the packed weight of all items and check the size again. | Pack and weigh the items together before you agree. A bundle often needs a bigger size. |

Limits, sizes and carriers differ by country and change over time. Check the app and the carrier's page when you list.

### Pack clothing flat in 6 steps
1. **Lay** the item face down on a clean table. Do up buttons and zips.
2. **Fold** the sleeves in to the middle of the back.
3. **Fold** the sides in so the item is about as wide as your mailer, minus 3 to 5 cm.
4. **Fold** it in half or in thirds from the bottom up. Aim for a flat rectangle.
5. **Slide** it into a clear bag if the mailer is not waterproof, then into the mailer. Press out the air and seal it.
6. **Add** the label on the flat front. Remove or cover any old barcodes on a reused bag or box.

Shoes, bags and stiff or fragile items go in a box with filling, so nothing moves when you shake it.

### Demo: Fernmoor wool cardigan
| Check | Demo value |
|---|---|
| Packaging | Grey poly mailer 35 x 45 cm, cardigan in a clear bag |
| Packed weight | 0.52 kg, rounded up to **0.6 kg** |
| Packed size | 31 x 26 x 6 cm (rounded up) |
| Dimensional weight | About 1 kg (31 x 26 x 6 / 5000) |
| Vinted | Smallest size with a limit above 0.6 kg that fits 31 x 26 x 6 cm |
| eBay | 0.6 kg and 31 x 26 x 6 cm entered, small parcel or package service with tracking, handling time 1 working day |
| Bundle with a scarf | 0.75 kg packed, still checked against the same limit before agreeing |

### Quick checklist before you list
- [ ] Item packed in the bag or box you will really use
- [ ] Packed parcel weighed on a scale, rounded up
- [ ] Length, width and height measured at the widest point, rounded up
- [ ] Dimensional weight checked if you use a courier or a box
- [ ] Vinted: smallest size that fits, with room to spare
- [ ] eBay: weight, size and package type entered, handling time you can meet
- [ ] Bundles weighed together before you agree
- [ ] Old labels and barcodes removed, new label flat and fully visible

### Common mistakes
- **Weighing the item, not the parcel.** The bag, box and filling can push it over a limit.
- **Rounding down.** A parcel 10 g over the limit counts as the next size.
- **A big box for a soft item.** You pay for air when the carrier uses dimensional weight.
- **Picking a Vinted size too small to save the buyer money.** The parcel can be refused, and the size cannot be changed after checkout.
- **Guessing on eBay.** If the carrier measures a bigger or heavier parcel, you pay the difference later.
- **Reusing a bag with an old barcode.** The parcel can go to the wrong place.

These checks help you send parcels at the right price. Postage prices are set by each app and carrier.

---

## 13. Etsy shop About and announcement template

**File:** [etsy-shop-about-announcement-template.csv](etsy-shop-about-announcement-template.csv)

Your shop title, announcement and About section are the first words many buyers read about you. They answer three questions: what do you make, who makes it, and when will my order arrive? This template gives you a formula for each part, fill-in blanks, live character counts and a filled demo (the made-up pottery shop Fernmoor).

### How to use it
1. **Open** the file in Google Sheets (File > Import) or Excel.
2. **Write** your text in the **Your text** column, row by row. The **Characters used** column counts it for you.
3. **Read** it out loud once. Cut any sentence that a buyer would skip.
4. **Paste** each part into Etsy (paths below), save, and mark the row **Y** in the **Done** column.

### Where each part shows and its limit
| Part | Where buyers see it | Limit | Where to edit |
|---|---|---|---|
| **Shop title** | Under your shop name on your shop home, and in Google results | Up to 55 characters | Shop Manager > pencil icon next to your shop name under **Sales Channels** > **Add a shop title** or **Edit** |
| **Announcement** | On your shop home page | No short limit in Etsy's help. Etsy says keep it "short and sweet". | Same pencil icon > **Announcement** > **Add a shop announcement** or **Edit** |
| **About your shop** | The About section of your shop | 5,000 characters or less | Shop Manager > **Settings** > **Your shop** > **Shop home editor** > About section |
| **Featured photos** | About section | Up to 5, each with a caption. .jpg, .png or .gif, up to 2 MB. Cropped to 760 x 468 px. | Shop home editor > About section |
| **Featured video** | About section | MP4, MOV, AVI, MPEG or M4V, up to 300 MB | Shop home editor > About section |
| **Shop team** | About page. Owners also show on listing pages. | Name, role, bio and photo per person | Shop home editor > About section |
| **Logo** | Shop home | .jpg, .png or .gif, under 10 MB, at least 500 x 500 px | Shop home editor > Shop basics |

Your shop must be open before you can add a title or announcement. Etsy changes its shop pages from time to time, so check the editor if a menu name looks different.

### Shop title: one line, up to 55 characters
**Formula:** what you sell + what makes it different.

| Weak | Better |
|---|---|
| Welcome to my shop!!! | Handmade stoneware mugs and vases in soft colours (49) |
| BEST GIFTS EVER | Personalised wooden name signs for kids' rooms |
| Fernmoor Studio | Hand-knitted wool scarves and hats in natural colours |

Use words a buyer would type. Your shop name already shows above it, so you do not need to repeat it.

### Shop announcement: 4 short lines
Put the most important line first. Many buyers read only that one.

| Line | What it says | Demo (Fernmoor) |
|---|---|---|
| **1. News** | The one thing that matters now: a delivery cut-off, a holiday break, a new collection. Add the date if it ends. | Holiday orders: order by 12 December for delivery before 24 December (UK addresses). |
| **2. Timing** | How long it takes to make and send an order | Every piece is made to order and ships in 5 to 7 working days. |
| **3. What you make** | One sentence, one true detail | We make stoneware mugs and vases by hand, in batches of 20 to 30. |
| **4. Next step** | One section to look at, and how to ask a question | Looking for a gift? See the Gift Sets section. Questions? Send us a message on Etsy. |

The demo is 4 lines and about 300 characters. Fill-in version:

```
[News or date to know]: [what is happening] [until or by date].
Every [item] is [made to order / ready to ship] and ships in [X to Y] working days.
We make [what you make] [one true detail about how].
Looking for [need]? See the [Section name] section. Questions? Send us a message on Etsy.
```

**Update it** when you go on a break, before holiday cut-offs, when you add a new range, and when a date has passed. An old date tells buyers nobody is home. If your shop language is not English, Etsy may not update the "posted" date, so write the date in line 1 yourself.

### About your shop: 5 parts
| Part | The question it answers | Length | Demo (Fernmoor) |
|---|---|---|---|
| **1. Who and what** | Who makes this, and what do you make? | 1 to 2 sentences | Fernmoor is a two-person pottery studio. [Name] throws every mug and vase on the wheel, and [Name] glazes, packs and answers your messages. |
| **2. Why** | Why did you start? | 1 to 3 sentences | We started Fernmoor because we wanted mugs that feel good to hold every morning: a wide handle, a thick rim and a size that fits a full coffee. |
| **3. How it is made** | What is it made of, and who does what? | 2 to 4 sentences | Each piece is made from stoneware clay, glazed in our own colours and fired twice in our kiln. Because every piece is made by hand, the speckles and glaze lines are a little different on each one. |
| **4. What to expect** | When will it arrive, how is it packed, how do I care for it? | 2 to 3 sentences | Orders are made to order and ship in 5 to 7 working days, wrapped in recycled paper and a gift box. All mugs are dishwasher and microwave safe. |
| **5. Next step** | What should I do now? | 1 sentence | Want a custom set or a different colour? Send us a message on Etsy and tell us what you have in mind. |

The demo is about 140 words. Etsy allows up to 5,000 characters, but 120 to 300 words is plenty for most shops. Buyers skim, so the first two sentences do most of the work.

Fill-in version:

```
[Shop name] is [one person / a team of X] making [what you make] in [place or "a home studio"].
[Who] [does what].

We started [Shop name] because [the real reason, one idea a buyer can picture].

Each [item] is made from [materials], [main steps]. [Who helps, including any production partner.]
[Why each piece may look a little different, if that is true.]

[Item] ships in [X to Y] working days, packed in [packaging]. [Care in one line.]

[One next step: a section to browse, or "Send us a message on Etsy for custom orders."]
```

### Photos, video and team
- **5 featured photos:** real ones only. Good picks: hands at work, your workspace, materials, packing an order, the full range. Keep the subject in the middle, because Etsy crops them to 760 x 468 px. Write one short caption each.
- **Video:** a short real clip of making or packing. Use only music you have the rights to.
- **Shop team:** only real people who work on the shop, each with a role and a 1-line bio. If a production partner helps you make items, Etsy asks you to declare it, so say so in your About text too.

### Rules that keep you safe
- **Only true facts.** No made-up awards, press mentions, customer numbers or reviews.
- **Keep buyers on Etsy.** Do not ask buyers to pay or order outside Etsy. Etsy's fee rules do not allow it.
- **Match your listings.** The processing time and care notes must be the same in your announcement, About text, listings and policies.
- **Questions through Etsy Messages.** It keeps every order conversation in one place.

### Quick checklist before you save
- [ ] Shop title says what you sell, in 55 characters or less
- [ ] Announcement line 1 is the most important thing right now, with a date if it ends
- [ ] Processing time matches your listings and shipping profiles
- [ ] About text answers who, why, how it is made, what to expect, and the next step
- [ ] Every fact is true, including who makes the items
- [ ] Up to 5 real photos with captions, subject in the middle
- [ ] Shop team shows real people with roles
- [ ] No request to buy outside Etsy
- [ ] A date in your calendar to check it again next month

### Common mistakes
- **A title that only says "Welcome".** It wastes the line that also shows in Google.
- **An old announcement.** "Back from holiday on 3 August" in November makes buyers think the shop is closed.
- **A long life story first.** Put what you make and who makes it at the top. The story comes second.
- **Different delivery times in different places.** Buyers trust the shortest one, then feel let down.
- **Stock photos in the About section.** Buyers want to see the real people and place.
- **Hiding who makes the items.** Be clear about any partner who helps.

A clear title, announcement and About section help buyers trust your shop. They do not guarantee sales or a higher place in search.

---

## 14. Depop and Vinted offer and bundle message templates

**File:** [depop-vinted-offer-bundle-messages.csv](depop-vinted-offer-bundle-messages.csv)

On Depop and Vinted, many sales start with a message: "Is this still available?", a low offer, or "Do you do bundle deals?". A fast, short, polite reply keeps the buyer talking. This file has 14 ready-to-fill replies, a filled demo for each (the made-up shop Fernmoor), live character counts and a tip per message.

### How to use it
1. **Open** the file in Google Sheets (File > Import) or Excel.
2. **Decide your 3 prices** for each item before you list (see the price plan below).
3. **Copy** a template into the **Your message** column and change every **[bracket]**. The **Characters used** column counts it for you.
4. **Save** your finished replies as notes on your phone, so you can paste them in seconds. Mark each row **Y** in the **Done** column.

### Before you list: your 3-price plan
Know your numbers before the first offer comes in. Then you never have to decide in a rush.

| Price | What it means | Demo (Fernmoor wool cardigan) |
|---|---|---|
| **Listed price** | What you show on the listing. Check sold items, not live ones. | £28 |
| **Yes price** | Any offer at or above this, you accept straight away. | £24 |
| **Lowest price** | You never go below this. Say it once, then stop. | £22 |

**Counter rule:** counter close to your yes price, never below your lowest price. Demo: an offer of £12 gets a counter at £24. A second offer of £18 gets "£22 is my lowest price".

### How offers and bundles work on each app
| | **Vinted** | **Depop** |
|---|---|---|
| **Offers** | Buyers can send an offer on one item or a bundle. You can accept, decline or send a counter offer. | Buyers tap **Make offer**. You can accept, counter or decline. Offers end after **24 hours** with no reply. |
| **After you accept** | The buyer can now buy at the offer price, plus postage and the buyer fee. | The buyer has **24 hours** to pay. Until they pay, anyone can still buy at full price. You can accept more than one offer: the first to pay gets it. |
| **Bundle discount** | Turn it on in your profile settings: a % off when a buyer takes more than one of your items. Pro sellers cannot use it. | **Settings > Sell more > Bundles**: a % off 2 or more items, or a postage deal. It applies at checkout by itself. |
| **How buyers bundle** | They add your items to a bundle (up to 100 items from one seller). The parcel size is picked by the app. | They add your items to their bag and check out once. |
| **You send offers** | Reply in chat or with a counter offer. | **Send offer** gives a lower price to people who liked the item. They have 24 hours to buy. |

Apps change these settings from time to time. Check the app's help pages if a menu looks different.

### The 14 replies at a glance
| # | Situation | Demo reply (Fernmoor) |
|---|---|---|
| 1 | Still available: yes | Hi Sam! Yes, it's still available. It's a size M, 54 cm pit to pit, worn twice with no flaws. You can buy it now or send me an offer. |
| 2 | Still available: sold | Hi Sam, sorry, this one has just sold. I have a similar cardigan in size M in oat colour in my shop if you'd like to have a look. |
| 3 | Buyer asks you to hold it | Hi Alex, thanks for asking! I can't hold items, so it goes to the first person who buys. If you're ready, you can buy it now with the Buy button. |
| 4 | Low offer: counter | Thanks for your offer, Jo! The lowest I can do is £24, because it's 100% wool and only worn twice. I've sent you a counter offer at £24. |
| 5 | Low offer: polite no | Thanks for the offer, Jo. I can't go that low on this one, but I'd be happy to accept £24. No worries if it's not for you! |
| 6 | Fair offer: accept (Vinted) | Thanks, Priya! I've accepted your offer of £25. Once you've paid, I'll send it within 2 working days with tracking through Vinted. |
| 7 | Fair offer: accept (Depop) | Thanks, Priya! I've accepted your offer of £25 plus postage. It's yours once you pay within 24 hours. I'll send it within 2 working days. |
| 8 | Second low offer: final price | Thanks, Jo. £22 is my lowest price for this one. It's listed at that price if you change your mind. |
| 9 | Offer a bundle | Hi Mia, I see you liked my wool cardigan and wool scarf. If you take both, I can do £33 for the two (you save £5) and they go in one parcel. |
| 10 | Buyer asks: do you do bundle deals? | Yes! I give 10% off when you buy 2 or more items. Add them to a bundle (Vinted) or your bag (Depop) and the discount shows at checkout. |
| 11 | Low bundle offer: counter | Thanks, Mia! For the 2 items the lowest I can do is £33. That's £5 off the full price, and postage is one parcel. I've sent a counter offer. |
| 12 | Accepted offer, buyer has not paid (Depop) | Hi Priya, just a reminder: your accepted offer of £25 ends in about 6 hours. After that it goes back to the full price. |
| 13 | Buyer wants to pay or chat outside the app | Thanks for asking! I only sell through Vinted, so the payment and the parcel are protected for both of us. You can buy it here with the Buy button. |
| 14 | Thank you after sending | Thanks for buying, Jo! Your wool cardigan is on its way today. Tracking is in the app. If you're happy with it, a review would help my shop. |

Demo prices: cardigan £28, scarf £10, together £38. The fill-in version of every reply is in the CSV.

### 5 rules for every reply
1. **Short.** 1 to 3 sentences, under about 160 characters. Buyers read on their phone.
2. **Name and thanks.** Start with their name and a thank you, even for a low offer.
3. **One fact.** Give one true detail that helps them decide: size, a measurement, condition or fabric.
4. **One next step.** Buy now, send an offer, pay within 24 hours. Never leave them guessing.
5. **Fast.** Reply within a few hours. On Depop an offer ends after 24 hours, and buyers keep scrolling.

### Rules that keep you safe
- **Keep everything in the app.** Never share your phone, email, social media or bank details. Protection only covers sales paid through the app.
- **Never send before it is paid.** Wait until the app shows the item as sold and paid.
- **No pressure tricks.** No fake "someone else wants it" or "last chance". Only true facts.
- **Bundles: weigh them together.** Two items packed can need a bigger parcel. See the [shipping and parcel size cheat sheet](#12-ebay-and-vinted-shipping-and-parcel-size-cheat-sheet).
- **Ask for an honest review.** Never ask for a set number of stars.

### Quick checklist before you reply
- [ ] Listed, yes and lowest price written down for this item
- [ ] Buyer's name used, and a thank you
- [ ] One true fact added (size, measurement, condition or fabric)
- [ ] Counter sent with the app's offer button, not only in chat
- [ ] One clear next step at the end
- [ ] Bundle weighed and parcel size checked before you agree
- [ ] No contact details, links to other sites or payment outside the app

### Common mistakes
- **Ignoring low offers.** A short, friendly counter often turns a low offer into a sale.
- **Saying "lowest price" and then going lower.** Buyers learn to push, and your next "lowest" means nothing.
- **Long replies.** A paragraph about the item's history gets skimmed. Put that in the description.
- **Saying "sold" when it is not.** It confuses buyers, and they may not come back.
- **Holding items for days.** Other buyers cannot buy it, and many holds never pay.
- **Agreeing a bundle price before weighing it.** A bigger parcel can eat the profit.

These replies help you answer buyers faster and more clearly. They do not guarantee a sale.

---

## 15. Shopify size chart template for clothing

**Files:** [shopify-size-chart-template.csv](shopify-size-chart-template.csv) and [shopify-size-chart-snippet.html](shopify-size-chart-snippet.html)

The first question a clothing buyer asks is "Will it fit me?". A clear size chart answers it on the product page. This kit has a fill-in sheet for your measurements (type cm, the inches fill themselves), how to measure each part, fit notes, and a ready HTML table you paste into Shopify. The demo is a linen shirt from the made-up shop Fernmoor.

### How to use it
1. **Open** the CSV in Google Sheets (File > Import) or Excel.
2. **Measure** one finished item in each size, laid flat (see the table below). Type the numbers in the **cm** rows. The **inches** rows work themselves out.
3. **Write** your fit notes in part 4 of the sheet. Only write what is true for your item.
4. **Copy** your numbers into the HTML snippet, replacing the demo numbers, and paste it into Shopify (see "Add it to your Shopify store").

### Garment or body measurements?
Pick one and say which one in the chart title. Buyers get the wrong size when they cannot tell.

| | **Garment measurements** | **Body measurements** |
|---|---|---|
| **What it is** | The clothes, measured flat | The person who wears them |
| **Best for** | Small shops, made to order, resale, one-off items | Big brands with a fixed size system |
| **How buyers check** | Measure a piece they own the same way and compare | Measure their own body |
| **Demo** | Fernmoor linen shirt, size M: chest all round 116 cm | Not used here |

If you only know one, use garment measurements. You can check them yourself with a tape measure.

### How to measure: lay it flat
**Rules for every item**
- Lay it on a table, buttoned and zipped, with no folds. Smooth it out, do not stretch it.
- Use a soft tape measure. Write cm and round to the nearest 0.5 cm.
- Measure the finished item, not the pattern or the label size.
- Measure 2 items of the same size if you can. If they differ, write the smaller number.
- Use the same method on every product, so buyers can compare across your shop.

| Part | How to measure |
|---|---|
| **Chest, pit to pit** | Straight across, 2.5 cm (1 inch) below the armholes, from side seam to side seam |
| **Chest, all round** | Pit to pit x 2 (the sheet does this for you) |
| **Length** | On the back, from the top of the shoulder next to the collar, straight down to the hem |
| **Shoulder** | From one shoulder seam to the other, across the back |
| **Sleeve** | From the shoulder seam to the end of the cuff, along the top of the sleeve |
| **Waist, flat** | Straight across the top of the closed waistband, edge to edge |
| **Hip, flat** | Straight across at the bottom of the zip |
| **Inseam** | From the crotch seam down the inside leg to the hem |
| **Front rise** | From the crotch seam up to the top of the front waistband |
| **Leg opening, flat** | Straight across the hem of one leg |

The sheet has rows for tops (filled with the demo) and for trousers, jeans and skirts (empty, ready for you).

### Demo chart: Fernmoor linen shirt
Garment measurements, measured flat. Numbers show cm / inches.

| Size | Chest, all round | Length | Shoulder | Sleeve |
|---|---|---|---|---|
| XS | 104 / 40.9 | 72 / 28.3 | 44 / 17.3 | 59 / 23.2 |
| S | 110 / 43.3 | 74 / 29.1 | 46 / 18.1 | 60 / 23.6 |
| M | 116 / 45.7 | 76 / 29.9 | 48 / 18.9 | 61 / 24.0 |
| L | 122 / 48.0 | 78 / 30.7 | 50 / 19.7 | 62 / 24.4 |
| XL | 128 / 50.4 | 80 / 31.5 | 52 / 20.5 | 63 / 24.8 |

Demo numbers only. Always use numbers from your own items. 1 inch = 2.54 cm.

### Fit notes that answer "Will it fit me?"
Numbers alone do not tell the whole story. Add 4 to 7 short notes under the chart.

| Note | What to write | Demo (Fernmoor linen shirt) |
|---|---|---|
| **Fit** | How it fits, and what to do for a closer or looser fit | Relaxed fit. For a closer fit, take one size down. |
| **Fabric and stretch** | The fabric, and if it stretches | 100% linen, no stretch. |
| **Between sizes** | Which way to go | Take the larger one for a relaxed look, the smaller one for a neater fit. |
| **Compare with your own** | An easy check at home | Lay a shirt you love flat, measure it the same way, and pick the closest size. |
| **Model info** | Model height and the size they wear (only if true) | Model is 183 cm (6 ft) tall and wears size M. |
| **How exact** | That numbers are measured by hand | Sizes can differ by about 1 cm. |
| **Wash and size** | Care that keeps the size, from the care label | Wash at 30°C and dry flat. |

Use the same fit words on every product: slim, regular, relaxed or oversized.

### Add it to your Shopify store
| Way | Best for | Steps |
|---|---|---|
| **A. One chart for many products** | All products of one type share the same sizes | 1. **Online Store > Pages > Add page**, title "Size chart: linen shirts". 2. Click **Show HTML** (the < > icon), paste the snippet, save. 3. **Online Store > Themes > Customize**, open the product page. 4. In the product information section, add a **Pop-up** or **Collapsible row** block, choose your size chart page, name the link "Size chart". Save. |
| **B. Different charts for different products** | Shirts and jeans need different charts | Do way A once per chart. In the theme editor, create a new product template for each chart and add its block there. Then on each product, choose that template under **Theme template**. |
| **C. One product only** | A single item or a one-off piece | Open the product, click **Show HTML** in the Description box, paste the snippet at the end, save. |

Block names differ by theme. In Dawn and other free Shopify themes, look for **Pop-up** or **Collapsible row**. If your theme has neither, use way C.

The snippet uses inline styles, so it looks the same in most themes. On a phone, the table scrolls sideways inside its own box. Selling on Etsy, eBay, Vinted or Depop too? Type the numbers for that one size as plain text, for example "Pit to pit 58 cm (22.8 in), length 76 cm (29.9 in)". See [section 4](#4-vinted-and-depop-listing-checklist).

### Quick checklist before you publish
- [ ] Chart title says garment or body measurements
- [ ] Size names match your Shopify variant names
- [ ] Every number measured on a real finished item, laid flat
- [ ] cm and inches both shown
- [ ] Pit to pit and all round never mixed up
- [ ] "How we measure" lines under the chart
- [ ] 4 to 7 fit notes, all true
- [ ] Checked on a phone: table readable, scrolls inside its box
- [ ] Size chart link shows near the size picker

### Common mistakes
- **No chart at all.** Buyers guess, or leave to find a shop that shows sizes.
- **Copying a chart from another brand.** Their sizes are not your sizes, and buyers notice when it does not fit.
- **Pit to pit called "chest".** A buyer reads 58 cm as all round, thinks it is far too small, and orders the wrong size or leaves.
- **cm only or inches only.** Half your buyers have to work it out, and many will not.
- **The chart as a photo.** Text in a photo is hard to read on a phone and harder for search engines and AI tools to read. Use the HTML table.
- **Hiding the chart.** Put the link next to the size picker, not at the bottom of the page.

A clear size chart helps buyers pick the right size. It does not guarantee fewer returns or more sales.

---

Want this done for your shop or deck? I do it as a fixed-price project on Upwork: [Hire me on Upwork](https://www.upwork.com/freelancers/~01c18d191d6a95988c)

Built by **Tuli, Satin & Scale**.
