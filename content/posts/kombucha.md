---
title: "Kombucha"
date: 2022-10-04T16:53:00+02:00
draft: true
author: Erik
images: ["images/kombucha.jpg"]
featuredImagePreview: "images/kombucha.jpg"
math: true
---

Fast jeder hat schon davon gehört oder kennt jemand der es mal ausprobiert hat.
Manche haben auch schon probiert. Entweder eine industriell abgefüllte
Version oder eine übergärige (...kommt noch) Flasche in einem
veganen Hipster Cafe.


<!-- ## Braumethoden -->
<!-- ### Batch -->
<!-- ### Kontinuerlich  -->
# 1. Fermentation 
## Rezept
### Kräuter-Kombucha
| Wieviel   | Einheit   | Was |
| --------- | --------- | --- |
| 8         |  Beutel (2 gr) | nicht-aromatisierter Kräuter-Tee |
| 200       | Gramm     | weißer, raffinierter Zucker |
| 250       | Mililiter | reife, saure Ansatzflüssigkeit |
| 1         | Stück     | SCOBY |

### Schwarzee-Kombucha
| Wieviel   | Einheit   | Was |
| --------- | --------- | --- |
| 10         |  Beutel (2 gr) | Darjeeling |
| 200       | Gramm     | weißer, raffinierter Zucker |
| 250       | Mililiter | reife, saure Ansatzflüssigkeit |
| 1         | Stück     | SCOBY |

## Anleitung
Da ich persönlich der Ansicht bin, denn Tee abzuschrecken anstatt langsam auf
Zimmertemperatur abkühlen zu lassen, beschreibe ich in der Anleitung auch nur diesen Fall.

```mermaid
graph TD;
    0[Start] --> Z
    0[Start] --> A

    Z[SCOBY und Ansatzsflüssigkeit abmessen und bereitstellen]
    A[1 l Wasser aufkochen] --> B[Tee hinzugeben und 10 min ziehen lassen];
    A --> D[Zucker abwiegen]
    B --> C[Teeblätter entfernen];
    C --> E[Zucker hinzugeben und verrühren]
    E --> F[2 l kaltes Wasser hinzugeben]
    Z -->|text| E
```

