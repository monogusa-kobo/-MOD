# サガエメ 戦闘・移動高速化MOD
# SaGa Emerald Beyond – Battle & Field Speed Mod

**Version: 0.9.11-beta.1**

**日本語 / English below**

## 日本語

### 概要

『サガ エメラルド ビヨンド』（Steam版）の戦闘演出とフィールド移動を高速化する非公式MODです。

[Denhonator氏のEmeraldBeyondQoL](https://github.com/Denhonator/EmeraldBeyondQoL) をベース・参考に、戦闘とフィールドの速度変更機能を開発しました。

開発にはOpenAI Codexを使用しています。作者自身のゲーム環境で動作確認を行っていますが、すべての環境での動作を保証するものではありません。

### 主な機能

- 戦闘演出を最大3倍速に変更
- フィールド移動を最大3倍速に変更
- **F10キー**で速度を切り替え
- 速度は1倍（OFF）・1.5倍・2倍・3倍から選択
- 戦闘、各世界のフィールドで速度設定を個別に保持
- 速度変更時は画面左上に倍率を一時表示
- 一部の船移動にも高速化を適用

起動時の初期設定は戦闘2倍速、フィールド移動3倍速です。

戦闘コマンド入力中など、一部の場面では高速化を適用しません。

### 必要環境

- Windows版『サガ エメラルド ビヨンド』（Steam）
- **MelonLoader 0.7.0**（動作確認の基準環境）
- IL2CPP用の.NET 6環境

※MelonLoaderは別途導入が必要です。ゲーム本体、MelonLoaderはMODに同梱していません。

### 導入方法

**1. MelonLoaderを導入する**

[MelonLoader公式GitHub](https://github.com/LavaGang/MelonLoader) からインストーラーを入手してください。

ゲームを終了した状態でインストーラーを起動し、『サガ エメラルド ビヨンド』のゲーム実行ファイルを指定してMelonLoaderをインストールします。

本MODの基準環境はMelonLoader 0.7.0です。異なるバージョンでの動作は保証していません。

**2. ゲームを一度起動する**

MelonLoader導入後、ゲームを一度起動して終了してください。

ゲームのインストールフォルダ内に `Mods` フォルダが作成されます。

ゲームのインストール先は、Steamライブラリでゲームを右クリックし、**プロパティ → インストール済みファイル → 参照** から確認できます。

**3. MODを配置する**

GitHubの **Releases** から最新の配布ZIPをダウンロードして解凍します。

ZIP内の `Mods/EmeraldSafeQoL.dll` を、ゲームの `Mods` フォルダにコピーしてください。

配置例：

```text
SaGa Emerald Beyond/
├── ゲーム実行ファイル
├── MelonLoader/
└── Mods/
    └── EmeraldSafeQoL.dll
```

**4. ゲームを起動する**

ゲームを起動し、戦闘中またはフィールド移動中に **F10キー** を押して速度が切り替われば導入完了です。

### 更新・アンインストール

更新する際はゲームを終了し、古い `EmeraldSafeQoL.dll` を新しいDLLに置き換えてください。

削除する場合は、ゲーム終了後に `Mods` フォルダから `EmeraldSafeQoL.dll` を取り除いてください。

### 注意事項

- 現在はベータ版です。
- ゲームの更新や環境の違いによって動作しない場合があります。
- 高速化により、一部の戦闘演出・表示・特殊な移動で不具合が生じる可能性があります。
- **クロウレルムの流砂など、特殊な移動床を利用する場面では、事前に移動速度を1倍（OFF）にしてください。**
- 導入は自己責任でお願いします。重要なセーブデータはバックアップを推奨します。

### クレジット

**元MOD・参考プロジェクト**

EmeraldBeyondQoL / Emerald Beyond Utility Mod  
Author: Denhonator  
https://github.com/Denhonator/EmeraldBeyondQoL

**本MODの制作・調整**

ものぐさ工房（monogusa-kobo）

開発・コード生成・検証支援：OpenAI Codex

本MODは非公式のファン制作物であり、スクウェア・エニックスおよび原作開発元とは関係ありません。

---

## English

### About

An unofficial speed enhancement mod for the Windows Steam version of **SaGa Emerald Beyond**.

This mod was developed based on and with reference to [EmeraldBeyondQoL by Denhonator](https://github.com/Denhonator/EmeraldBeyondQoL), with a focus on adjustable battle and field movement speeds.

OpenAI Codex was used during development. The author has confirmed functionality in their own gameplay environment, but compatibility with all systems and game situations is not guaranteed.

### Features

- Speed up battle animations and presentation up to **3x**
- Speed up field movement up to **3x**
- Press **F10** to change the speed
- Select between 1x (OFF), 1.5x, 2x and 3x
- Independent speed settings for battles, world fields
- Temporary on-screen speed indicator
- Speed adjustments for certain boat movement sequences

Default startup settings are **2x for battles** and **3x for field movement**.

Some situations, including battle command selection, remain at normal speed.

### Requirements

- SaGa Emerald Beyond (Windows / Steam)
- **MelonLoader 0.7.0** (reference environment)
- .NET 6 environment for IL2CPP

MelonLoader must be installed separately. The game and MelonLoader are not included in this download.

### Installation

**1. Install MelonLoader**

Download the installer from the [official MelonLoader GitHub repository](https://github.com/LavaGang/MelonLoader).

Close the game, run the installer, and select the SaGa Emerald Beyond game executable.

This mod was developed against MelonLoader 0.7.0. Other versions have not been verified.

**2. Launch the game once**

After installing MelonLoader, launch the game once and close it.

A `Mods` folder should be created in the game's installation directory.

You can locate the game folder through Steam: right-click the game, then select **Properties → Installed Files → Browse**.

**3. Install the mod**

Download the latest ZIP from the GitHub **Releases** page and extract it.

Copy `Mods/EmeraldSafeQoL.dll` from the ZIP into the game's `Mods` folder.

Example:

```text
SaGa Emerald Beyond/
├── Game executable
├── MelonLoader/
└── Mods/
    └── EmeraldSafeQoL.dll
```

**4. Launch the game**

Start the game and press **F10** during battles or while moving in the field to change the speed.

### Updating and uninstalling

To update, close the game and replace the previous `EmeraldSafeQoL.dll` with the new version.

To uninstall, close the game and remove `EmeraldSafeQoL.dll` from the `Mods` folder.

### Important notes

- This is a beta release.
- Compatibility may be affected by game updates or different system environments.
- Higher speeds may cause issues with certain battle animations, UI elements or special movement sequences.
- **Set field movement speed to 1x (OFF) before entering quicksand areas such as Crow Realm or other special moving-floor sections.**
- Use at your own risk. Backing up important save data is recommended.

### Credits

**Original mod / Reference project**

EmeraldBeyondQoL / Emerald Beyond Utility Mod  
Author: Denhonator  
https://github.com/Denhonator/EmeraldBeyondQoL

**Mod development and modifications**

Monogusa Kobo (monogusa-kobo)

Development, code generation and verification assistance: OpenAI Codex

This is an unofficial fan-made mod and is not affiliated with or endorsed by Square Enix or the original game developers.
