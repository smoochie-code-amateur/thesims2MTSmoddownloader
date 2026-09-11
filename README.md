# MTS TS2 Downloader

A desktop application to browse, search and download custom content (CC) for **The Sims 2** from [modthesims.info](https://modthesims.info). Built with Qt 5 and C++17.

### FOR LINUX ONLY.

## Features

- **Category browser** — the full MTS download category tree (Lots & Housing, Sims, Body Shop, Objects, …) with live item counts, sub-categories and age groups (e.g. Clothing: Baby/Toddler, Infant, Child, Teen, Young Adult, Adult, Elder).
- **Listing filters** — sort order, object type, required expansion packs, plus the per-category search filters parsed live from the MTS sidebar.
- **Detail view** — description, screenshot gallery with prev/next navigation, and stats (views / downloads / thanks).
- **Infinite scroll** — the card grid loads more results as you scroll and adapts to the window width.
- **Author profiles** — avatar, "about me", terms of use, stats, and the author's other downloads.
- **Organized downloads** — each item is saved to

  ```
  ~/Downloads/MTS/<subsection>/<category>/<sex>/<title>/
  ```

  together with a `_info.txt` file, the preview image, and automatic extraction of ZIP archives (requires `unzip`).
- **Wishlist** — save favourite items with one click (the star turns yellow), persisted in SQLite.
- **Download history** — the **Downloads** toolbar button lists everything you've downloaded.
- **Image cache** — LRU memory cache plus an on-disk cache for thumbnails, previews and author avatars (retrieves follow HTTP redirects).
- **Two themes** — dark and light, toggled from the toolbar.
- **Bilingual UI** — English and Українська, switchable in the toolbar.
- No account or login required — the app only reads public pages.


## Notes

- The scraper parses the HTML of modthesims.info. If the site restructures its pages, scraping may need updating.
- This tool only accesses public pages — please respect each content creator's terms of use.
