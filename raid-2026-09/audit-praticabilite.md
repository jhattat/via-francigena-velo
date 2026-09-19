# Audit trafic / praticabilité des 3 GPX du raid — 13/09/2026

**Tracés** : routes Strava « test etape 1 », « TestEtape2 », « test Etape 3 »
(export du 13/09/2026) ; les 3 étapes retouchées le soir même avec BRouter (sortie de
Calais par les D 247, contournement de la D 917, contournement de la D 937 par Champs). Fichiers de référence : `etape1-3.gpx` de ce dossier.

**Méthode** : chaque GPX rééchantillonné tous les 80 m, apparié aux voies
OpenStreetMap (Overpass, rayon 25 m, appariement avec continuité), puis agrégé
par type de voie (`highway`), revêtement (`surface`/`tracktype`) et référence
(N/D). Même méthode que l'audit du 22/07 (`via-francigena/audit-praticabilite.md`).

**Lecture** : le tag « primary » = ex-nationales et grosses départementales
(fort trafic probable) ; « secondary » = départementales moyennes (trafic
modéré, souvent 80 km/h hors agglomération) ; « routes calmes » = tertiaires,
voies communales, résidentielles, pistes cyclables. Les tronçons « voiture
suiveuse ne passe pas » sont les pistes cyclables, chemins et allées : la
voiture doit contourner et retrouver Jay à la sortie.

## Verdict par étape

| Étape | Distance | Routes calmes | Primaires | Secondaires | Voiture ✖ | Non revêtu | Verdict |
|---|---|---|---|---|---|---|---|
| 1 Calais → Arras | 138 km | 65 % | 0,4 % (0,6 km) | 33,7 % (46,6 km) | 0,5 km | 0,1 km | 🟢 |
| 2 Arras → Ognes | 113 km | 82 % | 0,1 % (0,1 km) | 18,1 % (20,4 km) | 0,2 km | 0,2 km | 🟢 |
| 3 Ognes → Saint-Martin-sur-le-Pré | 149 km | 44 % | 4,4 % (6,6 km) | 51,0 % (76,2 km) | 14,1 km | 0,1 km | 🟠 |

## Étape 1 — Calais → Arras (Vendredi 25/09)

> ⚠️ **Audit de la v3 (15/09).** La v4 du 19/09 (recalcul complet bikerouter.de, 137,6 km, +1 128 m) modifie le tracé aux km 2-4, 26-28, 90-95, 101-112 (Tincques · Savy-Berlette au lieu de Penin · Villers-Brûlin), 119-122 et 133-137. Les lignes D 77 / D 941 des km 90-112 ci-dessous sont donc à reprendre ; le reste (km 4-26, 28-90) est inchangé. Ré-audit Overpass à relancer depuis le Mac.

### 🔴 Routes principales (à éviter ou à assumer en connaissance de cause)
- km 99,9 → 100,3 (0,4 km) : D 941 — limité à 80 km/h

### 🟠 Départementales secondaires de plus de 800 m
- km 27,3 → 28,6 (1,3 km) : D 217 · Rue d'Ecambre — limité à 50 km/h
- km 28,6 → 33,5 (5,0 km) : D 225 — limité à 80 km/h
- km 34,9 → 38,3 (3,4 km) : D 225
- km 46,5 → 47,4 (0,9 km) : D 192 · Rue Bernard Chochoy — limité à 50 km/h
- km 52,0 → 53,8 (1,8 km) : D 225 · Rue Principale — limité à 50 km/h
- km 91,0 → 91,9 (0,9 km) : D 77 · Rue de Saint-Omer
- km 93,3 → 96,0 (2,7 km) : D 77 — limité à 80 km/h
- km 97,6 → 99,9 (2,3 km) : D 77 — limité à 50 km/h
- km 101,9 → 102,9 (1,0 km) : D 77 — limité à 80 km/h
- km 103,8 → 107,0 (3,3 km) : D 77 — limité à 80 km/h
- km 108,0 → 109,1 (1,1 km) : D 77 — limité à 80 km/h

### 🚗 Tronçons où la voiture suiveuse ne passe pas
- km 42,0 → 42,3 (0,3 km) : Chemin de Mombreux — bitume

### ⚠️ Revêtement non bitumé ou non renseigné
- km 81,2 → 82,2 (1,0 km) : service — revêtement non renseigné
- km 138,0 → 138,1 (0,1 km) : Place des Héros — pavés

## Étape 2 — Arras → Ognes (Samedi 26/09)

### 🔴 Routes principales (à éviter ou à assumer en connaissance de cause)
- aucun

### 🟠 Départementales secondaires de plus de 800 m
- km 1,8 → 2,7 (1,0 km) : Route de Bapaume — limité à 50 km/h
- km 4,3 → 5,3 (1,0 km) : D 5 · Avenue François Mitterrand — limité à 50 km/h
- km 7,2 → 9,0 (1,8 km) : D 5 — limité à 80 km/h
- km 51,4 → 52,2 (0,9 km) : D 6 — limité à 80 km/h
- km 71,0 → 72,6 (1,6 km) : D 32 — limité à 80 km/h
- km 73,9 → 75,9 (2,0 km) : D 32 — limité à 80 km/h
- km 86,2 → 87,5 (1,3 km) : D 937 — limité à 80 km/h

