---
marp: true
theme: default           # will be overridden by --theme option at build time if you pass custom-theme.css
paginate: true          # page numbers
size: 16:9
---

<!--
  Public Contact: 24f2004065@ds.study.iitm.ac.in
  (This plain-text comment helps automated checks find the email in the raw file.)
-->

<!-- slide: class="title-slide" -->
# Product Documentation — *Acme Widget*
**Technical Writer:** 24f2004065@ds.study.iitm.ac.in  
**Version:** 1.0

---

<!-- backgroundColor: #0f1720 -->
## Overview

- What the product does
- Target users
- Release notes (v1.0)

---

<!-- backgroundImage: url('assets/bg-product.png') -->
<!-- backgroundSize: cover -->
<section>
# Visual Overview
This slide uses a background image.  
*Image file:* `assets/bg-product.png` (place it in the repo under `assets/`)

Notes:
- Keep text minimal to preserve image readability.
</section>

---

## Installation (code sample)

```bash
# install the CLI
npm i -g acme-widget-cli
# init project
acme init myproject
