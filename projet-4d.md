# Projet : [nom]

Date : 

**Avant de commencer :** remplir les sections 1 et 2 AVANT d'ouvrir l'IA. Cinq minutes max. Si une case est vide, je ne suis pas prêt.
**Pendant :** section 3, en version courte à chaque étape et en version complète à chaque jalon.
**À la fin :** sections 4 et 5.

---

## 1. Delegation : qui fait quoi

**Objectif en une phrase :**

**Pour qui, et quel est le vrai besoin** (le problème que je crois avoir peut être différent du vrai problème) :

**Critère de réussite** (comment je saurai que c'est fini et que ça marche) :

**Ce que je veux comprendre à fond** (je ne le délègue pas) :

**Répartition par capacité** (l'IA peut aider partout, mais elle est beaucoup plus forte sur certaines capacités que sur d'autres) :

| Capacité | Moi | IA | Ensemble | Note |
|---|:-:|:-:|:-:|---|
| Empathie : pour qui, quel besoin réel | | | | |
| Design : à quoi ça ressemble, comment on s'en sert | | | | |
| Architecture : structure, choix techniques | | | | |
| Implémentation : écrire le code | | | | |
| Jugement : est-ce bon, est-ce le bon problème | | | | |
| Shipping : mise en service, partage, maintenance | | | | |

**Ce qui est risqué à déléguer** (données, évaluation du modèle, sécurité, vie privée, propriété intellectuelle Torngat) :

**Outil utilisé :**

---

## 2. Description : ce que je dis à l'IA

**Contexte à donner** (contraintes, stack, données, exemples) :

**Livrable attendu à chaque étape :**

**Message de départ à coller dans la conversation :**

> Voici mon projet : [objectif]. Pour qui : [utilisateur]. Mon critère de réussite : [critère].
> Je garde la main sur : [capacités cochées « Moi »]. Ne prends pas de décision à ma place sur ces points.
> Avant d'écrire du code, propose-moi un plan en étapes et pose-moi tes questions.
> Avance une étape à la fois et attends mon accord avant de passer à la suivante.
> Explique tes choix en quelques lignes. Dis-moi quand tu fais une hypothèse ou que tu n'es pas sûr.
> Quand tu livres du code, teste-le et montre-moi les résultats. Liste ensuite les hypothèses qu'il fait sur l'environnement réel.
> Si ma demande te semble mal pensée, dis-le-moi avant de l'exécuter.

**Si le projet a une interface, ajouter :**

> Prévois dès le départ l'accessibilité (contraste, navigation clavier, lecteur d'écran), des états de chargement, des confirmations et des messages d'erreur qui disent quoi faire ensuite.

---

## 3. Discernment : évaluer ce que l'IA produit

### À chaque étape (deux minutes)

Je n'avance pas tant que ces cases ne sont pas cochées.

- [ ] Je peux expliquer ce que ça fait sans relire le code
- [ ] Je l'ai exécuté moi-même (relire le code ne suffit pas)
- [ ] J'ai essayé au moins un cas limite ou un cas qui devrait échouer
- [ ] Rien d'inventé (fonction, paramètre, librairie, source)
- [ ] Ce que je change dans ma prochaine consigne :

**Journal des itérations** (une ligne par étape : ce que j'ai demandé, ce qui a marché ou pas) :

-

### À chaque jalon : les cinq lentilles

**Intégrité fonctionnelle : est-ce que ça marche vraiment?**
- [ ] Tous les cas de test sont couverts, pas juste celui qui fonctionne

**Prêt pour l'usage réel**
- [ ] L'IA a testé son propre code et j'ai vu les résultats
- [ ] Des scénarios réels ont été générés et vérifiés (données manquantes ou sales, capteur débranché, gros volume, mauvaise entrée)
- [ ] J'ai posé la question : « Quelles hypothèses ce code fait-il sur l'environnement réel? »

**Adéquation au problème : est-ce que ça résout le vrai problème?**
- [ ] Comparé au vrai besoin et au critère de réussite de la section 1

**Qualité de l'expérience** (si quelqu'un d'autre que moi l'utilise, ou s'il y a une interface)
- [ ] Clarté : l'interface reprend des concepts que l'utilisateur connaît déjà
- [ ] Hiérarchie : on trouve l'information utile au moment où on en a besoin
- [ ] Accessibilité : contraste, navigation clavier, lecteur d'écran, demandés explicitement à l'IA et testés
- [ ] Feedback : états de chargement, confirmations, messages d'erreur qui disent quoi faire
- [ ] C'est moi qui juge si c'est bon : l'IA n'a pas de goût, elle reproduit des patterns

**Impact responsable**
- [ ] J'ai demandé à l'IA de nommer ses biais
- [ ] Biais, vie privée et conséquences imprévues vérifiés, garde-fous en place
- [ ] ML seulement : pas de fuite de données, évaluation sur des données jamais vues, données représentatives

---

## 4. Diligence : avant de dire que c'est terminé

**Les trois habitudes**
- [ ] Vérification : j'ai cherché activement les cas limites et les hypothèses
- [ ] Transparence : le README dit ce que l'IA a fait et ce que j'ai fait
- [ ] Compréhension : je comprends comment le code fonctionne et je peux défendre chaque partie

**Responsabilité**
- [ ] J'assume ce que l'IA a produit comme si je l'avais écrit moi-même
- [ ] J'ai pensé à l'impact sur les autres (utilisateurs, collègues, clients)
- [ ] Politiques, vie privée et normes professionnelles respectées (propriété intellectuelle Torngat, données clients, normes du domaine)

**Pratiques d'ingénierie** (selon l'ampleur du projet)
- [ ] Tests automatisés pour les parties critiques
- [ ] Observabilité : logs, suivi des expériences ML, moniteur série pour l'Arduino
- [ ] Feature flags : seulement si d'autres personnes utilisent le projet en continu
- [ ] Limites connues notées

---

## 5. Bilan (trois lignes)

**Capacités où l'IA m'a le plus aidé, et le moins aidé :**

**Ce que je ne déléguerais plus :**

**Ce que je change pour le prochain projet :**
