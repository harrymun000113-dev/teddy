# Code Style Guidelines
- Indentation: 2 spaces
- Quotes: Single quotes (')
- Naming: camelCase for variables, PascalCase for components
- Strict Typing: Always use TypeScript interfaces in `src/types/`


I want to design a webpage high quality bear is walking across the screen horizontally and is a pixel world. there is a red roof house, and bear is coming out from the forest then reach the house. the bear is medium sized, father of two. now before you make the code. can you make me markdown.md

Your requested design specification document has been created:

MD 아이콘
markdown
 MD 
Document Summary
Below is a preview of the specification outline contained inside markdown.md:

Pixel Art Web Design Specification: The Father Bear's Journey
1. Overview & Concept
An interactive, high-quality 16-bit retro pixel scene featuring a medium-sized father bear (father of two) taking his journey home across the screen.

Start: Dense pixel forest on the left.

Path: Rolling green meadow with parallax background.

Destination: Cozy pixel house with a bright red roof and glowing windows on the right.

2. Visual Style & Color Palette
Pixel Style: Crisp 16/32-bit pixel art styled with CSS image-rendering: pixelated;.

Palette:

Sky: Warm Sunset Gradient (#1D2B53 → #7E2553 → #FFA300)

Forest: Deep Greens (#004035, #008751)

House: Bright Red Roof (#FF004D), Warm Wood (#FFF1E8), Glowing Yellow Window (#FFEC27)

Father Bear: Warm Brown (#733E39), Honey Tan (#B66F43), equipped with a subtle pixel scarf/tie.

3. Scene Parallax Layers
Background: Sunset sky & pixel clouds.

Far Midground: Distant pixel mountain range.

Midground: Dense forest edge (left) → Red-roofed home (right).

Foreground: Walking path, grass tufts, and the animated Father Bear.

4. Technical Implementation Plan
HTML5 Canvas / CSS3 animations with responsive integer pixel scaling.

Smooth frame-by-frame sprite animation with horizontal translation.

Interactive triggers (chimney smoke on hover, bear reaction on click).

Whenever you are ready, let me know and I will generate the complete HTML/CSS/JavaScript code for this webpage!




Gemini는 AI이며 인물 등에 관한 정보 제공 시 실수를 할 수 있습니다. 개인 정보 보호 및 Gemini새 창에서 열기

분석 중
# Pixel Art Web Design Specification: The Father Bear's Journey

## 1. Overview & Concept
This web page features an interactive, high-quality pixel art animation of a medium-sized father bear (father of two) walking horizontally across a retro pixel landscape. 

The story flows visually from left to right:
- **Starting Point:** A dense, lush pixel forest (representing work/the wild).
- **The Journey:** Moving across a gently rolling grassland/path.
- **Destination:** A cozy, warm house with a bright red roof (home where his two cubs await).

---

## 2. Visual Style & Color Palette

### 🎨 Pixel Art Aesthetic
* **Canvas Style:** 16-bit / 32-bit retro pixel aesthetic with clean line art, rich dithering, and smooth frame-by-frame animation.
* **Aspect Ratio:** Full-screen responsive viewport (`100vw` x `100vh`).

### 🌈 Color Palette
* **Sky & Atmosphere:**
  * Top Sky: `#1D2B53` (Deep Twilight Blue)
  * Middle Sky: `#7E2553` (Warm Sunset Magenta)
  * Horizon: `#FF004D` / `#FFA300` (Warm Golden Glow)
* **Environment & Forest:**
  * Foreground Grass: `#00E436` / `#008751`
  * Forest Canopy / Trees: `#004035`, `#052F27`, `#008751`
  * Dirt Path: `#AB5236`, `#5F574F`
* **The Red Roof House:**
  * Roof: `#FF004D` (Bright Crimson Red)
  * Walls: `#FFF1E8` (Soft Cream Wood) / `#C2C3C7` (Stone accents)
  * Chimney & Smoke: Warm grey puff particles
  * Glowing Window: `#FFEC27` (Warm Yellow Light)
* **Father Bear Character:**
  * Fur Primary: `#733E39` (Deep Bear Brown)
  * Fur Highlights: `#B66F43` (Warm Honey Tan)
  * Snout & Belly: `#FFCCAA`
  * Details: Small blue dad necktie / scarf (subtle character touch indicating fatherhood)

---

## 3. Character Design: Father Bear

* **Size:** Medium frame, sturdy build, friendly silhouette.
* **Attributes:**
  * Wearing a small pixel scarf/tie or carrying a little pixel basket/fish for his cubs.
  * Expressive walking cycle (4 to 8 frames of animation).
* **Movement Dynamics:**
  * Smooth horizontal traversal (`X: 0vw` $\rightarrow$ `X: ~75vw`).
  * Subtle vertical bobbing (`bounce`) while walking.

---

## 4. Scene Layout & Layers (Parallax Depth)

| Layer | Depth | Elements | Motion Speed |
| :--- | :--- | :--- | :--- |
| **Layer 0 (Background)** | Rear | Sky Gradient, Pixel Sun/Moon, Soft Clouds | Stationary / Ultra Slow |
| **Layer 1 (Far Midground)**| Far | Distant Pixel Mountain Silhouettes | Slow (`0.2x`) |
| **Layer 2 (Midground)** | Middle | Dense Forest (Left), Red Roof House (Right) | Medium (`0.5x`) |
| **Layer 3 (Foreground)** | Near | Path, Flowers, Animated Father Bear, Grass Tufts | Primary focus (`1.0x`) |

---

## 5. Technical Stack & Implementation Strategy

### 🛠️ Core Technologies
* **HTML5 Canvas / CSS3 Grid:** Webpage layout and frame rendering.
* **CSS Animations / JavaScript (GSAP or RequestAnimationFrame):** Smooth frame sequence playback and horizontal progression.
* **Pixel Rendering:** CSS `image-rendering: pixelated;` to ensure sharp pixel edges across high-DPI displays.

### 📜 Technical Feature Requirements
1. **Responsive Pixel Scaling:** Uses fixed pixel resolution canvas with integer scaling (`transform: scale(N)`).
2. **Interactive Elements:**
   * Hovering over the house lights up the window and sends smoke from the chimney.
   * Clicking the bear makes him do a happy roar/wave animation.
3. **Audio (Optional):** Subtle 8-bit ambient nature sounds and soft footstep sound effects.

---

## 6. Next Steps
- Finalize HTML structure & CSS styling.
- Create SVG/Canvas-based pixel sprites for the bear, forest, and red-roof house.
- Implement JavaScript motion loop for horizontal walking.