# yomiyasu-ja for Rakazo

Rakazo向けに移植した日本語推敲スキルです。元プロジェクトの推敲方針を参考に、外部スクリプト・Claude Code固有機能に依存しない形へ再構成しています。

## 構成

- `plugin.json`: Agent Plugin manifest
- `skills/yomiyasu-ja/SKILL.md`: スキル本体

## 元プロジェクトとの差分

この移植版は、元の `nanaism/yomiyasu` 3.0.0を参考にした互換実装です。元のPython lint、diff、hash照合、Hooks、`.yomiyasu-words/` の辞書機能は含みません。これらを実行したと主張せず、AIによる意味・条件の読み比べに置き換えています。

元プロジェクト: https://github.com/nanaism/yomiyasu
ライセンス: MIT（元プロジェクトのLICENSEも確認してください）
