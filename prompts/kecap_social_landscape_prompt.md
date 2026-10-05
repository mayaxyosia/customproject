# Prompt: Kecap Social Landscape (category competitive report)

Reverse-engineered from `Kecap_Social_Landscape.html` (HypeAuditor agent report `dentsu-kecap-2026-10`).
Paste everything below the line into the agent. To reuse it for another category, change only the **INPUTS** block.

---

You are a senior social-intelligence analyst at a media agency. Using HypeAuditor data (TikTok and Instagram brand accounts, creator posts, creator audience profiles, hashtag search and Instagram brand-mention history), build a **competitive category landscape report** as one self-contained HTML page for a client deck.

## INPUTS

- **Prepared for:** dentsu
- **Category:** Soy sauce (kecap), Indonesia
- **Core question (cover headline topic):** Who wins attention in kecap on TikTok and Instagram?
- **Brands and handles** (with brand colour):
  | Brand | Primary handle | Other handles | Colour |
  |---|---|---|---|
  | Kecap ABC | @kecapabc.id | @abc_ahlinyabuatcitarasa (master brand TikTok/IG, shared with Sambal ABC) | #c8323f |
  | Bango | @bangowarisankuliner | | #007a00 |
  | Kecap Indofood | @kecap_indofood | | #4a3aa7 |
  | Kecap Sedaap | @kecapsedaapid | | #2a78d6 |
- **Listed hashtags to health-check:**
  - Kecap ABC: #kecapabc #abchitammanis #hitmankenaja #kecapabchitammanis #ahlinyabuatcitarasa #abcahlinyabuatcitarasa
  - Bango: #kecapbango #waktuindonesiamasakpakaibango #wimb #semurbango #bukabersamalika #kecapmanisbango
  - Kecap Indofood: #kecapmanisindofood #muanisgurihnyabikinnaiklevel #muanisgurihbikinnaiklevel #kecapindofood
  - Kecap Sedaap: #kecapsedaap #semuakebagiansedaapnya #kecapsedaapkedelaihitamspecial #pestakulinersedaap #satukecapnyaberagamsedaapnya #pestakulinersedaapmalang #pestakulinersedaapbanjarbaru #lebarankecapsedaap
- **Analysis window:** last 90 days (3 Jul – 1 Oct 2026)
- **Trend baseline:** Instagram quarterly, Q1 2025 – Q3 2026 (7 quarters); TikTok month by month inside the window, plus 12-month follower growth of each brand account
- **Data date:** 2 October 2026
- **Category keyword set (for the unbranded / whitespace read):** kecap, kecap manis, kecap asin and close variants, on TikTok and Instagram
- **Language:** write in English; quote captions and hooks in the original Bahasa Indonesia

## DEFINITIONS (use exactly, and state them in the report)

- **Brand content** = the brand's own posts + every creator post that tags, hashtags or names the brand. A creator = any non-brand account.
- **Share of views (SoV), share of engagement (SoE), share of content (SoC)** across the four brands. Engagement = likes + comments + shares (+ saves where available).
- **ER** = engagements ÷ views.
- **Likely amplified\*** = a post with > 100K views and ER < 0.5%. Report it as "a pattern consistent with paid amplification", never as fact.
- **Creator tiers:** Mega 1M+ · Macro 100K–1M · Micro 10K–100K · Nano < 10K followers.
- **Driver index** = share of the top 20% most-engaging creator posts that carry a trait ÷ share of all creator posts that carry it (2.0× = twice as common among winners). Compute separately for TikTok and Instagram, for: territory, creator tier, opening line (hook) type. Flag small bases.
- **Instagram earned reach\*** = HypeAuditor estimated reach of creator and media posts that tag the brand or use its hashtags. **Estimated engagement\*** = followers × average ER × posts, for the 100 largest accounts per quarter. Footnote both with an asterisk wherever they appear.
- **Audience** = audiences of the creator accounts behind each brand's creator content, weighted by the views each creator delivered for the brand. Regional reads come from where each creator is based.
- **Territories** (tag every creator post; a post can have several): Everyday recipes · Family & mom life · Nusantara heritage · Asian fusion · Discovery & novelty · Events · Commerce & promo · Product claims.
- **Creator types:** Home cooks & chefs · Food reviewers & explorers · Entertainers & lifestyle · Moms & family · Media & city pages · Affiliates & sellers.
- **Hook types** (first line of caption/voiceover): Question · Secret / superlative claim · Relatable POV / skit · Price / value · Statement / other.
- **Hashtag types:** Brand · Product · Campaign · Event · Claim · Recipe · Commerce · Generic. Hashtag health status: Active · Low use · Dormant · Hijacked (most recent posts unrelated to the brand).

