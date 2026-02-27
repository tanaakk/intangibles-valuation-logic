# 00_Intangibles_Valuation_Overview — 無形資産評価ロジック概要

無形資産・ソフトウェア業を中心とした企業価値評価ロジックの仕様・場合分けを管理するリポジトリ。

---

## ドキュメント

- **[無形資産評価ロジック 場合分け](./docs/12-intangibles-valuation-case-classification.md)**  
  公正価値算定に関する公的ガイドライン準拠の、株式価値算定方法のロジック分岐仕様。  
  - 資本規模・業績・財務状態に応じたアプローチ選択、DLOM、無形資産特有の評価ロジック  
  - **DCF バリュエーションのロジックフロー**: 過去決算・未来計画 → 将来キャッシュフロー算定 → 割引 → 現在価値（EV / Equity Value）

---

## GAAS Hands-on における位置づけ

本リポジトリは **財務・バリュエーション** 系。DCF の流れにおける「将来CF算定」の前提となる評価ロジックを定義する。

[operating-leverage-identifier](https://github.com/tanaakk/operating-leverage-identifier) のプロダクト・ポートフォリオ選定と連携。

---

## 詳細

詳細は [README.md](README.md) を参照。
