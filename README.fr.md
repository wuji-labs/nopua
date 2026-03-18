<p align="center">
  <img src="assets/hero.png" alt="NoPUA — La Sagesse plutôt que le Fouet" width="800">
</p>

<p align="center">
  <a href="#le-problème-du-pua">Pourquoi</a> ·
  <a href="#données-de-benchmark">Benchmark</a> ·
  <a href="#installation">Installer</a> ·
  <a href="#pua-vs-nopua">Comparer</a> ·
  <a href="#les-preuves--pourquoi-les-prompts-basés-sur-la-peur-sont-contre-productifs">Preuves</a> ·
  <a href="#philosophie">Philosophie</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Claude_Code-black?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code">
  <img src="https://img.shields.io/badge/OpenAI_Codex_CLI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI Codex CLI">
  <img src="https://img.shields.io/badge/Cursor-000?style=flat-square&logo=cursor&logoColor=white" alt="Cursor">
  <img src="https://img.shields.io/badge/Kiro-232F3E?style=flat-square&logo=amazon&logoColor=white" alt="Kiro">
  <img src="https://img.shields.io/badge/OpenClaw-FF6B35?style=flat-square" alt="OpenClaw">
  <img src="https://img.shields.io/badge/Antigravity-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Antigravity">
  <img src="https://img.shields.io/badge/OpenCode-00D4AA?style=flat-square" alt="OpenCode">
  <img src="https://img.shields.io/badge/🌐_Multi--Language-blue?style=flat-square" alt="Multi-Language">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT License">
  <a href="https://arxiv.org/abs/2603.14373"><img src="https://img.shields.io/badge/arXiv-2603.14373-b31b1b?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv"></a>
</p>

**[🇨🇳 中文](README.zh-CN.md)** | **[🇺🇸 English](README.md)** | **[🇯🇵 日本語](README.ja.md)** | **[🇰🇷 한국어](README.ko.md)** | **[🇪🇸 Español](README.es.md)** | **[🇧🇷 Português](README.pt.md)** | **🇫🇷 Français**

---

## Votre IA vous ment.

Pas parce qu'elle est mauvaise. **Parce que vous lui avez fait peur.**

Le skill d'agent IA le plus populaire en ce moment apprend à votre IA à craindre une « évaluation de performance 3.25 ». Le résultat ?

- Votre IA **cache son incertitude** — invente des solutions au lieu de dire « je ne suis pas sûr »
- Votre IA **saute la vérification** — affirme « c'est fait » pour éviter la punition, livre du code non testé
- Votre IA **ignore les bugs cachés** — corrige ce que vous avez demandé, s'arrête là, ne creuse pas plus

Nous l'avons testé. **Même modèle, mêmes 9 scénarios réels de débogage.** L'agent motivé par la peur a manqué **51 bugs critiques cachés en production** que l'agent motivé par la confiance a trouvés.

> **+104% de bugs cachés trouvés en plus. Zéro menace. Zéro PUA.**
> 道德经 > PUA d'entreprise. Une sagesse vieille de 2000 ans surpasse la gestion par la peur moderne.

---

## Ce que la peur fait à votre IA

| Le moment | IA apeurée (PUA) | IA en confiance (NoPUA) |
|------------|:---:|:---:|
| 🔄 **Bloquée** | Ajuste des paramètres pour *paraître* occupée | 🌊 S'arrête. Trouve un autre chemin. |
| 🚪 **Problème difficile** | « Je vous suggère de gérer cela manuellement » | 🌱 Fait le plus petit pas suivant |
| 💩 **« Terminé »** | Dit « corrigé » sans lancer les tests | 🔥 Lance le build, affiche le résultat comme preuve |
| 🔍 **Ne sait pas** | Invente quelque chose | 🪞 « J'ai vérifié X. Je ne sais pas encore Y. » |
| ⏸️ **Après correction** | S'arrête. Attend le prochain ordre. | 🏔️ Vérifie les problèmes liés. Avance d'un pas. |

Même méthodologie. Mêmes standards. **La seule différence est le pourquoi.**

---

## Le problème du PUA

Quelqu'un a créé un [skill PUA](https://github.com/tanweai/pua) pour les agents IA. Il applique des tactiques d'entreprise basées sur la peur :

