# sumitool-3d

住友電工ハードメタル 3Dカタログビューワー

切削工具（インサート）の3Dモデルをブラウザ上で表示・AR体験できるWebアプリケーションです。

## 概要

- 製品一覧ページと製品詳細ページで構成されています
- `model-viewer` を使用した3Dモデル表示
- iOS/Android対応のARビュー機能
- QRコードによるスマートフォン共有機能

## ファイル構成

```
sumitool-3d/
├── index.html            # 製品一覧ページ
├── detail.html           # 製品詳細・3Dビューワーページ
├── test.glb              # 3Dモデルファイル（GLB形式）
├── test.usdz             # 3Dモデルファイル（USDZ形式）
├── thumb_cnmg120408.png  # 製品サムネイル画像
├── product1.png          # 関連製品画像
├── product2.png          # 関連製品画像
├── product3.png          # 関連製品画像
├── product4.png          # 関連製品画像
└── qrcode.png            # QRコード画像
```

## 使用技術

- [model-viewer](https://modelviewer.dev/) - 3Dモデル表示・ARビュー
- HTML / CSS / JavaScript（フレームワーク不使用）

## デモ

[GitHub Pages で公開中](https://daruma0411-crypto.github.io/sumitool-3d/)

## ライセンス

© Sumitomo Electric Industries, Ltd. All Rights Reserved.
