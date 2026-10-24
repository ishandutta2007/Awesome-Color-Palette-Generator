# Awesome-Color-Palette-Generator

# Top Color Palette Generator Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Color Theory Tools, AI Palette Generation & Self-Hosted Design Utilities*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Color Palette Generators**. These tools help designers and developers create harmonious color schemes—using color theory, AI, or curated collections—to build brand identities, UI systems, and visual designs with confidence.

**Examples** include Adobe Color, Coolors, Paletton, Color Hunt, Khroma, and the open-source leaders Color Hunter and Brand Color Palette Generator (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding subscription limits, and controlling the palette generation pipeline. The open-source landscape is anchored by **Color Hunter** (the Rust-based terminal palette generator with OKLCH perceptual color), **Brand Color Palette Generator** (the Bun-powered WCAG-compliant generator with Colormind AI integration), and **Coolors clones** (Next.js implementations for learning and self-hosting), with **Colormind's free API** providing AI generation for non-commercial use.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[Coolors](https://coolors.co/)** | The most popular palette generator with AI, 10M+ schemes, and export tools. | **Pro subscription** (pricing not displayed in search results; described as a subscription plan to premium features) . | **Free account**: Save up to **10 palettes**, **1 project**, **1 collection**, **5 favorite colors**. Ads displayed. Pro removes ads and unlocks AI, unlimited saves, 10-color palettes, and advanced exports . |
| **[Adobe Color](https://color.adobe.com/)** | Adobe's color wheel and palette tool integrated with Creative Cloud. | **Free** to use online. Saving to Brand Kit requires **Adobe Express Premium** . | **Free**: Create and export palettes online. Brand Kit saving is a premium feature . |
| **[Paletton](https://paletton.com/)** | Classic color scheme designer using RYB color theory with vision simulation. | **Free** (ad-supported). | **Fully free**: All features including color blindness simulation, WCAG contrast checking, and exports (HTML, CSS, LESS, XML, PNG, ACO, GPL) . |
| **[Color Hunt](https://www.colorhunt.co/)** | Curated collection of trending 4-color palettes, community-submitted. | **Free**. | **Fully free**: Browse, create, and submit palettes. No account required for browsing . |
| **[Khroma](https://www.khroma.co/)** | AI color tool that learns your preferences and generates infinite palettes. | **Free** (no paid tier reported). | **Fully free**: Train the neural network, generate unlimited palettes, search, and save to an unlimited library . |
| **[Colormind](http://colormind.io/)** | Deep learning palette generator trained on photographs, movies, and art. | **Free** for web use. **API**: free for personal/non-commercial; commercial use requires contact . | **Fully free**: Web generator with daily dataset rotation. API free for non-commercial use . |
| **[Canva Color Palette Generator](https://www.canva.com/colors/color-palette-generator/)** | Palette extraction from uploaded images within Canva's ecosystem. | Included with **Canva Free** or **Canva Pro**. | **Canva Free**: **1 palette** with up to **3 colors** . More palettes require Pro/paid plans . |

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
