# Sankalpify - Online Learning Platform

Welcome to the official repository for the **Sankalpify** website. Sankalpify is a modern, responsive single-page web application designed to showcase and offer online courses in leading technologies like Data Science, AI, and Machine Learning.

## 🚀 Live Demo

**(Link to your live GitHub Pages site will go here)**

## ✨ Features

  * **Single Page Application (SPA):** A smooth, app-like experience with JavaScript-powered navigation, eliminating page reloads.
  * **Fully Responsive Design:** A clean and modern interface that looks great on all devices, from mobile phones to desktops.
  * **Dynamic Page Content:** Sections for Home, Course Listings, Gallery, and the Team are loaded dynamically.
  * **Engaging UI/UX:**
      * Stunning hero section with a gradient text effect.
      * Subtle on-scroll animations powered by the AOS (Animate On Scroll) library.
      * A professional and attractive color palette.
  * **Dark/Light Mode Theme:** Easily switch between themes with a dedicated toggle button. The selected theme is saved in the user's browser for future visits.
  * **Detailed Course Pages:** Each course has a dedicated page with a comprehensive syllabus, pricing, and a direct link for enrollment.

## 🛠️ Tech Stack

  * **HTML5:** For the core structure and content.
  * **Tailwind CSS:** For a utility-first, modern styling approach.
  * **JavaScript (ES6):** For all interactivity, including the SPA routing, theme switching, and animations.
  * **AOS (Animate On Scroll) Library:** For engaging scroll-based animations.

## 📂 Project Structure

```
.
├── gallery1.jpg        # Your gallery images
├── gallery2.jpg
├── gallery3.jpg
├── gallery4.jpg
└── index.html          # The main (and only) HTML file for the entire site
```

## 🔧 How to Customize

This project is designed to be easily customizable. All content, including text, images, and course details, is located within the `index.html` file.

### Changing Course Details

To edit course information (like syllabus or pricing), search for the \`\` comment within `index.html`. Each course has a dedicated \`\<div\>\` with an ID like \`page-course-dsa\`. You can edit the text and pricing directly within these sections.

### Updating the Gallery

1.  Place your four image files (e.g., `my_photo.jpg`) in the same root folder as `index.html`.
2.  In `index.html`, scroll to the bottom `<script>` tag and find the `initGallery` function.
3.  Update the `images` array with your filenames:
    ```javascript
    // === EDIT THIS ARRAY TO CHANGE YOUR GALLERY PHOTOS ===
    const images = [ 'your_image_1.jpg', 'your_image_2.png', 'your_image_3.jpg', 'your_image_4.jpeg' ];
    // =====================================================
    ```

### Updating the Enrollment Link

The "Register Now" buttons link to a Google Form. To change this link:

1.  Search for `https://docs.google.com/forms/d/e/1FAIpQLSeojCeISaPTHJvp87ivPM9PA31QqBUAoIxglE9ILmRHD1OAjw/viewform?usp=dialog` in the `index.html` file.
2.  Replace this URL with your new link in all 5 locations.

## 🚀 Deployment

This project is a static website, making it incredibly easy to deploy.

### Deploying with GitHub Pages

1.  Push the entire project folder to a new GitHub repository.
2.  In your repository's settings, go to the "Pages" tab.
3.  Under "Build and deployment," select the source as **"Deploy from a branch."**
4.  Choose the branch your code is on (e.g., `main`) and the folder as `/ (root)`.
5.  Click **"Save."** Your website will be live at the provided URL in a few minutes.

## 🙏 Acknowledgements

  * **Tailwind CSS** for the modern CSS framework.
  * **AOS Library** for the beautiful scroll animations.
  * **Unsplash** for the high-quality stock images used throughout the site.
