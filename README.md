# Dongba World

A small 3D village built entirely from Dongba (纳西东巴文) glyphs. Walk around, meet villagers, cook, play music, practise writing in the study, and look up what every glyph means.

一个完全由纳西东巴文字搭建的小村庄。可以四处走动、和村民互动、做饭、演奏音乐、在学字台练字，并查看每个字的释义。

## Run locally

Open a terminal in this folder and run:

```
python3 -m http.server 8000
```

Then open http://localhost:8000 in a browser. (Opening `index.html` directly from the file system will not work, because the page loads its data with `fetch`.)

## Controls

- WASD — walk · Shift — run · Space — jump · C — sit
- F — interact · G — put down · Q / E — turn · right-drag — look · scroll — zoom
- Click any glyph to see its meaning
