# phototransistor
détection d'objet en mouvement avec phototransistor L14G1, comptage avec arduino

<img width="460" height="350" alt="Screenshot from 2026-01-19 15-39-43" src="./Screenshot_from_2026-01-19_15-39-43.png" />

<img width="460" height="350" alt="Screenshot from 2026-01-19 15-39-43" src="./Screenshot_from_2026-01-19_16-06-15.png" />

```mermaid
graph TD;
    Masse;
    DC12;
    R1K;
    R1M;
    R1M -->|base| L14G1;
    R1K -->|collector| L14G1;
    Masse -->|emitter| L14G1;
    Masse --> R1M;
    DC12 --- R1M;
```
