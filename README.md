# 🩻 DICOM Header to CSV Extractor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue.svg)](https://reactjs.org/)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]()

**A free, fast, and 100% secure online tool to extract DICOM headers and tags into CSV.** Runs entirely locally in your browser—no data is ever sent to external servers.

🌐 **[Try the Web App Here](https://saito-dicom-header-extractor.netlify.app/)**

![App Screenshot](https://saito-dicom-header-extractor.netlify.app/og-image.png)

> 🇯P **[日本語のREADMEはこちら (Japanese README)](README_ja.md)**

---

## ✨ Key Features

- **🛡️ 100% Local & Secure:** All DICOM parsing is done on your local machine using JavaScript. No medical data is ever uploaded to the internet, ensuring complete HIPAA/GDPR compliance.
- **⚡ Insanely Fast:** Capable of processing thousands of DICOM files in seconds.
- **📁 Drag & Drop Support:** Simply drop folders or `.zip` files (even nested ones!) directly into the browser.
- **📊 Smart Deduplication:** Automatically groups files by `SeriesInstanceUID` and extracts representative metadata.
- **📈 Acquisition Parameters Table:** Instantly generates a clean, APA-style cross-tabulation table of key imaging parameters (TR, TE, Pixel Spacing, etc.) ready for your academic papers.

## 🚀 How to Use

1. **Access the App:** Go to [DICOM Header to CSV Extractor](https://saito-dicom-header-extractor.netlify.app/).
2. **Select Mode:** - **Fast Mode:** (Best for standard datasets) Extracts only the first file of each folder.
   - **Accurate Mode:** Scans all files and deduplicates by SeriesInstanceUID.
3. **Drop Files:** Drag and drop your DICOM folders or ZIP archives into the designated area.
4. **Download:** Review the extracted metadata table and click **"Download CSV"**.
5. **View Parameters:** Switch to the **"Acquisition Parameters"** tab to view, reorder, and copy key imaging conditions for your research paper.

## 💖 Citation & Support

This tool is developed and provided entirely for free. If this tool saves you time and contributes to your research, software, or articles, **please consider citing it**. Your citations serve as a tangible track record of my contribution to the medical/research community, which directly motivates the continuous development of free tools.

### For Academic Papers, Conferences, Preprints (APA Format):
```text
Saito, Y. (2024). DICOM Header to CSV Extractor [Web application]. Available at: [https://saito-dicom-header-extractor.netlify.app/](https://saito-dicom-header-extractor.netlify.app/)
