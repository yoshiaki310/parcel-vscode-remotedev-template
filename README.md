# parcel-vscode-remotedev-template

## ナニコレ

Visual Studio Code + Remote Development + Docker で parcel + vue + TypeScript 環境を用意するやつのテンプレートプロジェクト

## できること

コンテナ上で TypeScript + vue を Parcel ビルドできます

## 準備

- vscode insoders 入れる
  - vscode insiders に remote development 拡張パック入れる
- Docker 入れる
  - Windows の場合は Docker Desktop を入れる必要がある
  - この時に Hyper-V を有効にし忘れてハマることが多いので、Hyper-V インストールの後、[スタート]-[Hyper-V]- [`Hyper-V Switch`] で有効にしておくこと
- このリポジトリを clone する
- [フォルダを Container として開く]する
- [コンテナに Attach]する
- `npm install`
- `npm run serve`
- http://localhost:1234 をブラウザで開き、コードを書く

一回やったら、[フォルダを Container として開く]より前は不要です