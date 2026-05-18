# Index des manuels Iveco Daily III 50C13 (2005)

Référence édition : `Print 603.93.281 — 1st Ed. May 2004` (révisé février 2005).

---

## Manuel électrique dédié

**Fichier** : `MANUEL-ELECTRIQUE-DAILY-3.pdf` (404 pages, espagnol).

C'est en réalité la **Section 14** du manuel mécanique, éditée séparément en version étendue (édition `Print 603.93.285`). À utiliser en priorité pour tout ce qui touche faisceaux, schémas, codes composants, diagnostic électrique.

---

## Manuel mécanique — 1898 pages

Splitté en 19 fichiers dans `MANUEL-MECANIQUE-DAILY-3/`, par tranches de ~100 pages. **Les numéros de page indiqués ci-dessous sont les pages absolues du manuel complet** (= position physique dans le PDF original).

### Table des sections

| # | Section | Pages absolues | Fichier(s) split |
|---|---------|----------------|------------------|
|  1 | General | 15–34 | `pages_1-100.pdf` |
|  2 | Engines | 35–730 | `pages_1-100.pdf` → `pages_701-800.pdf` (8 fichiers) |
|  3 | Clutch | 731–760 | `pages_701-800.pdf` |
|  4 | Transmission | 761–922 | `pages_701-800.pdf`, `pages_801-850.pdf`, `pages_851-900.pdf`, `pages_901-1000.pdf` |
|  5 | Propeller shafts | 923–934 | `pages_901-1000.pdf` |
|  6 | Rear axles | 935–1054 | `pages_901-1000.pdf`, `pages_1001-1100.pdf` |
|  7 | Axle (front) | 1055–1114 | `pages_1001-1100.pdf`, `pages_1101-1200.pdf` |
|  8 | Suspensions | 1115–1230 | `pages_1101-1200.pdf`, `pages_1201-1300.pdf` |
|  9 | Wheels and Tyres | 1231–1240 | `pages_1201-1300.pdf` |
| 10 | Steering gear | 1241–1268 | `pages_1201-1300.pdf` |
| 11 | Hydro-pneumatic / Brakes | 1269–1374 | `pages_1201-1300.pdf`, `pages_1301-1400.pdf` |
| 12 | Bodywork / Chassis / Air-conditioning | 1375–1434 | `pages_1301-1400.pdf`, `pages_1401-1500.pdf` |
| 13 | Scheduled Maintenance | 1435–1448 | `pages_1401-1500.pdf` |
| 14 | Electric/Electronic system | 1449–1898 | `pages_1401-1500.pdf` → `pages_1801-1898.pdf` (5 fichiers) |

> **À noter** : chaque section a sa propre pagination interne qui repart à 1. L'en-tête de chaque page affiche le nom de section + le numéro de page interne. Le tableau ci-dessus donne les pages absolues pour retrouver le bon fichier split rapidement.

---

## Section 2 — Moteurs (vue détaillée)

La section 2 regroupe **toutes** les motorisations Daily de l'époque. Sous-découpage interne :

| Sous-section | Page abs ~ | Modèles |
|--------------|-----------|---------|
| ENGINES 8140.XXX (généralités) | 37–58 | toutes variantes 8140 |
| **Moteurs à injection électronique haute pression** | **59–222** | **8140.43R/B/S/N** (Common Rail) |
| Moteurs à pompe d'injection rotative mécanique | 223–320 | 8140.43C, 8140.63C |
| F1A engine | 321–522 | F1AE0481 (96/116/136 ch) |
| F1C engine | 523–730 | F1CE0481 |

### Moteur 8140.43S (le tien — 125 ch, ID/TCA, Common Rail)

Deux variantes existent :
- **8140.43S.41XX** — avec EGR + OXICAT, MS6.3
- **8140.43S.43XX/44XX** — sans EGR, EDC16 sur 44XX

À identifier sur la **plaque moteur** (côté droit du carter). Cf. Section 1, p.3 (plaques d'identification).

Documentation principale concentrée pages absolues **~59 à ~222** (fichier `pages_1-100.pdf` et `pages_101-200.pdf`).

---

## Stratégie de lecture

- **Question électrique** → manuel électrique dédié en priorité.
- **Question moteur 8140.43S** → fichier `pages_1-100.pdf` (avec débordement sur `pages_101-200.pdf`).
- **Question boîte / pont / suspensions / freins** → ciblage direct via le tableau des sections.
- **Couples de serrage, fluides, plaques** → Section 1 (General).
- **Entretien périodique** → Section 13.
