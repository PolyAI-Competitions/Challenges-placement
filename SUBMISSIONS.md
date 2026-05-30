# Guide des Soumissions

**Important** : Les dossiers des défis doivent être créés et codés **directement dans ce dépôt**, pas dans un dépôt séparé.

## Architecture Recommandée

Organisez votre code comme ceci :

```
challenge_X_[nom]/
├── README.md
├── src/
├── data/
├── results/
└── requirements.txt
```

Adaptez la structure à vos besoins. L'important est que ce soit organisé et documenté.

**Vous êtes libre d'utiliser** :
- Des scripts Python classiques (`.py`)
- Des Jupyter Notebooks (`.ipynb`)
- Un Dockerfile pour simplifier le partage et l'exécution

---

## Votre README.md Doit Contenir

1. **Description rapide** - Qu'est-ce que votre solution fait
2. **Installation** - Comment installer les dépendances
3. **Comment lancer** - Les commandes exactes pour exécuter votre code
4. **Résultats attendus** - Qu'est-ce qui devrait s'afficher ou se générer
5. **Architecture** - Description de votre structure de code et de vos choix techniques

### Exemple minimal

```markdown
# Challenge 1 : Agent LLM

Description de ce que fait l'agent.

## Installation
pip install -r requirements.txt

## Lancer le code
python src/main.py

## Résultats
Décrivez ce qui devrait se produire et où sont sauvegardés les résultats.

## Approche
Expliquez votre architecture et vos choix techniques.
```

---

## Code Généré par LLM (ChatGPT, Claude, Copilot, etc.)

Soyons clairs : **l'utilisation d'LLM est autorisée**. Cependant :

- **Mentionnez explicitement** si du code a été généré par un LLM (dans le README ou les commentaires)
- Ce n'est **pas pénalisant** d'utiliser des outils IA pour générer du code
- **Mais** : Nous jugerons avec plus d'exigence les soumissions avec code généré

Ce qui compte vraiment : **comprendre les concepts et savoir expliquer votre code**.

Si vous utilisez un LLM :
- Mentionnez-le clairement
- Assurez-vous de comprendre les concepts

---

## Checklist Avant Push

- Code exécutable sans erreur
- README explique comment lancer le code
- Tous les livrables demandés sont générés
- requirements.txt à jour
- .gitignore configuré (pas de fichiers volumineux)

