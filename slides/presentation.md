---
marp: true
theme: archive
size: 16:9
paginate: true
title: The Data That Built the World
description: A brief history of influential datasets
---

<!-- _class: title -->
<!-- _paginate: false -->

# The Data That Built the World

### From handwritten records to a serious hoarding problem

A brief history of humanity's obsession with collecting things.

---

<!-- _class: statement -->

# Before we taught computers to understand the world...

## We had to turn the world into data.


---

<!-- _class: chapter -->

# 01 / COUNTING THE WORLD

## Before machine learning

---

<!-- _class: dataset -->

## 1854 / PUBLIC HEALTH

# John Snow's Cholera Map

Rejection of the _Miasma Theory_

\[[Download the GIS data](https://johnsnow.rtwilson.com/download.html)\]

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
</div>

<!-- This first dataset is the famous John Snow cholera map. On slides introducing a dataset, there are links to places where the data is publicly available, for your own research and modeling. -->

---

# What was collected?

A pretty map of dead people!

![bg right:45% contain](../assets/images/john-snow-cholera-map.jpg)

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
</div>

<!-- By combining geographic data, interviews, and observations, he helped establish the importance of contaminated drinking water in transmitting cholera, tying the outbreak to a single pump.--> 

---

# What changed?

**1854: Humanity discovers that plotting dead people on a map can reveal why they're dying.**

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
</div>

<!-- As a caveat, the outbreak had already largely run its course, so while they did remove the pump handle, cholera was already in decline. What we got was a new technique for representing data in real-world dimensions. Flash forward to... -->

---

<!-- _class: dataset -->

## 1890 / UNITED STATES

# The Census

__62,979,766 Americans. One enormous data-processing problem.__

\[[View surviving 1890 census fragments](https://www.archives.gov/research/census/1890)\]

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
</div>

<!-- Well approximately 62,979,766 Americans... --> 

---

# The problem

In 1888, the Census Bureau ran a desperate competition to solve the census's central problem: tabulating the count took too long.

**The solution?**

Herman Hollerith's electromechanical tabulating machines.

![bg right:45% contain](../assets/images/herman-hollerith.jpg)

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
</div>

<!-- The 1880 census took until 1887, nearly a decade, so the Bureau had to really crank this one out. After Hollerith's approach crushed the alternatives, they went with his machine.

If the punch-card method sounds familiar to anyone aware of early computing, that's because it is. He didn't invent the electromechanical punch-card system, but he does have a connection to IBM.

Hollerith's company became part of the Computing-Tabulating-Recording Company, which adopted the IBM name in 1924. -->

---

<!-- _class: concern census-categories -->

<div class="concern-badge">REPRESENTATION</div>

# The category machine

### The 1890 Census officially recognized eight racial categories: 

| Category     | Historical classification        |
| ------------ | -------------------------------- |
| **White**    | Classified as white              |
| **Black**    | ¾ or more Black ancestry         |
| **Mulatto**  | ⅜ to ⅝ Black ancestry            |
| **Quadroon** | ¼ Black ancestry                 |
| **Octoroon** | ⅛ or any trace of Black ancestry |
| **Chinese**  | Classified as Chinese            |
| **Japanese** | Classified as Japanese           |
| **Indian**   | Classified as American Indian    |

[The original 1890 instructions to enumerators](https://www.census.gov/programs-surveys/decennial-census/technical-documentation/questionnaires/1890/1890-instructions.html)

<!-- The definitions above follow the official 1890 instructions.

Of course there was no self-identification; you were slotted into whichever of these the enumerator deemed you fit.

1890 was the first census to introduce _Japanese_, _quadroon_, and _octoroon_ as distinct categories. By 1900, the supposedly precise categories of _mulatto_, _quadroon_, and _octoroon_ had vanished from the census.
-->

---

<!-- _class: dataset -->

## 1971 / DIGITAL LIBRARIES

# Project Gutenberg

**What if every book ever written could live on a computer?**

\[[Browse free ebooks](https://www.gutenberg.org/ebooks/)\]

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓   Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
</div>

<!-- 
Founded by Michael Hart in 1971, Project Gutenberg pioneered the digitization and free distribution of books and other written works.
-->

---

# What was collected?

It all began when Michael Hart manually typed the **Declaration of Independence** into a university mainframe.

It became Project Gutenberg's first ebook.

![bg right:45% contain](../assets/images/michael-s-hart-teletype.png)

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓   Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
</div>

<!-- **The first ebook was approximately 5 KB.**
Books are transcribed, OCR'ed, and proofread by volunteers. More importantly, they are now machine-readable.
 -->

---

<!-- _class: concern -->

<div class="concern-badge">RIGHTS &amp; ACCESS</div>

# Books have borders

## Jurisdiction and rights.

Public-domain status shifts across jurisdictions. A digitized page can still carry rights questions.

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓   Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
</div>

<!-- **The copyright catch:**

Most works are in the US public domain, but some are distributed with permission. Copyright varies by country, and free access doesn't automatically grant unrestricted reuse.

This presentation is released under the Creative Commons Attribution-ShareAlike 4.0 license. -->

---

<!-- _class: chapter -->

# 02 / MEASURING THE WORLD

## The rise of statistical datasets

---

<!-- _class: dataset -->

## 1936 / BOTANY

# The Iris Dataset

**150 flowers. 4 measurements. 90 years of homework.**

\[[Open dataset at UCI](https://archive.ics.uci.edu/dataset/53/iris)\]

<!--
Despite containing only 150 observations, it is still routinely used to introduce students to classification algorithms and as such has become one of the most recognizable datasets in statistics, data science, and machine learning education.

Source: Fisher (1936); UCI Machine Learning Repository.
-->

---

# A Remarkably Small Dataset

The measurements, and some graphs of their distributions:

- Sepal length and width
- Petal length and width
- Species: Setosa, Versicolor, Virginica

![bg right:45% contain](../assets/images/scikit-learn-iris-pca.png)

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers
</div>

<!--
The dataset contains exactly 50 observations from each of three iris species, made up of 4 measurements each.

The objective is simple: can we predict which species a flower belongs to using only those measurements?

Iris Setosa is relatively easy to distinguish. Iris Versicolor and Iris Virginica overlap more, making them a more interesting classification problem.

Source: UCI Iris Dataset.
-->

---

# What Changed?

### The "Hello, World!" of machine learning.

Nearly a century later, students still use these flowers to learn:

- Classification
- Decision trees/K-nearest neighbors
- Data visualization

**Humanity has spent decades teaching computers to identify the same three flowers.**

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers
</div>

<!--
Today, it appears in introductory machine learning courses, tutorials, textbooks, and literally baked into packages such as scikit-learn.

Students often train their first classifiers using Iris because it's small, relatively clean, and easy to visualize.

Source: Fisher (1936); UCI Machine Learning Repository; scikit-learn documentation.
-->

---

<!-- _class: concern -->

<div class="concern-badge">PROVENANCE</div>

# Small, Not Neutral

## Even 150 flowers have a complicated history.

**Two records in the commonly distributed UCI version differ from Fisher's original publication.**

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers
</div>

<!--
That being said, despite the diminutive size of this dataset, there are, of course, typos across the versions.

There are even questions as to the origin of the Virginica samples.

The larger point: a dataset does not become ground truth simply because it is widely used, and ground truth tends to lose fidelity over time.

Sources: UCI Iris Dataset; Unwin and Kleinman (2021).
-->

---

<!-- _class: dataset -->

## 1978 / HOUSING

# Boston Housing

**Can we put a price on clean air?**

506 neighborhoods. 13 features. One housing-price prediction.

\[[Open dataset at GeoDa](https://geodacenter.github.io/data-and-lab/boston-housing/)\]

<!--
In 1978, some economists published a study trying to answer the question: how much do people value clean air?

It's difficult to put a price tag on something like air quality, so they looked
at housing prices. The idea was that a house's value reflects more than the
building itself. You're also paying for the neighborhood, nearby services,
environmental conditions, and other factors.

They assembled data describing 506 census tracts in the Boston area, drawing
heavily on 1970-era records.
-->

---

# What Was Collected?

### 506 census tracts. 14 columns.

**The goal: explain why some neighborhoods cost more than others.**

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers<br>
  ✓ Housing with "clean air"
</div>

<!--
This doesn't model the price of a house; rather, it models neighborhood housing values.
The full dataset has 13 explanatory variables and one target variable.

They collected information about housing, land use, crime, local schools,
pollution, transportation, and demographics.

I wonder if you can see where I am going with this...
-->

---

# A Quick Tour of the Variables

### Everything seems perfectly reasonable.

| Variable  | Description               | Assessment |
| --------- | ------------------------- | ---------- |
| `CRIM`    | Crime rate                | ✓          |
| `INDUS`   | Industrial land           | ✓          |
| `PTRATIO` | Pupil-teacher ratio       | ✓          |
| `LSTAT`   | "Lower-status" population | ...        |
| `B`       | Racial composition index  | **???**    |

**Hang on. What's `B`?**

<!--
Let's take a closer look at the feature names.

CRIM. Crime. Fair enough.

INDUS. Industrial land. Makes sense.

PTRATIO. Pupil-teacher ratio. A bit awkward as abbreviations go,
but it's a reasonable neighborhood characteristic.

Then we get to LSTAT.

LSTAT stands for "lower status" of the population.

That's not my description. That's the terminology used in the dataset.

The original measure combined two things:
the proportion of adults without some high-school education,
and the proportion of male workers classified as laborers.

So we're taking educational attainment and occupational classifications,
combining them, and calling the result "lower status."

That's already an interesting set of assumptions to bake into a number.

And then there's B.

Just B.

One letter.

Very mysterious.
-->

---

<!-- _class: concern -->

<div class="concern-badge">REPRESENTATION</div>

# The Problem With `B`

### _B_ is derived from the following formula:

$$
B = 1000(B_k - 0.63)^2
$$

Where \(B_k\) is the proportion of Black residents in a town.

<!--
The original authors constructed B using the proportion of Black residents
in each town.

The formula is 1000 times the square of that proportion minus 0.63.

Now, why 0.63?

That number came from the researchers' modeling assumptions, including
the idea that racial self-segregation positively affected housing values.

Meaning: the variable encoded a racial assumption rather than a neutral measurement.

It's a remarkably specific assumption to preserve in a dataset that
subsequent generations of students would just load into Python without
necessarily examining its origins.
-->

---

<!-- _class: chapter -->

# 03 / LEARNING FROM THE WORLD

## When data became training material

<!--
So far, we've collected information about the world.

We've counted people, investigated cholera, digitized books,
measured flowers, and assigned numerical characteristics to neighborhoods.

But in 1990, scientists decided to take things a little further and digitize what makes us human.

This is where our collection gets considerably more personal...

This is also where I realized I had bitten off more than I could chew. I still have the research notes and bibliography, but these next few slides breeze through some awesome datasets that aren't snoozers before getting to the more modern ones you might know less about.
-->

---

<!-- _class: dataset -->
## 1990–2003 / GENOMICS

# Human Genome Project

**Humanity decides to read its own source code.**

An international effort to sequence approximately **3 billion DNA base pairs**.

\[[Browse the GRCh38 reference genome](https://www.ncbi.nlm.nih.gov/assembly/GCF_000001405.40/)\]

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers<br>
  ✓ Housing with "clean air"<br>
  ✓ Human source code
</div>

<!--
In 1990, the Human Genome Project officially began.

The original reference combined DNA from multiple donors.

In 1996, researchers established the Bermuda Principles.

The basic idea was that large-scale human genome sequence data
should be released publicly as quickly as possible. Wow. Scientists learned to share.

The issue is that the reference was not equally representative of all the donors.
**70% of the original reference sequence came from one person!**

Sources: NHGRI Human Genome Project Fact Sheet; NCBI GRCh38.
-->
---

<!-- _class: dataset -->

## 1998 / COMPUTER VISION

# MNIST

**Humanity teaches computers to recognize the numbers 0 through 9.**

\[[Open MNIST on Hugging Face](https://huggingface.co/datasets/ylecun/mnist)\]

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers<br>
  ✓ Housing with "clean air"<br>
  ✓ Human source code<br>
  ✓ 70,000 variations of the number 7
</div>

<!--
MNIST stands for Modified National Institute of Standards and Technology.

A very official name for a collection of handwritten numbers.

MNIST became one of the most recognizable benchmarks
in the history of machine learning.

And much like the Iris dataset, it became a rite of passage
for generations of computer science students.

MNIST contains 70,000 images of handwritten numbers.

60,000 for training, 10,000 for testing. Grayscale. Centered.

Every image contains exactly one digit.

Every digit is centered.

Every answer is an integer from zero to nine.

And we already know the correct answer for every example.

And so of course, MNIST also became educationally inescapable.

Just like Iris.

In real-world machine learning, getting data this clean and ground-truthed
is frequently the difficult part. *Foreshadowing!*

The fixed classification task made it possible to compare CNNs, SVMs, and other models. The catch is that the 10,000 test images were made public, so the answer key is effectively out there.

The concern is not social or ethical, it's methodological: the data is too clean, not like real life, and it's been done to death, so everyone already has the answer key.

Fun bonus connection to previous slides:

MNIST was derived from two earlier NIST handwriting datasets.

One contained handwriting from American high school students. The other was handwriting from employees of the US Census Bureau, of course.

Source: LeCun et al. (1998); UCI MNIST documentation.
-->

---

<!-- _class: dataset -->

## EARLY 2000s / CORPORATE EMAIL

# Enron Email Corpus

**A historic corporate scandal can make for a surprisingly successful dataset.**

 \[[Download the CMU corpus](https://www.cs.cmu.edu/~enron/)\]
 
<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers<br>
  ✓ Housing with "clean air"<br>
  ✓ Human source code<br>
  ✓ 70,000 variations of the number 7<br>
  ✓ 500,000 poorly aged emails
</div>

<!--
The Enron fraud and misconduct scandal is one of the most notorious corporate scandals in American history.

But we're not here for that. You know why we are here.

We are here for the dataset.

A gigantic collection of real workplace emails.

During investigations into Enron's activities, the Federal Energy
Regulatory Commission, or FERC, obtained company records and
made approximately half a million messages from around 150 Enron employees public, most of which belonged to senior management.

Enron went bankrupt. Its emails went on to have a very successful career.

The dataset needed a ton of cleaning, but it laid the groundwork for:

- Spam and email classification
- Natural-language processing
- Social networks and communication patterns
- Search and information retrieval

The concerns here continue the themes present throughout: naturally, massive issues with consent. Some employees got their data redacted from future versions of the dataset, but that doesn't stop the old datasets from continuing to make the rounds.

Sources: Carnegie Mellon Enron Email Dataset; FERC.
-->

---

<!-- _class: chapter -->

# 04 / MAPPING THE WEB

## Data becomes shared infrastructure

<!-- Even faster with this section now. Watch this. -->

---

<!-- _class: dataset -->

## 2006–2009 / RECOMMENDATION

# Netflix Prize

**Please make our recommendations less terrible 👉👈**

\[[View the released competition data](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data)\]

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers<br>
  ✓ Housing with "clean air"<br>
  ✓ Human source code<br>
  ✓ 70,000 variations of the number 7<br>
  ✓ 500,000 poorly aged emails<br>
  ✓ Your embarrassing watch history
</div>

<!--Netflix released 100 million anonymized movie ratings from nearly 500,000 users, offering a $1 million prize to anyone who could significantly improve its recommendation algorithm.

Researchers demonstrated that supposedly anonymous viewing histories could be linked to publicly available IMDb ratings to identify individual users, exposing the limits of anonymization. -->

---


<!-- _class: dataset collection-over-image -->

## 2004 / COLLABORATIVE MAPS

# OpenStreetMap

**Finally, one that is mostly good news**

 \[[Export OpenStreetMap data](https://www.openstreetmap.org/export)\]

<img class="slide-image" src="../assets/images/osm-logo.svg" alt="OpenStreetMap logo">

<div class="collection">
  <strong>HUMANITY'S COLLECTION</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers<br>
  ✓ Housing with "clean air"<br>
  ✓ Human source code<br>
  ✓ 70,000 variations of the number 7<br>
  ✓ 500,000 poorly aged emails<br>
  ✓ Your embarrassing watch history<br>
  ✓ A volunteer-drawn planet 💜<br>
</div>

<!-- A collaborative project where volunteers worldwide collect and map roads, buildings, trails, and other geographic features, creating a free, continuously updated map of the world. And you know what? This one is just awesome. Its edit history makes provenance unusually visible, though coverage remains uneven. -->

---

<!-- _class: dataset collection-over-image -->

## 2008 / WEB ARCHIVE

# Common Crawl

You meant to share that, right?

\[[Access the crawl archive](https://commoncrawl.org/get-started)\]

<img class="slide-image" src="../assets/images/hands-drawing.jpg" alt="Drawing of hands reaching out towards you">

<div class="collection">
  <strong>HUMANITY'S HOARD</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers<br>
  ✓ Housing with "clean air"<br>
  ✓ Human source code<br>
  ✓ 70,000 variations of the number 7<br>
  ✓ 500,000 poorly aged emails<br>
  ✓ Your embarrassing watch history<br>
  ✓ A volunteer-drawn planet 💜<br>
  ✓ Every bit of text on the internet
</div>

<!-- A nonprofit project that continuously crawls and archives billions of web pages, creating massive public datasets used in search, research, and training large language models.
Of course, scraping the public internet at scale raises questions about copyright, consent, privacy, and bias. Just because something is publicly accessible doesn't mean the creator intended it to train AI. -->

---

<!-- _class: dataset -->

## 2019 / LANGUAGE MODELS

# WebText / GPT-2

OpenAI's Reddit-shaped reading list

\[[OpenWebText replica](https://skylion007.github.io/OpenWebTextCorpus/)\]

<div class="collection">
  <strong>HUMANITY'S HOARD</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers<br>
  ✓ Housing with "clean air"<br>
  ✓ Human source code<br>
  ✓ 70,000 variations of the number 7<br>
  ✓ 500,000 poorly aged emails<br>
  ✓ Your embarrassing watch history<br>
  ✓ A volunteer-drawn planet 💜<br>
  ✓ Every bit of text on the internet<br>
  ✓ 8 Million baconing narwhals
</div>

---

<!-- _class: chapter -->

# 05 / SEEING AT SCALE

## Images, faces, and billions of pairs

<!-- At this point, we have lost the plot on consent, ethics, scale, and clean data. -->

---

<!-- _class: dataset -->

## 2009 / COMPUTER VISION

# ImageNet

**ImageNet helped teach computers to recognize objects in millions of photographs.**

\[[ImageNet download portal](https://www.image-net.org/download)\]

<div class="collection">
  <strong>HUMANITY'S HOARD</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers<br>
  ✓ Housing with "clean air"<br>
  ✓ Human source code<br>
  ✓ 70,000 variations of the number 7<br>
  ✓ 500,000 poorly aged emails<br>
  ✓ Your embarrassing watch history<br>
  ✓ A volunteer-drawn planet 💜<br>
  ✓ Every bit of text on the internet<br>
  ✓ 8 Million baconing narwhals<br>
  ✓ The web, judged by gig workers
</div>

<!-- Researchers assembled millions of images organized into thousands of categories, using crowdsourced human labeling to teach computers the difference between dogs, cats, and approximately everything else.

The dataset inherited biases from its image sources and human annotators, including offensive labels and problematic classifications of people, demonstrating that teaching computers to recognize the world also means teaching them human assumptions about it. -->

---

<!-- _class: dataset -->

## 2010–2011 / BIOMETRICS

# MEDS I & II

**Government identification records repurposed for facial-recognition research.**

\[[NIST MEDS catalog](https://www.nist.gov/itl/iad/btg/special-database-32-multiple-encounter-dataset-meds)\]

<div class="collection">
  <strong>HUMANITY'S HOARD</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers<br>
  ✓ Housing with "clean air"<br>
  ✓ Human source code<br>
  ✓ 70,000 variations of the number 7<br>
  ✓ 500,000 poorly aged emails<br>
  ✓ Your embarrassing watch history<br>
  ✓ A volunteer-drawn planet 💜<br>
  ✓ Every bit of text on the internet<br>
  ✓ 8 Million baconing narwhals<br>
  ✓ The web, judged by gig workers<br>
  ✓ Mugshots of the deceased, repurposed as a benchmark
</div>

<!-- The datasets contained 1,309 facial images of 518 individuals, allowing researchers to study how facial recognition performs across different photographs of the same person.

And this dataset right here is the reason I did this entire presentation. MEDS I and II, or the Multiple Encounter Dataset (yes, the S is doing a lot of work), is exactly every feeling and angle of this entire presentation, distilled into one thing.

The data in here is invaluable, historically important, and ethically fraught. The full name of MEDS is Multiple Encounter Dataset (Deceased Persons), and it is made up of booking photographs and related images from criminal cases. The people in the images had died, and agencies including MITRE, the FBI, and NIST assembled the material into an evaluation dataset. The data is high quality for its purpose: ground-truthed despite some errors, messy in resolution, pose, and lighting, and demographically skewed, including a disproportionate number of Black people. It has revolutionized biometrics and remains widely used. You can't just download it from NIST anymore, but researchers can request access. There are better ways to evaluate biometric performance today, but this was huge. The ethics remain deeply complicated.

There is more that can be said, and more that should not be said. Anyways, let's wrap this up with one of the modern datasets we can talk about. -->

---
## 2022 / MULTIMODAL AI

# LAION-5B

**The internet in 5.85 billion pictures (and their captions)**

\[[LAION-5B release and access notes](https://laion.ai/blog/laion-5b/)\]

<div class="collection collection-final">
  <strong>HUMANITY'S HOARD</strong>
  ✓ Cholera deaths<br>
  ✓ Suspiciously categorized citizens<br>
  ✓ Steal this Library!<br>
  ✓ A handful of flowers<br>
  ✓ Housing with "clean air"<br>
  ✓ Human source code<br>
  ✓ 70,000 variations of the number 7<br>
  ✓ 500,000 poorly aged emails<br>
  ✓ Your embarrassing watch history<br>
  ✓ A volunteer-drawn planet 💜<br>
  ✓ Every bit of text on the internet<br>
  ✓ 8 Million baconing narwhals<br>
  ✓ The web, judged by gig workers<br>
  ✓ Mugshots of the deceased, repurposed as a benchmark<br>
  ✓ A crawler's guess at what a picture means
</div>

<!-- This is where things stand now. This is a public dataset of the internet, technically not the images themselves, but links and metadata. They released the first version in 2022, immediately realized they had issues with copyright, labeling, what they could access, and accuracy. Since then, they have been gradually releasing new versions to try and clean up the mess they made. They are using AI trained on this dataset to prune this dataset, and this is just what is publicly available. I think there are a few things we can conclude here. -->

---

<!-- _class: statement -->
<!-- _paginate: false -->

# No dataset is pristine

## The wrong kind of clean can make a dataset less useful

---

<!-- _class: statement -->
<!-- _paginate: false -->

# Ethics is often a secondary consideration

## And you cannot control how others will reuse it


<!-- These two slides can be distilled into this: -->


---


<!-- _class: statement -->
<!-- _paginate: false -->

# The dataset is not the world.

## It is the part of the world we chose to record.

<!-- This presentation grew out of years of encountering these datasets and talking them through with colleagues. The culture around datasets and the way we try to measure our world is continuously fascinating. I spent many hours researching them and found lots of little through lines. I had to cut this presentation from around 45 minutes to what I hope is about 15. If you have more questions or ideas, I would love to keep the conversation going about any of these, or others. -->

---

<!-- _class: bibliography -->
<!-- _paginate: false -->

# Sources / 1 of 2

- **John Snow cholera map and data:** [Wellcome Collection](https://wellcomecollection.org/works/dx4prdbj); [Robin Wilson](https://johnsnow.rtwilson.com/download.html)
- **1890 Census and Hollerith:** [U.S. Census Bureau](https://www.census.gov/programs-surveys/decennial-census/technical-documentation/questionnaires/1890/1890-instructions.html); [National Archives](https://www.archives.gov/publications/prologue/1996/spring/1890-census); [USPTO patent image](https://www.uspto.gov/sites/default/files/2019-12/hollerith-joi-patent.jpg)
- **Project Gutenberg:** [Project Gutenberg](https://www.gutenberg.org/ebooks/)
- **Iris:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/53/iris); [R datasets](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/iris.html)
- **Boston Housing:** [Harrison and Rubinfeld (1978)](https://www.sciencedirect.com/science/article/pii/0095069678900062); [GeoDa data mirror](https://geodacenter.github.io/data-and-lab/boston-housing/)
- **Human Genome Project:** [NHGRI](https://www.genome.gov/about-genomics/educational-resources/fact-sheets/human-genome-project); [GRCh38 at NCBI](https://www.ncbi.nlm.nih.gov/assembly/GCF_000001405.40/)
- **MNIST:** [NIST](https://tsapps.nist.gov/BDbC/Search/Details/387); [LeCun, Cortes, and Burges](https://huggingface.co/datasets/ylecun/mnist)
- **Enron emails:** [Library of Congress](https://www.loc.gov/item/2018487913/); [Carnegie Mellon University](https://www.cs.cmu.edu/~enron/)

---

<!-- _class: bibliography -->
<!-- _paginate: false -->

# Sources / 2 of 2

- **Netflix Prize:** [Netflix / Kaggle](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data); [Narayanan and Shmatikov (2008)](https://doi.org/10.1109/SP.2008.33)
- **OpenStreetMap:** [OpenStreetMap](https://www.openstreetmap.org/export); [OpenStreetMap Wiki](https://wiki.openstreetmap.org/wiki/History_of_OpenStreetMap)
- **Common Crawl:** [Common Crawl](https://commoncrawl.org/get-started)
- **WebText / GPT-2:** [OpenAI](https://openai.com/index/better-language-models/); [OpenWebText](https://skylion007.github.io/OpenWebTextCorpus/)
- **ImageNet:** [Deng et al. (2009)](https://doi.org/10.1109/CVPR.2009.5206848), including Amazon Mechanical Turk label verification
- **MEDS I & II:** [NIST MEDS catalog](https://www.nist.gov/itl/iad/btg/special-database-32-multiple-encounter-dataset-meds); [MEDS-I](https://www.nist.gov/publications/multiple-encounter-dataset-i-meds-i); [MEDS-II](https://www.nist.gov/publications/nist-special-database-32-multiple-encounter-dataset-ii-meds-ii-data-description)
- **LAION-5B:** [Schuhmann et al. (2022)](https://papers.nips.cc/paper/2022/hash/a1859debfb3b59d094f3504d5ebb6c25-Abstract-Datasets_and_Benchmarks.html); [LAION release notes](https://laion.ai/blog/laion-5b/)

Full research bibliography: `research/bibliography.md`
