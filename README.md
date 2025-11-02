# AIトレーナーこたくん LP

LINEで続く健康管理サービスのランディングページ

## 開発環境での実行

```bash
npm install
npm run dev
```

ブラウザで http://localhost:3000 にアクセス

## デプロイ方法

### Netlify
1. [Netlify](https://netlify.com) にアカウントを作成
2. プロジェクトをGitHubにプッシュ
3. NetlifyでGitHubリポジトリを接続
4. デプロイコマンド: `npm run build`
5. 公開ディレクトリ: `.`

### Vercel
1. [Vercel](https://vercel.com) にアカウントを作成
2. プロジェクトをGitHubにプッシュ
3. VercelでGitHubリポジトリを接続
4. 自動でデプロイされます

### GitHub Pages
1. GitHubリポジトリの Settings > Pages
2. Source: Deploy from a branch
3. Branch: main / (root)

## ファイル構成

- `index.html` - メインのLPファイル
- `package.json` - プロジェクト設定
- `README.md` - このファイル