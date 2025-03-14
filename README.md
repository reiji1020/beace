# Beace

手芸道具整理サービス「Beace」のFEコードです


## Developing

推奨パッケージマネージャーは`pnpm`です。pnpm導入後、初回は依存パッケージインストールのために`pnpm install`を実行してください。

```bash
# ローカルサーバーを起動
pnpm run dev

# 自動でブラウザ起動したい場合は以下のコマンドを実行
pnpm run dev -- --open
```

## Building

本番環境用のビルドを行う時は以下のコマンドを実行してください。

```bash
pnpm run build
```

本番環境のビルドを用いて動作確認をしたい場合は`npm run preview`を実行してください。


---

# Beace

This is the frontend (FE) code for the handicraft tool organization service "Beace."

## Developing

The recommended package manager is `pnpm`. After installing `pnpm`, run `pnpm install` to install the dependencies for the first time.

```bash
# Start the local server
pnpm run dev

# If you want the browser to open automatically, run the following command:
pnpm run dev -- --open
```

## Building

To build for the production environment, run the following command:

```bash
pnpm run build
```

If you want to check the operation using the production build, run `pnpm run preview`.