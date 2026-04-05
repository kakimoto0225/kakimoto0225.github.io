# 🏠 柿本源心 — 個人ホームページ

> 京都大学経済学部 経営学科 4年 柿本源心の個人ホームページ

[![GitHub Pages](https://img.shields.io/badge/Live%20Site-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://kakimoto0225.github.io/homepage/)

📖 **English version of this README**: [README_en.md](./README_en.md)

---

## 🔗 ホームページへのアクセス

以下のリンクをブラウザにコピー＆ペーストして開いてください：

| 言語 | URL |
|---|---|
| 🇯🇵 **日本語版** | **https://kakimoto0225.github.io/homepage/** |
| 🇬🇧 **English** | **https://kakimoto0225.github.io/homepage/index_en.html** |

> 💡 上記リンクをクリック、またはブラウザのアドレスバーにコピーするだけでアクセスできます。

---

## 📌 概要

このリポジトリは、柿本源心の研究活動・プロフィールをまとめた **個人ホームページ** のソースコードです。  
日本語版と英語版の2つのページで構成されており、GitHub Pages で公開しています。

---

## 🎯 サイトの特徴

| 特徴 | 説明 |
|---|---|
| 🌙 **ダークテーマ** | 夜景写真に合わせた高級感のあるダークUIデザイン |
| 🪟 **グラスモーフィズム** | 半透明のガラス風カードUIで統一されたモダンなデザイン |
| ✨ **パーティクルアニメーション** | ヒーローセクションに浮遊する光の粒子（CSS only） |
| 📱 **完全レスポンシブ** | デスクトップ・タブレット・スマートフォンに対応 |
| 🌐 **日英バイリンガル** | 日本語 / English の切り替え対応 |
| 🎞️ **スクロールアニメーション** | IntersectionObserver による要素のフェードイン |

---

## 🗂️ ディレクトリ構成

```
homepage/
├── index.html                  # 日本語版トップページ
├── index_en.html               # 英語版トップページ
├── README.md                   # このファイル（日本語版README）
├── README_en.md                # 英語版README
├── assets/
│   ├── css/
│   │   └── style.css           # メインスタイルシート（ダークテーマ・アニメーション含む）
│   └── images/
│       ├── profile_large.jpg   # ヒーローセクションの縦長プロフィール写真
│       ├── profile_small.jpg   # プロフィールカード用写真
│       ├── face.jpg            # ヒーローアバター用の顔写真
│       ├── hobby_movie.jpg     # 趣味：映画
│       ├── hobby_baseball.jpg  # 趣味：野球
│       └── hobby_orienteering.jpg  # 趣味：オリエンテーリング
└── .github/
    └── workflows/              # GitHub Actions（GitHub Pages デプロイ設定）
```

---

## 🔬 研究関心

- **計量経済学**
- **因果推論**
- **実証産業組織論**
- **機械学習**

---

## 📄 掲載論文

### Fine-tuning llm-jp4 using Japanese financial dataset

日本語の金融データセットを用いた大規模言語モデル（llm-jp4）のファインチューニングに関するプロジェクト。

- **共著者**: [AtsushiYanaigsawa768](https://github.com/AtsushiYanaigsawa768)
- **GitHub**: [kakimoto0225/ft-llm-2026](https://github.com/kakimoto0225/ft-llm-2026)
- **PDF**: Coming Soon
- **Yanagisawaのブログ記事**: [日本語](https://atsushiyanaigsawa768.github.io/mysite/ja/blog/compass/) | [English](https://atsushiyanaigsawa768.github.io/mysite/en/blog/compass/)

> 📝 **今後の研究（Future Works）** — 3つのプロジェクトスロットを準備中です。Coming Soon!

---

## 🏅 資格

| 資格名 | 取得時期 |
|---|---|
| TOEIC 915点 | 2023年9月 |
| データサイエンティスト検定 リテラシーレベル | 2024年3月 |
| 英検 準1級 | 2022年9月 |
| 統計検定 準1級 | 2026年2月 |

---

## 🛠️ 技術スタック

| 技術 | 用途 |
|---|---|
| **HTML5** | セマンティックなページ構造 |
| **CSS3** | カスタムプロパティ、グラスモーフィズム、CSS Grid/Flexbox、キーフレームアニメーション |
| **Vanilla JavaScript** | IntersectionObserver によるスクロールアニメーション |
| **Google Fonts** | Inter / Noto Sans JP |
| **GitHub Pages** | 静的サイトホスティング |

> フレームワークやビルドツールを使用していない、**ゼロ依存**の静的サイトです。

---

## 🚀 ローカルで確認する

1. このリポジトリをクローンします:
   ```bash
   git clone https://github.com/kakimoto0225/homepage.git
   cd homepage
   ```

2. ブラウザで `index.html` を開きます:
   ```bash
   # macOS
   open index.html

   # Windows
   start index.html

   # Linux
   xdg-open index.html
   ```

   または、VS Code の Live Server 拡張機能を使うと、ホットリロード付きで確認できます。

---

## 📬 連絡先

- **GitHub**: [kakimoto0225](https://github.com/kakimoto0225)

---

## 📝 ライセンス

© 2026 Genshin Kakimoto. All rights reserved.
