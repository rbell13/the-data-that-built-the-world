---
title: "Boston Housing"
years: "1978"
collection: "Census-tract housing variables"
scale: "506 Boston-area census tracts"
status: "developing"
spark: "a city compressed into columns"
concern: "segregation, proxies, and targets"
margin_note: "a neat table with sharp edges"
---

# Boston Housing

## Collected / origin

- The rows summarize Boston-area census tracts for a 1978 study of housing values and clean-air questions.
- It became a compact regression benchmark, commonly distributed as 506 rows with 13 features and a median-home-value target.
- Its columns include variables that look routine in a spreadsheet but carry local history, policy, and discrimination inside them.

## Why it sticks

- It is a sharp example of a city compressed into columns, then offered as a tidy prediction problem.
- The dataset exposes a recurring ML move: convert a social outcome into a target, then let correlations look like neutral inputs.
- It remains useful precisely because the unease is visible once the variable names are read closely.

## Caveat in the margin

- The `B` variable encodes a racialized calculation from the original study. It should be named and examined, not treated as an ordinary feature.
- Census tracts are aggregates, not people. Prediction can reproduce the geography of inequality without explaining it.

## Thread it to

- [[01-1890 census|1890 Census]]: official categories and place-based records do not disappear when a table becomes a benchmark.
- [[09-netflix-prize|Netflix Prize]]: both show how seemingly ordinary columns can reveal more about people than their collectors first admit.
- [[topics/sourcing-and-ethics|Sourcing, access and ethics]]: targets and proxies deserve the same scrutiny as model accuracy.

## Presentation hook

> A clean regression exercise, until you read the headers and notice the city underneath the math.

## Visual scraps

- Street grid, price column, historically redlined boundaries.
- A tidy scatter plot with an untidy city underneath.

## Sources

- [[bibliography#BOSTON-HOUSING|BOSTON-HOUSING]]
- [[bibliography#BOSTON-HOUSING-VARIABLES|BOSTON-HOUSING-VARIABLES]]
