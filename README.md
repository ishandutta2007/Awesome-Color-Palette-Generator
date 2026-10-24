# Awesome-Color-Palette-Generator

## Top Color Palette Generator Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Color Theory Tools, AI Palette Generation & Self-Hosted Design Utilities*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Color Palette Generators**. These tools help designers and developers create harmonious color schemes—using color theory, AI, or curated collections—to build brand identities, UI systems, and visual designs with confidence.



**Examples** include Adobe Color, Coolors, Paletton, Color Hunt, Khroma, and the open-source leaders Color Hunter and Brand Color Palette Generator (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding subscription limits, and controlling the palette generation pipeline. The open-source landscape is anchored by **Color Hunter** (the Rust-based terminal palette generator with OKLCH perceptual color), **Brand Color Palette Generator** (the Bun-powered WCAG-compliant generator with Colormind AI integration), and **Coolors clones** (Next.js implementations for learning and self-hosting), with **Colormind's free API** providing AI generation for non-commercial use.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The digital design and color tooling market is valued at approximately **$10.1B to $10.5B** globally (growing at ~9% CAGR as part of the broader creative software ecosystem). The sector exhibits a **moderately-to-highly concentrated, tiered structure**: massive enterprise ecosystems (Adobe, Canva) dominate broad design workflows through consolidated suites and aggressive AI integration, while specialized, lightweight palette generation remains fragmented across highly popular indie/micro-SaaS utilities and open-source web projects.



## SaaS/Hosted Platforms

| Product | Company Scale (Valuation / Revenue) | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Adobe Color](https://color.adobe.com/)** | **~$100B - $146B Market Cap** (~$23.8B - $26.0B Ann. Revenue) | Adobe's color wheel and palette tool integrated with Creative Cloud. | **$9.99/mo** (Adobe Express Premium individual tier; also bundled with CC paid plans) | **Free forever plan**: Unlimited online color wheel generation & CSS/XML export. (Saving themes to Brand Kit / CC Libraries requires 30-day free trial or Premium plan) |
| **[Canva Color Palette Generator](https://www.canva.com/colors/color-palette-generator/)** | **~$32B - $42B Valuation** (~$3.5B - $4.0B ARR) | Palette extraction from uploaded images and color wheel generator within Canva's ecosystem. | **$15/mo** (or $120/yr billed annually for Canva Pro) | **Canva Free plan**: Extracts 1 palette with up to 4-5 dominant colors per upload; Brand Kit palette storage limited to 1 palette of up to 3 colors. (30-day free trial for Canva Pro) |
| **[Coolors](https://coolors.co/)** | **~$1M - $3M ARR (Est.)** (Profitable solo bootstrapped micro-SaaS; 1.7M+ monthly users) | The most popular palette generator with AI, 10M+ schemes, and export tools. | **$5/mo** (or $3/mo billed annually at $36/yr for Coolors Pro) | **Free forever plan**: Save up to 10 palettes, 1 project, 1 collection, and 5 favorite colors; ad-supported; export limited to standard formats. (No trial required) |
| **[Paletton](https://paletton.com/)** | **Bootstrapped Indie / Private** (Classic ad-supported utility, founded 2002) | Classic color scheme designer using RYB color theory with vision simulation. | **$0/mo** (100% Free, display ad supported) | **Free forever plan**: Unlimited access to all wheel schemes, contrast checks, vision simulations, and multi-format exports (HTML, CSS, LESS, XML, ACO). |
| **[Color Hunt](https://www.colorhunt.co/)** | **Bootstrapped Indie / Private** (Curated side project with 1M+ monthly users) | Curated collection of trending 4-color palettes, community-submitted. | **$0/mo** (100% Free, community-driven) | **Free forever plan**: Unlimited browsing, searching, bookmarking, and custom palette submissions; no account or payment required. |
| **[Khroma](https://www.khroma.co/)** | **Bootstrapped Indie / Private** (Independent AI side project by George Hastings) | AI color tool that learns your preferences and generates infinite palettes. | **$0/mo** (100% Free, no paid tier) | **Free forever plan**: Unlimited AI neural network training (50 color choices), infinite personalized palette generation, and unlimited library saves. |
| **[Colormind](http://colormind.io/)** | **Bootstrapped Indie / Private** (Independent AI project by Jack Qiao) | Deep learning palette generator trained on photographs, movies, and art. | **$0/mo** (Free for web and personal API use; commercial API pricing via custom developer contact) | **Free forever plan**: Unlimited web palette generation with daily dataset rotation; REST API free for personal/non-commercial projects without account signup. |

## Open-Source GitHub Projects



- **[Color Hunter](https://github.com/aprogramq/color-hunter)** [![GitHub Stars](https://img.shields.io/github/stars/aprogramq/color-hunter?style=social&color=white)](https://github.com/aprogramq/color-hunter/stargazers)  

  **The terminal-native palette generator.** MIT licensed. **Six palette generators**: Color Hunter, complementary, analogous, triadic, split-complementary, and Coolors.co-style. **Perceptual color generation** using OKLCH and OKHSL with sRGB gamut mapping. **Features**: keyboard-driven workflow with Vim keys, palette history (100 palettes), clipboard export as CSS/SCSS/Tailwind/SVG/PNG, and HEX/RGB/HSL output with human-readable color names. **Platform**: Linux only (requires Rust 1.88+ and a True Color terminal) . Best for developers wanting a fast, keyboard-first palette generator that lives where they work.



- **[Brand Color Palette Generator](https://github.com/bivex/brand-color-palette-generator)** [![GitHub Stars](https://img.shields.io/github/stars/bivex/brand-color-palette-generator?style=social&color=white)](https://github.com/bivex/brand-color-palette-generator/stargazers)  

  **The WCAG-compliant brand palette generator.** Built with Bun, Semantic UI, and Chroma.js. **13 color generation schemes** including analogous, complementary, triadic, tetradic, and WCAG Accessible mode. **16 brand style presets** (Vibrant, Muted, Neon, Earthy, Tech, etc.). **Accessibility engine**: mathematically calibrated contrast ratios for AA (≥4.5:1) and AAA (≥7:1). **Colormind AI integration** with a local proxy to avoid CORS issues. **Real-world UI preview**: live component cards showing Primary Actions, Light Surfaces, and Dark Mode themes . Best for teams wanting a self-hosted generator that guarantees accessible color combinations.



- **[Coolors Clone (nisargkavi)](https://github.com/nisargkavi/coolors-clone)** [![GitHub Stars](https://img.shields.io/github/stars/nisargkavi/coolors-clone?style=social&color=white)](https://github.com/nisargkavi/coolors-clone/stargazers)  

  **The Next.js learning implementation.** A simplified Coolors clone built with Next.js. Offers color palette generation, exploration of different schemes, and saving preferred colors/palettes for future reference. **Status**: practice project for learning Next.js . Best for developers wanting a reference implementation to build upon or learn from.



- **[Coolors Clone (evergreenx)](https://github.com/evergreenx/coollors)** [![GitHub Stars](https://img.shields.io/github/stars/evergreenx/coollors?style=social&color=white)](https://github.com/evergreenx/coollors/stargazers)  

  **The full-stack Coolors clone.** Built with Next.js, Supabase, Shadcn UI, Tailwind CSS, and Clerk Auth. **Features**: palette generation, saving to Supabase database, authentication, CRUD operations, and export as PNG/PDF/SVG . Best for developers wanting a production-pattern reference with auth and database integration.



- **[Color Magic](https://github.com/moeezahmad-tech/Color-Magic)** [![GitHub Stars](https://img.shields.io/github/stars/moeezahmad-tech/Color-Magic?style=social&color=white)](https://github.com/moeezahmad-tech/Color-Magic/stargazers)  

  **The PHP-based palette explorer.** Features 150+ curated palettes, color theory generation, image-to-palette extraction, hex-to-name lookup, gradients, and favorites. **Tech stack**: PHP, Tailwind CSS, vanilla JavaScript. **Pages**: palette explorer, gradient browser, color name finder, image extraction, and brand color reference . Best for PHP developers wanting a self-hosted palette tool with broad utility features.



### Additional Strong Open-Source Options



- **Rickrack** — Python-based harmonious color generator with 453 stars. Best for programmatic color generation in Python workflows.

- **Chroma.js** — JavaScript color manipulation library underlying many generators. Best as the engine for custom palette applications.

- **Colormind API** — Free REST API for personal/non-commercial use. Best for integrating AI palette generation into open-source projects without building a model from scratch .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **Free tiers vary in usefulness**: Coolors is the most generous with **10 saved palettes, 1 project, and 5 favorites** on a free account , while Canva Free limits to **1 palette with 3 colors** . Paletton, Color Hunt, Khroma, and Colormind are genuinely free without account limits.

- **AI palette generation is available free through Colormind**: the web generator is free, and the API is free for personal/non-commercial use—commercial applications require contacting the developer .

- **Open-source generators are niche tools, not full platforms**: Color Hunter is terminal-only (Linux); Brand Color Palette Generator requires Bun and a self-hosted server; Coolors clones are learning projects rather than production-ready products. Match the tool to your workflow.

- **Coolors Pro pricing is not publicly listed** in search results—verify current rates on the site before subscribing .



---



**Made for designers, developers, and anyone building color systems with confidence.**  

Let's make color palette generation more open, accessible, and perceptually grounded.
