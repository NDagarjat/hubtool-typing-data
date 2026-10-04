# HubTool Typing Corpus Dataset

Official multi-language dataset powering the **Pro Typing Speed Test & Practice Suite** on **[HubTool.cc](https://hubtool.cc)**.

This repository hosts over **33,000+ curated, clean typing passages** across **16 world major languages**, categorized into 4 difficulty tiers and optimized for zero-latency in-browser streaming via jsDelivr CDN.

---

## Supported Languages (16 Global Locales)

| Code | Language | Country / Region | Files Available |
| :--- | :--- | :--- | :--- |
| `en` | **English** | Global / US / UK | Beginner, Medium, Advance, Test Pool |
| `hi` | **Hindi (हिन्दी)** | India (InScript / Devanagari) | Beginner, Medium, Advance, Test Pool |
| `es` | **Spanish** | Spain / Latin America | Beginner, Medium, Advance, Test Pool |
| `fr` | **French** | France / Canada (AZERTY) | Beginner, Medium, Advance, Test Pool |
| `de` | **German** | Germany / Austria (QWERTZ) | Beginner, Medium, Advance, Test Pool |
| `pt` | **Portuguese** | Brazil / Portugal | Beginner, Medium, Advance, Test Pool |
| `it` | **Italian** | Italy | Beginner, Medium, Advance, Test Pool |
| `ru` | **Russian** | Russia (Cyrillic) | Beginner, Medium, Advance, Test Pool |
| `tr` | **Turkish** | Turkey | Beginner, Medium, Advance, Test Pool |
| `id` | **Indonesian** | Indonesia | Beginner, Medium, Advance, Test Pool |
| `pl` | **Polish** | Poland | Beginner, Medium, Advance, Test Pool |
| `nl` | **Dutch** | Netherlands / Belgium | Beginner, Medium, Advance, Test Pool |
| `vi` | **Vietnamese** | Vietnam | Beginner, Medium, Advance, Test Pool |
| `ar` | **Arabic** | Middle East / North Africa (RTL) | Beginner, Medium, Advance, Test Pool |
| `ja` | **Japanese** | Japan (Kana / Kanji) | Beginner, Medium, Advance, Test Pool |
| `ko` | **Korean** | South Korea (Hangul) | Beginner, Medium, Advance, Test Pool |

---

## Dataset Architecture & Tiers

For each language, the corpus is split into 4 independent JSON chunks:

1. **`{lang}_beginner_360.json`**: 360 foundational short passages (15–35 words) for finger placement & speed drills.
2. **`{lang}_medium_360.json`**: 360 standard encyclopedic paragraphs (36–75 words) for general typing practice.
3. **`{lang}_advance_360.json`**: 360 complex long-form essays (80–160 words) for stamina and endurance testing.
4. **`{lang}_test_pool_1000.json`**: 1,000 comprehensive test paragraphs strictly containing numbers, dates, and punctuation for standardized certified examinations.

---

## Direct CDN Usage (jsDelivr)

All JSON chunks are served globally via jsDelivr Anycast CDN with zero CORS restrictions.

* **Base CDN URL:** `https://cdn.jsdelivr.net/gh/NDagarjat/hubtool-typing-data@main/{filename}.json`
* **Example Hindi Medium:** `https://cdn.jsdelivr.net/gh/NDagarjat/hubtool-typing-data@main/hi_medium_360.json`
* **Example English Test:** `https://cdn.jsdelivr.net/gh/NDagarjat/hubtool-typing-data@main/en_test_pool_1000.json`

---

## Attribution & Licensing

> **Notice:** This dataset is provided for open educational, linguistic, and skill-testing purposes.

| Entity | Details |
| :--- | :--- |
| **Data Source** | Text passages are harvested and sanitized from [Wikipedia](https://www.wikipedia.org/) via the [Wikimedia Action API](https://www.mediawiki.org/wiki/API:Main_page). |
| **License** | Distributed under the **[Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)**. |
| **Platform** | Curated, maintained, and utilized by **[HubTool.cc](https://hubtool.cc)** for browser-based keystroke evaluation and certified assessment tools. |
