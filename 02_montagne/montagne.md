# Ma montagne mémoire

Machine: …

| Niveau | Taille déduite de la courbe | Taille annoncée (TP 1) | Débit (Go/s) |
|---|---|---|---|
| L1 | 64K | 320 KiB | 40 |
| L2 | 512K | 2 MiB | 30 |
| L3 | 8M | 8 MiB | 15 |
| RAM | | | |

Taille de ligne déduite du pas: … octets (annoncée: …)

Réponses aux questions 1 à 5:
1. Sur la coupe à pas 1, il y a un palier à 64K, 512K et un à 8M de données. Le premier palier correspond très certainement à L1iB + L1i = 320 KiB, même si . Le deuxième palier correspond à L2 (2 MiB). Enfin, le dernier palier s'observe à 8M, ce qui correspond à L3. Les différences entre les valeurs obtenues sur la courbe et celles annoncées sont très grandes dans le cas de L1 et L2. Une hypothèse est que le premier palier que l'on observe est le palier entre L1i et L1iB, si toutefois il existe. Il faudrait plus de points sur la courbe pour pouvoir conclure. 

2. En mémoire vive, le débit de L1 est d'environ 40 Go/s, celui de L2 d'environ 30 Go/s, et celui de L3 d'environ 15 Go/s. 

