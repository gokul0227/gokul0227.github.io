# Personal Portfolio Website

A clean, modern, and responsive personal portfolio website built using **only HTML5 and CSS3**. NO JavaScript or frameworks were used.

## Features

- **Responsive Design**: Mobile-first approach, works on all devices.
- **Pure CSS**: Flexbox, Grid, CSS Variables, and CSS-only interactions (Mobile Menu, Hover effects).
- **PWA Ready**: Includes `manifest.json` and `offline.html` fallback.
- **Cross-Browser Compatible**: Works on modern browsers (Chrome, Firefox, Safari, Edge).

## Project Structure

```
portfolio-website/
│
├── index.html          (Home Page)
├── about.html          (About Me & Timeline)
├── skills.html         (Technical Skills & Progress Bars)
├── projects.html       (Project Gallery)
├── contact.html        (Contact Form & Info)
├── offline.html        (PWA Offline Fallback)
├── manifest.json       (PWA Manifest)
├── README.md           (Documentation)
│
├── css/
│   └── style.css       (Global Stylesheet)
│
└── assets/
    ├── images/         (Place your project images here)
    └── icons/          (Place PWA icons here)
```

## How to Use

1. **Unzip** the folder.
2. Open `index.html` in your web browser.
3. **Customize**:
   - Edit the HTML files to update your content (Name, Bio, Projects, etc.).
   - Replace placeholder text and images in `assets/images/`.

## Customization Tips

- **Colors**: Change the colors in `css/style.css` under the `:root` variables:
  ```css
  :root {
      --primary-color: #2563EB;
      --secondary-color: #1F2937;
      /* ... */
  }
  ```
- **Images**: Add your images to the `assets/images` folder and update the `src` attributes in the HTML files.

## Credits

Created by [Your Name]
