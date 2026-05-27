# Comprehensive English to Bengali Kindle Dictionary 📱📚

A high-performance, fully indexed English-to-Bengali (Bangla) translation dictionary built specifically as a system-integrated, instant pop-up lookup utility for Amazon Kindle devices.

---

## 📖 Description

Unlike standard eBooks, this project compiles a massive vocabulary database into a native Kindle dictionary architecture (`.mobi` / dual-format engine). When installed on a Kindle device, it integrates silently into the operating system. Readers can simply press and hold any English word while reading a book, news article, or document, and the precise Bengali meaning will instantly appear in a native pop-up window without interrupting the reading flow.

### Key Features
* **Native System Integration:** Operates directly within the Kindle OS environment.
* **Instant Pop-up Lookup:** Zero-lag translation layout optimized for e-ink displays.
* **Clean Formatting:** Built with customized typography layouts so Bengali scripts and parts of speech render beautifully without breaking fonts.
* **Optimized for Kindle:** Fully compatible with Amazon's proprietary indexing requirements.

---

## 🛠️ Installation & Setup Process

To use this dictionary on your personal Kindle device, follow these quick and easy steps:

### Step 1: Transfer the File to Kindle
1. Connect your **Kindle device** to your computer using a USB data cable.
2. Open your File Explorer (Windows) or Finder (Mac) and navigate to the connected Kindle drive.
3. Locate the folder named **`documents`** at the root level of your Kindle storage.
4. Inside `documents`, open the subfolder named **`dictionaries`**.
5. Copy your generated **`Official-Eng-Bn-Dictionary.mobi`** (or the dual-format file) and **Paste** it directly into this `dictionaries` folder.
6. Safely eject and disconnect your Kindle device from the computer.

### Step 2: Set as Default Lookup Utility
1. Open **any English book** or document on your Kindle.
2. **Press and hold** any English word on the screen until the text highlight and default pop-up dictionary box appear.
3. Tap the **Dictionary Name** or the **Settings icon** located at the bottom-right corner of the pop-up window.
4. Select **"Comprehensive English to Bengali Kindle Dictionary"** from the drop-down list.
5. **Success!** Your Kindle will now prioritize this dictionary, providing automatic English-to-Bengali translations for all future lookups.

---

## 📜 Technical Details

The source code architecture is structured to support Amazon's `kindlegen` framework:
* **Format:** Mobipocket / KF8 Dual-Format eBook Architecture
* **Source Metadata:** Standardized Dublin Core (`dc-metadata`) with targeted dictionary tags:
  * `<DictionaryInLanguage>en-us</DictionaryInLanguage>`
  * `<DictionaryOutLanguage>bn</DictionaryOutLanguage>`
* **Style:** Embedded minimalist `style.css` tailored for Amazon Ember and native e-ink screen readability.

---

## ⚖️ Legal Terms & License

* **Copyright:** © 2026 Bondhon Das. All rights reserved.
* **Usage License:** This source configuration and compiled database are provided strictly for educational and personal deployment use on authorized e-readers. Unauthorized commercial distribution, automated database extraction, or mirroring of this project file without explicit written consent is strictly prohibited.
![Book Cover](cover.jpg)
