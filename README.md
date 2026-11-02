# pwa-install

PWA Installation Standard v1.0

Standardized Web App installation configuration using HTML, CSS, JavaScript and Web App Manifest.

Purpose
A minimal reference implementation for configuring and testing Web App installation across supported desktop and mobile platforms.

Features
    Web App Manifest configuration.
    Standardized application icons.
    Favicon configuration.
    Apple Touch Icon support.
    Desktop and mobile installation screenshots.
    Responsive HTML structure.
    Relative paths compatible with GitHub Pages subdirectories.
    Online-only operation (no offline support).


├── index.html
├── manifest.json
├── README.md
│
└── assets/
    ├── css/
    │   └── style.css
    │
    ├── js/
    │   └── app.js
    │
    ├── icons/
    │   ├── favicon-16x16.png
    │   ├── favicon-32x32.png
    │   └── favicon-48x48.png
    │
    └── pwa/
        ├── icons/
        │   ├── icon-192.png
        │   ├── icon-512.png
        │   ├── icon-maskable-512.png
        │   └── apple-touch-icon.png
        │
        └── screenshots/
            ├── desktop.png
            └── mobile.png
