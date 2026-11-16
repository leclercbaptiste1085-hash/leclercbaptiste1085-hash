## Baptiste Leclerc

**Data et pilotage financier** · contrôle de gestion · analyse financière · estimation de coûts

Paris · disponible immédiatement · [LinkedIn](https://www.linkedin.com/in/baptiste-leclerc-4b8a34346) · leclercbaptiste1085@gmail.com

---

### À propos

Économiste de formation (Master Économie Appliquée, Université de Lille, mention Bien), je travaille à la jonction de la donnée et de la finance. Je pars d'une question de gestion, je construis un jeu de données fiable, puis je produis un chiffre que la direction peut utiliser.

Chez **EDF**, pendant six mois, comme estimateur de coûts en appui au contrôle de gestion, j'ai :
- construit la trajectoire budgétaire à dix ans d'un marché national, indexée sur un indice contractuel ;
- séparé effet prix et effet volume dans l'analyse des coûts ;
- fiabilisé les extractions SAP ;
- refondu le tableau de bord Power BI partagé par vingt sites.

| Formation | Expérience | Langues |
|:--|:--|:--|
| Master Économie Appliquée, mention Bien | EDF · estimation de coûts, contrôle de gestion | Anglais C1 |
| Économétrie, contrôle de gestion, analyse financière | DRFiP Lille · comptabilité et recouvrement | Espagnol B2 · Italien B2 |

---

### Projets

#### [Reporting producteur d'énergies renouvelables →](https://github.com/leclercbaptiste1085-hash/1-reporting-producteur-energie)

SQL · PostgreSQL · Python · Power BI · données réelles RTE et prix spot, janvier à août 2026

Un producteur éolien et solaire des Hauts-de-France a-t-il tenu son budget ? Et l'écart vient-il de la production ou des prix ?

| Chiffre d'affaires vs budget | Effet volume | Effet prix | Heures à prix négatif |
|:-:|:-:|:-:|:-:|
| **−6,0 %** | **−535 k€** | **+152 k€** | **452 h** |

Le manque à gagner vient du vent, pas du marché. Le solaire ne capte que 39,7 €/MWh, contre environ 73 €/MWh en moyenne sur le marché : c'est l'effet de cannibalisation.

[![Tableau de bord Power BI](https://raw.githubusercontent.com/leclercbaptiste1085-hash/1-reporting-producteur-energie/main/rapport_p1.png)](https://github.com/leclercbaptiste1085-hash/1-reporting-producteur-energie)

#### [Usine : coût de revient réel vs standard →](https://github.com/leclercbaptiste1085-hash/2-usine-cout-de-revient)

SQL · PostgreSQL · Power BI (DAX, PBIP) · prix spot réels de l'électricité 2022-2025

Une usine de pièces automobiles a-t-elle tenu ses coûts standards en 2025 ? Où part l'argent : matière, main-d'œuvre, énergie, rebuts ?

| Écart de coût | Rebuts | Prix de l'électricité | Sous-activité d'août |
|:-:|:-:|:-:|:-:|
| **+331 k€ (+6,3 %)** | **+215 k€** | **−74 k€** | **130 k€** |

Le rebut coûte plus que tous les autres écarts réunis. L'électricité moins chère que prévu a sauvé 74 k€, mais aux prix de 2022 la facture aurait dépassé le budget de 880 k€.

[![Tableau de bord Power BI](https://raw.githubusercontent.com/leclercbaptiste1085-hash/2-usine-cout-de-revient/main/rapport_p1.png)](https://github.com/leclercbaptiste1085-hash/2-usine-cout-de-revient)

#### [La défiance des ménages français envers les valeurs mobilières →](https://github.com/leclercbaptiste1085-hash/3-defiance-valeurs-mobilieres)

R · économétrie (régression, Newey-West, test ADF) · Eurostat, INSEE, AMF

Pourquoi les Français, à revenu comparable, détiennent-ils si peu d'actions, d'obligations et de parts de fonds ?

| Part de l'épargne financière (2025) | Écart à PIB égal | Ménages détenteurs | Parmi les 10 % les plus aisés |
|:-:|:-:|:-:|:-:|
| **10,9 %** (9e sur 10 pays) | **−7,9 points** | **24 % → 17 %** (2004-2024) | **52 % sans aucune** |

Les cours des actions ont été multipliés par 2,5 depuis 1998 et ont effacé chaque krach ; le nombre de détenteurs, lui, ne s'est jamais reconstitué. La crise ne fait pas vendre tout le monde, mais elle réduit durablement le nombre d'épargnants en Bourse.

[![Cours des actions et taux de détention](https://raw.githubusercontent.com/leclercbaptiste1085-hash/3-defiance-valeurs-mobilieres/main/sorties/5_cours_vs_detention.png)](https://github.com/leclercbaptiste1085-hash/3-defiance-valeurs-mobilieres)

#### [La France et la mer : un savoir-faire réel, un espace délaissé →](https://github.com/leclercbaptiste1085-hash/4-france-maritime)

R · données publiques (Eurostat, Cour des comptes) · comptes de cinq industriels cotés

La France possède le deuxième espace maritime du monde. Qu'en fait-elle, et que valent ses industriels de la mer ?

| Aquaculture : Norvège / France | Marge nette de GTT (2025) | Bénéteau, de 2023 à 2025 | Fret porté par le fleuve |
|:-:|:-:|:-:|:-:|
| **× 9** | **51,5 %** | **+12,6 % → −5,1 %** | **1,8 %** |

La valeur est dans la connaissance : GTT vend la conception des cuves de méthaniers, la construction est partie en Asie. Le fleuve, lui, souffre d'un réseau resté au gabarit de 1879.

[![Marge nette des industriels de la mer](https://raw.githubusercontent.com/leclercbaptiste1085-hash/4-france-maritime/main/sorties/3_entreprises_marge.png)](https://github.com/leclercbaptiste1085-hash/4-france-maritime)

#### [La France et la terre : l'agriculture 2.0, mêler au lieu de séparer →](https://github.com/leclercbaptiste1085-hash/5-france-terre)

R · Python · Power BI (DAX, paramètres de simulation, PBIP) · FAOSTAT, INSEE, Eurostat, INRAE

Le rendement du blé plafonne depuis le milieu des années 1990 et la France importe l'essentiel de ses engrais. Que rapporte l'agroforesterie, qui mêle arbres, cultures et bêtes sur le même hectare, et pourquoi a-t-elle disparu ?

| Agroforesterie (gain mesuré) | Part des grandes cultures | Prés-vergers, 1950 → aujourd'hui | Systèmes comparés |
|:-:|:-:|:-:|:-:|
| **× 1,34** | **0,1 %** | **500 000 → 100 000 ha** | **19** |

L'arbre n'a pas reculé parce qu'il produisait moins : la PAC payait l'hectare d'une seule culture. Ce qui subsiste en France vit au contact de l'eau (étangs de la Dombes, riz de Camargue, prés-salés, claires à huîtres), et onze systèmes étrangers montrent qu'on peut encore mêler à grande échelle. Un simulateur Power BI chiffre en complément l'azote que l'on pourrait ne plus perdre.

[![Gain de l'agroforesterie](https://raw.githubusercontent.com/leclercbaptiste1085-hash/5-france-terre/master/sorties/6_agroforesterie.png)](https://github.com/leclercbaptiste1085-hash/5-france-terre)

**En préparation** : modèle de financement d'une centrale solaire (TRI, VAN, DSCR, scénarios).

---

### Méthode

| Sourcer | Formaliser | Contrôler | Restituer |
|:--|:--|:--|:--|
| Données publiques et traçables | Hypothèses écrites et justifiées | Valeurs de contrôle à chaque étape | Une note lisible par un décideur, avec ses limites |

### Outils

`Excel` `Power Query` `Power BI` `SQL` `PostgreSQL` `Python` `R` `SAS` `Stata` `SAP`

Économétrie (panel, séries temporelles) · analyse d'écarts · budget · modélisation financière
