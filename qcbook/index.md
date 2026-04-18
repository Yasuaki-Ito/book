---
layout: default
title: "量子化学計算のしくみ — サポートページ"
---

[← 書籍一覧に戻る](../)

# 量子化学計算のしくみ

**分子軌道法の理論とアルゴリズム** — 伊藤 靖朗 著

---

## 書籍情報

Hartree-Fock法からCoupled Cluster法、励起状態計算まで、理論の導出とアルゴリズムの両面から体系的に解説する教科書です。ブラウザで動く GANSU Lite と MOrbVis を使って、手を動かしながら学べます。

- **著者**：伊藤 靖朗
- **発行**：Amazon Kindle Direct Publishing
- **形式**：ペーパーバック / Kindle

---

## 関連ツール

### [GANSU Lite](https://yasuaki-ito.github.io/GANSU-Lite/)

ブラウザで動く量子化学計算ツール。インストール不要。HF / DFT / MP2 / MP3 / CCSD / CIS / ADC(2) に対応。本書の各章のテーマに対応したデモページを備えています。

### [MOrbVis](https://yasuaki-ito.github.io/morbvis/)

分子軌道を3次元で可視化するブラウザツール。GANSU Lite の計算結果から直接開くことができます。

### [GANSU](https://github.com/Yasuaki-Ito/GANSU)

C++ / CUDA で書かれた本格的な量子化学計算ソフトウェア。本書で解説する理論とアルゴリズムの参照実装です。GPU 上での高速計算が可能。オープンソース。

---

## 正誤表

現在報告されている正誤情報です。見つけた誤りは[下記の連絡先](#お問い合わせ)からお知らせください。

現在、報告されている正誤はありません。

<!-- 正誤が見つかった場合は以下のテーブル形式で追記:
| 版 | ページ | 箇所 | 誤 | 正 | 報告日 |
|---|--------|------|---|---|--------|
| 初版 | p.XX | 式(X.X) | ... | ... | 2026-XX-XX |
-->

---

## 補足資料

本書に入りきらなかった資料や、読者からの要望に基づく補足を公開しています。

- (準備中)

---

## よくある質問

**Q. GANSU Lite で計算が遅い / 動かない**

Chrome / Edge / Firefox / Safari の最新版を推奨します。SIMD 対応ブラウザで高速化されます。モバイル端末では計算速度が PC 比で大幅に低下します。大きな分子(ベンゼン以上)を大きな基底(cc-pVDZ以上)で計算する場合は時間がかかることがあります。

**Q. GANSU Lite で CCSD(T) は使えますか？**

GANSU Lite は CCSD(T) に対応していません。CCSD(T) を実行するには [GANSU](https://github.com/Yasuaki-Ito/GANSU)(C++/CUDA、GPU対応)をお使いください。

**Q. 本書の数式を自分で実装したい**

[GANSU のソースコード](https://github.com/Yasuaki-Ito/GANSU)が参照実装として利用できます。本書の式番号と対応するソースコードの関係は、将来の補足資料で公開予定です。

---

## お問い合わせ

正誤のご報告、ご意見・ご感想は以下の連絡フォームからお寄せください。

- **連絡フォーム**：[https://forms.gle/EmTWhXoxAEaDB8U3A](https://forms.gle/EmTWhXoxAEaDB8U3A)

---

<small>&copy; 2026 伊藤 靖朗</small>
