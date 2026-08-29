# 🌸 Code-a-Pookkalam

An interactive **Onam flower rangoli (pookkalam)** generator, built entirely with HTML, CSS, and SVG — no frameworks, no dependencies.

Design your own digital pookkalam by customizing petal count, swirl, spin speed, and color palette, then download it as a clean SVG file.

---

## ✨ Features

- 🌼 **Fully generative SVG design** — layered rings, a swirled outer pinwheel flower, and a two-tone starburst inner flower, all drawn procedurally
- 🎛️ **Live controls**
  - **Petals** — adjust the number of petals (6–12)
  - **Swirl** — control how much the outer flower bends into a paisley pinwheel
  - **Spin speed** — set the design spinning, from still to a slow rotation
- 🎨 **Multiple color palettes** — Onam, Marigold, Lotus, and Kerala themes
- 🎲 **Randomize** — instantly generate a new design with one click
- 🖱️ **Click-to-reshape** — tap the pookkalam itself to cycle its petal count
- ⬇️ **Export as SVG** — save your design and use it anywhere

---

## 🚀 Live Demo

_Add your live link here once deployed, e.g._
👉 [irfanfarisf.github.io/code-a-pookalam](https://irfanfarisf.github.io/code-a-pookalam)

---

## 🖥️ Running Locally

No build step, no dependencies — just open the file.

```bash
git clone https://github.com/irfanfarisf/code-a-pookalam.git
cd code-a-pookalam
```

Then simply open `index.html` in your browser, or serve it locally:

```bash
python3 -m http.server 8000
```

and visit `http://localhost:8000`.

---

## 🛠️ Tech Stack

- **HTML5** — structure
- **CSS3** — theming, layout, and animations
- **Vanilla JavaScript** — all SVG rendering logic, no libraries
- **SVG** — every ring, band, and petal is drawn programmatically at render time

---

## 📂 Project Structure

```
code-a-pookalam/
└── index.html   # entire app: markup, styles, and generative SVG logic
```

---

## 🎨 How It Works

The pookkalam is built as a series of concentric SVG layers, drawn from the outside in:

1. Base disc + colored ring bands (green, dashed, yellow, orange, maroon)
2. An outer **pinwheel flower** — swirled wedge petals that bend based on the "swirl" control
3. A small connecting ring
4. An **inner starburst flower** — pointed, two-tone petals radiating from the center
5. A **bullseye center** — layered concentric circles

All colors are pulled from the active palette, and every shape recalculates live as you move a slider or click a swatch.

---

## 🙌 Credits

Built for Onam, inspired by traditional Kerala pookkalam (flower rangoli) designs.

## 📄 License

Feel free to fork, remix, and use this project for your own Onam celebrations!
