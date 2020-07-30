# LADR-template

Lightweight Architecture Decision Recordsテンプレート。

## LADRとは

**L**ightweight **A**rchitecture **D**ecision **R**ecordsの略。

「なぜそのアーキテクチャ選択を行ったのか」という意思決定（ADR）を簡潔（軽量、Lightweight）に記録を残すこと。

## 記録方法

- [TEMPLATE.md](TEMPLATE.md)の書式にしたがって記述
- 1アーキテクチャ1ファイル
  - ファイル名の接頭辞に`adr-001-`などとつけると決定の順に並ぶのでいいかもしれない
- できる限り対象アプリケーションのソースコードレポジトリに格納
- 原則、一度確定したADRは更新しない
  - 関連する意思決定を行う場合は既存の関連ADRを参照しつつ新しいADRを記録
