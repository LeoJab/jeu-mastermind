# Chad Mastermind 🧠

Mastermind pour le hub **ChadGangGames** : un seul fichier `index.html`, 100 % statique.

## Modes
- **🧠 Solo** : 4 niveaux (Facile, Normal, Expert, Giga Chad). Score = (essais restants + vitesse) × multiplicateur du niveau → classement « Solo » du hub.
- **⚔️ Course en ligne** (2 à 8 joueurs) : tout le monde cherche le même code, le moins de coups gagne, le chrono départage → classement des victoires.
- **🤝 Duel même écran** : 2 manches, chacun compose un code pour l'autre (ne compte pas au classement).

## Mise en ligne
```bash
git init
git add .
git commit -m "Chad Mastermind"
git branch -M main
git remote add origin https://github.com/<toi>/jeu-mastermind.git
git push -u origin main
```
Puis dans le hub : **Admin → Jeux → Ajouter le jeu** et colle le lien du dépôt.

## Fichiers
- `index.html` : le jeu
- `chadgang.json` : fiche du jeu + classements (principal = victoires en ligne, `solo` = score)
- `cover.png` : image de couverture 1280×720
