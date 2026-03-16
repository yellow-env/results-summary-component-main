# Frontend Mentor - Results Summary Component Solution

![Design preview for the Results summary component coding challenge](./design/desktop-preview.jpg)
*(Kalau preview.jpg ada di root atau design/, ganti pathnya ya~)*

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
- [My solution](#my-solution)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This is my solution to the **Results Summary Component** challenge from Frontend Mentor. A clean, responsive card that shows your overall result score in a glowing circle, plus a breakdown of category scores (Reaction, Memory, Verbal, Visual) with colorful icons and bars.

Built it with vanilla tech supaya fokus ke HTML/CSS layout & styling — plus sedikit JS buat dynamic load dari data.json biar lebih fleksibel.

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

Bonus (optional): Populate the summary section dynamically using the provided data.json file.

[Live challenge page →](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV)

## My solution

- Pixel-perfect match dengan design (gradient background, circle result glowing, kategori warna spesifik: merah Reaction, kuning Memory, hijau Verbal, biru Visual).
- Fully responsive: desktop dua kolom side-by-side, mobile stack vertikal smooth.
- Hover/focus state di button Continue (gradient shift + scale kecil biar interaktif).
- Dynamic summary dari data.json via fetch JS — biar gampang update skor tanpa ubah HTML.
- Clean code: semantic HTML, CSS variables buat theme mudah, flexbox/grid buat layout.

### Screenshot

![My solution screenshot](./preview.jpg)
*(Tambahin screenshot desktop & mobile kalau bisa, atau pakai yang ada)*

## Links

- Solution URL: [GitHub Repo](https://github.com/yellow-env/results-summary-component-main)
- Live Site URL: [https://yellow-env.github.io/results-summary-component-main](https://yellow-env.github.io/results-summary-component-main)

## Built with

- Semantic HTML5
- CSS custom properties (variables)
- Flexbox & CSS Grid
- Mobile-first responsive design
- Vanilla JavaScript (fetch API untuk load data.json)

## What I learned

- Lebih dalam paham cara bikin gradient keren di circle & background tanpa overkill.
- Praktek fetch JSON lokal + populate DOM dynamically — bagus buat latihan JS dasar.
- Polishing hover/focus states & transitions biar UI terasa hidup meski simple project.
- Pentingnya clean repo & README bagus buat showcase skill ke orang lain.

## Useful resources

- [Frontend Mentor Challenge Page](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV) — design files & style guide.
- [CSS Gradient Generator](https://cssgradient.io/) — bantu bikin gradient circle & bg.
- [MDN Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) — referensi JS fetch.

## Author

- GitHub - [@yellow-env](https://github.com/yellow-env)
- Frontend Mentor - [@yellow-env](https://www.frontendmentor.io/profile/yellow-env) *(kalau udah punya profile, tambahin linknya ya~)*

## Acknowledgments

Big thanks to **Frontend Mentor** buat challenge keren ini! Membantu banget buat improve skill HTML/CSS/JS secara real-project.

Jackpot kalau kamu submit solution ini ke FM — pasti dapet feedback bagus~
