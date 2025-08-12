---
marp: true
title: Product Documentation — Overview
theme: product-docs
paginate: true
size: 16:9
math: katex
header: Product Docs — Q3 2025
footer: © 2025 YourCompany
style: |
  /* Extra deck-local styling via Marp directive */
  h2 {
    border-bottom: 3px solid var(--accent);
    padding-bottom: 6px;
  }
---

<!-- _class: lead -->
<!-- _backgroundImage: url('https://raw.githubusercontent.com/23f2004940/product-docs-marp/main/assets/bg.jpg') -->
![bg]('https://raw.githubusercontent.com/23f2004940/product-docs-marp/main/assets/bg.jpg')
# Product Documentation Deck

**23f2004940@ds.study.iitm.ac.in**

Maintainable, versioned, and convertible docs with **Marp**.

---

## Why Marp for Product Docs?

- Author in Markdown ✓  
- Keep **version control** history ✓  
- Convert to **HTML / PDF / PPTX** ✓  
- Use **custom themes** and **directives** ✓

> Tip: This deck uses a **custom theme**, **page numbers**, and **math**.

---

<!-- A slide with a background image -->
<!-- _backgroundImage: url('https://raw.githubusercontent.com/23f2004940/product-docs-marp/main/assets/bg.jpg') -->
<!-- _backgroundSize: cover -->
<!-- _color: #ffffff -->
<!-- _class: lead -->
# Architecture at a glance

Concise, visual overview with branded background.

---

<!-- _class: two-col -->
## Release Process

**Left (process)**
- Feature freeze
- RC build
- Internal QA
- Docs freeze
- GA release

**Right (artifacts)**
- Release notes
- API changelog
- Migration guide
- Helm chart changes
- SDK version bump

---

## Algorithmic Complexity (Math)

Inline: $O(n \log n)$ and $O(1)$ space.

Block:

$$
T(n) = 2\,T\!\left(\frac{n}{2}\right) + O(n)
\Rightarrow T(n) = O(n \log n)
$$

(Enabled via `math: katex`.)

---

## Custom Styling via Directives

This deck uses:

- `theme: product-docs` (custom theme)
- `paginate: true` (page numbers)
- `style:` (deck-specific CSS)
- Slide directives:
  - `_class: lead`, `_class: two-col`
  - `_backgroundImage`, `_backgroundSize`, `_color`

---

## Contact

Questions?  
**23f2004940@ds.study.iitm.ac.in**
