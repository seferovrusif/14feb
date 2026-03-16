# ❤️ Minimalist Valentine's Day Surprise Page

This project is an elegant, single-page web application designed as a special surprise for Valentine's Day. It features a modern "Glassmorphism" UI, background music, a typewriter effect for personal messages, and a dynamic heart-particle animation system.

## 🚀 Live Demo
You can deploy this project instantly using **GitHub Pages**.

---

## ✨ Key Features
- **Modern UI:** Uses backdrop filters for a sleek "frosted glass" effect.
- **Typewriter Animation:** Messages are revealed letter-by-letter for a personal, romantic touch.
- **Dynamic Particles:** JavaScript-driven heart animation with depth (blur) and scale effects.
- **Fully Responsive:** Optimized for a seamless experience on both mobile and desktop screens.
- **Social Media Ready:** Pre-configured Meta Tags (Open Graph) for professional link previews on WhatsApp, Instagram, and more.

---

## 🛠️ How to Customize

### 1. Change the Message ✍️
Open `index.html` and navigate to the `<script>` section at the bottom to edit your personal message:
- `message`: Your heartfelt long-form text.
- `titleText`: The main heading (e.g., "My Dear Love,").

### 2. Change the Music 🎵
1. Upload your music file (e.g., `music.mp3`) to the root directory of your repository.
2. Ensure the filename matches the source tag in the HTML:
   ```html
   <source src="music.mp3" type="audio/mpeg">
3. Change the Preview Image (WhatsApp/Social Media) 🖼️
To customize the thumbnail image that appears when you share the link:

Upload your image (e.g., sekil.png) to your repository.

Update the og:image meta tag in the <head> section:

HTML
<meta property="og:image" content="[https://yourusername.github.io/your-repo-name/sekil.png](https://yourusername.github.io/your-repo-name/sekil.png)">
🌐 Deployment Instructions
Create a Repository: Start a new repo on GitHub (e.g., valentine-surprise).

Upload Assets: Upload index.html, your music file, and your image to the repo.

Enable GitHub Pages:

Go to Settings > Pages.

Under "Build and deployment", select the main branch and click Save.

Share: Wait a few seconds for the link to go live, then share your unique URL!

📜 Technical Details
Tech Stack: HTML5, CSS3, Vanilla JavaScript.

Typography: Google Fonts (Playfair Display, Poppins).

Animations: CSS Keyframes & JavaScript Intervals.