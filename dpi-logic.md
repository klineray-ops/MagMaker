# DPI logic
printWidthIn: A4=8.27, A5=5.83, 5x8=5.0
effectiveDPI = min(imgW/printW, imgH/printH)
>=300 green Print-ready, 150-299 amber OK for web, <150 red Low quality
Show math: "1800 px / 8.27 in = 218 DPI"
