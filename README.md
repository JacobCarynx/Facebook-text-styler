# 🎨 FB Text Styler Pro

Une application web autonome, élégante et performante conçue pour styliser vos textes pour les réseaux sociaux (Facebook, Instagram, Twitter, TikTok, bios, etc.). 

L'outil intègre une interface moderne de type **SaaS (Glassmorphism Cyberpunk)**, disponible en modes Sombre et Clair, avec des options de recherche temps réel, des statistiques de texte et un système de copie rapide.

## 🚀 Lien de l'application en ligne
👉 **[jacobcarynx.github.io/Facebook-text-styler/](https://jacobcarynx.github.io/Facebook-text-styler/)**

---

## 🛠️ Guide de Mise à Jour du Dépôt (Mémo Futur)

Si vous (ou votre assistant IA) devez apporter des modifications à l'application à l'avenir, suivez ce protocole rapide depuis votre terminal local :

### 1. Naviguer vers le dossier du projet
```bash
cd /home/yaakov/Facebook-text-styler
```

### 2. Effectuer vos modifications
Modifiez le code directement dans le fichier `index.html` (et répercutez-les dans `bold-facebook.html` si vous souhaitez garder une copie conforme de sauvegarde).

### 3. Tester localement
Double-cliquez sur `index.html` pour l'ouvrir dans votre navigateur et tester les changements.

### 4. Publier et mettre à jour sur GitHub
Une fois vos modifications validées, exécutez ces commandes Git classiques :

```bash
# Ajouter toutes les modifications au suivi Git
git add .

# Enregistrer vos changements avec un message explicatif
git commit -m "Description de la modification (ex: style: ajustement des marges)"

# Pousser les modifications sur la branche principale
git push origin main
```

> [!NOTE]
> Dès que vous lancez `git push origin main`, GitHub met à jour vos fichiers et relance automatiquement le déploiement sur votre lien **GitHub Pages** (cela prend environ 30 à 45 secondes pour devenir visible en ligne).

---

## 🎨 Fonctionnalités techniques
* **Styles inclus** : Gras, Italique, Gras-Italique, Sans-Serif, Script (Calligraphie), Gothique (Fraktur), Double-Barre, Chasse-Fixe, Bulles, Petites Majuscules, À l'Envers (Upside Down), Miroir (Backwards).
* **Modificateurs cumulatifs** : Souligné, Double souligné, Barré, Tranché (Slash), Décorations d'étincelles (✨).
* **UI/UX** : Thème dual réactif (Light/Dark), barre de recherche instantanée par mots-clés, compteurs de caractères/mots en temps réel, toasts de copie non intrusifs.
