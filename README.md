# FlowOut for Windows

Windows 11向け日本語IMEの配布専用リポジトリです。ソースコードや更新署名の秘密鍵は含みません。

[最新版のダウンロード](https://github.com/yachtida/FlowOut-releases/releases/latest)

`FlowOut-Setup-<version>.exe`を通常のエクスプローラーから起動してインストールします。WindowsへのIME登録時に管理者確認が必要です。入力方式からFlowOutを選択してください。日本語Microsoft IMEが利用できるWindows 11 x64が必要です。x64・x86アプリ用接続部を同梱します。

- 入力中のライブ変換。Space・上下キーで候補選択、Enterで確定。
- Escで読みへ戻す／取消、F6でひらがな、F7でカタカナ、Ctrl+Spaceで直接入力切替。
- 通常権限で署名付きruntimeを自動更新。未確定入力は旧版を維持し、確定・取消後の入力から新版へ切り替えます。
- 削除はWindowsの「インストールされているアプリ」から行います。

先行版です。候補はMicrosoft IMEのIFELanguageが返す候補と元の読みです。文節編集、辞書UI、独自学習、ARM64、AppContainerは提供・対応確認の範囲に含みません。

更新manifestはRSA-PSS/SHA-256署名とパッケージのSHA-256を検証します。WindowsのAuthenticode署名とは別で、現在のセットアップにAuthenticode署名はありません。