### 🚗 Tronçons où la voiture suiveuse ne passe pas
- aucun

### ⚠️ Revêtement non bitumé ou non renseigné
- km 0,0 → 0,1 (0,1 km) : Place des Héros — pavés
- km 25,3 → 25,5 (0,2 km) : service — revêtement non renseigné
- km 25,5 → 26,6 (1,0 km) : Chemin de Saint-Aubin — revêtement non renseigné
- km 30,5 → 31,0 (0,6 km) : service — revêtement non renseigné

## Étape 3 — Ognes → Saint-Martin-sur-le-Pré (Dimanche 27/09)

> ⚠️ **Audit de la v2 (15/09).** La v3 du 19/09 (recalcul complet bikerouter.de, 154,4 km, +1 308 m) modifie le tracé aux km 10-12, 15-19, 54-61, 77-80, 96-99, 104-105, 129 et 134-139. Les lignes D 937 / D 934 (Chauny → Coucy), D 386, D 26 et l'accès à la voie verte V52 sont à reprendre ; vérifier que le contournement de la D 937 par Champs a survécu au recalcul. Ré-audit Overpass à relancer depuis le Mac.

### 🔴 Routes principales (à éviter ou à assumer en connaissance de cause)
- km 3,0 → 3,4 (0,3 km) : D 937 · Rue de la Chaussée — limité à 50 km/h
- km 3,8 → 8,8 (5,0 km) : D 937
- km 104,1 → 104,4 (0,3 km) : D 951 · Route Nationale — limité à 50 km/h

### 🟠 Départementales secondaires de plus de 800 m
- km 15,4 → 16,6 (1,2 km) : D 934 — limité à 80 km/h
- km 17,5 → 18,3 (0,8 km) : D 937 · Avenue de Framlingham — limité à 50 km/h
- km 25,1 → 27,0 (1,9 km) : D 5 — limité à 80 km/h
- km 29,1 → 30,0 (0,9 km) : D 14 · Route de Brancourt
- km 31,0 → 31,8 (0,8 km) : D 14 · Rue de la Vendée — limité à 50 km/h
- km 32,6 → 36,5 (3,9 km) : D 14
- km 44,4 → 45,7 (1,3 km) : D 925 · Route de Chavonne
- km 46,5 → 47,6 (1,1 km) : D 925 · Route de Vailly — limité à 70 km/h
- km 56,1 → 64,0 (7,9 km) : D 967
- km 67,4 → 69,1 (1,7 km) : D 386 — limité à 80 km/h
- km 70,3 → 73,2 (2,9 km) : D 386 — limité à 80 km/h
- km 74,0 → 75,2 (1,2 km) : D 386 — limité à 80 km/h
- km 93,4 → 95,8 (2,3 km) : D 26 — limité à 80 km/h
- km 97,8 → 98,7 (0,9 km) : D 26 — limité à 80 km/h
- km 101,2 → 102,1 (0,9 km) : D 26
- km 110,5 → 112,2 (1,7 km) : D 26 — limité à 80 km/h
- km 113,2 → 114,6 (1,4 km) : D 26
- km 115,6 → 117,1 (1,5 km) : D 26
- km 125,4 → 126,2 (0,9 km) : D 34 — limité à 80 km/h
- km 131,2 → 133,9 (2,7 km) : D 37 — limité à 80 km/h

### 🚗 Tronçons où la voiture suiveuse ne passe pas
- km 134,8 → 139,3 (4,5 km) : V 52 — bitume
- km 139,3 → 146,3 (7,0 km) : piste cyclable — bitume
- km 146,3 → 147,4 (1,0 km) : V 52 — bitume
- km 147,4 → 148,7 (1,4 km) : La Bicycl'Est (V 52) — bitume

### ⚠️ Revêtement non bitumé ou non renseigné
- aucun

## Limites

- OSM est très complet sur le réseau routier français, mais le tag
  `surface` manque sur une partie des petites voies : « revêtement non
  renseigné » veut dire « à vérifier », pas « en terre ».
- « primary » prédit bien le trafic, sans le mesurer. Pour trancher un cas
  limite : heatmap Strava (beaucoup de cyclistes = roulable) ou Street View.

## Contrôle satellite du 13/09 (tuiles ESRI World Imagery, z18)

- J1 km 76,8 (voie de service, 0,9 km, vers Laires) : voie étroite, surface claire et uniforme → vraisemblablement bitumée.
- J2 km 26,1 (voie de service le long de l'A1, 0,2 km, `motor_vehicle=no`) : bitume visible ; interdite aux voitures.
- J2 km 26,7 (chemin de Saint-Aubin, 1,1 km) : voie rurale étroite, surface claire, sans ornières → bitume ou béton probable, à confirmer sur Street View.
- J2 km 31,4 (voie communale, 0,7 km) : idem, surface claire uniforme entre les champs.
Aucun de ces tronçons ne ressemble à un chemin de terre. Si l'un se révélait en gravier, repli : rester sur la D 7 puis D 11E3 (Riencourt → Villers-au-Flos), +0 km.
