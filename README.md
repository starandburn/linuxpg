# Linux Playground for NKK

ブラウザー上で動作する授業用の Linux・Git 演習環境です。Learn DevOps の Linux Playground を教育向けに改変しています。

## 利用方法

GitHub Pages で公開した URL をブラウザーで開くと、自動的に Linux が起動します。インターネット接続が必要です。ページの再読み込みにより演習環境は初期化されます。

## 初期設定

- コンソールの文字サイズ：27px
- 作業ディレクトリ：`~/lesson`
- 初期ファイル：`program.cs`
- プロンプト：現在のディレクトリと `$`
- Git ユーザー名：`Student`
- Git メールアドレス：`student@example.com`
- 初期ブランチ：`main`
- 標準エディター：`nano`
- ページャー：変更なし
- 色表示：`auto`

## 出典・ライセンス

- [Learn DevOps](https://github.com/dmccuk/learndevops) — MIT License（プログラム部分）
- Copyright (c) 2026 Dennis McCarthy and contributors
- 元のライセンス全文は `LICENSE` および `index.html` 内に保持しています。

## 外部依存

以下のライブラリと Linux イメージは外部から読み込み、このリポジトリには同梱していません。

- [v86](https://github.com/copy/v86) 0.5.472
- [xterm.js](https://github.com/xtermjs/xterm.js) 6.0.0
- [@xterm/addon-fit](https://github.com/xtermjs/xterm.js) 0.11.0
- [Learn DevOps Linux VM](https://dmccuk.github.io/learndevops/playground/)

各依存ソフトウェアにはそれぞれのライセンスが適用されます。
