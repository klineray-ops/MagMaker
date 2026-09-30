# Mag Maker

Web app to create flippable Bengali / Hindi / English magazines.
A4, A5, 5x8" (Amazon KDP). 16/32/64/128 pages.

## Status
MVP prototype v1 done. Now building React + Vite production version.

## 3-Screen Flow
1. *Create:* Name, Size (A4/A5/5x8"), Language (bn/hi/en), Pages, KSBN (optional)
2. *Editor:* 15 layouts, content upload (.txt/.docx), image upload (DPI check + copyright gate), bleed/margin guides
3. *Export:* Pre-flight check, flipbook preview, PDF Print / Web, Publish link

## Tech
React + Vite, TipTap, Firebase (Auth/Storage/Hosting), LanguageTool API
