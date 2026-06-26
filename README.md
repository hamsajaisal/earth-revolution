# Earth's Revolution — The Travelling Sun 🌍🌞

An interactive, highly accessible educational web application designed under the principles of **Universal Design for Learning (UDL)**. It helps high school students (both sighted and blind/visually impaired) explore Earth's 23.5° axial tilt and understand why the subsolar point (direct sunlight) travels between the Tropic of Cancer, the Equator, and the Tropic of Capricorn throughout a single revolution (year).

🔗 **Live Page**: [https://hamsajaisal.github.io/earth-revolution/](https://hamsajaisal.github.io/earth-revolution/) *(Follow setup instructions below to enable the live link!)*

---

## 🌟 Universal Design for Learning (UDL) Features

This app is built from the ground up to support multiple means of representation, engagement, and action:

### 1. For Sighted Students (Visual Representation)
* **Interactive SVG Orbit Diagram**: A clear, smooth visual display showing Earth's position relative to the Sun, axial tilt, and the direct sunlight beam.
* **Color-Coded Latitude Bands**: Tropic of Cancer (blue/cyan), Equator (green), and Tropic of Capricorn (pink) matching throughout the visual readouts.
* **Flexible Modes**: A **Full Mode** for standard detail and a **Simple Mode** that hides extra text to prevent cognitive overload.
* **Bilingual UI**: Fully localized in both **English** and **Malayalam (മലയാളം)**.

### 2. For Blind & Low-Vision Students (Auditory & Non-Visual Representation)
* **Real-time Sonification**: Uses the Web Audio API to translate the Earth's latitude dynamically into a sound frequency (pitch) between 220Hz and 660Hz. As the subsolar point moves North, the pitch rises; as it moves South, the pitch drops.
* **Spoken Narration (Text-to-Speech)**: Integrated narration using the Web Speech API that reads the details of key dates out loud in English or Malayalam with proper voice matching.
* **Accessible Slider Control (`aria-valuetext`)**: The scrubber slider is fully keyboard-accessible and reports the exact date and latitude (e.g., *"June 21. 23.5° north of the Equator, moving south"*) instead of just raw numbers.
* **Throttled Live Announcements (`aria-live`)**: Updates screen readers immediately when entering solstices or equinoxes without spamming announcements.

### 3. Navigation and Control (Action & Expression)
* **Keyboard Navigation**: Press **Arrow Left** or **Arrow Right** anywhere to manually rotate the Earth. All buttons and settings are fully focusable and operable via the keyboard.
* **Responsive Layout**: Designed to adapt fluidly to desktops, tablets, and smartphones.

---

## 🛠️ How to Enable the Live Web Page (GitHub Pages)

To launch this application live on your GitHub account, do the following:

1. Go to your repository settings on GitHub: **[hamsajaisal/earth-revolution Settings](https://github.com/hamsajaisal/earth-revolution/settings)**.
2. In the left sidebar, click on **Pages**.
3. Under **Build and deployment**:
   * **Source**: Select **Deploy from a branch**.
   * **Branch**: Change from `None` to `main`, keep `/ (root)` selected, and click **Save**.
4. Within 1–2 minutes, GitHub will deploy your site to:
   👉 **`https://hamsajaisal.github.io/earth-revolution/`**

---

## 📂 Project Structure

* `index.html` — The single-file web application combining styling (CSS), structure (HTML), and interactivity/accessibility logic (JavaScript).
* `README.md` — This documentation file.

---

*Created for inclusive classroom environments, matching educational curriculums with modern web accessibility guidelines.*
