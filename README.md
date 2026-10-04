# Zeeviiii.github.io

My personal website: **[ZeevTapoohi.com](https://zeevtapoohi.com/)**

## What Is Here

A single page with:
- Python programs that run in the browser (Pyodide)
- Certificates gallery
- Contact form

Programs are loaded automatically from
https://github.com/Zeeviiii/zeev-python-portfolio,
so a new program pushed there shows up on the site without touching this repository.

## How It Is Served

- This repository is the source.
- Cloudflare Workers deploys it to [zeevtapoohi.com](https://zeevtapoohi.com/) on every push to `main`.
- The old address, zeeviiii.github.io, still works and forwards to the new domain.

## Built With

- HTML, CSS and JavaScript, no framework
- Pyodide (Python in WebAssembly)
- Cloudflare Workers (hosting, HTTPS, domain)
- GitHub Pages (old address, forwarding only)
