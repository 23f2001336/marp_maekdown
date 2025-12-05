---
marp: true
title: Product Documentation Overview
author: Technical Writer
theme: custom-docs
paginate: true
footer: 23f2001336@ds.study.iitm.ac.in
---

<style>
/* @theme custom-docs */
section {
  background-color: #0f172a;
  color: #e5e7eb;
  font-size: 26px;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

h1, h2 {
  color: #38bdf8;
}

code {
  background-color: #020617;
  color: #f8fafc;
  padding: 6px 8px;
  border-radius: 6px;
  font-size: 0.85em;
}

/* Custom class for lead slide */
section.lead h1 {
  font-size: 2.6em;
}

section.lead h2 {
  font-size: 1.4em;
}
</style>

<!-- _class: lead -->

# Product Documentation System  
### Software Engineering Team  

📧 **23f2001336@ds.study.iitm.ac.in**

---

## Why Marp for Documentation?

- Markdown-based **single source of truth**
- Easy to track in **Git / GitHub**
- Can be converted to:
  - PDF
  - PowerPoint (PPTX)
  - HTML slides
- Supports:
  - Custom themes
  - Background images
  - Math formulas
  - Code blocks

---

<!-- This slide has a background image (required by assignment) -->

![bg](https://images.unsplash.com/photo-1519389950473-47ba0277781c)

# System Architecture Overview

- Cloud-native deployment
- Microservices-based design
- REST + gRPC APIs
- Central documentation hub

📧 23f2001336@ds.study.iitm.ac.in

---

## Algorithmic Complexity (Math ✅)

For a typical optimized search routine:

\[
T(n) = O(n \log n)
\]

Dynamic programming recurrence used in our analytics engine:

\[
DP(n) = DP(n-1) + DP(n-2)
\]

Used in:

- Search optimization
- Recommendation pipelines
- Caching and precomputation

---

## Custom-Styled Code Block

```python
def binary_search(arr, x):
    low, high = 0, len(arr) - 1

    while low <= high:
        mid = (low + high) // 2
        if arr[mid] == x:
            return mid
        elif arr[mid] < x:
            low = mid + 1
        else:
            high = mid - 1

    return -1
