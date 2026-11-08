---
title: "LAION-5B"
years: "2022"
collection: "Web image-text associations"
scale: "Roughly 5.85 billion pairs"
status: "developing"
spark: "captions paired with a very large internet"
concern: "privacy, harm, copyright, and safety"
margin_note: "the internet’s caption drawer"
---

# LAION-5B

## Collected / origin

- LAION-5B describes roughly 5.85 billion image-text associations drawn from web-scale material.
- The release is primarily an index of image URLs, captions or alt text, and metadata, rather than one giant downloadable sack of image files.
- CLIP-based similarity filtering helped select pairs from the much larger web collection process.

## Why it sticks

- It makes the scale of modern multimodal training data feel almost absurd: captions paired with a very large internet.
- The dataset is a useful bridge between web archives and image models: links and metadata become a resource for training systems that generate or describe images.
- Its publication sparked wide attention because “open” infrastructure can make both research and harm easier to scale.

## Caveat in the margin

- Web-scale material can include private, harmful, copyrighted, or otherwise sensitive content. A URL and caption do not solve the underlying provenance problem.
- Later releases and project updates added safety changes. “LAION” should not become shorthand for every image model or every version of this dataset.

## Thread it to

- [[10-common-crawl|Common Crawl]]: crawl-scale web material becomes a downstream image-text index through further filtering and selection.
- [[11-imagenet|ImageNet]]: the category-driven image benchmark gives way to an association-driven web-scale collection.
- [[13-webtext|WebText / GPT-2]]: both expose how collection rules turn the web into a model's reading or viewing list.

## Presentation hook

> The internet's caption drawer, opened so wide that the scale bar runs out of room.

## Visual scraps

- Image and alt text, repeated until the page becomes texture.
- A scale bar that runs out of room.

## Sources

- [[bibliography#LAION-RELEASE|LAION-RELEASE]]
- [[bibliography#LAION-PAPER|LAION-PAPER]]
- [[bibliography#LAION-UPDATE|LAION-UPDATE]]
- [[bibliography#LAION-METHODOLOGY|LAION-METHODOLOGY]]
