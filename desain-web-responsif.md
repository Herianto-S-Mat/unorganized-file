# Resume Course Responsive Web Design FreeCodeCamp 2022

Course ini terdiri dari 20 proyek, yang terdiri dari 5 sertifikasi dan 15 proyek latihan. Berikut adalah daftar seluruh proyek dalam course ini:

| No. | Nama Proyek (Project Name) | Tipe | Teknologi & Konsep Kunci |
| :-- | :--- | :--- | :--- |
| 1 | Learn HTML by Building a Cat Photo App | Praktik | HTML Dasar, Elemen Teks, Tautan, Gambar, Daftar, Formulir Dasar |
| 2 | Learn Basic CSS by Building a Cafe Menu | Praktik | CSS Dasar, Selektor, Properti Warna & Font, Model Box (Dasar) |
| 3 | Learn CSS Colors by Building a Set of Colored Markers | Praktik | Model Warna (RGB, HEX), Gradien CSS |
| 4 | Learn HTML Forms by Building a Registration Form | Praktik | Formulir HTML Lanjutan, Tipe Input, Atribut Formulir, Aksesibilitas Dasar |
| <span style="color: red"> | Build a Survey Form | Sertifikasi | Aplikasi HTML & CSS, Desain Formulir, Elemen Formulir Interaktif |</span> |
| 5 | Learn the CSS Box Model by Building a Rothko Painting | Praktik | CSS Box Model (Margin, Padding, Border, Width, Height) |
| 6 | Learn CSS Flexbox by Building a Photo Gallery | Praktik | CSS Flexbox, Tata Letak Fleksibel, Penjajaran Item |
| 7 | Learn Typography by Building a Nutrition Label | Praktik | Tipografi Web, Hirarki Visual, Properti Font Lanjutan |
| 8 | Learn Accessibility by Building a Quiz | Praktik | Aksesibilitas Web (WAI-ARIA), HTML Semantik, Kontras Warna |
| <span style="color: red"> | Build a Tribute Page | Sertifikasi | Aplikasi HTML & CSS, Tata Letak Halaman, Desain Responsif Dasar |</span> |
| 9 | Learn More About CSS Pseudo Selectors By Building A Balance Sheet | Praktik | Pseudo-Class & Pseudo-Element CSS, Selektor Tingkat Lanjut |
| 10 | Learn Intermediate CSS by Building a Picasso Painting | Praktik | Positioning, Stacking Context (z-index), Transformasi CSS |
| 11 | Learn Responsive Web Design by Building a Piano | Praktik | Media Queries, Desain Responsif, Viewport |
| <span style="color: red"> | Build a Technical Documentation Page | Sertifikasi | Tata Letak Dua Kolom, Navigasi Halaman, Flexbox/Grid |</span> |
| 12 | Learn CSS Variables by Building a City Skyline | Praktik | Variabel CSS (Custom Properties) untuk Desain yang Dapat Dipelihara |
| 13 | Learn CSS Grid by Building a Magazine | Praktik | CSS Grid, Tata Letak Berbasis Grid, Penjajaran Item Grid |
| <span style="color: red"> | Build a Product Landing Page | Sertifikasi | Aplikasi Flexbox & Grid, Desain Halaman Marketing, Video Tertanam |</span> |
| 14 | Learn CSS Transforms by Building a Penguin | Praktik | Properti transform (rotate, scale, skew, translate) |
| 15 | Learn CSS Animation by Building a Ferris Wheel | Praktik | Animasi CSS dengan @keyframes dan properti animation |
| <span style="color: red"> | Build a Personal Portfolio Webpage | Sertifikasi | Proyek Puncak, Media Queries, Tata Letak Responsif, Integrasi Proyek |</span> |

 
*proyek berwana merah adalah proyek-proyek yang belum saya pelajari
 
## Breakdown Semua Proyek yang dipelajari

### 1. **Cat Photo App**
**Konsep yang Dipelajari:** HTML dasar, semantic elements, form elements, dan struktur dokumen
**Implementasi Utama:**
```html
<main>
  <h1>CatPhotoApp</h1>
  <section>
    <h2>Cat Photos</h2>
    <img src="cat.jpg" alt="Cat photo">
    <a href="#" target="_blank">cat photos</a>
  </section>
  <section>
    <h2>Cat Lists</h2>
    <ul>
      <li>cat nip</li>
      <li>laser pointers</li>
    </ul>
  </section>
</main>
```

