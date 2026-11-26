# 🌙 WitchAbe.com - Master Development Grimoire & Core Specifications

## 🏢 1. Brand Identity & Visual Guardrails
*   **Domain**: witchabe.com
*   **Aesthetic Theme**: Modern Witchcraft / Green Magick / Sterile Alchemical Lab.
*   **Strict Category Constraint**: NOTHING involving active mushrooms, live spores, or mycology organisms will ever be sold or listed on this site.
*   **Niche Integration**: Sterile Lab Media, Occult Wares, Botanicals, Subscription Boxes, and a Restricted Apothecary Glass/Headshop.

## 🎨 2. The Core Design System (CSS Variables Palette)
*   **Obsidian Canvas (Background)**: `#0E0E10` (Body Viewports & Wrapper Panels)
*   **Altar Slate (Containers)**: `#161619` (Product Grids & Dropdowns)
*   **Ritual Gold (Primary Accent/CTA)**: `#D4AF37` (Titles, Links, Primary Buttons)
*   **Alchemical Sage (Hover States)**: `#7A9A82` (Button Hovers, Link Hovers)
*   **Ghost Silver (Default Text)**: `#CBD5E1` (High-readability paragraph copy)

## ✒️ 3. Typography Architecture (No Overlapping 'W's)
*   **Brand Logotype**: 'Cinzel Decorative' (Luxury Roman serifs with clean custom W asset)
*   **Headings & Navigation Bar**: 'Rubik' (Clean, normal, bold geometric sans-serif)
*   **Body Copy & Lab Logs**: 'Ubuntu Mono' (Fixed-width sterile typewriter font style)

## 🗂️ 4. Active Database Category Structure (Catalog Tree)
*   **Witchery (The Spirit)**
    ├── Stones & Crystals (Raw clusters, amulets, talismans)
    ├── Ritual & Tools (Altar cloths, candles, incantations)
    ├── Divination (Tarot decks, runes, pendulums)
    └── Esoteric Botanicals (Raw ritual herbs, smudging sage, resins)
*   **Undergrowth (The Earth - Pure Sterile Lab Infrastructure Only)**
    ├── Sterile Lab Media (Pre-poured agar petri dishes, sterile nutrient broths)
    ├── Sterilized Grains & Substrates (Autoclaved whole oats, rye berry bags)
    └── Lab Hardware & Tools (Scalpels, parafilm, inoculation loops, filters)
*   **Apothecary (The Medicine - Controlled Headshop Matrix)**
    ├── Artisan Glassware (Pipes, chillums, display hardware)
    ├── Botanical Vaporizers (Consumption tools)
    └── Storage & Grinders (Apothecary preservation)

## ⚙️ 5. Advanced Backend Requirements (nopCommerce 4.90 Core)
*   **The Coven Box (Subscriptions)**: Native nopCommerce Recurring Product mapped to a 1-Month billing cycle via direct gateway integration (e.g., Stripe).
*   **Discreet Logistics Settings**: Mandatory Checkout Attribute checkbox requiring anonymous brown box shipping configurations with hidden merchant address labels.
*   **Legal Age Gate**: Mandatory Checkout Attribute (Control Type: Checkbox) tied strictly to the `Apothecary` Category ID tree, enforcing a "21+ verification assertion" before routing to the payment terminal.

## 📁 6. Critical Local Code File Directories
*   **Master Variables Palette**: `~/src/Presentation/Nop.Web/Themes/DefaultClean/Content/css/variables.css`
*   **Master Layout Overrides (Phase 3 CSS Semicolon Bug Location)**: `~/src/Presentation/Nop.Web/Themes/DefaultClean/Content/css/witchabe.css`
*   **Platform Document Core Head Template**: `~/src/Presentation/Nop.Web/Themes/DefaultClean/Views/Shared/Head.cshtml`

## 7. WitchAbe Tracker https://docs.google.com/spreadsheets/d/e/2PACX-1vRXyBqekJF7KDCJiBSFCnGMB6nJhO2FZHz7WKpM7JX9zk6MVEPgjQpJXA446ojSXU_Ti5DdNMw1dXVE/pub?output=xlsx
