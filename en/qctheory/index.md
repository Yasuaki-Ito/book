---
layout: default
title: "Theory of Computational Quantum Chemistry — Companion Site | Ito Bunko"
lang: en
alt_url: /qctheory/
permalink: /en/qctheory/
---

<a class="back-link" href="{{ '/en/' | relative_url }}"><span class="arrow">←</span> Back to all books</a>

<section class="hero hero--with-cover">
  <img class="hero__cover" src="{{ '/qctheory/cover-en.jpg' | relative_url }}" alt="Theory of Computational Quantum Chemistry — cover">
  <div class="hero__body">
    <div class="hero__eyebrow">Book 02 — Companion</div>
    <h1 class="hero__title">Theory of Computational Quantum Chemistry</h1>
    <p class="hero__lead">From the Schrödinger Equation to Electronic-Structure Theory</p>
    <p class="hero__byline">by Yasuaki Ito<span class="seal">靖</span></p>
  </div>
</section>

<div class="ornament">❦</div>

## About the Book

The quantum chemistry book that leaves nothing "as an exercise for the reader."

Open almost any quantum chemistry textbook and you will meet the same two sentences: "The derivation is left as an exercise for the reader." "For details, see the references." One line of text, one lost evening — and often, in the end, one abandoned chapter.

This book omits none of it. Starting from the Schrödinger equation, it builds a single continuous argument through Hartree–Fock theory, electron correlation (configuration interaction, perturbation theory, coupled cluster), and excited-state methods (CIS/TDHF, ADC, EOM-CC), without skipping a line of algebra anywhere along the way.

The only prerequisite is high-school mathematics. The linear algebra, calculus, and variational methods you need are developed from scratch in the text, so no prior quantum mechanics or physical chemistry is assumed. It was written by a computer scientist who went looking for a textbook with nothing hidden between the lines, could not find one, and wrote it — for self-learners and students who want to follow every step themselves.

<dl class="info-grid">
  <dt>Author</dt><dd>Yasuaki Ito</dd>
  <dt>Imprint</dt><dd>Ito Bunko（伊藤文庫）</dd>
  <dt>Published via</dt><dd>Amazon Kindle Direct Publishing</dd>
  <dt>Format</dt><dd>Paperback / Kindle</dd>
  <dt>Published</dt><dd>3 August 2026</dd>
  <dt>Length</dt><dd>557 pages</dd>
  <dt>ISBN-13</dt><dd>979-8190481334</dd>
  <dt>Buy</dt><dd><a href="https://www.amazon.com/dp/B0HCP8L9QG">Amazon.com</a> ／ <a href="https://www.amazon.co.jp/dp/B0HCP8L9QG">Amazon.co.jp</a></dd>
</dl>

## What Sets This Book Apart

- Every intermediate step written out, from the Schrödinger equation all the way to EOM-CCSD
- Begins at high-school level: linear algebra, the variational principle, and Lagrange multipliers are built up before they are used
- Carries the derivations down to implementation level — CCSD residual equations, the Davidson algorithm, Obara–Saika and McMurchie–Davidson integral recursions, Schwarz screening
- An algorithmic viewpoint runs through the whole book: the O(*M*<sup>*n*</sup>) cost of each method, and where that exponent comes from
- Real numbers from real calculations — H₂ dissociation, SCF convergence, basis-set convergence — computed with PySCF and reported throughout
- Appendices bridge to density functional theory (Kohn–Sham) and QM/MM

## Contents

34 chapters plus Appendices A–G:

Mathematical preliminaries (linear algebra, variational methods) · foundations of quantum mechanics · many-electron systems and second quantization · Hartree–Fock theory (RHF, UHF, ROHF) · basis sets and the Roothaan–Hall equations · molecular integral algorithms · SCF convergence acceleration (DIIS) · energy gradients and geometry optimization · electron correlation (CI, MP, CCSD(T), multireference methods) · excited states (CIS, TDHF, ADC, EOM-CC) · a closing survey of accuracy versus computational cost

If the companion volume, [*Inside Quantum Chemistry Calculations*]({{ '/en/qcbook/' | relative_url }}), is the book that gives you the concepts and the intuition, this is the one that derives every equation standing behind them — for everyone who wants to work through the theory with a pencil in hand and make it their own.

## Errata

Reported errata for this book. If you find an error, please report it via the [contact form](#contact).

No errata have been reported so far.

<!-- When errata are reported, append in the following table format:
| Edition | Page | Location | Incorrect | Correct | Reported |
|---------|------|----------|-----------|---------|----------|
| 1st | p.XX | Eq. (X.X) | ... | ... | 2026-XX-XX |
-->

## Supplementary Materials

Material that did not fit into the book, plus supplements written in response to reader requests.

- (Coming soon)

<div class="ornament">❦</div>

## Contact

<div class="contact">
  <p>Errata reports, questions, and feedback are warmly welcomed via the form below.</p>
  <p><a class="btn" href="https://forms.gle/EmTWhXoxAEaDB8U3A">Open contact form →</a></p>
</div>