### 2. **Cafe Menu**
**Konsep yang Dipelajari:** CSS dasar, typography, text alignment, dan basic styling
**Implementasi Utama:**
```css
body {
  background-image: url(coffee-beans.jpg);
  font-family: sans-serif;
}

.menu {
  width: 80%;
  background-color: burlywood;
  margin-left: auto;
  margin-right: auto;
  padding: 20px;
}

.item p {
  display: inline-block;
  margin-top: 5px;
  margin-bottom: 5px;
}

.price {
  text-align: right;
  width: 75px;
}
```

### 3. **Colored Markers**
**Konsep yang Dipelajari:** CSS colors, RGB, HSL, gradients, dan color theory
**Implementasi Utama:**
```css
.marker {
  width: 200px;
  height: 25px;
  margin: 10px auto;
}

.red {
  background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
}

.green {
  background: linear-gradient(#55680D, #71F53E, #116C31);
}

.blue {
  background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%), hsl(240, 56%, 42%));
}

.sleeve {
  width: 110px;
  height: 25px;
  background-color: rgba(255, 255, 255, 0.5);
}
```

### 4. **Registration Form**
**Konsep yang Dipelajari:** HTML forms, input types, form validation, dan accessibility
**Implementasi Utama:**
```html
<form method="post" action='https://register-demo.freecodecamp.org'>
  <fieldset>
    <legend>Account info</legend>
    <label for="first-name">Enter Your First Name: 
      <input id="first-name" name="first-name" type="text" required />
    </label>
    <label for="email">Enter Your Email: 
      <input id="email" name="email" type="email" required />
    </label>
    <label for="new-password">Create a New Password: 
      <input id="new-password" name="new-password" type="password" pattern="[a-z0-5]{8,}" required />
    </label>
  </fieldset>
</form>
```

```css
input, textarea, select {
  margin: 10px 0 0 0;
  width: 100%;
  min-height: 2em;
}

input[type="radio"], input[type="checkbox"] {
  vertical-align: middle;
  width: unset;
  margin: 0 0.5em 0 0;
}
```

### 5. **Rothko Painting**
**Konsep yang Dipelajari:** CSS Box Model, borders, positioning, dan artistic layouts
**Implementasi Utama:**
```css
.canvas {
  width: 500px;
  height: 600px;
  background-color: #4d0f00;
  overflow: hidden;
  filter: blur(2px);
}

.frame {
  border: 50px solid black;
  width: 500px;
  padding: 50px;
  margin: 20px auto;
}

.one {
  width: 425px;
  height: 150px;
  background-color: #efb762;
  margin: 20px auto;
  box-shadow: 0 0 3px 3px #efb762;
  border-radius: 9px;
  transform: rotate(-0.6deg);
}

.two {
  width: 475px;
  height: 200px;
  background-color: #8f0401;
  margin: 0 auto 20px;
  box-shadow: 0 0 3px 3px #8f0401;
  border-radius: 8px 10px;
  transform: rotate(0.4deg);
}
```

### 6. **Photo Gallery**
**Konsep yang Dipelajari:** CSS Flexbox, responsive images, dan gallery layouts
**Implementasi Utama:**
```css
.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  gap: 16px;
  max-width: 1400px;
  margin: 0 auto;
  padding: 20px 10px;
}

.gallery img {
  width: 100%;
  max-width: 350px;
  height: 300px;
  object-fit: cover;
  border-radius: 10px;
}

.gallery::after {
  content: "";
  width: 350px;
}
```

### 7. **Nutrition Label**
**Konsep yang Dipelajari:** Typography, spacing, borders, dan data presentation
**Implementasi Utama:**
```css
.label {
  border: 2px solid black;
  width: 270px;
  margin: 20px auto;
  padding: 0 7px;
}

.bold {
  font-weight: 800;
}

.large {
  height: 10px;
}

.medium {
  height: 5px;
}

.small-text {
  font-size: 0.85rem;
}

.calories-info {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}

.left-container p {
  margin: -5px -2px;
  font-size: 2em;
  font-weight: 700;
}
```