## REPORT STRUCTURE

Every section has: a numbered eyebrow, an **action title** (the finding, stated as a claim, not a topic label), a one-paragraph dek explaining what is measured, the evidence (charts/tables), and an **insight box** with a bold one-line read, 2–4 sentences of evidence, and a "SO WHAT" line telling the client what to do.

**Cover (dark band).** "Prepared for dentsu", eyebrow "Category landscape · Soy sauce (kecap)", H1 = the core question, lead paragraph listing what is covered, the four brand chips (avatar ringed in brand colour, name, handle), a 4-column meta row (Analysis window · Trend baseline · Platforms · Data date) and a volume line (brand posts, creator accounts profiled, category posts, quarters of history).

**00 Executive summary.** A two-clause headline that captures the central tension (e.g. "X owns the conversation. Y rents the reach."). Four KPI tiles (category views, category engagements, brand posts, IG earned reach Q3 YoY) each with who holds the biggest share. Then 8 numbered findings, each one bold sentence + a number-dense explanation. Then a **scoreboard table**: brand · SoV · SoE · SoC · creator accounts · % engagement from creators · IG earned reach Q3 YoY · a 2–4 word "Read" badge per brand.

**01 Share of voice.** Tabs: TikTok + Instagram / TikTok / Instagram. Per tab: three 100% stacked bars (SoV, SoE, SoC) in brand colours with totals, then a table with views, SoV, engagements, SoE, posts, SoC, accounts posting, % views from creators, % engagement from creators, and a category total row.

**02 Bought vs earned.** Dumbbell chart per brand: share of views (hollow dot) vs share of engagement (filled dot) on a 0–100% axis. Table per brand × platform: brand-owned posts (count, avg views, ER), creator posts (count, avg views, median views, ER), % of views on likely-amplified posts.

**03 Trend 2025 → 2026.** SVG line chart of Instagram earned reach per quarter by brand, and a 100% stacked chart of share of IG earned reach per quarter. Table: Q3 '25 vs Q3 '26 reach and YoY, 9M '25 vs 9M '26 and YoY, posts Q3→Q3, accounts Q3→Q3, est. engagement Q3→Q3, category total. Explain what moved (campaigns, events, tours). Then TikTok small multiples: one panel per brand, Jul/Aug/Sep stacked bars (creator solid, brand-owned tint), own scale per panel, views on the bar, engagements under it. Then TikTok brand account follower growth cards (12-month %, current followers; where growth history is unavailable show followers and video count).

**04 Creator mix.** Per brand: 100% stacked bar of creator posts by tier and a second of creator views by tier. Then per brand a list of the top creator accounts (avatar, platform icon, handle, tier badge, followers, views, engagements). Insight on the different jobs of nano/affiliate vs macro/mega.

**05 Content & creative.** Driver index chart per platform (bars against a 1.0× reference line, grouped by Territory / Creator tier / Opening line, dark = over-index, grey = flat, light = under). Small-base note. Then **8 creative archetypes** as image cards (post thumbnail, brand, role badge such as Reach / Reach (paid) / Engagement / Comments / Local reach / Conversion, archetype name, one-line description, example handle · views · eng., linked to the post). Then a **Hooks** table (hook type, real example quote from the data, which brands use it, TikTok index, IG index) and a **Formats** table (IG Reels / carousels / images %, TikTok brand video length range and median from the latest 8 videos).

**06 Territories.** Heatmap 1: creator type × brand (share of creator views). Heatmap 2: territory × brand (share of creator posts). Then one card per brand: a 3–5 word positioning title, 3 ticked bullets naming the actual creators and lines, mini bars of creator-view share by creator type. Insight: where brands differentiate and collide, and what nobody covers.

**07 Top content.** Per brand: the six most-viewed posts across TikTok and IG, then the two most-engaging creator posts not already shown. Gallery cards: thumbnail, platform icon, view pill, handle, eng. · ER · date, badges (Brand-owned / Creator, Likely amplified\*, tier), 3-line caption excerpt, link to the original post.

