# 2025-4Cinf-ex-instanceof
Esercizi su instanceof

```mermaid
 classDiagram
    class CreaturaFantastica
    class Folletto
    class Mostro
    class Fata
    class Gnomo
    class Drago
    class Scheletro
    class Vola

    CreaturaFantastica <|-- Folletto
    CreaturaFantastica <|-- Mostro
    Folletto <|-- Fata
    Folletto <|-- Gnomo
    Mostro <|-- Drago
    Mostro <|-- Scheletro
    Vola <|.. Drago
    Vola <|.. Fata
```
