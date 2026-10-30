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

More templates are coming soon: a Shopify SEO and AEO fields checklist for every product.

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

Want this done for your shop or deck? I do it as a fixed-price project on Upwork: [Hire me on Upwork](https://www.upwork.com/freelancers/~01c18d191d6a95988c)

Built by **Tuli, Satin & Scale**.
