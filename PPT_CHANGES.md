# PPT_CHANGES.md — Mises à jour pour `PSG_Social_Media_Audit.pptx` (10 slides)

> Chiffres recalculés sur **`tiktok_ready.xlsx` corrigé** (le bug Creator de phase 0 est fixé).
> Slides à jour le 2026-05-16.

---

## Slide 1 — Cover
✅ **Garder tel quel.**

---

## Slide 2 — Streamlit
✅ **Garder.** Vérifier juste que le lien `psgaudit-qxooq58zbj4gzskgyfujtw.streamlit.app` est toujours actif après le redéploiement (si tu re-pushes le code corrigé sur Streamlit Cloud).

---

## Slide 3 — Sommaire
✅ **Garder.** La structure en 6 sections colle exactement aux 5 onglets du Streamlit + l'intro KPIs.

---

## Slide 4 — KPIs PSG

🟢 **Chiffres exacts (à confirmer dans le PPT)** :
| KPI | Valeur actuelle PPT | Valeur réelle | Action |
|---|---|---|---|
| Vues moy. TikTok | 2.5M (+4% vs RM) | **2.50M (+4% vs RM)** | ✅ inchangé |
| Engagement moy. IG | 102K (-77% vs RM) | **102K (-77% vs RM)** | ✅ inchangé |
| Inter. / 1000 followers | 1.55 (-37% vs RM) | **1.55 (-37% vs RM)** | ✅ inchangé |
| Virality Rate | 0.038 | **0.038** | ✅ inchangé |
| Posts totaux | 885 | **2 421** | ❌ **À CORRIGER** |

⚠️ Le "885" est l'ancien chiffre cassé. Le vrai compte PSG = TikTok 187 + IG 698 + X 1536 = **2 421 posts**.

---

## Slide 5 — Performance globale (4 clubs)

