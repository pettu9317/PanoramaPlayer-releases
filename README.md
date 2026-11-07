# Panorama — Windows用VR動画プレイヤー

360°／180°のVR動画を通常のモニターで見るためのアプリです。このリポジトリはインストーラーと更新ファイルの配布専用です。

## インストール

1. [Releases](https://github.com/pettu9317/PanoramaPlayer-releases/releases/latest) から `Panorama-win-Setup.exe` をダウンロードして実行します。
2. .NET 8 Desktop Runtime が入っていない場合は、インストーラーが自動で導入します。
3. **VLC media player 3.x（64ビット）** を別途インストールしてください: https://www.videolan.org/vlc/

デスクトップとスタートメニューに「Panorama」が追加されます。

## アップデート

起動時に新しいバージョンを確認します。新しいバージョンがあると画面右上に「vX.X.X に更新」ボタンが表示され、クリックすると更新して再起動します。

## アンインストール

Windowsの「設定」→「アプリ」→「インストールされているアプリ」から「Panorama」をアンインストールします。ライブラリの設定（`%LOCALAPPDATA%\PanoramaPlayer`）は残ります。
