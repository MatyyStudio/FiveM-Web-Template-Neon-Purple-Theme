# NEON PURPLE - FiveM Server Landing Page

This is a static landing page for a fictional FiveM server called "NEON PURPLE". The page is designed in a modern, futuristic neon/cyberpunk style with an emphasis on visual effects and responsiveness.

## 🚀 Project Goal

The goal was to create a visually appealing and immersive "one-page" website to serve as the main hub and information portal for the server's players. The page introduces the team, key server features, and provides basic statistics.

## 👁️ Preview



*(It's recommended to add a screenshot of the finished page here so visitors can immediately see what it's about.)*

## ✨ Key Features and Sections

The page is divided into several logical sections:

1.  **Navigation:** A fixed navigation bar with a glassmorphism effect that adapts smoothly on scroll. The links point to the different sections of the page.
2.  **Hero Section (`#home`):** A full-screen introductory section with a dynamic background powered by **Particle.js** and a striking headline with a gradient and "glow" animation.
3.  **Team Section (`#team`):** Introduces the team members using cards with an animated border on hover.
4.  **Stats Section:** Displays key statistics (player count, uptime...) that use JavaScript for an animated **counter**, which activates when the section scrolls into view (using `IntersectionObserver`).
5.  **Server Info (`#server`):** A clear breakdown of "Server Details" (IP, status) and "Features" (custom economy, housing, etc.).
6.  **Why Choose Us (`#features`):** A section highlighting the server's three main advantages (Secure, Active, Community) using Font Awesome icons.
7.  **Footer:** Contains social media links and copyright information.

### Technical Highlights

* **Custom Cursor:** The page implements a custom dual cursor (a dot and a circular "follower") for a unique user experience.
* **Neon Effects:** Heavy use of CSS variables (`--neon-purple`, `--neon-pink`) for easy maintenance of the color scheme and implementation of "glow" effects (using `text-shadow` and `box-shadow`).
* **Responsive Design:** Uses the Bootstrap 5 grid and custom `@media` rules to ensure the page looks great on both mobile devices and large monitors.

## 💻 Technologies Used

* **HTML5:** Semantic structure.
* **CSS3:**
    * Custom styles (inline in `<style>`)
    * CSS Variables
    * Flexbox
    * Animations (`@keyframes`) for "glow" and border rotation
* **Bootstrap 5.3.0:** For the grid system and basic components.
* **JavaScript (ES6+):**
    * DOM Manipulation (for the custom cursor and counter)
    * `IntersectionObserver` API to trigger animations on scroll
* **Third-Party Libraries:**
    * **Particle.js:** For the animated background in the hero section.
    * **Google Fonts:** Uses the `Orbitron` (for headings) and `Exo 2` (for text) fonts.
    * **Font Awesome:** For icons in the feature sections and social links.

## 📞 Contact and Support

Although the HTML file has a navigation link for a `#contact` section that isn't present in the body, the main point of contact for support is the official Discord server.

* **Discord:** [Join us on Discord](https://discord.gg/dBvPBQpKEe)

## 🔧 How to Run

Since this is a purely static page with no backend, no complex installation is needed.

1.  **Download the file:** Save the provided `index.html` file (or the entire repository if it were in Git).
2.  **Open in browser:** Double-click the `index.html` file.
3.  **Done!** The page will load locally in your default web browser. All libraries (Bootstrap, Font Awesome, Particle.js) are loaded from a CDN, so an internet connection is required for them to display correctly.

## 📄 Credits

* **Design:** MatyyStudio (according to the footer copyright).
