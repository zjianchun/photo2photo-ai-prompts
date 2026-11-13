# Photo2Photo AI — Image-to-Image Studio Prompts & Strength Benchmarks

[![Live Studio](https://img.shields.io/badge/Live_Studio-photo2photo.io-orange?style=for-the-badge)](https://photo2photo.io)
[![Tools Directory](https://img.shields.io/badge/Tools_Directory-17_Workflows-blue?style=for-the-badge)](https://photo2photo.io/tools)
[![Free Trial](https://img.shields.io/badge/Free_Trial-3_No_Sign_Up-green?style=for-the-badge)](https://photo2photo.io/image-to-image-ai-free)

Open reference dataset and benchmark guide for the **17 zero-prompt image-to-image studio workflows** running on [Photo2Photo AI](https://photo2photo.io) (powered by **FLUX.1 Kontext Pro** and **ByteDance Seedream 5.0 Flash**).

Explore the interactive browser studio: **[https://photo2photo.io](https://photo2photo.io)**  
Browse all 17 workflows visually: **[Photo2Photo AI Tools Directory](https://photo2photo.io/tools)**

---

## Visual Transformations (Before → After Showcase)

| Workflow | Output Sample | Open Tool |
| :--- | :---: | :--- |
| **AI Outfit Changer** | ![Burgundy Leather Jacket Try-On](https://photo2photo.io/assets/demo/real/outfit-beauty-after.webp) | [Try AI Outfit Changer](https://photo2photo.io/ai-outfit-changer) |
| **AI Hairstyle Changer** | ![French Bob Haircut Simulation](https://photo2photo.io/assets/demo/real/hair-beauty-bob-after.webp) | [Try AI Hairstyle Changer](https://photo2photo.io/ai-hairstyle-changer) |
| **Professional Headshot AI** | ![LinkedIn Executive Headshot](https://photo2photo.io/assets/demo/real/headshot-beauty-after.webp) | [Try Professional Headshot AI](https://photo2photo.io/professional-headshot-ai) |
| **Image Input Generator** | ![Golden Hour Tropical Portrait](https://photo2photo.io/assets/demo/real/beach-beauty-after.webp) | [Try Multi-Photo Reference Studio](https://photo2photo.io/ai-image-generator-with-image-input) |

---

## 17 Calibrated Studio Presets & Transformation Strengths

Full structured JSON export is included in [`data/presets-and-recipes.json`](./data/presets-and-recipes.json).

| Preset Name | Preset ID | Default Strength | Purpose | Studio Link |
| :--- | :--- | :---: | :--- | :--- |
| **Character Consistency** | `character-consistency` | `0.65` | Keep the face & outfit, switch the scene | [Launch Preset](https://photo2photo.io/?preset=character-consistency#workbench) |
| **Sketch to Realistic** | `sketch-to-realistic` | `0.8` | Line art / clay model to realistic photo | [Launch Preset](https://photo2photo.io/?preset=sketch-to-realistic#workbench) |
| **3D / Clay Style** | `3d-clay` | `0.7` | Photo to 3D blind-box or game asset | [Launch Preset](https://photo2photo.io/?preset=3d-clay#workbench) |
| **Anime Style** | `anime-style` | `0.7` | Real photo to high-quality anime | [Launch Preset](https://photo2photo.io/?preset=anime-style#workbench) |
| **Product Background Swap** | `product-background` | `0.55` | Studio lighting, clean pedestals & shadow grounding | [Launch Preset](https://photo2photo.io/?preset=product-background#workbench) |
| **Old Photo Restore & Colorize** | `photo-restore` | `0.6` | Repair scratches, restore color | [Launch Preset](https://photo2photo.io/?preset=photo-restore#workbench) |
| **Professional Headshot** | `professional-headshot` | `0.6` | Selfie to LinkedIn-ready portrait | [Launch Preset](https://photo2photo.io/?preset=professional-headshot#workbench) |
| **Layered 3D Papercraft** | `papercraft-3d` | `0.75` | Tactile paper cutouts, shadowbox depth & relief art | [Launch Preset](https://photo2photo.io/?preset=papercraft-3d#workbench) |
| **Photo Remix Diptych** | `photo-diptych` | `0.7` | Split-panel comparison poster: photo on top, stylized art below | [Launch Preset](https://photo2photo.io/?preset=photo-diptych#workbench) |
| **Retro Risograph Poster** | `vintage-poster` | `0.75` | Vintage screenprint & poetic editorial art | [Launch Preset](https://photo2photo.io/?preset=vintage-poster#workbench) |
| **Editorial Lifestyle Magazine** | `editorial-magazine` | `0.65` | Vogue & GQ style cinematic lighting | [Launch Preset](https://photo2photo.io/?preset=editorial-magazine#workbench) |
| **Product Poster Proposals** | `product-poster-batch` | `0.7` | One product, 8 poster styles — Amazon & Shopify ready | [Launch Preset](https://photo2photo.io/?preset=product-poster-batch#workbench) |
| **Photo to Sketch & Line Art** | `photo-to-sketch` | `0.75` | Turn photos into pencil sketches & ink drawings | [Launch Preset](https://photo2photo.io/?preset=photo-to-sketch#workbench) |
| **Photo to Coloring Page** | `photo-to-coloring-page` | `0.8` | Printable pure B&W outlines for kids & adults | [Launch Preset](https://photo2photo.io/?preset=photo-to-coloring-page#workbench) |
| **AI Outfit & Clothes Changer** | `ai-outfit-changer` | `0.65` | Virtual outfit try-on with 1:1 facial lock | [Launch Preset](https://photo2photo.io/?preset=ai-outfit-changer#workbench) |
| **AI Hairstyle & Color Try-On** | `ai-hairstyle-changer` | `0.6` | Test haircuts, bangs & hair colors on your photo | [Launch Preset](https://photo2photo.io/?preset=ai-hairstyle-changer#workbench) |
| **Anime to Real Life AI** | `anime-to-real-life` | `0.7` | 2D anime & cartoon characters to real human photos | [Launch Preset](https://photo2photo.io/?preset=anime-to-real-life#workbench) |

---

## Strength Calibration Guidelines

- **`0.55 – 0.60` (Identity & Edge Lock)**: Best for [Product Background Swap](https://photo2photo.io/ai-product-background), [Professional Headshot AI](https://photo2photo.io/professional-headshot-ai), [AI Hairstyle Changer](https://photo2photo.io/ai-hairstyle-changer), and [Old Photo Restoration](https://photo2photo.io/old-photo-restore). Keeps package typography, facial landmarks, and brow lines stable.
- **`0.65 – 0.70` (Structural Remix)**: Ideal for [Consistent Character AI](https://photo2photo.io/consistent-character-ai), [AI Outfit Changer](https://photo2photo.io/ai-outfit-changer), [Photo to 3D Clay AI](https://photo2photo.io/photo-to-3d-clay-ai), [Photo to Anime AI](https://photo2photo.io/photo-to-anime-ai), and [Anime to Real Life AI](https://photo2photo.io/anime-to-real-life-ai). Re-drapes clothing and translates shaders without identity drift.
- **`0.75 – 0.80` (Line Extraction & Sketch Synthesis)**: Calibrated for [Photo to Sketch & Line Art](https://photo2photo.io/photo-to-sketch), [Photo to Coloring Page](https://photo2photo.io/photo-to-coloring-page), and [Sketch to Image AI](https://photo2photo.io/sketch-to-image-ai).

---

## Complete Landing Page Index (18 Pages)

- [AI Hairstyle Changer — Try New Haircuts & Colors on Your Photo](https://photo2photo.io/ai-hairstyle-changer) (`preset: ai-hairstyle-changer`)
- [AI Image Converter — Transform Photos into Any Style in Seconds](https://photo2photo.io/ai-image-converter) (`preset: anime-style`)
- [AI Image Generator from Image — Multi-Photo Reference Studio](https://photo2photo.io/ai-image-generator-with-image-input) (`preset: character-consistency`)
- [AI Photo Editor & Image Changer — Free Online, No Sign Up](https://photo2photo.io/ai-image-to-image) (`preset: character-consistency`)
- [AI Outfit Changer — Virtual Clothes Try-On in Seconds](https://photo2photo.io/ai-outfit-changer) (`preset: ai-outfit-changer`)
- [AI Product Photography — Commercial E-Commerce Studio](https://photo2photo.io/ai-product-background) (`preset: product-background`)
- [Anime to Real Life AI — Turn Any Character into a Real Person](https://photo2photo.io/anime-to-real-life-ai) (`preset: anime-to-real-life`)
- [Consistent Character AI Generator — Same Character, Every Scene](https://photo2photo.io/consistent-character-ai) (`preset: character-consistency`)
- [Image to Image AI Generator — Free Photo to Photo Studio](https://photo2photo.io/) (`preset: character-consistency`)
- [Image to Image AI No Sign Up — Free Instant Generator](https://photo2photo.io/image-to-image-ai-free) (`preset: sketch-to-realistic`)
- [Nano Banana AI — Fast Image Editing, Free to Try](https://photo2photo.io/nano-banana-ai) (`preset: character-consistency`)
- [Old Photo Restoration AI — Restore, Sharpen & Colorize](https://photo2photo.io/old-photo-restore) (`preset: photo-restore`)
- [Photo to 3D Clay AI — Cute Blind-Box & Claymation Toy Filter](https://photo2photo.io/photo-to-3d-clay-ai) (`preset: 3d-clay`)
- [Photo to Anime AI — Turn Any Photo into Anime Free](https://photo2photo.io/photo-to-anime-ai) (`preset: anime-style`)
- [Turn Any Photo into a Printable Coloring Page](https://photo2photo.io/photo-to-coloring-page) (`preset: photo-to-coloring-page`)
- [Photo to Sketch & Line Art — Turn Pictures into Drawings](https://photo2photo.io/photo-to-sketch) (`preset: photo-to-sketch`)
- [AI Headshot Generator — Your Selfie, Now a Professional Headshot](https://photo2photo.io/professional-headshot-ai) (`preset: professional-headshot`)
- [Sketch to Image AI — Turn Drawings into Realistic Photos](https://photo2photo.io/sketch-to-image-ai) (`preset: sketch-to-realistic`)

- [Transparent Pay-As-You-Go Pricing](https://photo2photo.io/pricing) (Starts at $9.90, Credits Never Expire, 100% Automatic Refund on Failed Generations)

---

## Architecture Stack

- **Frontend / Edge**: Next.js 15 App Router deployed on Cloudflare Pages (`@cloudflare/next-on-pages`)
- **Storage & Ledger**: Cloudflare R2 ephemeral reference image storage + Cloudflare D1 atomic credit ledger
- **Client-Side Compression**: Browser-side WebP resizing (`maxEdge: 2048px`, `quality: 0.88`) reducing median upload time under 400ms
- **Inference Gateways**: Fast Tier (Seedream 5.0 Flash) & Studio Pro Tier (FLUX.1 Kontext Pro)

---

## License

MIT License — see [`LICENSE`](./LICENSE). Dataset maintained by [Photo2Photo AI](https://photo2photo.io).
