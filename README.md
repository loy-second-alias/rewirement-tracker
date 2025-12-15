# The Science of Well-Being: Rewirement Workbook

A modern, aesthetic, and privacy-focused digital companion for the [Yale University "The Science of Well-Being"](https://www.coursera.org/learn/the-science-of-well-being) course on Coursera.

## 🧠 The Big Picture

The original workbook for this course is a static PDF. While functional, it lacks the interactivity and visual engagement that often helps with habit formation. This project transforms that static document into a fluid, **Single Page Application (SPA)** contained entirely within one HTML file.

It bridges the gap between academic rigor and personal well-being practice by offering a "Glassmorphism" interface that is calming to use, while ensuring that your personal reflections remain 100% private on your own device.

## ✨ Key Features

* **Zero-Server Architecture:** Runs entirely in the browser. No databases, no tracking, no external servers.

* **Privacy-First:** All data (happiness scores, journal entries) is saved to your browser's `localStorage`.

* **Single-File Portability:** The entire app is a single `.html` file. You can email it, save it to a USB, or run it offline.

* **Dynamic Themes:** Switch between four distinct atmospheres to match your mood:

  * 🌌 **Starry Night** (Deep Purple/Blue)

  * 🏝️ **Neon Miami** (Cyan/Pink)

  * 🌲 **Deep Forest** (Emerald/Lime)

  * 🌅 **Golden Sunset** (Amber/Red)

* **Submission Ready:** Includes a specialized "Export Report" engine that reformats your colorful interface into a clean, academic black-and-white document for PDF submission.

* **Mobile Optimized:** Designed to function like a native app on Android/iOS when added to the Home Screen.

## 🛠️ Technical Philosophy

This project uses a unique "No-Build" architecture to maximize accessibility.

* **Core:** React 18 & ReactDOM (loaded via CDN)

* **Styling:** Tailwind CSS (loaded via CDN)

* **Transpilation:** Babel Standalone (in-browser JSX compilation)

**Why this approach?**
Usually, React apps require complex build chains (Node.js, Webpack, etc.). By using the CDN approach inside a single HTML file, we lower the barrier to entry to zero. Anyone can download the file and run it immediately without being a developer.

## 🚀 How to Use

### On Desktop

1. Download the `rewirement_workbook.html` file.

2. Double-click to open it in any modern browser (Chrome, Firefox, Edge, Safari).

3. Your progress saves automatically as you type or click.

### On Mobile (Android/iOS)

1. Send the file to your phone (or download it directly).

2. Open the file in Chrome (Android) or Safari (iOS).

3. **Android:** Tap the menu (⋮) -> "Add to Home Screen".

4. **iOS:** Tap Share -> "Add to Home Screen".

5. It will now launch like a standalone app.

### Submitting Your Work

1. Complete your tracking for the required weeks.

2. Click the **Print/Export** icon in the top right.

3. The view will strip away the colors and gradients.

4. Select "Save as PDF" in your printer dialog.

## 🔒 Privacy Statement

**Confidence: 100%**
This application does not transmit data to the internet.

* All `localStorage` data resides strictly on the device where the file is opened.

* If you clear your browser cache/data, your workbook progress will be reset.

* To backup your data, simply keep the PDF reports you generate.
