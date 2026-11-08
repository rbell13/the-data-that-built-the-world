---
title: "Netflix Prize"
years: "2006–2009"
collection: "Movie ratings"
scale: "100 million ratings, 480,189 subscribers"
status: "developing"
spark: "stars arranged into a matrix"
concern: "reidentification from preferences"
margin_note: "your taste, unexpectedly identifying"
---

# Netflix Prize

## Collected / origin

- Netflix released a large, sparse matrix of movie ratings for a million-dollar recommendation challenge.
- The public competition data contained 100 million ratings from 480,189 subscribers across 17,770 films.
- A private prediction problem became a public scoreboard, with teams optimizing an explicit accuracy target.

## Why it sticks

- It made recommender systems visible as a technical sport: build a better guess about what someone will enjoy.
- Sparse matrices became intuitive, almost physical: rows of people, columns of films, a few stars scattered between them.
- The prize helped establish collaborative filtering as a public ML narrative, not just a quiet product feature.

## Caveat in the margin

- Pseudonyms do not erase identity. Narayanan and Shmatikov showed how sparse ratings could be linked with other public information.
- Data can be “anonymous” only inside a story that ignores what other datasets exist.

## Thread it to

- [[07-enron|Enron Email Corpus]]: different records, same lesson that release and privacy do not neatly separate.
- [[04-Boston Housing|Boston Housing]]: apparently ordinary features can preserve socially consequential information.
- [[topics/sourcing-and-ethics|Sourcing, access and ethics]]: anonymized is not impossible to reidentify.

## Presentation hook

> Your taste in movies is a fingerprint with a popcorn smell.

## Visual scraps

- Matrix of stars, one very large prize ribbon.
- “You may also like” with a tiny warning label.

## Sources

- [[bibliography#NETFLIX-DATA|NETFLIX-DATA]]
- [[bibliography#NETFLIX-PRIVACY|NETFLIX-PRIVACY]]
