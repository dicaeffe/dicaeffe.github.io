---
layout: post
title: "Let's try Jekyll!"
intro: "Just another beginnig."
shortTitle: The beginning
redirect_from:
  - /blog/beginning
date: 2025-04-15 10:29:03 +0200
categories: jekyll update
---

This is the begininning.

I am using the excuse of a personal site to explore the Jekyll opportunity to be used for a static site for technical documentation at work.

# Some html pages to test

- [Pagina template](/template)
- [Prova grafici](/poc_chart)
- [Grafici governi](/gov_chart): durata media di un governo nel tempo.

# How is Markdown rendered?

{:toc}

# h1

## h2

This is a descriptive line

# Another paragraph

- bullet
  - bullet
- bullet

* bullet
  - bullet
* bullet

1. list
   1. list
1. list

## Table

| A   |  B  |   C |
| :-- | :-: | --: |
| 1   |  2  |   3 |

# Mermaid

```mermaid
flowchart TD
    A[Christmas] -->|Get money| B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[fa:fa-car Car]
```

```mermaid
stateDiagram-v2
    [*] --> Still
    Still --> [*]
    Still --> Moving
    Moving --> Still
    Moving --> Crash
    Crash --> [*]
```

```mermaid
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
```

```mermaid!
pie title Pets adopted by volunteers
  "Dogs" : 386
  "Cats" : 85
  "Rats" : 35
```
