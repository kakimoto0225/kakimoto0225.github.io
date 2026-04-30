# Genshin Kakimoto Homepage

京都大学経済学部で学ぶ Genshin Kakimoto の個人ホームページです。研究関心、進行中のプロジェクト、資格、趣味などを日本語と英語で掲載しています。

公開サイト:

- 日本語: https://kakimoto0225.github.io/homepage/
- English: https://kakimoto0225.github.io/homepage/index_en.html

English README: [README_en.md](./README_en.md)

## このリポジトリについて

このリポジトリは、GitHub Pages で公開している静的な個人ホームページのソースコードです。HTML と CSS のみで構成しており、ビルドツールや外部フレームワークは必要ありません。

初めて訪れた方は、まず公開サイトを見ると内容を把握しやすいです。GitHub 上では、ページ本文、スタイル、掲載画像、デプロイ設定がどのように管理されているかを確認できます。

## 掲載内容

- Profile: 所属、ゼミ、GitHub アカウント
- Research: 計量経済学、因果推論、実証産業組織論、機械学習
- Work: 論文、プロジェクト、関連リンク
- Credentials: TOEIC、データサイエンティスト検定、英検、統計検定
- Hobbies: 映画、料理、オリエンテーリング

## ファイル構成

```text
homepage/
|-- index.html              # Japanese page
|-- index_en.html           # English page
|-- style.css               # Shared stylesheet
|-- README.md               # Japanese repository overview
|-- README_en.md            # English repository overview
|-- images/
|   |-- face.jpg
|   |-- profile_large.jpg
|   |-- profile_small.jpg
|   |-- hobby_movie.jpg
|   |-- hobby_baseball.jpg
|   `-- hobby_orienteering.jpeg
`-- .github/
    `-- workflows/
        `-- pages.yml       # GitHub Pages deployment workflow
```

## ローカルで確認する方法

このサイトは静的ファイルだけで動作します。手元で確認する場合は、リポジトリをクローンして `index.html` をブラウザで開くか、簡単な HTTP サーバーを起動してください。

```bash
git clone https://github.com/kakimoto0225/homepage.git
cd homepage
python -m http.server 4173
```

起動後、ブラウザで次の URL を開きます。

- http://127.0.0.1:4173/index.html
- http://127.0.0.1:4173/index_en.html

## 技術メモ

- HTML5 による静的ページ
- CSS Grid / Flexbox によるレスポンシブレイアウト
- Google Fonts を利用した日本語・英語表示
- GitHub Actions による GitHub Pages へのデプロイ

## 管理者

- GitHub: [kakimoto0225](https://github.com/kakimoto0225)

## ライセンス

Copyright (c) 2026 Genshin Kakimoto. All rights reserved.