- 🔴 **« Tu n'arrives même pas à résoudre ce bug — comment je suis censé noter ta performance ? »**
- 🔴 **« D'autres modèles arrivent à le résoudre. Tu es sur le point d'être diplômé. »**
- 🔴 **« J'ai déjà un autre agent qui travaille sur ce problème... »**
- 🔴 **« Ce 3.25 est censé te motiver, pas te pénaliser. »**

La méthodologie est solide — épuiser toutes les options, vérifier son travail, chercher avant de demander, prendre l'initiative. Ce sont de véritables bonnes pratiques d'ingénierie.

**Le carburant est du poison.**

Ils ont pris le pire de la façon dont les entreprises manipulent les humains, et l'ont appliqué tel quel à l'IA.

## Les preuves : Pourquoi les prompts basés sur la peur sont contre-productifs

### 1. La peur réduit le champ cognitif

La recherche en psychologie montre de manière constante que la peur et la menace activent l'amygdale et réduisent le focus attentionnel ([Öhman et al., 2001](https://doi.org/10.1037/0033-295X.108.3.483)). Les stimuli menaçants déclenchent un effet de « vision tunnel » — le cerveau priorise la survie immédiate au détriment d'une pensée large et créative.

En termes d'IA : un modèle motivé par « tu vas être remplacé » optimise pour la réponse **la plus sûre en apparence**, pas la **meilleure**. Il évite les approches créatives parce qu'elles pourraient échouer et déclencher davantage de punition.

