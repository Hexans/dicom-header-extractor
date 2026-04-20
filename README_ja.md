# 🩻 DICOM Header to CSV Extractor

![DICOM Header to CSV Extractor](./og-image.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue.svg)](https://reactjs.org/)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]()

**ブラウザ上で完結する、無料で高速・安全なDICOMヘッダー解析ツール**
アップロード不要。すべての処理はローカルPCのメモリ上で行われるため、医療データのプライバシーは完全に守られます。

🌐 [**Webアプリを利用する（インストール不要）**](https://saito-dicom-header-extractor.netlify.app/)

---

## ✨ 主な機能

- **🛡️ 100% ローカル完結の安全性:** 画像データが外部サーバーに送信されることは一切ありません。オフライン環境と同等の強固なセキュリティを担保します。
- **⚡ 劇的な処理速度:** 数千〜数万件のDICOMファイルを数秒で解析し、CSV化します。
- **📁 フォルダ＆ZIP対応:** フォルダやZIPファイル（ネストされたZIP含む）をそのままドラッグ＆ドロップするだけで読み込めます。
- **📊 スマートな重複排除:** `SeriesInstanceUID` に基づいて自動でシリーズを判別し、代表データを抽出します。
- **📈 撮像パラメータ表の自動生成:** 論文にそのまま貼り付けられるフォーマットで、TRやTE、Pixel Spacingなどの主要パラメータをまとめたクロス集計表をワンクリックで生成・ダウンロードできます。

## 🚀 使い方

1. [Webアプリ](https://saito-dicom-header-extractor.netlify.app/) にアクセスします。
2. 処理モードを選択します（通常は「Accurate Mode」を推奨）。
3. 点線枠内に、DICOMデータを含むフォルダまたはZIPファイルをドラッグ＆ドロップします。
4. 解析が完了したら、プレビュー表を確認して **「CSVダウンロード」** をクリックします。
5. 論文やレポート用の条件表が必要な場合は、**「撮像パラメータ」** タブを開き、コピーまたはCSV保存してください。

## 💖 引用・クレジットのお願い

本ツールは、医学・研究の発展を願い、斎藤 勇哉 (Yuya Saito) によって完全無償で開発・提供されています。もしあなたの研究、論文、ソフトウェア開発、または技術ブログ等でこのツールがお役に立ちましたら、ぜひ引用やクレジット表記をお願いいたします。皆様からの引用実績が、本ツールを将来にわたって無料で提供し、アップデートし続けるための最大の原動力になります。

### 学術研究（論文・学会のポスター発表・プレプリント）:
```text
Saito, Y. (2026). DICOM Header to CSV Extractor [Web application]. Available at: https://saito-dicom-header-extractor.netlify.app/
```

### 開発・メディア（自作ソフトウェア・技術ブログ・ポートフォリオ）:
```text
Data extraction was performed using DICOM Header to CSV Extractor, developed by Yuya Saito (https://saito-dicom-header-extractor.netlify.app/).
```

## 👨‍💻 開発者について

Developed with ❤️ by **斎藤 勇哉 (Yuya Saito)**.

医療・研究コミュニティの皆さまの毎日の作業を少しでも楽にし、医学や研究の更なる発展に貢献したいという願いからツールを開発しています。

- 🔗 [**ResearchGate**](https://www.researchgate.net/profile/Yuya-Saito)
- 🔗 [**researchmap**](https://researchmap.jp/yschinchilla)
- 🔗 [**GitHub (@Hexans)**](https://github.com/Hexans)

## 📄 ライセンス

本プロジェクトは **MIT ライセンス** の下で公開されています。詳細は [LICENSE](LICENSE) ファイルをご覧ください。

---
*免責事項: 本ソフトウェア（DICOM Header to CSV Extractor）は、「現状有姿（As-is）」で提供され、一切の保証はありません。本ソフトウェアは認証された医療機器ではありません。利用者は自己責任において使用するものとします。*
