---
title: "Challenges for biological data management in the context of AI"
author: "Erick Ratamero"
format:
  revealjs:
    incremental: true
    transition: slide
    auto-stretch: true
---

# Personal intro

## Hello!

:::: {.columns}

::: {.column width="60%"}
- I am **very** excited to be here!
- Quick background:
    - Engineering undergrad 
    - Computational physics M.Sc. and Ph.D.
    - Working with microscopy data for the last (almost) 8 years
- Outside work: video games (especially speedrunning), hiking, swimming
:::

::: {.column width="40%"}
```{=html}
<video style="display: block; margin: 0 auto;" controls muted autoplay loop>
  <source src="datamanagementAI_images/myVisitedPlaces.webm" type="video/webm">
</video>
```
:::

::::

::: {.notes}
Speaker notes go here.
:::

# Let's talk about AI (the fun part)

## AI is data-hungry.{.center}


## 

![](datamanagementAI_images/sa1b.png){width=80% fig-align="center"}

::: aside
Kirillov A, Mintun E, Ravi N, Mao H, Rolland C, Gustafson L, Xiao T, Whitehead S, Berg AC, Lo WY, Dollár P. Segment anything. In Proceedings of the IEEE/CVF international conference on computer vision 2023 (pp. 4015-4026).
:::

## Provisioning, storing, maintaining large amounts of data is _not trivial_. {.center}

##

![](datamanagementAI_images/100years.png){width=80% fig-align="center"}

::: aside
from [Century-Scale Storage by Maxwell Neely-Cohen](https://lil.law.harvard.edu/century-scale-storage/)

from [AWS S3 Pricing](https://aws.amazon.com/s3/pricing/)
:::

![](datamanagementAI_images/aws.png){width=80% fig-align="center"}

## _Any_ data won't be enough. {.center}

## AI (the good part)
 - Requires a LOT of data: how to make a lot of data accessible?
 - Requires "good data" - what does that mean? Metadata, annotations provide context
 - the imaging case: NGFF challenge as blueprint

# Let's talk about AI (the ugly part)

## AI (the bad part)
 - Licensing situation is more and more complicated
 - Resource issues: crawlers, bots, and so on

## The bad part has no clear solution and will be an evolving picture for the near future

## The good part is solved on the technical side; the challenge is societal/lowercase-p political
