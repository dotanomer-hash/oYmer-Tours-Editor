# oYmer VR Tours - the published editor

This repository exists for one reason: **GitHub Pages cannot serve a private repository.**
It holds a published copy of the oYmer VR Tours editor and nothing else.

Live at **https://editor.omerdotan.com**

## This is not the source

The source is the private repository `oYmer-VR-Tours`, and the master file there is
`Tours-Editor.html`. Never edit `index.html` here - the next publish overwrites it.
`Tours-Build.js` in the product folder copies the master into this repo byte for byte.

## Why it is separate from omerdotan.com

Omer's rule, 2026-09-02: the VR Tours editor is a different product from the website.
omerdotan.com is his Hebrew services site and only links here. The editor is English only,
and may grow a login or a price. They share no files, no folder and no domain - only a link.

## What is in here

| File | What it is |
|---|---|
| `index.html` | the editor, a byte-for-byte copy of `Tours-Editor.html` |
| `media/tutorial-en.js` | the Tutorial window, English |
| `media/tour-tutorial.mp4` | the clip it plays |
| `media/tutorial-poster.jpg` | its poster frame |
| `CNAME` | tells GitHub Pages to answer on editor.omerdotan.com |
| `.nojekyll` | stops Jekyll processing the files |

Copyright 2026 Omer Dotan / oYmer VR. All rights reserved. Proprietary software - published
here to be run, not to be copied or reused.
