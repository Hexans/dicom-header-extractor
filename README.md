# 🩻 DICOM Header to CSV Extractor

![DICOM Header to CSV Extractor](./og-image.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue.svg)](https://reactjs.org/)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]()

**A free, fast, and 100% secure online tool to extract DICOM headers and tags into CSV.** Runs entirely locally in your browser—no medical data is ever sent to external servers.

🌐 [**Launch the Web App Here**](https://saito-dicom-header-extractor.netlify.app/) (No installation required)

> 🇯🇵 [**日本語のREADMEはこちら (Japanese README)**](README_ja.md)

---

## ✨ Key Features

- **🛡️ 100% Local & Secure:** All DICOM parsing is performed on your local machine using JavaScript. No medical data is ever uploaded to the internet, ensuring complete HIPAA/GDPR/APPI compliance.
- **⚡ Insanely Fast:** Capable of processing thousands of DICOM files in seconds.
- **📁 Drag & Drop Support:** Simply drop folders or `.zip` files (even nested ones!) directly into the browser.
- **📊 Smart Deduplication:** Automatically groups files by `SeriesInstanceUID` and extracts representative metadata.
- **📈 Acquisition Parameters Table:** Instantly generates a clean, APA-style cross-tabulation table of key imaging parameters (TR, TE, Pixel Spacing, etc.) ready to be copied into your academic papers.

## 🚀 How to Use

1. **Access the App:** Go to [DICOM Header to CSV Extractor](https://saito-dicom-header-extractor.netlify.app/).
2. **Select Mode:**
   - **Fast Mode:** Extracts only the first file of each folder (best for standard datasets).
   - **Accurate Mode (Recommended):** Scans all files and deduplicates by SeriesInstanceUID.
3. **Drop Files:** Drag and drop your DICOM folders or ZIP archives into the designated area.
4. **Download:** Review the extracted metadata table and click **"Download CSV"**.
5. **View Parameters:** Switch to the **"Acquisition Parameters"** tab to view, reorder, and download key imaging conditions.

## 💖 Citation & Support

This tool is developed and provided entirely for free by Yuya Saito to contribute to the advancement of medical research. If this tool saves you time and contributes to your work, **please consider citing it**. Your citations serve as a tangible track record of my contribution to the community, which directly supports the continuous development of this tool.

### For Academic Research (Papers, Conferences, Preprints):
```text
Saito, Y. (2026). DICOM Header to CSV Extractor [Web application]. Available at: https://saito-dicom-header-extractor.netlify.app/
```

### For Development & Media (Software, GitHub, Tech Blogs, Portfolios):
```text
Data extraction was performed using DICOM Header to CSV Extractor, developed by Yuya Saito (https://saito-dicom-header-extractor.netlify.app/).
```

## 👨‍💻 About the Developer

Developed with ❤️ by **Yuya Saito**.

I am passionate about creating tools that streamline workflows in the medical and research fields and aim to support the global community's progress. Feel free to connect with me!

* 🔗 [**ResearchGate**](https://www.researchgate.net/profile/Yuya-Saito)
* 🔗 [**researchmap**](https://researchmap.jp/yschinchilla)
* 🔗 [**GitHub (@Hexans)**](https://github.com/Hexans)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

*Disclaimer: This software is provided "AS IS", without any warranties. It is not a certified medical device. Use at your own risk.*
