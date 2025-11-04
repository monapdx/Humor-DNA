# 🎭 Humor DNA  
*A fun quiz to identify your humor style and preferences*  

![Humor DNA Banner](https://raw.githubusercontent.com/monapdx/Humor-DNA/refs/heads/main/banner.png)

<p align="center">
  <a href="https://monapdx.github.io/Humor-DNA/">
    <img src="https://img.shields.io/badge/Live_Demo-View_Now-ffb300?style=for-the-badge" alt="Live Demo Badge">
  </a>
  <img src="https://img.shields.io/badge/HTML5-black?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge">
  <img src="https://img.shields.io/badge/CSS3-black?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3 Badge">
  <img src="https://img.shields.io/badge/License-MIT-e91e63?style=for-the-badge" alt="MIT License Badge">
</p>

---

## 🧬 Overview

## Main Screenshot
![Screenshot](https://raw.githubusercontent.com/monapdx/Humor-DNA/refs/heads/main/HumorDNA-screenshot.png)

## Results Screenshot

![Screenshot](https://raw.githubusercontent.com/monapdx/Humor-DNA/refs/heads/main/quiz-results-screenshot.png)

**Humor DNA** is a minimal, visually engaging concept that explores the idea of mapping out your personal comedy style — a creative “DNA test” for humor.  
This demo includes simple setup instructions, clean design, and easily replaceable assets so you can use it as a foundation for your own creative quiz, personality project, or portfolio concept.

---

## 🧩 Features

- Responsive, minimal layout  
- Custom gradient typography (`#e91e63 → #ffb300`)  
- Includes demo image assets for quick setup  
- Easy to replace with your own visuals and text  
- Works seamlessly with GitHub Pages, Netlify, or local hosting

---

## 🖼️ Image Setup

### Folder Structure
```
Humor-DNA/
 ├── index.html
 ├── style.css
 ├── README.md
 └── img/
      ├── humor-dna.png
      ├── demo-image-1.png
      └── demo-image-2.png
```

### Using the Demo Images
By default, `index.html` points to the images included in the `/images` folder:
```html
<img src="img/humor-dna.png" alt="Humor DNA">
```
You can view and modify them freely — they’ll display automatically when you open or deploy the project.

---

### 🧩 Replacing with Custom Images
1. Add your own image files to the `/img` folder.  
2. Use **descriptive filenames** that reflect what each image represents, such as:  
   ```
   img/dry-humor.png
   img/sarcasm-style.png
   img/slapstick.png
   ```
3. Open the HTML file (usually `index.html`) and update the image file names in the `src` attributes:
   ```html
   <img src="img/your-file-name.png" alt="Description of image">
   ```
4. Save your changes, then commit and push to GitHub.

**Tip:**  
Using descriptive file names makes it easier to organize and identify your humor style graphics — especially if you expand the project to include multiple quiz results or personality types.

---

## 🚀 Quick Start

### Option 1: View Online
If you’ve enabled GitHub Pages for your repo, open:
```
https://monapdx.github.io/Humor-DNA/
```

### Option 2: Run Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/monapdx/Humor-DNA.git
   ```
2. Open `index.html` in your browser.

---

## 🎨 Customization

- **Colors:** Edit the gradient in `style.css`:
  ```css
  background: linear-gradient(90deg, #e91e63, #ffb300);
  ```
- **Font:** Adjust font families or sizes directly in the CSS.
- **Text:** Change the tagline (“A fun quiz to identify your humor style and preferences”) inside the HTML file.

---

## 🧠 Inspiration

The concept behind **Humor DNA** blends personality quizzes, minimalist design, and a pop-art club aesthetic.  
It’s ideal for creative developers, designers, or writers who want to showcase interactive or identity-driven web projects.

---

## 🪪 License

MIT License © Ashly Lorenzana 2025  
Free to remix, adapt, and build upon — just credit or link back to this repository if you use it publicly.
