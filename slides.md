---
marp: true
title: Product Documentation Overview
author: Technical Writer
theme: custom-theme
paginate: true
footer: 23f2001336@ds.study.iitm.ac.in
---

<style>
section {
  background-color: #0f172a;
  color: #e5e7eb;
  font-size: 26px;
}

h1, h2 {
  color: #38bdf8;
}

code {
  background-color: #020617;
  color: #f8fafc;
  padding: 6px;
  border-radius: 6px;
}
</style>

# Product Documentation System  
### Software Engineering Team  
📧 **23f2001336@ds.study.iitm.ac.in**

---

## Why Marp for Documentation?

- ✅ Markdown-based documentation  
- ✅ Easy Git version control  
- ✅ Converts to:
  - PDF
  - PowerPoint
  - HTML
- ✅ Supports:
  - Themes
  - Styling
  - Math
  - Backgrounds

---

<!--
_backgroundImage: url("https://images.unsplash.com/photo-1519389950473-47ba0277781c")
_backgroundSize: cover
-->

# System Architecture  
### Background Image Slide ✅

- Cloud-native
- Microservices-based
- API-first design

📧 23f2001336@ds.study.iitm.ac.in

---

## Algorithmic Complexity (Math ✅)

For an optimized search algorithm:

\[
T(n) = O(n \log n)
\]

Dynamic Programming recurrence:

\[
DP(n) = DP(n-1) + DP(n-2)
\]

Used in:
- Search optimization
- Recommendation engines
- Caching strategies

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
