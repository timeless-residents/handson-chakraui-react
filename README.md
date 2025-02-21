# Chakra UI + React ハンズオン

このプロジェクトは、React と Chakra UI を使用したハンズオン学習用のテンプレートです。Vite を使用して構築され、HMR（Hot Module Replacement）とESLintの基本設定が含まれています。

## 機能

- ⚡️ [Vite](https://vitejs.dev/) による高速な開発環境
- ⚛️ [React 19](https://react.dev/) の最新機能
- 🎨 [Chakra UI](https://chakra-ui.com/) によるモダンなUIコンポーネント
- 🔄 GitHub Actions による自動デプロイ

## 始め方

```bash
# リポジトリのクローン
git clone https://github.com/timeless-residents/handson-chakraui-react.git
cd handson-chakraui-react

# 依存関係のインストール
npm install

# 開発サーバーの起動
npm run dev
```

## 利用可能なコマンド

- `npm run dev` - 開発サーバーを起動します（http://localhost:5173）
- `npm run build` - プロダクション用にプロジェクトをビルドします
- `npm run preview` - ビルドしたプロジェクトをプレビューします
- `npm run lint` - ESLintによるコード検証を実行します

## デプロイ

このプロジェクトはGitHub Pagesへの自動デプロイが設定されています。`main`ブランチにプッシュすると、GitHub Actionsワークフローが自動的に実行され、アプリケーションがデプロイされます。

デプロイされたアプリケーションは以下のURLで確認できます：
https://yourusername.github.io/handson-chakraui-react/

## プロジェクト構成

```
handson-chakraui-react/
├── src/
│   ├── assets/     # 画像などの静的ファイル
│   ├── App.jsx     # メインのアプリケーションコンポーネント
│   └── main.jsx    # アプリケーションのエントリーポイント
├── public/         # 静的ファイル
└── index.html      # HTMLテンプレート
```

## 技術スタック

- [React](https://react.dev/)
- [Chakra UI](https://chakra-ui.com/)
- [Vite](https://vitejs.dev/)
- [Emotion](https://emotion.sh/)
- [Framer Motion](https://www.framer.com/motion/)
