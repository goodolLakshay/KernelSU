# KernelSU とは?

KernelSU は Android GKI デバイスのための root ソリューションです。カーネルモードで動作し、カーネル空間で直接ユーザー空間アプリに root 権限を付与します。

## 機能

KernelSU の最大の特徴は、**カーネルベース**であることです。KernelSU はカーネルモードで動作するため、今までにないカーネルインターフェイスを提供できます。例えば、カーネルモードで任意のプロセスにハードウェアブレークポイントを追加できる、誰にも気づかれずに任意のプロセスの物理メモリにアクセスできる、カーネル空間で任意のシステムコールを傍受できる、などです。

また、KernelSU は OverlayFS によるモジュールシステムを提供しており、カスタムプラグインをシステムに読み込めます。`/system` パーティションを変更する仕組みも提供しています。

## 使用方法

こちらをご覧ください: [インストール方法](installation)

## ビルド方法

[ビルドするには](../../guide/how-to-build)

## ディスカッション

- Telegram: [@KernelSU](https://t.me/KernelSU)