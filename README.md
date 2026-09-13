<p align="center">
  <img src="Banner.jpeg" alt="عرّاف التراث السعودي" width="100%">
</p>

<p align="center">
  <b>عرّاف التراث السعودي</b> — a Saudi National Day guessing game.<br>
  Think of anything Saudi. It works out what you have in mind from yes / no questions.
</p>

<p align="center">
  <img alt="items" src="https://img.shields.io/badge/items-524-1E8A5C">
  <img alt="questions" src="https://img.shields.io/badge/questions-119-1E8A5C">
  <img alt="engine" src="https://img.shields.io/badge/engine-statistical%2C%20no%20LLM-C9A227">
  <img alt="deps" src="https://img.shields.io/badge/dependencies-none-C9A227">
</p>

---

## What it is

A single HTML file. Open it in a browser and it runs — no server, no build step, no internet
connection, nothing to install. Drop it on a tablet and it works all day at a booth.

The game asks questions in Arabic and narrows down 524 items of Saudi heritage — food, places,
customs, clothing, landmarks, cities, sport, national symbols — using three buttons:
**نعم / لا / لا أعلم**.

There are no model calls at any point. Every answer is handled by arithmetic that runs in about
**16 milliseconds**, so the next question appears instantly.

## Changing the banner image

The banner at the top of this page is `Banner.jpeg`, sitting in the root of this repository.

To replace it: click on `Banner.jpeg` in the file list above, click the trash/pencil icon area
(or use **Add file → Upload files** and upload a new image with the exact same name,
`Banner.jpeg`, to overwrite it) — then commit the change. This README always points at that
filename, so it updates automatically; nothing else needs editing.

If you upload your new image under a different name or file type (e.g. `banner.png`), update the
`src="Banner.jpeg"` at the very top of this file to match.
