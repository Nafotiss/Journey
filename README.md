a/E:\AI\Journey\v0.2\README.md → b/E:\AI\Journey\v0.2\README.md
+# Journey
+
+A minimalist, aesthetically immersive "ritual tracker" designed to help you cultivate consistency through daily practice.
+
+## 🌿 The Vision
+Evolved from the "Daily Five" concept, **Journey** focuses on the ritual itself. It combines a serene, glassmorphic interface with a focused tracking experience, featuring a monk mascot and a lotus arc to ground the user in their daily journey.
+
+## ✨ Features
+- **Stand-alone Experience:** The entire application is contained within a single HTML file (including all assets, styles, and scripts).
+- **Advanced Persistence:** Version 0.2 introduces a "Sidecar" data architecture (`journey_data.json`), allowing your progress, history, and statistics to persist across different browsers and devices.
+- **Immersive UI:** A custom-built charcoal-slate theme with glassmorphism and subtle micro-interactions.
+- **Auditory Feedback:** Dynamic audio cues that signal completion of rituals.
+- **Customizable Settings:** Granular control over themes, colors, and data links.
+
+## 🚀 Getting Started
+
+### Installation
+1. Clone or download the repository.
+2. Navigate to the `v0.2` directory:
+   ```bash
+   cd v0.2
+   ```
+3. Open `journey_v0.2.html` in any modern web browser.
+
+### Setup & Persistence
+To ensure your data is saved:
+1. Open the **Settings** menu in the app.
+2. Locate the **Data Sidecar** section.
+3. Click **Link Data File** and select `journey_data.json` located in the same folder.
+4. Toggle **Auto-save** to `On`.
+
+*Note: For the best experience, browser-based local files should ideally be served via a local server (e.g., `python -m http.server 8000`), though the application works on the `file://` protocol with the "Link Data File" step.*
+
+## 📂 File Structure
+- `journey_v0.2.html`: The core application (HTML/CSS/JS).
+- `journey_data.json`: The local database for your rituals, history, and settings.
+
+## 🛠️ Development
+- **Current Version:** v0.2
+- **Next Goals:** Further refinement of ritual logic and expanded UI customization.
+
+---
+*Your journey of a thousand miles begins with a single ritual.*
