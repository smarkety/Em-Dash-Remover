# Em-Dash-Remover
Bookmarklet to remove em dashes from any webpage. Works on WordPress, Shopify, Webflow, Framer, Notion and any CMS.
A lightweight browser bookmarklet that removes em dashes from any webpage and replaces them with contextually correct punctuation. One click, works on any page, no install required.

## Download
Go to [em-dash-remover.html](./em-dash-remover.html), click the download icon (⬇) top right.

---

## Why

AI-generated content, CMS editors and autocorrect love inserting em dashes (—) where they don't belong. This tool lets you clean them up instantly on any page: your own site, a client's WordPress, a Shopify store, a Framer or Webflow site, a Notion export, or anything else.

---

## How it works

The bookmarklet runs JavaScript directly in your browser on the current page. No server, no extension, no permissions required. It scans all visible text on the page and replaces em dashes and en dashes with contextually appropriate punctuation.

**Smart replacement logic:**

| Context | Replaced with | Example |
|---|---|---|
| Before punctuation | removed | `great—,` → `great,` |
| After sentence end | space | `done.—Then` → `done. Then` |
| Between two words | comma | `good—great` → `good, great` |
| En dash (–) | same rules | U+2013 treated identically |
| Fallback | spaced hyphen | anything else → ` - ` |

Changes are visual only. The actual page source is not modified. Copy cleaned text manually or use it for review.

---

## Install

1. Open `em-dash-remover.html` in your browser
2. Copy the bookmarklet code using the Copy button
3. Create a new bookmark in your browser
4. Set the name to **Em Dash Remover**
5. Paste the copied code into the URL field instead of a web address
6. Save

Click the bookmark on any page to run it.

---

## Use cases

- Cleaning up AI-generated copy before publishing
- Reviewing and editing content in WordPress, Shopify, Webflow, Framer, Notion, or any CMS
- Proofreading client websites
- Removing em dashes from blog posts, landing pages, product descriptions, and articles
- Typography cleanup for copywriters, editors, content marketers, and web designers

---

## Files

| File | Description |
|---|---|
| `em-dash-remover.html` | Installer page with bookmarklet code and instructions |

---

## Author

Built by [smarkety](https://smarkety.io).
