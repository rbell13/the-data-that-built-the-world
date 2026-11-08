---
title: "WebText / GPT-2"
years: "2019"
collection: "Reddit-linked web pages"
scale: "Pages linked from posts with at least three karma"
status: "developing"
spark: "an upvote-shaped reading list"
concern: "curation bias and unavailable originals"
margin_note: "an upvote-shaped reading list"
---

# WebText / GPT-2

## Collected / origin

- WebText selected outbound web pages linked from Reddit posts that had received at least three karma.
- That rule turns votes into a loose editorial signal for “worth reading,” with all the cultural and platform-specific preferences that implies.
- The original corpus was not released in full. Descriptions, model work, and later replications stand in for a downloadable original.

## Why it sticks

- It helped make the training corpus a public part of the language-model story.
- The selection rule is memorable because it is neither a library catalogue nor a random sample. It is an upvote-shaped reading list.
- It demonstrates that collection filters are editorial decisions even when they look like code.

## Caveat in the margin

- Reddit's preferences are not the web's preferences, and the web is not the world's preferences.
- Keep WebText separate from released GPT-2 outputs, evaluation data, and open replications such as OpenWebText.

## Thread it to

- [[03-project-gutenberg|Project Gutenberg]]: both organize reading material, but volunteer curation and social-link filtering create very different collections.
- [[10-common-crawl|Common Crawl]]: Common Crawl is broad archive infrastructure; WebText is a selective corpus assembled from a platform signal.
- [[14-laion-5b|LAION-5B]]: both turn web-derived links and metadata into training-data logic at different modalities and scales.

## Presentation hook

> A model reads the web through an upvote-shaped keyhole.

## Visual scraps

- Reddit → links → pages → model.
- A reading list assembled by the crowd.

## Sources

- [[bibliography#WEBTEXT-OPENAI|WEBTEXT-OPENAI]]
- [[bibliography#WEBTEXT-GPT2|WEBTEXT-GPT2]]
- [[bibliography#OPENWEBTEXT|OPENWEBTEXT]]
