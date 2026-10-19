# Finca La Zarza — marketing site (v1)

Brand: **Finca La Zarza** (Agost, Spain)  
Product now: Guara almonds (2 kg / 5 kg jute bags). Pickup in Agost only.  
Order via **WhatsApp** (no payment, no contact form).

## Run locally

```bash
cd website
npm install
npm run dev
```

Open the URL Vite prints (usually `http://localhost:5173`).

```bash
npm run build && npm run preview
```

## WhatsApp number

**Placeholder (dummy ES-looking number)** — swap before launch:

```js
// src/main.js — one config constant
const WHATSAPP_E164 = '34600000000' // DUMMY — replace with real E.164 without +
```

Real Spain mobile example: `34612345678`. Links use `https://wa.me/<number>?text=…` with NL/ES prefills for 2 kg / 5 kg + afhalen Agost.

## What’s in v1

- Hero: blossom-macro + Finca La Zarza
- Finca / Agost intro
- Seasonal arc: bloesem → groei → noten → oogst (own photos)
- Products 2/5 kg → WhatsApp CTAs
- Afhalen + WhatsApp order block
- NL (default) + ES toggle
