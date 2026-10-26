---
title: Lens theme documentation
---

Lens is a clean, conversion-focused theme for direct-to-consumer brands built around a hero product, with the catalog tools to scale to hundreds of products. This guide covers setup, every section and the main theme settings.

> Support: onair.tecnologies+lens-shopify@gmail.com

## 1. Get started

1. In your Shopify admin go to **Online Store → Themes**, then **Add theme** and upload or install Lens.
2. Click **Customize** to open the theme editor.
3. Open **Theme settings** (the paintbrush icon) and set your logo, colors, fonts and buttons.
4. Use the page selector at the top of the editor to edit each template: Home, Products, Collections, Cart, Blog, Pages, Search, 404.

Lens works without JavaScript for browsing, filtering, variants and checkout. JavaScript adds the cart drawer, predictive search, instant filtering and the media lightbox.

## 2. Theme settings

| Group | What you control |
|---|---|
| **Logo and favicon** | Logo image and width, favicon. |
| **Colors** | Background, text, product stage, button and shadow colors. Sections can pick a color scheme, so you can alternate light and dark bands. |
| **Typography** | Heading and body fonts, font size scales, uppercase headings, label letter spacing. |
| **Layout** | Page width, section spacing scale, grid gap. |
| **Buttons and corners** | Corner radius, button shape, primary and secondary styles, uppercase labels. |
| **Product cards** | Image aspect ratio and fit, text alignment, vendor, rating, color swatches, quick add, shadow, second image on hover. |
| **Badges** | Sale badge style and sold-out badge. |
| **Cart** | Drawer or page, cart note, complementary products, free shipping threshold. |
| **Social media** | Facebook, Instagram, TikTok, YouTube, X, Pinterest and Snapchat links. |
| **Animations** | Reveal sections on scroll, zoom images on hover (reveal respects the visitor's reduced-motion setting). |

## 3. Sections

### Home page
- **Slideshow** — hero images or video with headline and buttons; separate mobile image per slide.
- **Trust bar** — short reassurance items (shipping, returns, warranty) with icons.
- **Featured product** — a complete product buy box on the home page, with price, variants and add to cart.
- **Featured collection** — product grid from one collection.
- **Product bundle** — bundle several products with a combined add to cart.
- **Icon columns**, **Multicolumn**, **Image with text**, **Rich text** — benefit and story blocks.
- **Video** — hosted or YouTube/Vimeo video.
- **Testimonials**, **Collapsible content** (FAQ), **Email signup**, **Blog posts**, **Collection list**.
- **Custom Liquid** and **Apps** — add your own code or app blocks.

### Header, footer and global
- **Announcement bar** — rotating messages, with optional language and country selectors.
- **Header** — logo, menu with optional mega menu, search, account and cart.
- **Footer** — link lists, text, image, newsletter and social blocks, plus payment icons and localization.

### Product page
**Product information** is built from blocks you can reorder: text (vendor, SKU), title, price, rating, variant picker (buttons, swatches or dropdown), quantity, buy buttons (Shop Pay and dynamic checkout), inventory status, description, collapsible rows, icon row, share, complementary products, pop-up and Custom Liquid.
Also on the page: **Media gallery** (thumbnails or stacked, zoom, video and 3D), **Sticky add to cart**, **Related products** and **Pickup availability**.

### Collections and search
- **Product grid** with filters (drawer or sidebar), sorting and pagination.
- **Collection banner**, **Collections list**.
- **Search results** with predictive search in the header.

### Cart
- **Cart drawer** or **cart page**, discounts, order notes, **Cart recommendations** and selling plan (subscription) support.

### Other pages
Blog and article pages, contact form, 404, password page, gift card page.

## 4. Common tasks

**Change colors.** Theme settings → Colors, and pick a *Color scheme* in each section for light or dark bands.

**Show a sold-out product correctly.** Nothing to do: Lens disables add to cart, hides accelerated checkout and shows "Out of stock".

**Enable filters.** Shopify admin → Online Store → Navigation → Collection and search filters. Choose drawer or sidebar in the collection section.

**Add a size chart or shipping info to products.** Add a *Collapsible row* block to Product information.

**Subscriptions.** Install a selling plan app, assign plans to products; Lens shows the plan picker and cart details.

## 5. Accessibility and performance

- Keyboard navigable, visible focus, ARIA labels on icon buttons, color contrast verified in tests.
- Responsive images with `srcset`, lazy loading below the fold, first image prioritized.
- Small payload: about 110 KB of theme CSS and JavaScript on the home page.

## 6. Support

Contact: onair.tecnologies+lens-shopify@gmail.com. Include your store URL and a description or screenshot of the issue. See also the [support page](support).
