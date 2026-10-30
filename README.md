# projet-template

Template de départ pour mes projets construits avec l'IA, basé sur l'approche 4D du cours *AI Fluency for Builders* d'Anthropic (Delegation, Description, Discernment, Diligence).

## Pourquoi ce template existe

Quand je construis avec l'IA, j'ai tendance à passer en pilote automatique. L'IA propose, je colle, ça avance, mais je perds le contrôle du projet et l'impression d'y participer vraiment.

Ce template sert à garder la main. Il m'oblige à décider ce que je fais moi-même avant de commencer, à vérifier ce que l'IA produit pendant le projet et à assumer le résultat à la fin.

Ce n'est pas une liste à cocher. Les 4D forment une boucle : ce que j'apprends en évaluant le travail de l'IA change ma façon de lui parler et ce que je choisis de lui confier.

## Comment l'utiliser

1. **Nouveau projet :** « Use this template » sur ce repo. Pour un repo existant, copier `projet-4d.md` à la racine.
2. **Avant d'ouvrir l'IA (5 minutes) :** remplir les sections 1 et 2. Si une case reste vide, je ne suis pas prêt à commencer.
3. **Coller le message de départ** de la section 2 au début de la conversation avec l'IA.
4. **Pendant :** la vérification courte de la section 3 à chaque étape, les cinq lentilles à chaque jalon. Une ligne dans le journal à chaque itération.
5. **À la fin :** sections 4 et 5, puis je reporte les leçons du bilan dans ce template.

## Les 4D en bref

**Delegation : décider qui fait quoi.**
L'IA peut aider sur les six capacités d'un builder (empathie, design, architecture, implémentation, jugement, shipping), mais elle est beaucoup plus forte sur certaines que sur d'autres. Je choisis consciemment ce que je garde, surtout ce que je veux comprendre à fond.

**Description : dire clairement ce que je veux.**
Le contexte, le livrable attendu et la façon de travailler. Le message de départ force l'IA à proposer un plan, à avancer une étape à la fois et à signaler ses hypothèses. C'est ce qui casse le mode « 200 lignes de code à coller ».

**Discernment : évaluer ce que l'IA produit.**
Relire le code est nécessaire, mais ça ne suffit pas pour savoir si ça marche. Les cinq lentilles :
- *Intégrité fonctionnelle :* est-ce que ça marche vraiment, dans tous les cas?
- *Prêt pour l'usage réel :* quelles hypothèses le code fait-il sur l'environnement réel?
- *Adéquation au problème :* est-ce que ça résout le vrai problème, pas seulement celui que j'ai décrit?
- *Qualité de l'expérience :* est-ce clair, accessible, agréable? L'IA n'a pas de goût, elle reproduit des patterns.
- *Impact responsable :* biais, vie privée, conséquences imprévues.

**Diligence : assumer ce que je livre.**
Trois habitudes : vérifier (cas limites et hypothèses), être transparent (dire ce que l'IA a fait) et comprendre (savoir comment le code fonctionne). J'assume ce que l'IA produit comme si je l'avais écrit moi-même.

## Le test le plus important

> Est-ce que je peux expliquer ce que ça fait sans relire le code?

Si la réponse est non, je suis en pilote automatique. C'est le signal de ralentir, pas de continuer.

## Faire évoluer le template

Après chaque projet, le bilan (section 5) me dit ce qui a servi et ce qui ne sert à rien. Je corrige ce repo en conséquence. C'est la seule version de référence.

## Contenu

- `projet-4d.md` : le template à remplir pour chaque projet
- `README.md` : ce fichier

## Source

Inspiré du cours *AI Fluency for Builders* (Anthropic Academy) et du cadre *AI Fluency Framework* de Rick Dakan et Joseph Feller. Les adaptations à mes projets (ML, Arduino, contraintes Torngat) sont les miennes.
