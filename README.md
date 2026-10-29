Developer from Ukraine. I build data tools, AI features and web products with AI coding agents, under my own specs, tests and review. Right now I'm building a small data business on Apify.

## Data tools on Apify

- [Shopify Store Leads & Finder](https://apify.com/insanedev/shopify-store-list): an index of 950K Shopify stores found through Chrome UX Report, Tranco and Common Crawl, DNS checks and each store's public metadata. A scheduled pipeline on Apify refreshes it and runs a QA gate before publishing. Apps, theme and public contacts are read live from each storefront.
- [Shopify Price Tracker & Scraper](https://apify.com/insanedev/shopify-price-tracker): Shopify and WooCommerce catalogues with price, stock and new-product changes between runs.
- [Google Trends API & Scraper](https://apify.com/insanedev/google-trends-scraper): up to 50 terms on one 0-100 scale, and daily data for years stitched from 269-day windows.
- [Google Trends Trending Now API](https://apify.com/insanedev/google-trends-trending-now): real-time trending searches in 125 countries.

Each Actor is benchmarked against the top Apify Store alternatives before release.

## AI

- An in-app LLM assistant for a company system: role agents, skills bound to tools and a map of the screens, so it knows where the user is. 141 eval cases with an LLM judge check it.
- A remote MCP server with OAuth (RFC 8414, 9728, 7591) and 6 read-only tools, so AI assistants can read projects, tasks and the knowledge base.
- Speech-to-text and OCR pipelines with faster-whisper and RapidOCR.
- Custom Claude Code skills and hooks for my own projects; agents write most of the code, and the specs, tests and review are mine.

## Other work

- **Tech-stack detector (Go):** 7,542 technologies and 13,923 patterns. An Aho-Corasick prefilter cut matching from 221 ms to 12 ms per page, with a test showing it drops nothing.
- **Company system (Laravel 13, React 19):** projects, tasks, HR and a knowledge base; 574 PHP test files.
- **Escrow marketplace for YouTube channels (Laravel, React):** a 14-step deal flow with two 7-day waits, encrypted deal chat, a wallet ledger and 1,449 tests on Postgres.
- **Telegram:** a marketplace for channels that vets reach through MTProto and tests a TON NFT sale contract; a Mini App for a barbershop with bookings, loyalty and HMAC-verified sign-in.
- **Smaller things:** a Rust/Tauri tray timer, WordPress themes built to a Lighthouse budget (mobile performance 97-98, CLS 0).

## Stack

Python, TypeScript/Node, Go, Rust, PHP · Laravel, React, Astro, FastAPI, Tauri · Postgres, Docker · Apify, Crawlee, Playwright · MCP, LLM evals · Telegram Bot API, MTProto, TON · WordPress

Site: [insanedev.dev](https://insanedev.dev) · Contact: hello.insanedev@proton.me