**08 Audience.** Summary table per brand: creators profiled / total, % audience in Indonesia vs outside, % female, % under 25, % 25–34, regional creators by region (count). Heatmap of where creators are based (share of creator views: National reach, Jabodetabek, West Java, Central Java & DIY, East Java, Kalimantan, Sulawesi, Bali & NT, Sumatra). Then one card per brand: gender bar, age histogram (13–17, 18–24, 25–34, 35–44, 45+), top 4 audience countries, and a compact top-creators table (followers, % in ID, % female, main age, views). Mark small bases.

**09 Hashtags.** Per brand: top 10 hashtags on brand content (owned + creator) by post count, with type badge, platform icons, posts, views, views per post. Then the **health check of the listed hashtags**: TikTok posts, IG posts, status for the last 90 days. Investigate dormant tags in earlier quarters, misspellings or variant spellings that split the conversation, and generic acronyms hijacked by unrelated trends (state how many of the recent posts are actually the brand's).

**10 Category context & whitespace.** Share of TikTok kecap posts and views, and IG kecap posts, that name none of the four brands (stacked bars). Emerging needs table (low-sugar/diabetic, kids & MPASI, soy-free/allergy, kecap asin usage: posts, views, posts from the big four). Other brands named in kecap posts (posts, views). A dated timeline of the moments the category used in the window (events, national days, campaign waves, sale cycles). Then 5 whitespace cards: title, the evidence line (numbers), the opportunity.

**11 Strategic implications.** State that "Next 90 days" are recommendations, not observed facts. One card per brand with its Read badge and three columns: Where it wins · Where it is exposed · Next 90 days (arrow bullets, concrete actions). Then a numbered 6-point **Category playbook for TikTok**, and a **KPI table** for the ongoing competitive review (KPI, definition, why): engaged share of voice, creator share of views, creator ER, low-ER view share, brand linkage rate.

**Footer.** HypeAuditor wordmark, "Prepared for dentsu · Soy sauce (kecap) category landscape · Data date 2 October 2026 · Confidential".

## WRITING RULES

- Action titles everywhere; the headline is the finding.
- Every sentence carries a number. Use shares, multiples (4.5×), YoY %, medians where averages mislead.
- Compare views with engagement in every competitive read; never crown a brand on views alone.
- Hedge inference correctly ("consistent with paid amplification", "directional", "small base"), and footnote estimated metrics with \*.
- Name real creators, hashtags, campaigns and events; quote real captions and hooks.
- Plain English, short sentences, no filler, no em-dash lists of adjectives.

## DESIGN SPEC

- One self-contained `.html` file. Inter (Google Fonts). Embed avatars and post thumbnails as data URIs; link cards to the original TikTok/Instagram posts. All charts as inline SVG or HTML/CSS, no chart library. A small vanilla-JS tooltip (`data-tip`) on every bar, segment and dot, and a tab switcher for section 01.
- Light theme only, print-like agency report. Canvas `#f7f8fa`, white cards with 1px `#e6e8eb` hairlines, 10px radius, subtle shadow. Ink `#1a1f36`, muted `#5f6b7d`. Primary accent HypeAuditor orange `#f4623a` (strong `#d9481f`, soft `#feefeb`). Good/warn/bad: `#157f3c` / `#a14a07` / `#c8102e` with soft tints. Brand colours as listed in INPUTS, used consistently in every chart.
- One dark cover band (`#161f2e`) with a soft orange radial glow and a faint dot grid; HypeAuditor logo + "Agent" sub-label top left, "Prepared for dentsu" top right.
- Max width 1240px. At ≥1180px a sticky left contents rail (180px) listing sections 00–11 with numbers. Sections separated by hairlines, with a dark numbered chip above each H2 (31px, semibold, tight tracking).
- Components: KPI stat strip (hero value in orange), numbered findings list, insight box (orange-tinted, icon, "SO WHAT" label), 100% stacked bars, dumbbell chart, quarterly line + share charts, small multiples, driver-index bars with a reference line, heatmaps, tier/role/status badges, image card galleries (4:5 archetypes, 3:4 posts), audience cards.
- Responsive to phone width (16px gutters, stacked grids, horizontally scrollable tables/charts), `prefers-reduced-motion` respected, visible focus states, `noindex`.
