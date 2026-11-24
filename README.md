# Sayu_WebPane_Obsidian

Open the Discord web app as a pane inside Obsidian (desktop), using the community plugin [Custom Frames](https://github.com/Ellpeck/ObsidianCustomFrames).

This repository contains only a settings file. It does not include, modify or redistribute any Discord or Obsidian software.

[日本語](#日本語)

## Setup

1. In Obsidian, open **Settings → Community plugins → Browse**, install **Custom Frames** and enable it.
2. Close Obsidian.
3. Copy `data.example.json` to `<your vault>/.obsidian/plugins/obsidian-custom-frames/data.json`.
   If that file already exists, add the entry inside `"frames"` to your existing list instead of overwriting it.
4. Start Obsidian. Click the speech-bubble icon in the left ribbon, or run **Custom Frames: Open Discord** from the command palette.
5. Sign in to Discord inside the pane (first time only).

You can also add the same frame from the Custom Frames settings screen without copying the file: URL `https://discord.com/channels/@me`, name `Discord`.

## Notes

- Desktop only (`hideOnMobile` is on).
- `customCss` and `customJs` are left empty on purpose. Injecting code into the Discord page may break Discord's Terms of Service.
- Sign-in may ask for a CAPTCHA or a QR-code login; complete it yourself in the pane.

## Trademarks

Discord and Obsidian are trademarks of their respective owners. This project is not affiliated with, sponsored or endorsed by them.

---

## 日本語

コミュニティプラグイン [Custom Frames](https://github.com/Ellpeck/ObsidianCustomFrames) を使って、Obsidian（デスクトップ版）の中で Discord の Web 版を開くための設定です。

このリポジトリに入っているのは設定ファイルだけです。Discord や Obsidian のソフトウェアを含んだり、改変・再配布したりはしていません。

### 導入

1. Obsidian の **設定 → コミュニティプラグイン → 閲覧** から **Custom Frames** を入れて有効にします。
2. Obsidian を閉じます。
3. `data.example.json` を `<保管庫>/.obsidian/plugins/obsidian-custom-frames/data.json` としてコピーします。
   すでにそのファイルがある場合は上書きせず、`"frames"` の中身を既存の一覧に足してください。
4. Obsidian を起動し、左のリボンの吹き出しアイコンか、コマンドパレットの **Custom Frames: Open Discord** で開きます。
5. 枠の中で Discord にログインします（初回だけ）。

ファイルをコピーせず、Custom Frames の設定画面から URL `https://discord.com/channels/@me`、名前 `Discord` で追加しても同じです。

### 注意

- デスクトップ版だけです（`hideOnMobile` が有効）。
- `customCss` と `customJs` はあえて空にしています。Discord のページにコードを差し込むと、Discord の利用規約に反するおそれがあります。
- ログイン時に CAPTCHA や QR コードでのログインを求められることがあります。枠の中でご自身で操作してください。

### 商標

Discord と Obsidian は、それぞれの権利者の商標です。このプロジェクトは権利者と提携しておらず、後援・承認も受けていません。
