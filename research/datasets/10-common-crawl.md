---
title: "Common Crawl"
years: "Crawling since 2008"
collection: "Publicly accessible web pages"
scale: "Web-scale archives"
status: "developing"
spark: "the web boxed into archives"
concern: "permission, exposure, and representation"
margin_note: "the internet in a warehouse"
---

# Common Crawl

## Collected / origin

- A nonprofit web crawler gathers pages and makes large crawl archives available as raw WARC files and derived formats.
- The basic pipeline is easy to sketch and hard to comprehend at scale: URL → fetch → archive → extract → filter → somebody else's dataset.
- The crawl is infrastructure, not a single curated corpus. Downstream builders decide which releases, languages, pages, and filters become “the data.”

## Why it sticks

- It is background scenery for much of the modern language-data story.
- The collection makes web-scale text and metadata accessible enough for research groups to build new corpora without crawling the entire web themselves.
- It makes the difference between an archive and a dataset important: an archive holds possibilities; a dataset is a set of choices.

## Caveat in the margin

- Publicly reachable is not blanket permission for every reuse. Exposure, copyright, personal data, and terms do not evaporate at crawl time.
- The crawl reflects what the web exposes, links, and serves to a crawler. That is not the same as a representative sample of human language or knowledge.

## Thread it to

- [[03-project-gutenberg|Project Gutenberg]]: text becomes computational material through a much more deliberate, rights-conscious collection path.
- [[13-webtext|WebText / GPT-2]]: WebText selects a slice of linked pages; Common Crawl is part of the much larger source landscape.
- [[14-laion-5b|LAION-5B]]: image-text metadata can be derived from crawl-scale web material, then filtered into a new training resource.

## Presentation hook

> The internet, boxed and labeled “misc.” Then filtered until it looks like a dataset.

## Visual scraps

- URL → crawler → WARC → text, like a conveyor belt.
- The internet in a warehouse.

## Sources

- [[bibliography#CC-ABOUT|CC-ABOUT]]
- [[bibliography#CC-OVERVIEW|CC-OVERVIEW]]
