# Artifacter for Discord(Pycord)

## ※本リポジトリはActCelelyさんの改変版となります

[改変前のコード](https://github.com/ActCelely/Genshin-Artifacter-BOT)

これはGenshin Artifacter BOTの再現版です。
(py-cordなので注意してください)

# 動作環境

・本BotはPython3.10以降でのみ動作確認しています。(エラーは出ますが3.9でも一応は動きます)
<br>・推奨Pycordバージョン: 2.4.0以上

# 必要モジュール

・Pycord <br>・Pillow: v9.3.0以下

# モジュールのインストール方法

```
python3.10 -m pip install Pillow==9.3.0 pycord
```

# 動作方法

Discordのアプリケーショントークンを取得後「Artifacter.py」を開き「TOKEN」部分を変更する。<br>または
「token.txt」を「Artifacter.py」と同じフォルダへ作成してトークンを「token.txt」へ書き込み以下を実行

```
python3.10 Artifacter.py
```

## コマンド

```
/build
```
<br>または

```
/start
```
で作成ボタンを表示

## 改変前のコードとの相違

・変更点１<br>[変更前] kuroneko Severの「gensinAPI」を使用<br>[変更後] 自前で高速にEnkaNetworkから直接取得
<br><br>・変更点２<br>[変更前] Artifacterの旧デザインをそのまま使用<br>[変更後] 独自のビルドカードデザインへ変更<br><br>・変更点３<br>[変更前] 膨大なキャラ画像データ類を直接編集<br>[変更後] キャラ画像データ類を全てEnkaNetworkからの取得後編集へ

## ライセンスについて

本ツールはMITライセンスです。MITライセンス下でならご自由にお使いください。