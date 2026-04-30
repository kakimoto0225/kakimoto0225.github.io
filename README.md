# Genshin Kakimoto Homepage (柿本 源心 個人ホームページ)

京都大学経済学部で学ぶ Genshin Kakimoto（柿本 源心）の個人ホームページのリポジトリです。
自身の研究関心（計量経済学、因果推論、実証産業組織論、機械学習）、進行中のプロジェクト、資格、趣味などを日本語と英語のバイリンガルで掲載・運用しています。

**🌍 公開サイト (Live Site)**
- 日本語版: [https://kakimoto0225.github.io/homepage/](https://kakimoto0225.github.io/homepage/)
- 英語版 (English): [https://kakimoto0225.github.io/homepage/index_en.html](https://kakimoto0225.github.io/homepage/index_en.html)

English repository overview is available here: [README_en.md](./README_en.md)

---

## 🚀 このリポジトリについて

このリポジトリは、GitHub Pages で公開している静的な個人ホームページのソースコードを管理するものです。
フロントエンドはプレーンな HTML と CSS のみで構成しており、ビルドツール（WebpackやViteなど）や外部フレームワーク（ReactやVueなど）に依存しないシンプルかつ高速な設計を採用しています。機能追加やメンテナンスが容易であることが特徴です。

初めて訪れた方は、まず[公開サイト](https://kakimoto0225.github.io/homepage/)を参照いただくことで、全体像を容易に把握できます。GitHub 上では、ページ本文やスタイル、掲載画像、GitHub Actions を用いたデプロイ設定などがどのように実装・管理されているかを確認できます。

## ✨ 主な特徴 (Features)

- **Vanilla HTML/CSS**: 余分な依存関係を持たない軽量な設計。
- **レスポンシブデザイン**: CSS Grid と Flexbox を駆使し、スマートフォン、タブレット、PCなど幅広いデバイスに最適化されたレイアウトを実現。
- **多言語対応 (i18n)**: 日本語用 (`index.html`) と英語用 (`index_en.html`) のページを用意し、シンプルなトグルリンクでの言語切り替えをサポート。
- **CI/CD 自動デプロイ**: GitHub Actions を利用し、`main` ブランチに変更がプッシュされると自動で GitHub Pages に最新版がデプロイされるワークフローを構築。

## 📖 掲載コンテンツ (Contents)

ウェブサイトには主に以下のセクションが含まれています。

1. **Profile (プロフィール)**
   - 所属（京都大学経済学部経済経営学科）、所属ゼミ（柳ゼミ）、GitHub アカウント情報。
2. **Research (研究関心)**
   - 計量経済学、因果推論、実証産業組織論、機械学習といった分野に対する学術的な関心。
3. **Work (論文・プロジェクト)**
   - 現在進行中のプロジェクト（例: 日本語の金融データセット用LLMファインチューニング）や発表論文、関連リンク。
4. **Credentials (資格など)**
   - TOEIC、データサイエンティスト検定、英検、統計検定などの取得資格やスキルセット。
5. **Hobbies (趣味)**
   - 映画鑑賞、野球、オリエンテーリングなど、学業以外の活動風景。

## 📂 ファイル・ディレクトリ構成

```text
homepage/
├── .github/
│   └── workflows/
│       └── pages.yml           # GitHub Pagesへの自動デプロイを設定するCI/CDワークフロー
├── images/                     # サイト内で使用・表示される画像ファイル群
│   ├── face.jpg                # トップのアバター画像
│   ├── profile_large.jpg       # トップの背景画像
│   ├── profile_small.jpg       # モバイル用のプロフィール画像
│   ├── hobby_movie.jpg         # 趣味紹介用の画像 (映画)
│   ├── hobby_baseball.jpg      # 趣味紹介用の画像 (野球)
│   └── hobby_orienteering.jpeg # 趣味紹介用の画像 (オリエンテーリング)
├── index.html                  # 【メインページ】日本語版のエントリーポイント
├── index_en.html               # 英語版ページ
├── style.css                   # 全ページ共通のスタイルシート (Vanilla CSS)
├── README.md                   # このファイル（日本語でのリポジトリ解説）
└── README_en.md                # 英語でのリポジトリ解説
```

## 🛠️ ローカルでの環境構築・実行方法 (Local Setup)

このプロジェクトはプレーンなHTML/CSSで書かれているため、特別なインストール作業は不要です。

1. **リポジトリのクローン**
   ```bash
   git clone https://github.com/kakimoto0225/homepage.git
   cd homepage
   ```

2. **ブラウザでの確認**
   - ローカルの `index.html` または `index_en.html` をお好みのブラウザ（Chrome, Firefox, Safariなど）にドラッグ＆ドロップして開いてください。
   - VS Code をお使いの場合、拡張機能の **Live Server**（Ritwick Dey氏作）をインストールし、右下の「Go Live」ボタンをクリックすることで、ホットリロード付きの開発用ローカルサーバーを立ち上げることができます。

## 📝 今後の開発予定 (TODO)

- [ ] 新たな学術論文・研究ノートの追加（PDFリンクの整備）
- [ ] OGP (Open Graph Protocol) 対応の拡充（SNSシェア時のサムネイル表示最適化）
- [ ] ダークモード (Dark Mode) の実装
- [ ] サイトのアクセシビリティ (a11y) 改善

## 👤 管理者・著者

- **Genshin Kakimoto (柿本 源心)**
- GitHub: [@kakimoto0225](https://github.com/kakimoto0225)

## 📄 ライセンス (License)

Copyright (c) 2026 Genshin Kakimoto. All rights reserved.

本リポジトリ内のコードおよび画像等のコンテンツについて、許可なく複製、改変、再配布することを禁じます。
