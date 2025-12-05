---
marp: true
title: Product Documentation Overview
author: Technical Writer
theme: custom-docs
paginate: true
footer: 23f2001336@ds.study.iitm.ac.in
math: true
---

<style>
/* @theme custom-docs */
section {
  background-color: #0f172a;
  color: #e5e7eb;
  font-size: 26px;
  font-family: system-ui, -apple-system, "Segoe UI", sans-serif;
}

h1, h2 {
  color: #38bdf8;
}

code {
  background-color: #020617;
  color: #f8fafc;
  padding: 6px 8px;
  border-radius: 6px;
}

section.lead h1 { font-size: 2.6em; }
section.lead h2 { font-size: 1.4em; }
</style>

<!-- _class: lead -->

# Product Documentation System  
### Software Engineering Team  

📧 **23f2001336@ds.study.iitm.ac.in**

---

## Why Marp for Documentation?

- Markdown-based documentation
- Easy Git version control
- Converts to:
  - PDF
  - PPTX
  - HTML
- Supports:
  - Custom themes
  - Background images
  - **LaTeX math**
  - Code blocks

---

<!-- Background image slide (required) -->

![bg](https://images.unsplash.com/photo-1519389950473-47ba0277781c)

# System Architecture

- Cloud-native
- Microservices
- CI/CD enabled
- API-first design

📧 23f2001336@ds.study.iitm.ac.in

---

## Algorithmic Complexity (LaTeX Math ✅)

**Merge Sort time complexity (block LaTeX):**

$$ T(n) = O(n \log n) $$

**Binary Search recurrence:**

$$ T(n) = T(n/2) + O(1) $$

**Dynamic Programming relation:**

$$ DP(n) = DP(n-1) + DP(n-2) $$

**Inline example:**  
Binary search runs in **$O(\log n)$** time, while a simple linear scan runs in **$O(n)$** time.

---

## Custom Styled Code Block

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
