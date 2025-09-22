# ディレクトリ構成

このプロジェクトは React + TypeScript + Vite + Tailwind CSS を使用したTemplateです。

## プロジェクト構造

```
react-vite-template/
├── public/                 # 静的ファイル
│   └── vite.svg            # Viteロゴファイル
├── src/                    # ソースコード
│   ├── components/         # 再利用可能なReactコンポーネント
│   ├── features/           # 機能別コンポーネント・ロジック
│   ├── pages/              # ページコンポーネント
│   ├── App.tsx             # メインアプリケーションコンポーネント
│   ├── index.css           # グローバルスタイル
│   ├── main.tsx            # アプリケーションエントリーポイント
│   └── vite-env.d.ts       # Vite環境型定義
├── .prettierrc.json        # Prettier設定
├── directory-structure.md  # このファイル（ディレクトリ構成説明）
├── index.html              # HTMLエントリーポイント
├── README.md               # プロジェクト説明
├── tsconfig.app.json       # TypeScript設定（アプリケーション用）
├── tsconfig.json           # TypeScript基本設定
├── tsconfig.node.json      # TypeScript設定（Node.js用）
└── vite.config.ts          # Vite設定ファイル
```

## 主要ディレクトリの説明

### `/src`
アプリケーションのメインソースコードが格納されています。

- **`components/`**: 再利用可能なUIコンポーネント
- **`features/`**: 機能別に整理されたコンポーネントとロジック
- **`pages/`**: ページレベルのコンポーネント（ルーティング対応）
- **`App.tsx`**: ルートコンポーネント
- **`main.tsx`**: Reactアプリケーションのエントリーポイント
- **`index.css`**: Tailwind CSSとグローバルスタイル

### `/public`
静的ファイルが格納されています。ビルド時にそのまま出力ディレクトリにコピーされます。

## 技術スタック

- **React 19**: UIライブラリ
- **TypeScript**: 型安全なJavaScript
- **Vite**: 高速ビルドツール
- **Tailwind CSS**: ユーティリティファーストCSSフレームワーク
- **ESLint**: コード品質チェック
- **Prettier**: コードフォーマッター

## 開発コマンド

```bash
pnpm run dev      # 開発サーバー起動
pnpm run build    # プロダクションビルド
pnpm run lint     # ESLintでコードチェック
pnpm run format   # Prettierでコードフォーマット
pnpm run preview  # ビルド結果のプレビュー
```