### 8. **Quiz**
**Konsep yang Dipelajari:** Accessibility, semantic HTML, form styling, dan ARIA attributes
**Implementasi Utama:**
```html
<form method="post" action="https://freecodecamp.org/practice-project/quiz">
  <section role="region" aria-labelledby="student-info">
    <h2 id="student-info">Student Info</h2>
    <div class="info">
      <label for="student-name">Name:</label>
      <input type="text" name="student-name" id="student-name" />
    </div>
  </section>
</form>
```

```css
@media (prefers-reduced-motion: no-preference) {
  * {
    scroll-behavior: smooth;
  }
}

.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}
```

### 9. **Balance Sheet**
**Konsep yang Dipelajari:** CSS Pseudo-selectors, table styling, dan complex layouts
**Implementasi Utama:**
```css
span[class~="sr-only"] {
  border: 0;
  clip: rect(1px, 1px, 1px, 1px);
  clip-path: inset(50%);
  height: 1px;
  width: 1px;
  position: absolute;
  overflow: hidden;
  white-space: nowrap;
}

tr.data {
  background-image: linear-gradient(to bottom, #dfdfe2 1.845rem, white 1.845rem);
}

tr.total {
  border-bottom: 4px double #0a0a23;
  font-weight: bold;
}

th {
  color: #0a0a23;
  font-size: 1.2rem;
  text-align: left;
  padding-top: 0.3rem;
}
```

### 10. **Picasso Painting**
**Konsep yang Dipelajari:** CSS positioning, z-index, complex shapes, dan artistic layouts
**Implementasi Utama:**
```css
#back-wall {
  background-color: #8B4513;
  width: 100%;
  height: 60%;
  position: absolute;
  top: 0;
  left: 0;
  z-index: -1;
}

#offwhite-character {
  width: 300px;
  height: 550px;
  background-color: GhostWhite;
  position: absolute;
  top: 20%;
  left: 17.5%;
}

.black-mask {
  width: 100px;
  height: 50px;
  background-color: rgb(45, 31, 19);
  position: absolute;
  top: 0;
  left: 50%;
  z-index: 1;
}

.gray-instrument {
  width: 15px;
  height: 40px;
  background-color: rgb(167, 162, 117);
  position: absolute;
  top: 50px;
  left: 125px;
  z-index: 1;
}
```

### 11. **Piano**
**Konsep yang Dipelajari:** CSS pseudo-elements, responsive design, dan interactive layouts
**Implementasi Utama:**
```css
.keys {
  display: flex;
}

.key {
  height: 180px;
  width: 32px;
}

.key.black--key::after {
  background-color: #1d1e22;
  content: "";
  position: absolute;
  left: -18px;
  width: 32px;
  height: 100px;
}

.key.white--key {
  background-color: white;
  position: relative;
}

@media (max-width: 768px) {
  .keys {
    flex-direction: column-reverse;
    align-items: center;
  }
  .key {
    height: 80px;
    width: 100px;
  }
}
```

### 12. **City Skyline**
**Konsep yang Dipelajari:** CSS variables, gradients, complex shapes, dan responsive design
**Implementasi Utama:**
```css
:root {
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699;
  --building-color4: #538cc6;
  --window-color1: #bb99ff;
  --window-color2: #8cd9b3;
  --window-color3: #d98cb3;
  --window-color4: #8cb3d9;
}

.background-buildings, .foreground-buildings {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: flex-end;
  justify-content: space-evenly;
}

.building-wrap {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.bb1 {
  width: 10%;
  height: 70%;
  background: linear-gradient(
    var(--building-color1),
    var(--building-color1) 80%,
    var(--window-color1)
  );
}

@media (max-width: 1000px) {
  .sky {
    background: radial-gradient(
      closest-corner circle at 15% 15%,
      #ccc,
      #ccc 20%,
      #445 21%,
      #223 100%
    );
  }
}
```

