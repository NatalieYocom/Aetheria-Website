# 🌌 Aetheria Visual Identity Specification: Cyber-Etheric Sovereign

* **Target Repositories:** `Aetheria-Website`, `Aetheria-Unity` (UI Shaders & HUD)
* **Design Philosophy:** A mysterious, serene digital sanctuary built on self-sovereign, retro-tech roots.

---

## 🎯 Core Aesthetic Intent

Aetheria does not look like a corporate metaverse or a flat Web3 landing page. It feels like stepping into a private, uncharted layer of the internet—a high-tech haven where power users and close friends meet in quiet, low-noise environments.

* **Ethereal & Deep:** Uses dark, volumetric gradients, glassmorphic containers, and glowing ambient accents instead of harsh flat colors.
* **Functional & Sovereign:** Retains dense, precise data displays, sharp panel borders, and tactile UI elements reminiscent of early-2000s cyber infrastructure.

---

## 🎨 Color Palette & Variables

### Primary Palette (The Void & Energy)
```css
:root {
  /* Backgrounds & Base Layers */
  --bg-void: #070913;          /* Core background - Deep cosmic indigo */
  --bg-surface: #0f1424;       /* Card & panel base */
  --bg-glass: rgba(15, 20, 36, 0.65); /* Glassmorphism background */
  
  /* Borders & Glass Accents */
  --border-glass: rgba(0, 242, 254, 0.15); /* Soft cyan glow border */
  --border-sharp: #1e293b;                 /* Structural container border */

  /* Primary Accent & Glows */
  --accent-cyan: #00f2fe;      /* Primary interactive element / Active state */
  --accent-emerald: #00ff88;   /* System health / Terminal indicators / Approved */
  --accent-violet: #7928ca;    /* Ambient lighting / Secondary highlights */

  /* Text & Typography */
  --text-primary: #f8fafc;     /* Crisp white headings */
  --text-secondary: #94a3b8;   /* Muted gray body text */
  --text-dim: #475569;         /* Subtitles & metadata */
}
