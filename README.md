# BetterDarkGUI_pack

![pack_banner](https://user-images.githubusercontent.com/82772868/208215406-c69168df-8a80-4d7f-ad82-1a853db2e3c4.png)

![](https://img.shields.io/badge/Minecraft-Resourcepack-blue)
![](https://img.shields.io/badge/Recommended-Optifine-yellow)
![](https://img.shields.io/badge/Version-1.17+-brightgreen)
![](https://img.shields.io/badge/Progress-95%25-brightgreen)
<br>
<br>
## 概要
- このリソースパックは、MinecraftのGUIをダークテーマに変更します。

  This Resource Pack is a  dark theme for the Minecraft GUI.


- より読みやすいフォントに変更します。
 
  Change Font for better readability.

- Optifineの使用を推奨します。（ローディング時のカラーに反映される）
  
  Recommended use [Optifine](https://optifine.net/downloads).

- フォントの外見上、GUIの大きさは3を推奨します。

  Recommended `GUI scale: 3`

## Utility UI

![darkgui_hotbar](https://user-images.githubusercontent.com/82772868/123035765-ddcd5800-d426-11eb-9e68-2797ac3c6ac3.jpg)

![darkgui_preview2](https://user-images.githubusercontent.com/82772868/122931915-432e3400-d3a8-11eb-9440-88550749b28d.jpg)


## Options UI

Revamp `pixel M Plus 12`font

![darkgui_preview](https://user-images.githubusercontent.com/82772868/122922173-4f14f880-d39e-11eb-8c65-676fda47f13a.jpg)

## ファイル構造 (自分でカスタムする人向け)
![structure](https://user-images.githubusercontent.com/82772868/122955654-3f57dd00-d3bb-11eb-89b4-f6c0901ac429.png)


<!--
BetterdarkGUI
├── .git
├── .vscode
├── asset
│   ├── minecraft
│   │   ├── font
│   │   │   ├── custom.ttf (フォントファイル)
│   │   │   └── default.json (フォントの細かな設定)
│   │   ├── optifine
│   │   │   └── color.properties (ローディング時の背景カラーやプログレスバーの設定)
│   │   └── textures
│   │       ├── gui
│   │       │   ├── title
│   │       │   │   ├── mojangstudios.png (ローディング時のロゴ)
│   │       │   │   └── background
│   │       │   │       └── panorama_x.png (タイトル画面時の背景xには0~5の数字が入る)   
│   │       │   ├── container
│   │       │   │   ├── xxx.png (inventory.pngなどの主なUtility系のUIテクスチャ)
│   │       │   │   └── creative_inventory (クリエイティブ時のUIテクスチャ)
│   │       │   ├── options_background.png (オプション時の背景タイル画像)
│   │       │   └── xxx.png (ホットバーなどのUIのテクスチャ)
│   │       └── mob_effect
│   │           └── xxx.png (エフェクト関連のテクスチャ)
│   ├── .mcassetroot
│   └── .gitkeep
├── .gitignore
├── LICENCE
├── pack.png (Resourcepackのアイコン画像)
├── pack.mcmeta (Description等)
└── README.md
-->
