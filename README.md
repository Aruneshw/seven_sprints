# மெய்ப்பொருள் — திருக்குறள் 423 (Seven Sprints)

> **"எப்பொருள் யார்யார்வாய்க் கேட்பினும் அப்பொருள்  
> மெய்ப்பொருள் காண்பது அறிவு."**  
> — *திருக்குறள் (அறிவுடைமை, குறள் 423)*

An immersive, cinematic, and mobile-adaptive experiential web application exploring the profound wisdom of **Thirukkural 423**. Built for interactive storytelling, inquiry-based learning, and philosophical discovery.

---

## 🌟 Overview & Experiential Journey

This application takes the user through seven distinct interactive chapters ("Seven Sprints"), translating classical Tamil literary philosophy into a modern sensory web experience:

1. **தொடக்க நிலை (Prologue)**: Atmospheric awakening with breathing visuals, ambient light, and natural audio soundscapes.
2. **கேள் (Listen)**: Narrative vignette illustrating how rumors and unexamined assertions spread in human society.
3. **சிந்தி (Reflect)**: Deep reflection challenging the instinct to trust authority blindly rather than examining facts.
4. **வினா (Inquire)**: Interactive tripartite inquiry mechanism (**பார்**, **வினா**, **ஆராய்**).
5. **குறள் (The Seven Words & Palm Leaf)**: Interactive exploration of each of the seven words with automated cadence, progressing into the sacred sliding palm-leaf manuscript (**ஓலைச்சுவடி**) adhering to classical Tamil Venba meter (4 words + 3 words).
6. **ஆராய் (Analyze & Discern)**: Contextual decision-making quiz evaluating true cognitive discernment.
7. **புரிந்து கொள் (Synthesize)**: Interactive word-reconstruction jumble puzzle assembling the kural into its authentic prosodic order.
8. **மெய்ப்பொருள் (Epiphany)**: Realistic stylus-and-manuscript engraving animation revealing the culmination: **மெய்ப்பொருள் காண்பது அறிவு**.

---

## 🛠️ Technical Architecture & Stack

| Technology / Component | Details & Implementation |
| :--- | :--- |
| **Core Architecture** | Pure Vanilla Web Stack (Zero external frameworks, ultra-fast bundle size) |
| **Markup (HTML5)** | Semantic HTML5 structure, accessible ARIA roles, modern viewport metadata (`width=device-width, initial-scale=1`) |
| **Styling (CSS3)** | Modular Vanilla CSS, CSS Custom Properties (`--gold`, `--paper`, `--ink`), Glassmorphism, CSS Grid, and Flexbox |
| **Responsive Design** | Fluid typography using `clamp()`, dynamic viewport height (`100dvh`), dedicated breakpoints (`@media (max-width: 768px)` and `@media (max-width: 380px)`) |
| **JavaScript (ES6+)** | Native ES6 modules, hash routing (`#kel`, `#sindhi`, `#vina`, `#kural`, `#quiz`, `#jumble`, `#final`), event delegation, dynamic state machine |
| **Audio Pipeline** | YouTube IFrame API integration with interactive ambient audio control and single-play policy |
| **Typography** | Google Fonts — **Noto Serif Tamil** (literary elegance) & **Noto Sans Tamil** (interface clarity) |
| **Visual Assets** | High-fidelity heritage illustrations, palm leaf manuscript textures, and particle firefly canvas simulations |

---

## 📱 Mobile Responsiveness & Adaptability

The application is engineered to be fully mobile-adaptive:
- **Zero Horizontal Overflow**: All containers, text blocks, and palm leaves fit strictly within screen boundaries.
- **Dynamic Viewport (`100dvh`)**: Immune to address-bar shrinking and expanding on mobile browsers (Safari iOS, Chrome Mobile).
- **Touch-Friendly Controls**: Touch targets meet WCAG standards with minimum tap areas and generous hit states.
- **Responsive Palm Leaf**: Gracefully adapts from multi-column desktop layouts to stacked, readable classical 4+3 metrical formats on mobile displays.
- **Interactive Word Jumble**: Touch-optimized chips that wrap naturally on small screens without breaking layout integrity.

---

## 🚀 Running the Project Locally

No compilation or build step is required:

```bash
# Clone the repository
git clone https://github.com/Aruneshw/seven_sprints.git

# Navigate to the project directory
cd seven_sprints

# Serve using any static server or Python
python3 -m http.server 3000
# or using npx
npx serve .
```

Open `http://localhost:3000` in your web browser.

---

## 👥 Team Information

- **Team Name**: `zeropi`
- **Team Members**:
  - **HARISH RAGHAVENDRA M**
  - **ARUNESHWARAN K**

---

## 📄 License

This project is licensed under the **MIT License**.

```text
MIT License

Copyright (c) 2026 zeropi (HARISH RAGHAVENDRA M, ARUNESHWARAN K)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
