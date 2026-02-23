# homepage

柿本源心さんの自己紹介ページ（日本語 + 英語）です。

## 現在の内容
- `index.html`: 日本語ページ
- `index_en.html`: 英語ページ
- `assets/css/style.css`: 共通スタイル
- `assets/images/`: プロフィール・趣味写真
- `.github/workflows/pages.yml`: GitHub Pages 用ワークフロー

## 画像対応
- `profile_small.jpg`: 写真75（小さいプロフィール）
- `profile_large.jpg`: 写真76（大きいプロフィール）
- `hobby_movie.jpg`: 写真77（映画）
- `hobby_baseball.jpg`: 写真78（野球）
- `hobby_orienteering.jpg`: 写真79（オリエン）

## 論文PDFリンク
- LLM: `C:/Users/Owner/OneDrive - Kyoto University/LLMコンペ/発表資料/experiment_report_en.pdf`
- MLB移籍: `C:/Users/Owner/OneDrive - Kyoto University/論文/posting/paper_sports/main.pdf`

## ローカルで閲覧
1. `index.html` をブラウザで開く
2. 英語版は `index_en.html`

## GitHubにprivateリポジトリとして保存する手順
以下は `https://github.com/kakimoto0225/homepage` を private で作る想定です。

1. GitHubで新規リポジトリ作成
- URL: `https://github.com/new`
- Repository name: `homepage`
- Visibility: `Private`
- README等の初期ファイルは作らない（空で作成）

2. ローカルからpush
```powershell
git init
git branch -M main
git add .
git commit -m "Initial homepage"
git remote add origin https://github.com/kakimoto0225/homepage.git
git push -u origin main
```

## privateリポジトリをWebページとして閲覧する方法

### 方法A: GitHub Pages（推奨）
注意: private repoのGitHub Pagesは、アカウントプランによって利用可否が異なります（GitHub Pro/Team/Enterprise では利用可能）。

1. リポジトリ `homepage` の `Settings` を開く
2. `Actions` -> `General` でワークフロー実行を許可
3. `Pages` を開き、`Build and deployment` の Source を `GitHub Actions` にする
4. `main` に push すると `.github/workflows/pages.yml` が実行される
5. 数分後、`https://kakimoto0225.github.io/homepage/` で閲覧

### 方法B: GitHub Pagesがprivateで使えない場合
1. 一時的にリポジトリを `Public` に変更してPages公開
2. もしくは Vercel / Cloudflare Pages / Netlify で private repo 連携してデプロイ

## 注意事項
- 現在の論文PDFリンクはローカルPC上の `file:///` を参照するため、他の閲覧者には開けません。
- 公開サイトでPDFを誰でも開けるようにするには、PDFをリポジトリ内に配置して相対パスでリンクしてください（例: `assets/pdfs/experiment_report_en.pdf`）。
