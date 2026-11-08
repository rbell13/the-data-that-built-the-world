---
title: "ImageNet"
years: "2009 onward"
collection: "Labeled web images"
scale: "3.2 million images, 5,247 concepts in the 2009 paper"
status: "developing"
spark: "a visual filing cabinet"
concern: "taxonomy, labeling, and copyright"
margin_note: "a filing cabinet for the visual world"
---

# ImageNet

## Collected / origin

- ImageNet assembled web images into concepts organized through the WordNet hierarchy.
- The 2009 paper described more than 3.2 million images across 5,247 concepts; the later 1,000-class challenge is a notable subset, not the whole project.
- Human workers verified candidate labels, putting annotation labor at the center of the system rather than outside it.

## Why it sticks

- Scale plus a public challenge changed the tempo of computer vision research.
- It gave researchers a shared task, shared labels, and a scoreboard that made progress feel measurable.
- The dataset demonstrates how a taxonomy can become infrastructure: names chosen for a benchmark travel into model behavior, papers, and products.

## Caveat in the margin

- Categories are choices, not natural law. Taxonomies can be useful and still carry assumptions, omissions, and harmful labels.
- Web images bring copyright, provenance, and representation questions that do not end when an image has a class label.

## Thread it to

- [[06-mnist|MNIST]]: another visual benchmark, scaled from tidy digits to a broad and messier label universe.
- [[14-laion-5b|LAION-5B]]: labeled image collections shift toward web-scale image-text associations and automated filtering.
- [[05-human-genome|Human Genome Project]]: both become reference infrastructures that shape what later research can easily ask.

## Presentation hook

> First, make a filing cabinet for the visual world. Then teach a machine to file faster than anyone can look.

## Visual scraps

- Image-label montage with one very odd taxonomy branch.
- Millions of pictures trying to convince a computer that a dog is a dog.

## Sources

- [[bibliography#IMAGENET-PAPER|IMAGENET-PAPER]]
- [[bibliography#IMAGENET-ANNOTATION|IMAGENET-ANNOTATION]]