### 13. **Magazine**
**Konsep yang Dipelajari:** CSS Grid, responsive typography, dan complex layouts
**Implementasi Utama:**
```css
.main-text {
  display: grid;
  grid-template-columns: minmax(2rem, 1fr) minmax(min-content, 94rem) minmax(2rem, 1fr);
  row-gap: 3rem;
}

.text {
  grid-column: 2;
  font-size: 1.8rem;
  letter-spacing: 0.6px;
  column-width: 25rem;
  text-align: justify;
}

.hero {
  grid-column: 1 / -1;
  position: relative;
}

.image-wrapper {
  display: grid;
  grid-template-columns: 2fr 1fr;
  grid-template-rows: repeat(3, min-content);
  gap: 2rem;
  place-items: center;
}

@media only screen and (max-width: 720px) {
  .image-wrapper {
    grid-template-columns: 1fr;
  }
  .text {
    font-size: 1.6rem;
  }
}
```

### 14. **Ferris Wheel**
**Konsep yang Dipelajari:** CSS animations, transforms, keyframes, dan motion effects
**Implementasi Utama:**
```css
.wheel {
  border: 2px solid black;
  border-radius: 50%;
  margin-left: 50px;
  position: absolute;
  height: 55vw;
  width: 55vw;
  max-width: 500px;
  max-height: 500px;
  animation-name: wheel;
  animation-duration: 10s;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
}

@keyframes wheel {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

.cabin {
  background-color: red;
  width: 20%;
  height: 20%;
  position: absolute;
  border: 2px solid;
  transform-origin: 50% 0%;
  animation: cabins 10s ease-in-out infinite;
}

@keyframes cabins {
  0% {
    transform: rotate(0deg);
  }
  25% {
    background-color: yellow;
  }
  50% {
    background-color: purple;
  }
  75% {
    background-color: yellow;
  }
  100% {
    transform: rotate(-360deg);
  }
}
```

### 15. **Penguin**
**Konsep yang Dipelajari:** CSS transforms, positioning, dan complex shapes dengan CSS
**Implementasi Utama:**
```css
.penguin {
  width: 300px;
  height: 300px;
  margin: auto;
  margin-top: 75px;
  z-index: 4;
  position: relative;
  transition: transform 1s ease-in-out 0ms;
}

.penguin * {
  position: absolute;
}

.ground {
  width: 100vw;
  height: 400px;
  background: linear-gradient(90deg, rgb(88, 175, 236), rgb(182, 255, 255));
  z-index: 3;
  position: absolute;
  margin-top: -58px;
}

.penguin-head {
  width: 50%;
  height: 45%;
  background: linear-gradient(
    45deg,
    gray,
    rgb(239, 240, 228)
  );
  border-radius: 70% 70% 65% 65%;
  top: 10%;
  left: 25%;
  z-index: 1;
}

.penguin:active {
  transform: scale(1.5);
  cursor: not-allowed;
}
```

---

## Konsep Inti Yang Dipelajari Sepanjang Course

### **HTML Semantic Elements**
```html
<header>, <nav>, <main>, <section>, <article>, <aside>, <footer>
```

### **CSS Flexbox**
```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}
```

### **CSS Grid**
```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}
```

### **CSS Animations**
```css
@keyframes example {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

.animated {
  animation: example 2s infinite linear;
}
```

### **Media Queries**
```css
@media (max-width: 768px) {
  .container {
    flex-direction: column;
    padding: 10px;
  }
}
```

### **CSS Variables**
```css
:root {
  --primary-color: #007bff;
  --font-size: 1.2rem;
}

.element {
  color: var(--primary-color);
  font-size: var(--font-size);
}
```

---

## Skill Yang Dikuasai Setelah Menyelesaikan Course

1. **HTML Structure**: Pembuatan struktur website yang semantic dan accessible
2. **CSS Styling**: Styling komprehensif dengan modern CSS techniques
3. **Responsive Design**: Website yang berfungsi optimal di semua device sizes
4. **Layout Techniques**: Menguasai Flexbox dan CSS Grid untuk layout kompleks
5. **Animations**: Membuat animasi dan transisi yang menarik
6. **Form Handling**: Membuat form yang user-friendly dan accessible
7. **Performance Optimization**: Optimasi gambar dan CSS untuk loading yang cepat
8. **Accessibility**: Memahami prinsip-prinsip web accessibility