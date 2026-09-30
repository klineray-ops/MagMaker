# PROJECT BRIEF: Mag Maker - v1
Client: Kalyan Roy | Date: Oct 2026
Goal: Web app to create flippable Bengali/Hindi/English magazines.

## 1. CORE FLOW
Screen 1 Create: Magazine Name, Size [A4|A5|5x8"], Language [bn|hi|en], Pages [16|32|64|128], KSBN optional
Screen 2 Editor: Layout library (15), preview with bleed/margin, fonts auto by language, image tabs Upload/Search/Generate, fit modes Safe/Fill-to-Bleed/Frame
Screen 3 Export: Pre-flight (spelling, plagiarism google-check, copyright, composition), flipbook preview, PDF Print/Web, Publish link

## 2. TECH
React+Vite, TipTap, StPageFlip, Firebase free tier, LanguageTool API free

## 3. KEY SPECS
- Fonts: bn Noto Serif Bengali+Noto Sans Bengali, hi Tiro Devanagari+Noto Sans Devanagari, en Playfair Display+Poppins
- Layouts (15): Cover Front/Back, Contents, Poem Centered, Image Left/Text Right, Full Image, Quote Breaker, 2-Column, Editor Note, Ad Full, Ad Half, Chapter Opener, Timeline, Thank You, Bleed Overlay
- Bleed: A4/A5 3mm, 5x8" 0.125in. Margins: A4 1.5cm, A5 1.2cm, 5x8" inside 0.5in outside 0.375in