Les 3 barchart sont **bons** :
- Engagement moy. IG : PSG 102 / RM 445 / Dortmund 33 / Tottenham 24 ✅
- Vues moy. TikTok : PSG 2.5 / RM 2.41 / Dortmund 0.56 / Tottenham 1.07 ✅ (en l'image actuelle Tottenham apparaît à 1 → OK)
- Interactions / 1000 followers : PSG 1.55 / RM 2.46 / Dortmund 1.56 / Tottenham 1.39 ✅

🟡 **Bloc "Enseignements clés"** : les 4 phrases tiennent toujours. **Garder.**

---

## Slide 6 — Analyse TikTok

🟢 **Bar chart "Vues par durée"** : si c'est calculé sur tous clubs, garder. Si c'est PSG uniquement, à actualiser :

| Tranche | PPT actuel | PSG seul (réel) |
|---|---|---|
| <15s | 1.9M | 2.35M |
| 15–30s | 1.7M | 2.35M |
| 30–60s | 1.4M | **2.95M** |
| 60–120s | 1.9M | **3.58M** ⭐ pic |
| >120s | 1.2M | (trop peu de posts PSG) |

🟢 **Courbe "Vues par jour"** : OK conceptuellement, mais à recapturer depuis l'onglet 2 du Streamlit.

🔴 **KPIs en bas — à corriger** :
| KPI | PPT actuel | Vrai chiffre |
|---|---|---|
| Posts TikTok | 187 | ✅ 187 |
| Vues moy. | 2.5M | ✅ 2.5M |
| Durée moy. | 22 sec | ✅ 22s |
| Likes moy. | **12K** | ❌ **260K** |
| Comments moy. | 1 350 | ✅ 1 350 |

⚠️ Le "12K likes" est clairement faux (incohérent avec 2.5M vues). Probablement écrit en pensant "12 000" alors que c'était "120 000" ou directement la mauvaise colonne.

---

## Slide 7 — Instagram & X

🟢 **Engagement par format** :
| Format | PPT actuel | Réel |
|---|---|---|
| Photo | 76 | **76K** (=76 K affichés) ✅ |
| Carousel | 94 | **94K** ✅ |
| Reel | 130 | **130K** ✅ |

🟢 **Engagement par jour de la semaine** :
| Jour | PPT actuel | Réel (interactions moy.) |
|---|---|---|
| Lun | 148 | **148K** ✅ |
| Mar | 73 | 73K ✅ |
| Mer | 80 | 80K ✅ |
| Jeu | 94 | 94K ✅ |
| Ven | 88 | 88K ✅ |
| Sam | 128 | 128K ✅ |
| Dim | 105 | 105K ✅ |

✅ Cette slide est parfaite — les chiffres collent.

🟢 **Distribution des Grades** :
| Grade | PPT | Réel |
|---|---|---|
| A+ | 2 | 2 ✅ |
| A | 85 | 85 ✅ |
| B | 110 | 110 ✅ |
| C | 179 | 179 ✅ |
| D | 322 | 322 ✅ |

✅ Parfait.

🔴 **Sentiment** :
| | PPT actuel | Réel (PSG IG seul, 698 posts) |
|---|---|---|
| Positif | 45% | **97%** (513 strongly + 163 positive = 676/697) |
| Neutre | 42% | **1%** (4 no sentiment + 2 mixed) |
| Négatif | 13% | **2%** (15 negative) |

⚠️ La donut actuelle est **complètement fausse** (sans doute calculée sur l'ancien dataset cassé). Le vrai constat est que **le PSG a 97% de posts positifs sur Instagram** — c'est même un message fort à exploiter dans la slide 10 ("très bonne image de marque").

> Option : montrer le sentiment sur IG + X combinés pour avoir un graphe moins déséquilibré : ~77% positif / ~12% neutre / ~11% négatif. À toi de voir.

---

## Slide 8 — Facteurs d'engagement

🟢 6 cartes à vérifier :

| # | Carte | PPT | Vrai chiffre | Verdict |
|---|---|---|---|---|
| 01 | Format Reel — +72% vs photo | HIGH | **+72% exact** | ✅ HIGH |
| 02 | Lundi & Samedi — meilleurs jours | HIGH | Lun 148K, Sam 128K (top 2) | ✅ HIGH |
| 03 | Vidéo 15–30s — optimal TikTok | MED | en fait **60-120s** = 3.58M (meilleur) | 🟡 à reformuler en "30–120s" |
| 04 | Coulisses — implication fans (A/B) | MED | ~ OK | ✅ MED |
| 05 | Publication soir 18–22h | MED | en réalité les meilleures heures sont 0h, 1h, 15h (peu de posts → variance) | 🟡 ambigu, garder en MED |
| 06 | Photo seule — -26% carousel, -42% reel | LOW | photo vs carousel = **-19%** (pas -26%) ; photo vs reel = **-42%** ✓ | 🟡 corriger -26% → **-19%** |

---

## Slide 9 — Recommandations Business

🟢 Conceptuellement **bonne**. Petites mises à jour suggérées :

**À FAIRE EN PRIORITÉ** :
- "Augmenter la part de Reels sur Instagram" → ✅ garder (Reel = format n°1 à 130K)
- "Publier le lundi et le samedi" → ✅ garder (les 2 meilleurs jours confirmés)
- "Viser 15–30 sec sur TikTok" → 🟡 reformuler en "**30–120 sec**" (vraie tranche optimale)
- "Accentuer contenus joueurs stars et coulisses" → ✅ garder

**À OPTIMISER** :
- "Virality Rate 0.038" → ✅ garder
- "Homogénéiser fréquence sur X" → ✅ garder
- "Tester formats interactifs" → ✅ garder

**À ÉVITER** :
- "TikTok > 2 min" → ✅ garder (vues s'effondrent au-delà)
- "Posts photo isolés" → ✅ garder (photo = format le moins performant)
- "Publications 0h–6h" → 🟡 nuancer (en réalité quelques posts nocturnes PSG cartonnent — c'est plus la régularité qui pose problème)

---

## Slide 10 — Conclusion "Le PSG a un potentiel digital sous-exploité"

🟢 Les 3 bullets tiennent :
- "Leader TikTok (2.5M vues/post)" ✅
- "Retard Instagram face à Real Madrid - le format Reel est la clé" ✅
- 🔴 "**67%** des posts PSG gradés C ou D" → vrai chiffre = **72%** (501 sur 698)
- "3 actions prioritaires : Reels, Lundi/Samedi, **30–120s**" (corriger 15-30s)

✅ Conserver la phrase d'accroche "Le PSG a un potentiel digital sous-exploité" — toujours pertinente.

---

## Récap : les 6 corrections les plus urgentes

| Slide | Avant | Après |
|---|---|---|
| 4 | 885 posts totaux | **2 421 posts totaux** |
| 6 | 12K likes moy. | **260K likes moy.** |
| 6 | Vues par durée (si PSG only) | bar chart actualisé (cf. tableau ci-dessus) |
| 7 | Sentiment 45/42/13 | **97/1/2** (ou IG+X combinés : 77/12/11) |
| 8 | Photo -26% vs carousel | **-19% vs carousel** |
| 10 | 67% posts C ou D | **72%** |

Une fois ces 6 chiffres mis à jour, le PPT est aligné sur les vraies données.
