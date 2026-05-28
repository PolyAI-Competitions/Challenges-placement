# 🚀 Workshop IA - Évaluation des Compétences

Bienvenue au workshop pratique ! Ce dépôt contient **3 défis** conçus pour évaluer votre niveau en Intelligence Artificielle, du Traitement du Langage Naturel (LLM) à la Vision par Ordinateur, en passant par les Réseaux de Neurones sur Graphes.

---

## 🛠️ Instructions pour participer

Pour valider vos défis de manière anonyme et privée, suivez rigoureusement ces étapes :

1. Cliquez sur le bouton vert **"Use this template"** (Utiliser ce modèle) en haut à droite de cette page.
2. Créez un nouveau dépôt sur votre compte personnel. **⚠️ IMPORTANT : Configurez le dépôt en mode PRIVÉ.**
3. Allez dans les **Settings** (Paramètres) de votre dépôt fraîchement créé > **Collaborators** > Cliquez sur **Add people** et ajoutez mon compte : lucaidan.
4. Clonez votre dépôt localement, codez vos solutions dans les dossiers respectifs, et faites un `git push`. 
(5. Un bot d'évaluation automatique sera potentiellement implémenté et s'exécutera à chaque push ! Vous pourrez voir vos résultats dans l'onglet **Actions**.)

---

## 🎯 Les Défis

### 🤖 Défi 1 : Agent LLM (Planner-Executor)
**Dossier :** `/challenge_1_llm`

L'objectif est de concevoir un agent autonome capable de raisonner, de planifier des actions et d'utiliser des outils externes.

1. **Planification & Exécution :** Implémentez un agent selon le paradigme Planner-Executor (ou ReAct). L'agent doit décomposer une requête complexe en sous-étapes logiques avant de répondre.
2. **Utilisation d'Outils (Tools) :** Donnez à votre agent la capacité d'interagir avec au moins **deux outils** distincts (ex: une calculatrice personnalisée, un outil de recherche web, ou une API météo).
3. **Mémoire Épisotique :** Ajoutez une gestion du contexte (mémoire des échanges passés). L'agent doit être capable de se souvenir des requêtes précédentes au sein d'une même session et d'expliquer son raisonnement si l'utilisateur lui demande *"Pourquoi as-tu utilisé cet outil ?"*.

---

### 🕸️ Défi 2 : Science des Données & Graphes (GCN)
**Dossier :** `/challenge_2_gcn`

Le Deep Learning ne se limite pas aux images et au texte. Ce défi évalue votre capacité à manipuler des données structurées sous forme de graphes.

1. **Implémentation d'un GCN :** Construisez et entraînez un Réseau de Neurones Convolutionnel pour Graphes (*Graph Convolutional Network*). Vous pouvez utiliser le dataset académique **CORA** (classification de publications) ou une application de votre choix (ex: système de recommandation).
2. **Visualisation des Embeddings :** Extrayez l'espace latent (les embeddings) généré par votre GCN juste avant la couche de classification. Utilisez une méthode de réduction de dimension ($t$-SNE, UMAP ou PCA) pour générer un graphique 2D de ces embeddings. Sauvegardez l'image sous le nom `embeddings_viz.png`.
3. **Étude d'Ablation (1 Couche vs 2 Couches) :** Modifiez l'architecture de votre réseau pour comparer les performances d'un GCN à **1 seule couche** d'agrégation face à un GCN à **2 couches**. Inclure un court commentaire dans votre code pour expliquer l'impact

---

### 👁️ Défi 3 : Vision par Ordinateur (Multi-Object Tracking)
**Dossier :** `/challenge_3_cv`

Ce défi porte sur le traitement vidéo et le suivi temporel d'objets en mouvement.

1. **Suivi Multi-Objets (MOT) :** Implémentez un algorithme de suivi d'objets sur une vidéo de votre choix (ex: suivi de voitures dans le trafic routier, suivi de joueurs sur un terrain de sport). Vous pouvez combiner un détecteur (YOLO, Faster R-CNN) avec un tracker (SORT, DeepSORT, ByteTrack).
2. **Analyse de Flux & Métriques :** Ajoutez une fonctionnalité de comptage ou d'extraction de métriques. Par exemple : tracer une ligne virtuelle sur la vidéo et compter le nombre exact d'objets qui la franchissent, ou calculer la vitesse relative des objets. La vidéo finale doit être sauvegardée avec les annotations visuelles (boîtes, IDs uniques, et compteurs).

---

## 🏆 Critères d'Évaluation

Chaque défi sera évalué selon :
* **La justesse technique :** Le code s'exécute-t-il sans erreur ? Les modèles convergent-ils ?
* **La structure du code :** Clarté, commentaires et modularité.
* **Le respect des consignes :** Présence des visualisations demandées et comportement attendu des agents/modèles.

Bonne chance à tous ! 🚀
