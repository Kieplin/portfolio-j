---
layout: post
title:  "Aukciszek: cryptographically secure auctions."
date:   2025-06-10 12:00:00 +0200
categories:  projects
---

## *Aukciszek*

*Aukciszek* is a research and development team project developed throughout my master's degree. It is a cryptographically secure auction platform that uses Shamir secret-sharing scheme and multi-party-computation to conduct auctions in a semi-trusted environment. Its server side is developed in Python and the client site is made with Typescript.

The source code is made public at [github.com/Aukciszek](https://github.com/Aukciszek). For testing we conducted auctions on Azure servers and secured their connection with HTTPS and JSON Web Tokens.

I contributed mainly to its server side, implementing cryptographic protocols. I also wrote my [master's thesis]( {{ site.baseurl }}{% post_url 2025-09-30-masters-thesis %}) on it.

### Final presentation (2025-06-10)

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQLpZWpmvOpjXFKqH-kdHTJeTIwpNUchN9TImqghaircoFBxwnMG5z0KylxVnzCF2KbbUALNjQiKA4w/pubembed?start=false&loop=true&delayms=5000" style="width: 100%; aspect-ratio: 16 / 9; border-radius: 8px;" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

### Poster outlining the project (2025-01-22)

[*Aukciszek* on UAM WMI website](https://wmi.amu.edu.pl/wydzial/projekty/studenckie-projekty-badawczo-rozwojowe/20242025/aukciszek)

<iframe src="{{ '/resources/Aukciszek_poster.pdf' | relative_url }}" style="width: 100%; aspect-ratio: 1 / 1;">>
</iframe>

### Pitch deck (2024-11-08)

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTz5lBAl1IXerXNd4A4df_-bxxzMKz6fWfc5v6Fou4NpD-LPqaCLdsboAAqSOg3-S-HCUTBlq7lJM6J/pubembed?start=false&loop=true&delayms=5000" frameborder="0" style="width: 100%; aspect-ratio: 16 / 9; border-radius: 8px;" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

<!-- wideo z prezentacji dla inwestorow
### Animation showing the multi-party computation

<video 
  controls 
  style="width: 100%; aspect-ratio: 16 / 9; background: #000; border-radius: 8px;"
>
  <source src="{{ '/resources/Aukciszek_prezentacja_animacja.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>

### Video recording of an example auction with client and server views.

<video 
  controls 
  style="width: 100%; aspect-ratio: 16 / 9; background: #000; border-radius: 8px;"
>
  <source src="{{ '/resources/Aukciszek_prezentacja_nagranie_aukcji.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>
-->
