---
layout: default
title: "Inside Quantum Chemistry Calculations — Companion Site"
lang: en
alt_url: /qcbook/
permalink: /en/qcbook/
---

<a class="back-link" href="{{ '/en/' | relative_url }}"><span class="arrow">←</span> Back to all books</a>

<section class="hero hero--with-cover">
  <img class="hero__cover" src="{{ '/qcbook/cover.png' | relative_url }}" alt="Inside Quantum Chemistry Calculations — cover">
  <div class="hero__body">
    <div class="hero__eyebrow">Book 01 — Companion</div>
    <h1 class="hero__title">Inside Quantum Chemistry Calculations</h1>
    <p class="hero__lead">Theory and Algorithms of Molecular Orbital Methods</p>
    <p class="hero__byline">by Yasuaki Ito<span class="seal">靖</span></p>
  </div>
</section>

<div class="ornament">❦</div>

## About the Book

A textbook that systematically derives the methods of modern quantum chemistry — from Hartree–Fock and DFT to MP*n*, Coupled Cluster, and excited-state methods — covering both the theoretical foundations and the practical algorithms. Each topic is paired with hands-on exercises you can run directly in the browser using GANSU Lite and MOrbVis.

<dl class="info-grid">
  <dt>Author</dt><dd>Yasuaki Ito</dd>
  <dt>Publisher</dt><dd>Amazon Kindle Direct Publishing</dd>
  <dt>Format</dt><dd>Paperback / Kindle</dd>
</dl>

## Companion Tools

<div class="tool">
  <h4><a href="https://yasuaki-ito.github.io/GANSU-Lite/">GANSU Lite</a></h4>
  <p>An in-browser quantum chemistry calculator. No installation required. Supports HF / DFT / MP2 / MP3 / CCSD / CIS / ADC(2). Each chapter of the book has a matching demo page.</p>
</div>

<div class="tool">
  <h4><a href="https://yasuaki-ito.github.io/morbvis/">MOrbVis</a></h4>
  <p>An in-browser 3D molecular orbital viewer. You can open results from GANSU Lite directly in MOrbVis.</p>
</div>

<div class="tool">
  <h4><a href="https://github.com/Yasuaki-Ito/GANSU">GANSU</a></h4>
  <p>A full-featured quantum chemistry package written in C++ / CUDA. It is the reference implementation of the theory and algorithms covered in the book, with high-performance computation on GPUs. Open source.</p>
</div>

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

## Frequently Asked Questions

<div class="faq-item">
  <p class="q">GANSU Lite is slow or doesn't work on my machine.</p>
  <p class="a">The latest version of Chrome / Edge / Firefox / Safari is recommended. Performance improves significantly on browsers with SIMD support. Mobile devices are noticeably slower than desktops. Larger molecules (benzene-sized or above) with larger basis sets (cc-pVDZ or above) can take significant time.</p>
</div>

<div class="faq-item">
  <p class="q">Does GANSU Lite support CCSD(T)?</p>
  <p class="a">No, GANSU Lite does not support CCSD(T). To run CCSD(T), please use <a href="https://github.com/Yasuaki-Ito/GANSU">GANSU</a> (C++ / CUDA, GPU-enabled).</p>
</div>

<div class="faq-item">
  <p class="q">I want to implement the equations from the book myself.</p>
  <p class="a">The <a href="https://github.com/Yasuaki-Ito/GANSU">GANSU source code</a> serves as a reference implementation. A future supplement will publish the mapping between equation numbers in the book and the corresponding source locations.</p>
</div>

<div class="ornament">❦</div>

## Contact

<div class="contact">
  <p>Errata reports, questions, and feedback are warmly welcomed via the form below.</p>
  <p><a class="btn" href="https://forms.gle/EmTWhXoxAEaDB8U3A">Open contact form →</a></p>
</div>
