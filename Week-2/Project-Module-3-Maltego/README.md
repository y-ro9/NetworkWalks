# 🕸️ W2-PM3: Maltego based Footprinting

## 🎯 Objective
To install Maltego Graph and utilize its OSINT (Open Source Intelligence) capabilities to visually map and harvest email addresses associated with the target domain `networkwalks.com`.

## 🛠️ Step-by-Step Guide

1. **Installation:** Downloaded and installed Maltego from the official website and registered for a free Community Edition account (Maltego ID).
2. **Graph Setup:** Searched for the `Domain` entity in the Palette and dragged it to the graph area.
3. **Target Configuration:** Double-clicked the entity and renamed it to `networkwalks.com`.
4. **Running Transforms:** Right-clicked the Domain entity, selected `Run Transforms` -> `To Emails @domain [Search Engine]`.
5. **Result:** The graph automatically expanded and mapped the domain to the harvested email: `info@networkwalks.com`.

## ⚠️ Challenges & Troubleshooting
* **Challenge:** Initially had limited API credits for the Community Edition.
* **Solution:** Optimized searches by only running specific transforms (Search Engine) rather than running all available transforms at once, which saved credits and provided precise results.

## 📸 Evidence & Screenshots
![Showing the domain setup](01.JPG)
![howing the graph with email link](02.JPG)
