# Ma machine

| Question | Réponse |
|---|---|
| Processeur, architecture |  x86-64 |
| Sockets / cœurs / threads | 1 socket, 4 cores, 2 threads per core (8 in total) |
| Cœurs P / E | no |
| Fréquence de base / max | max : 3.90 GHz, base : 1.30 GHz |
| L1d / L2 / L3, ligne |L1iB: 192 KiB (4 instances), L1i : 128 KiB (4 instances), L2 : 2 MiB (4 instances), L3 : 8 MiB (1 instance) |
| Caches partagés? | level 1 : 0, level 2 : 12, level 3 : 16  |
| SIMD et largeur | sse4, avx2, avx512 |
| Mémoire: capacité, type, canaux | 64 GB, DDR4-3200, LPDDR4-3733, 2 canaux |
| FMA | Oui |

## Crête

- Double précision: 499.2 Gflop/s
- Simple précision: 998.4 Gflop/s
- Un programme python ordinaire peut atteindre 20.0 Gflops/s sur 1 coeur, soit 1/500 eme de la fraction de cette crête. 
- Bande passante mémoire théorique: 13.5 Go/s
- Intensité arithmétique d'équilibre: 37 flop/octet en double précision

## Énergie (optionnel)

- Au repos: … W
- Un cœur occupé: … W
