---
layout: default
title: "量子化学計算のしくみ　サポートページ｜伊藤文庫"
lang: ja
alt_url: /en/qcbook/
---

<a class="back-link" href="{{ '/' | relative_url }}"><span class="arrow">←</span> 書籍一覧へ戻る</a>

<section class="hero hero--with-cover">
  <img class="hero__cover" src="{{ '/qcbook/cover.png' | relative_url }}" alt="量子化学計算のしくみ 表紙">
  <div class="hero__body">
    <div class="hero__eyebrow">Book 01 — Companion</div>
    <h1 class="hero__title">量子化学計算のしくみ</h1>
    <p class="hero__lead">分子軌道法の理論とアルゴリズム</p>
    <p class="hero__byline">伊藤靖朗　著<span class="seal">靖</span></p>
  </div>
</section>

<div class="ornament">❦</div>

## 書籍情報

Hartree-Fock法からCoupled Cluster法、励起状態計算まで、理論の導出とアルゴリズムの両面から体系的に解説する教科書です。ブラウザで動くGANSU LiteとMOrbVisを使って、手を動かしながら学べます。

<dl class="info-grid">
  <dt>著者</dt><dd>伊藤靖朗</dd>
  <dt>発行</dt><dd>Amazon Kindle Direct Publishing</dd>
  <dt>形式</dt><dd>ペーパーバック ／ Kindle</dd>
  <dt>ISBN-13</dt><dd>979-8257774102</dd>
  <dt>購入</dt><dd><a href="https://www.amazon.co.jp/dp/B0GX2VGWGT">Amazon.co.jp</a></dd>
</dl>

## 関連ツール

<div class="tool">
  <h4><a href="https://yasuaki-ito.github.io/GANSU-Lite/">GANSU Lite</a></h4>
  <p>ブラウザで動く量子化学計算ツール。インストール不要。HF / DFT / MP2 / MP3 / CCSD / CIS / ADC(2) に対応。本書の各章のテーマに対応したデモページを備えています。</p>
</div>

<div class="tool">
  <h4><a href="https://yasuaki-ito.github.io/morbvis/">MOrbVis</a></h4>
  <p>分子軌道を3次元で可視化するブラウザツール。GANSU Lite の計算結果から直接開くことができます。</p>
</div>

<div class="tool">
  <h4><a href="https://github.com/Yasuaki-Ito/GANSU">GANSU</a></h4>
  <p>C++ ／ CUDA で書かれた本格的な量子化学計算ソフトウェア。本書で解説する理論とアルゴリズムの参照実装です。GPU 上での高速計算が可能。オープンソース。</p>
</div>

## 正誤表

現在報告されている正誤情報です。見つけた誤りは[お問い合わせ](#お問い合わせ)からお知らせください。

現在、報告されている正誤はありません。

<!-- 正誤が見つかった場合は以下のテーブル形式で追記:
| 版 | ページ | 箇所 | 誤 | 正 | 報告日 |
|---|--------|------|---|---|--------|
| 初版 | p.XX | 式(X.X) | ... | ... | 2026-XX-XX |
-->

## 補足資料

本書に入りきらなかった資料や、読者からの要望に基づく補足を公開しています。

- （準備中）

## よくある質問

<div class="faq-item">
  <p class="q">GANSU Lite で計算が遅い ／ 動かない</p>
  <p class="a">Chrome ／ Edge ／ Firefox ／ Safari の最新版を推奨します。SIMD 対応ブラウザで高速化されます。モバイル端末では計算速度が PC 比で大幅に低下します。大きな分子（ベンゼン以上）を大きな基底（cc-pVDZ以上）で計算する場合は時間がかかることがあります。</p>
</div>

<div class="faq-item">
  <p class="q">GANSU Lite で CCSD(T) は使えますか？</p>
  <p class="a">GANSU Lite は CCSD(T) に対応していません。CCSD(T) を実行するには <a href="https://github.com/Yasuaki-Ito/GANSU">GANSU</a>（C++／CUDA、GPU対応）をお使いください。</p>
</div>

<div class="faq-item">
  <p class="q">本書の数式を自分で実装したい</p>
  <p class="a"><a href="https://github.com/Yasuaki-Ito/GANSU">GANSU のソースコード</a>が参照実装として利用できます。本書の式番号と対応するソースコードの関係は、将来の補足資料で公開予定です。</p>
</div>

<div class="ornament">❦</div>

## お問い合わせ

<div class="contact">
  <p>正誤のご報告、ご意見・ご感想は連絡フォームからお寄せください。</p>
  <p><a class="btn" href="https://forms.gle/EmTWhXoxAEaDB8U3A">連絡フォームを開く →</a></p>
</div>