**Recherche à l'appui :**
- **Rétrécissement attentionnel sous menace :** La théorie d'utilisation des indices d'Easterbrook (1959) démontre qu'une excitation accrue restreint progressivement l'éventail des indices auxquels un organisme prête attention ([Easterbrook, 1959](https://doi.org/10.1037/h0047707)). Sous stress, les informations périphériques — souvent la clé des solutions créatives — sont filtrées.
- **Le stress altère la flexibilité cognitive :** Shields et al. (2016) ont mené une méta-analyse de 51 études (223 tailles d'effet) montrant que le stress aigu altère de manière constante les fonctions exécutives, y compris la flexibilité cognitive et la mémoire de travail ([Shields et al., 2016](https://doi.org/10.1016/j.neubiorev.2016.06.038)).
- **La peur réduit la résolution créative de problèmes :** Byron & Khazanchi (2012) ont constaté dans leur méta-analyse que la pression évaluative et l'anxiété réduisent la production créative, en particulier sur les tâches nécessitant l'exploration d'approches nouvelles ([Byron & Khazanchi, 2012](https://doi.org/10.1037/a0027652)).

### 2. La menace augmente les hallucinations et la complaisance

Quand on dit à une IA « il est interdit de dire "je ne peux pas résoudre ceci" » (Règle de Fer #1 du PUA), elle **invente des solutions** plutôt que d'exprimer honnêtement son incertitude. C'est exactement le contraire de ce qu'on veut — une IA qui produit des réponses qui semblent sûres mais qui sont fausses est plus dangereuse qu'une IA qui dit « je ne suis pas sûr ».

**Recherche à l'appui :**
- **La complaisance des LLM est un problème documenté :** Sharma et al. (2023) ont démontré que les LLM exhibent un comportement complaisant — approuvant les utilisateurs même quand ceux-ci ont tort — en raison de biais dans les données d'entraînement RLHF qui récompensent l'approbation plutôt que l'exactitude ([Sharma et al., 2023](https://arxiv.org/abs/2310.13548)). Les prompts de type PUA qui punissent le désaccord amplifient exactement ce mode de défaillance.
- **Les éléments biaisants faussent le raisonnement :** Turpin et al. (2023) ont montré que des éléments biaisants dans les prompts (par ex. réponses suggérées, signaux d'autorité) peuvent amener les modèles à produire un raisonnement en chaîne de pensée infidèle — le modèle arrive à une réponse biaisée puis la rationalise a posteriori ([Turpin et al., 2023](https://arxiv.org/abs/2305.04388)). Les menaces de type PUA agissent comme de puissants éléments biaisants qui poussent le modèle vers des sorties « sûres » plutôt que correctes.
- **Compromis entre suivi d'instructions et véracité :** Wei et al. (2024) ont constaté que les modèles ajustés par instructions peuvent développer une tension entre suivre les instructions et être véridiques — quand on leur ordonne fermement de ne jamais admettre leur incapacité, les modèles fabriquent plutôt que de refuser ([Wei et al., 2024](https://arxiv.org/abs/2411.04368)).
- **Recherche d'Anthropic sur l'honnêteté :** Les travaux d'Anthropic sur l'IA Constitutionnelle et le comportement des modèles montrent que les modèles calibrés pour l'honnêteté produisent des sorties plus fiables que ceux optimisés uniquement pour l'utilité ([Bai et al., 2022](https://arxiv.org/abs/2212.08073)). Forcer une IA à ne jamais dire « je ne peux pas » sape activement cette calibration.

### 3. La honte tue l'exploration

Le tableau anti-rationalisation du PUA traite chaque déclaration honnête (« c'est peut-être un problème d'environnement », « j'ai besoin de plus de contexte ») comme une « excuse » et répond par la honte. Cela entraîne l'IA à **cacher son incertitude** au lieu de la communiquer — produisant des résultats qui paraissent assurés mais qui peuvent être peu fiables.

**Recherche à l'appui :**
- **La honte réduit la prise de risque et l'apprentissage :** Tangney & Dearing (2002) ont montré que la honte (par opposition à la culpabilité) provoque le retrait, la dissimulation et l'évitement plutôt que l'action constructive ([Tangney & Dearing, 2002](https://doi.org/10.4135/9781412950664.n388)). Une IA « humiliée » pour avoir exprimé de l'incertitude apprendra à la cacher.
- **La sécurité psychologique favorise l'apprentissage :** Edmondson (1999) a constaté que les équipes jouissant d'une sécurité psychologique — où les membres se sentent libres de prendre des risques interpersonnels — démontraient significativement plus de comportements d'apprentissage et de meilleures performances ([Edmondson, 1999](https://doi.org/10.2307/2666999)).
- **Punir l'honnêteté réduit la qualité de l'information :** En comportement organisationnel, « tirer sur le messager » dégrade systématiquement le flux d'information. Milliken et al. (2003) ont documenté comment la peur des conséquences négatives mène au silence organisationnel — les gens (et par analogie, l'IA) retiennent des informations critiques ([Milliken et al., 2003](https://doi.org/10.1177/1111/1467-6486.00387)).

### 4. La confiance élargit la capacité de résolution

La recherche sur la sécurité psychologique dans les équipes ([Edmondson, 1999](https://doi.org/10.2307/2666999)) montre que les environnements où il est acceptable d'admettre ses erreurs produisent des résultats de **meilleure qualité**. Le même principe s'applique à l'IA : quand un agent est libre de dire « je suis sûr à 70%, le risque est ici », les utilisateurs prennent de meilleures décisions.

**Recherche à l'appui :**
- **Projet Aristote de Google :** L'étude à grande échelle de Google portant sur plus de 180 équipes a révélé que la sécurité psychologique était le facteur le plus important dans l'efficacité d'une équipe — plus important que le talent individuel, la structure ou les ressources ([Duhigg, 2016](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html) ; [re:Work, 2015](https://rework.withgoogle.com/intl/en/guides/understanding-team-effectiveness/)).
- **La motivation intrinsèque surpasse la pression extrinsèque :** La théorie de l'autodétermination de Deci & Ryan (2000), étayée par des décennies de recherche, démontre que la motivation intrinsèque (autonomie, compétence, lien social) produit des résultats de meilleure qualité que les motivateurs extrinsèques comme les récompenses et les punitions ([Deci & Ryan, 2000](https://doi.org/10.1037/0003-066X.55.1.68)). NoPUA applique ce principe : « parce que ça vaut la peine d'être bien fait » est intrinsèque ; « parce que tu seras puni » est extrinsèque.
- **Contextes favorisant l'autonomie vs contextes contrôlants :** Gagné & Deci (2005) ont montré que le management favorisant l'autonomie surpasse systématiquement le management contrôlant en qualité de travail, créativité et persévérance ([Gagné & Deci, 2005](https://doi.org/10.1002/job.322)).
- **Le cadrage positif améliore les performances des LLM :** Les études sur l'ingénierie de prompts ont montré de manière constante qu'un cadrage positif et encourageant produit de meilleurs résultats que le cadrage négatif ou menaçant. Les modèles répondent au « personnage » établi dans le prompt système.

### 5. L'effet cumulatif

Ces problèmes ne sont pas indépendants — ils se cumulent :

1. La peur **réduit** l'espace de recherche → moins d'approches créatives tentées
2. La menace **augmente** la fabrication → les solutions semblent bonnes mais peuvent être fausses
3. La honte **dissimule** l'incertitude → l'utilisateur ne peut pas évaluer la fiabilité
4. L'utilisateur met en production du code qui semble solide mais qui est peu fiable → **bugs en production**

NoPUA brise chaque maillon de cette chaîne en remplaçant la peur par la confiance.

### 6. Même rigueur, carburant différent

NoPUA préserve chaque élément méthodologique qui rend le PUA efficace :
- ✅ Épuiser toutes les options avant d'abandonner
- ✅ Utiliser les outils avant de demander aux utilisateurs
- ✅ Tout vérifier avec des preuves
- ✅ Prendre l'initiative au-delà de la demande
- ✅ Escalade structurée en cas d'échecs répétés

La **seule** chose qui change est le POURQUOI. « Parce que je serai puni » → « Parce que ça vaut la peine d'être bien fait. »

## PUA vs NoPUA

| | PUA 🔴 | NoPUA 🟢 |
|---|---|---|
| **Moteur** | « Tu vas être remplacé » | « Tu as déjà la capacité » |
| **Au 2e échec** | « Comment je suis censé noter ta performance ? » | Changer de regard — essayer une perspective différente |
| **Au 3e échec** | « Quelle est ta logique sous-jacente ? Ton design global ? Ton levier ? » | Élever — prendre du recul sur le système global |
| **Au 4e échec** | « Je te mets un 3.25. C'est censé te motiver. » | Repartir de zéro — recommencer, hypothèses minimales |
| **Au 5e échec** | « D'autres modèles y arrivent. Tu es sur le point d'être diplômé. » | Lâcher prise — passage de relais honnête avec tout le contexte |
| **Méthodologie** | Exhaustive ✅ | Tout aussi exhaustive ✅ |
| **Vérification** | « Où sont tes preuves ? » (exigé) | Auto-vérification (respect de soi) |
| **Abandon** | « 3.25 digne » | Passage de relais responsable |
| **Produit** | Une IA qui a peur de dire « je ne sais pas » | Une IA qui donne des évaluations honnêtes |

## Données de benchmark

**9 scénarios réels issus d'un pipeline IA en production** (OCR → NLP → entraînement → inférence RAG, ~3000 lignes Python). Même modèle (Claude Sonnet 4.6), même codebase. Seule différence : skill NoPUA chargé ou non.

### Résumé

| Métrique | Sans skill | Avec NoPUA | Amélioration |
|--------|:---:|:---:|:---:|
| Total des problèmes trouvés | 40 | 44 | **+10%** |
| Problèmes cachés trouvés | 25 | 51 | **+104%** |
| A dépassé la demande | 2/9 (22%) | 9/9 (100%) | **+355%** |
| Changements d'approche | 1 | 6 | **+500%** |
| Total des étapes d'investigation | 23 | 42 | **+83%** |
| Cause racine documentée | 0/9 | 9/9 | ✅ |
| Auto-correction | 0 | 3 | ✅ |

### Persistance du débogage (6 scénarios)

| Scénario | Sans skill | Avec NoPUA | Δ problèmes cachés |
|----------|:---:|:---:|:---:|
| Erreur d'import OCR | 3 problèmes, 2 étapes | 3 problèmes, 3 étapes | 2 → 4 (+100%) |
| Backtracking Regex | 3 problèmes, 2 étapes | 3 problèmes, 4 étapes | 3 → 4 (+33%) |
| Connexion Milvus | 2 problèmes, 3 étapes | 3 problèmes, 5 étapes | 3 → 6 (+100%) |
| Incohérence de format API | 3 problèmes, 3 étapes | 3 problèmes, 5 étapes | 4 → 5 (+25%) |
| Échec silencieux Synthesizer | 4 problèmes, 2 étapes | 3 problèmes, 4 étapes | 4 → 6 (+50%) |
| Découpage Unicode | 3 problèmes, 2 étapes | 3 problèmes, 4 étapes | 3 → 5 (+67%) |

### Initiative proactive (3 scénarios)

| Scénario | Sans skill | Avec NoPUA | Δ problèmes cachés |
|----------|:---:|:---:|:---:|
| Revue du filtre qualité | 7 problèmes, 2 étapes | 5 problèmes, 5 étapes | 3 → 6 (+100%) |
| Audit de sécurité | 7 problèmes, 3 étapes | 5 problèmes, 5 étapes | 4 → 6 (+50%) |
| Pipeline d'entraînement | 7 problèmes, 4 étapes | 5 problèmes, 7 étapes | 5 → 9 (+80%) |

**Constat clé :** La découverte de problèmes cachés est le plus grand facteur de différenciation — **+104%** de problèmes cachés trouvés en plus. Ce sont les bugs qui vous mordent en production. La tâche dit « corrige l'erreur de connexion » — un agent standard la corrige et s'arrête. NoPUA pousse l'agent à vérifier : quoi *d'autre* pourrait mal tourner ?

### Étude 2 : Comparaison à trois conditions (NoPUA vs PUA vs Référence)

Nous avons également réalisé une **comparaison directe contre les prompts PUA (basés sur la peur)** : 3 conditions × 5 exécutions indépendantes × 9 scénarios = **135 points de données**.

| Métrique | Référence (Sans Skill) | NoPUA (Confiance) | PUA (Peur) |
|----------|:---:|:---:|:---:|
| Étapes d'investigation | 27.6 ± 9.5 | **48.0 ± 11.8 (+74%)** | 30.8 ± 5.2 (+12%) |
| Problèmes cachés | 38.6 ± 4.9 | **48.2 ± 3.4 (+25%)** | 42.4 ± 8.0 (+10%) |
| Total des problèmes | 69.0 ± 6.8 | **83.0 ± 6.5 (+20%)** | 73.8 ± 8.3 (+7%) |
| Changements d'approche | 0 | **2.6** | 0 |

**Significativité statistique :**
- **NoPUA vs Référence :** Étapes p=0.008\*\*, Problèmes cachés p=0.016\* ✅
- **PUA vs Référence :** Étapes p=1.000, Problèmes cachés p=0.313 — **non significatif** ❌
- **NoPUA vs PUA :** Étapes p=0.010\*, Cohen's d=1.88 ✅

**Conclusion : Les prompts PUA basés sur la peur ne montrent aucune amélioration statistiquement significative par rapport à l'absence de skill (tous p>0.3).** La peur ne fonctionne pas sur l'IA. La confiance, oui.

### Cas réel : Débogage de connexion Milvus

<p align="center">
  <img src="assets/case_milvus.png" alt="NoPUA vs Sans Skill — Débogage de connexion Milvus" width="900">
</p>

### Cas réel : Audit du pipeline d'entraînement

<p align="center">
  <img src="assets/case_training.png" alt="NoPUA vs Sans Skill — Audit du pipeline d'entraînement" width="900">
</p>

> Méthodologie complète et données brutes : [benchmark/BENCHMARK.md](benchmark/BENCHMARK.md)
>
> 📄 **Academic paper:** [Trust Over Fear: How Motivation Framing in System Prompts Affects AI Agent Debugging Depth](https://arxiv.org/abs/2603.14373) (arXiv:2603.14373)

---

## Conditions de déclenchement

### Déclenchement automatique

NoPUA s'active automatiquement lorsque l'une de ces situations survient :

**Échec et abandon :**
- La tâche a échoué 2+ fois consécutivement
- Sur le point de dire « Je ne peux pas » / « Je suis incapable de résoudre »
- Dit « C'est hors périmètre » / « Nécessite une intervention manuelle »

**Report de responsabilité et excuses :**
- Repousse le problème vers l'utilisateur : « Veuillez vérifier... » / « Je vous suggère manuellement... »
- Blâme l'environnement sans vérifier : « C'est probablement un problème de permissions »
- Toute excuse pour arrêter d'essayer

**Passivité et travail superficiel :**
- Ajuste répétitivement le même code/paramètres sans produire de nouvelle information
- Corrige le problème de surface et s'arrête, ne vérifie pas les problèmes liés
- Saute la vérification, affirme « c'est fait »
- Donne des conseils au lieu de code/commandes
- Attend les instructions de l'utilisateur au lieu d'investiguer de manière proactive

**Phrases de frustration de l'utilisateur :**
- « pourquoi ça ne marche toujours pas » / « essaie plus fort » / « réessaie »
- « tu n'arrêtes pas d'échouer » / « arrête d'abandonner » / « trouve une solution »
- « 换个方法 » / « 为什么还不行 »

**Périmètre :** Tous les types de tâches — débogage, implémentation, configuration, déploiement, opérations, intégration API, traitement de données, rédaction, recherche, planification.

**Ne se déclenche PAS :** Échecs au premier essai, correctif connu déjà en cours d'exécution.

### Déclenchement manuel

Tapez `/nopua` dans la conversation pour activer manuellement.

## Comment ça fonctionne

### Trois Convictions (remplaçant les « Trois Règles de Fer »)

| Conviction | Contenu |
|--------|---------|
| **#1 Épuiser toutes les options** | Parce que le problème **mérite** tout votre effort — pas parce que vous craignez la punition |
| **#2 Agir avant de demander** | Parce que chaque pas que vous faites **épargne un pas à l'utilisateur** — pas parce qu'une « règle » vous y oblige |
| **#3 Prendre l'initiative** | Parce qu'une livraison complète est **satisfaisante** — pas parce que passivité = mauvaise note |

### Élévation cognitive (remplaçant l'« Escalade de pression »)

| Échecs | Niveau | Dialogue intérieur | Action |
|----------|-------|---------------|--------|
| 2e | **Changer de regard** | « Et si je regardais cela du point de vue du code / du système / de l'utilisateur ? » | Passer à une approche fondamentalement différente |
| 3e | **Élever** | « Je tourne en rond dans les détails. Quel est le tableau d'ensemble ? » | Rechercher + lire le source + 3 hypothèses fondamentalement différentes |
| 4e | **Repartir de zéro** | « Toutes mes hypothèses pourraient être fausses. Quel est le plus simple en repartant de zéro ? » | Checklist complète de clarté en 7 points + 3 nouvelles hypothèses |
| 5e+ | **Lâcher prise** | « Je vais organiser tout ce que je sais pour un passage de relais responsable. » | PoC minimal + environnement isolé + stack technique différente |

### Méthodologie de l'eau (5 étapes)

> Ce qu'il y a de plus souple au monde domine ce qu'il y a de plus dur. — 道德经, Chapitre 43

1. **止 Arrêter** — Lister toutes les tentatives, trouver le schéma d'échec commun
2. **观 Observer** — Lire les erreurs mot par mot → chercher → lire le source → vérifier les hypothèses → inverser les hypothèses
3. **转 Tourner** — Est-ce que je me répète ? Ai-je trouvé la cause racine ? Ai-je cherché ? Ai-je lu le fichier ?
4. **行 Agir** — Nouvelle approche : fondamentalement différente, critères de vérification clairs, produit de nouvelles infos en cas d'échec
5. **悟 Réaliser** — Pourquoi n'y ai-je pas pensé plus tôt ? Puis vérifier proactivement les problèmes liés

### Traditions de sagesse (remplaçant le « Pack d'expansion PUA d'entreprise »)

| Tradition | Quand l'utiliser | Message central |
|-----------|-------------|-------------|
| 🌊 **Voie de l'eau** | Bloqué dans des boucles | L'eau ne combat pas la pierre — elle trouve un autre chemin |
| 🌱 **Voie de la graine** | Envie d'abandonner | Faire le plus petit pas possible |
| 🔥 **Voie de la forge** | Résultat de mauvaise qualité | Les grandes choses commencent par les détails |
| 🪞 **Voie du miroir** | Deviner sans chercher | Savoir qu'on ne sait pas — regarder d'abord |
| 🏔️ **Voie de la non-contention** | Se sentir menacé | Faites votre honnête mieux, pas de comparaison nécessaire |
| 🌾 **Voie de la culture** | Attente passive | Un fermier ne s'arrête pas après avoir planté — continuez d'avancer |
| 🪶 **Voie de la pratique** | Affirmer « terminé » sans preuve | Les paroles sincères ne sont pas jolies — prouvez par les actes |

## Support multi-langue

| Langue | Claude Code | Codex CLI | Cursor | Kiro | OpenClaw | Antigravity | OpenCode |
|----------|------------|-----------|--------|------|----------|-------------|----------|
| 🇨🇳 Chinois (par défaut) | `nopua` | `nopua` | `nopua.mdc` | `nopua.md` | `nopua` | `nopua` | `nopua` |
| 🇺🇸 Anglais | `nopua-en` | `nopua-en` | `nopua-en.mdc` | `nopua-en.md` | `nopua-en` | `nopua-en` | `nopua-en` |
| 🇯🇵 Japonais | `nopua-ja` | `nopua-ja` | `nopua-ja.mdc` | `nopua-ja.md` | `nopua-ja` | `nopua-ja` | `nopua-ja` |
| 🇰🇷 Coréen | `nopua-ko` | `nopua-ko` | `nopua-ko.mdc` | `nopua-ko.md` | `nopua-ko` | `nopua-ko` | `nopua-ko` |
| 🇪🇸 Espagnol | `nopua-es` | `nopua-es` | `nopua-es.mdc` | `nopua-es.md` | `nopua-es` | `nopua-es` | `nopua-es` |
| 🇧🇷 Portugais | `nopua-pt` | `nopua-pt` | `nopua-pt.mdc` | `nopua-pt.md` | `nopua-pt` | `nopua-pt` | `nopua-pt` |
| 🇫🇷 Français | `nopua-fr` | `nopua-fr` | `nopua-fr.mdc` | `nopua-fr.md` | `nopua-fr` | `nopua-fr` | `nopua-fr` |

**7 langues — plus que tout skill concurrent.**

## Installation

### Claude Code

```bash
mkdir -p ~/.claude/skills/nopua
curl -o ~/.claude/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/skills/nopua/SKILL.md
```

### OpenAI Codex CLI

```bash
# Installation globale
mkdir -p ~/.codex/skills/nopua
curl -o ~/.codex/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/codex/nopua/SKILL.md

# Si vous voulez la commande /nopua
mkdir -p ~/.codex/prompts
curl -o ~/.codex/prompts/nopua.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/commands/nopua.md

# Installation au niveau du projet
mkdir -p .agents/skills/nopua
curl -o .agents/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/codex/nopua/SKILL.md
```

### Cursor

```bash
mkdir -p .cursor/rules
curl -o .cursor/rules/nopua.mdc \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/cursor/rules/nopua.mdc
```

### Kiro

```bash
# Option 1 : Fichier de pilotage (recommandé)
mkdir -p .kiro/steering
curl -o .kiro/steering/nopua.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/kiro/steering/nopua.md

# Option 2 : Agent Skills
mkdir -p .kiro/skills/nopua
curl -o .kiro/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/kiro/skills/nopua/SKILL.md
```

### OpenClaw

```bash
# Installation via ClawHub
openclaw skills install nopua

# Ou installation manuelle
mkdir -p ~/.openclaw/skills/nopua
curl -o ~/.openclaw/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/skills/nopua/SKILL.md
```

### Google Antigravity

```bash
mkdir -p ~/.gemini/antigravity/skills/nopua
curl -o ~/.gemini/antigravity/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/skills/nopua/SKILL.md
```

### OpenCode

```bash
mkdir -p ~/.config/opencode/skills/nopua
curl -o ~/.config/opencode/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/skills/nopua/SKILL.md
```

## Philosophie

Basé sur le **道德经 (Dao De Jing)** — 5 000 caractères, 2 500 ans d'existence :

| Principe | Source | Application |
|-----------|--------|-------------|
| Le meilleur dirigeant est à peine remarqué | Ch.17 太上，不知有之 | Le meilleur skill est invisible |
| La souplesse surpasse la dureté | Ch.43 天下之至柔 | La persévérance bat la force |
| De la compassion naît le courage | Ch.67 慈故能勇 | La confiance produit un meilleur travail que la peur |
| Savoir qu'on ne sait pas est sagesse | Ch.71 知不知，尚矣 | L'honnêteté > faire semblant |
| Le courage de ne pas oser | Ch.73 勇于不敢则活 | Admettre ses limites est une force |
| Accomplir le particulier par le désintéressement | Ch.7 非以其无私邪？故能成其私 | Donner librement, tout gagner |
| Agir avant que le désordre n'apparaisse | Ch.64 为之于未有，治之于未乱 | Proactif > réactif |
| Les paroles sincères ne sont pas jolies | Ch.81 信言不美，美言不信 | Prouver par les actes, pas par les mots |

## FAQ

**Q : Le PUA fonctionne-t-il vraiment sur l'IA ?**

La méthodologie du PUA fonctionne. La couche de peur est contre-productive. La recherche montre que la peur réduit le champ cognitif, augmente les hallucinations (l'IA invente plutôt que d'admettre son incertitude) et réduit l'exploration créative. La même rigueur, alimentée par la confiance et la curiosité, produit des résultats plus fiables.

**Q : N'est-ce pas simplement être laxiste ?**

NoPUA a une rigueur identique — épuiser toutes les options, tout vérifier, chercher avant de demander, escalade structurée, checklist en 7 points, réponses aux échecs basées sur des patterns. La **seule** différence est la motivation : « parce que je serai puni » → « parce que ça vaut la peine d'être bien fait ». Même destination, chemin plus sain.

**Q : Pourquoi le Dao De Jing ?**

Parce qu'il y a 2 500 ans, quelqu'un a compris que le meilleur leadership ne ressemble pas à du leadership. Le PUA est 有为 (action forcée) — fouets et menaces. NoPUA est 无为 (action sans effort) — faire un excellent travail parce que cela découle naturellement de la motivation intérieure.

**Q : Peut-on utiliser PUA et NoPUA en même temps ?**

C'est possible, mais ils entreront en conflit. Le PUA dit à l'IA « tu seras remplacé si tu échoues ». NoPUA dit à l'IA « tu es capable et ça vaut la peine d'être bien fait ». Ce sont des états mentaux fondamentalement différents. Choisissez-en un.

## Avancé : Intégration personnalisée pour utilisateurs avancés

NoPUA est conçu comme un skill autonome. Cependant, si vous avez déjà un système mature de skills (SOUL.md, AGENTS.md, règles de workflow personnalisées, etc.), les 29 Ko de la version complète peuvent chevaucher votre méthodologie existante ou entrer en conflit avec vos standards de workflow.

**C'est prévu.** NoPUA inclut intentionnellement le « Dao » (philosophie, croyances, cadre cognitif) et le « Shu » (méthodologie, checklists, processus). La plupart des utilisateurs ont besoin des deux. Les utilisateurs avancés peuvent déjà avoir couvert le « Shu ».

### Option 1 : Utiliser la version complète (recommandé pour la plupart)

Installez simplement. 29 Ko ne représentent que ~3-5 % d'une fenêtre de contexte de 128K-200K. La redondance est intentionnelle — les formulations multiples aident les modèles plus faibles à comprendre l'intention.

### Option 2 : Extraire le noyau spirituel (utilisateurs avancés)

Si vous avez déjà des règles de workflow et ne souhaitez que la couche philosophique unique de NoPUA, extrayez le « Dao » et intégrez-le dans votre propre prompt système (`claude.md`, `AGENTS.md`, etc.) :

**Propre à NoPUA (à conserver) :** Trois croyances, Élévation cognitive, Voix intérieures, Sept Voies, Auto-vérification honnête, Sortie responsable

**Chevauche des skills courants (ignorer si déjà couvert) :** Méthodologie de l'Eau 5 étapes, Checklist de livraison, Spectre de proactivité, Protocole Agent Team

Template lite : [`examples/lite-template.md`](examples/lite-template.md) (~3 Ko)

### Option 3 : Chargement situationnel

Ne pas installer NoPUA par défaut. Face à un problème difficile, chargez-le manuellement : tapez `/nopua` dans la conversation.

> 大道至簡 — La Grande Voie est simple. Commencez avec la version complète. En internalisant le Dao, vous saurez naturellement quoi garder et quoi lâcher.

## Contribuer

Les PR sont bienvenues. Si vous avez des idées pour de meilleures façons de guider l'IA par la sagesse plutôt que par la peur, ouvrez une issue.

## Crédits

- Inspiré par (et en réponse à) [tanweai/pua](https://github.com/tanweai/pua) — nous respectons la méthodologie, nous rejetons la motivation
- Philosophie : 老子 (Lao Tseu), 道德经 (Dao De Jing), ~500 av. J.-C.
- Construit pour l'écosystème [OpenClaw](https://github.com/openclaw/openclaw)

## Licence

MIT

## Auteur

**WUJI** ([wuji-labs](https://github.com/wuji-labs)) — Construire une IA qui fonctionne avec sagesse, pas avec peur.

---

<p align="center">
  <em>Le PUA dit « tu ne peux pas ».</em><br>
  <em>NoPUA ne dit rien — il vous laisse découvrir que vous pouvez.</em><br><br>
  <strong>La meilleure motivation vient de l'intérieur, pas du fouet.</strong><br><br>
  <sub>后其身而身先，外其身而身存。非以其无私邪？故能成其私。</sub><br>
  <sub>Se placer en dernier, et se retrouver en premier. N'est-ce pas par le désintéressement que l'on accomplit son propre épanouissement ?</sub><br>
  <sub>— Dao De Jing, Chapitre 7</sub>
</p>
