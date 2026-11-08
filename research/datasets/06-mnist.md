---
title: "MNIST"
years: "1998"
collection: "Handwritten digit images"
scale: "70,000 grayscale 28×28 images"
status: "developing"
spark: "a seven, pixel by pixel"
concern: "benchmark limits"
margin_note: "a very famous number 7"
---

# MNIST

## Collected / origin

- MNIST standardized handwritten digits from NIST source datasets, centering them in 28×28 grayscale images.
- It is conventionally split into 60,000 training images and 10,000 test images.
- The transformation is the point: variable handwriting becomes a fixed, repeatable input for comparing classifiers.

## Why it sticks

- A repeatable benchmark gave neural-network and classifier work a common proving ground.
- It is visually immediate. Anyone can see the task, inspect a mistake, and understand why accuracy became a headline number.
- The dataset became shorthand for “first successful model,” even though the task is unusually clean.

## Caveat in the margin

- Recognizing centered digits is not general vision, handwriting recognition in the wild, or intelligence.
- A benchmark rewards the particular conventions of its split and preprocessing. Be careful when a leaderboard starts sounding like the world.

## Thread it to

- [[02-iris|Iris]]: small benchmark, durable classroom life, and a very narrow slice of a much larger problem.
- [[11-imagenet|ImageNet]]: vision benchmarks grow in scale and messiness, but still inherit labels and chosen tasks.
- [[topics/sourcing-and-ethics|Sourcing, access and ethics]]: a benchmark is not the real world.

## Presentation hook

> The world's most famous handwritten 7, repeated until an entire field could agree on a score.

## Visual scraps

- A giant pixelated 7.
- A hundred tiny digits looking unusually confident.

## Sources

- [[bibliography#MNIST-UCI|MNIST-UCI]]
- [[bibliography#MNIST-NIST|MNIST-NIST]]
- [[bibliography#MNIST-ACCESS|MNIST-ACCESS]]
