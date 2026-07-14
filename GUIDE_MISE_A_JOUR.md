# Guide de Mise à Jour du Dépôt (Mémo Futur)

Si vous (ou votre assistant IA) devez apporter des modifications à l'application à l'avenir, suivez ce protocole rapide depuis votre terminal local :

## 1. Naviguer vers le dossier du projet

**Sur Windows (votre système actuel) :**
```powershell
cd "C:\Users\YOATH\Downloads\facebook-text-styler"
```

**Sur Linux / macOS :**
```bash
cd /home/yaakov/Facebook-text-styler
```

---

## 2. Effectuer vos modifications

Modifiez le code directement dans le fichier `index.html` (et répercutez-les dans `bold-facebook.html` si vous souhaitez garder une copie conforme de sauvegarde).

---

## 3. Tester localement

Double-cliquez sur `bold-facebook.html` (ou `index.html`) pour l'ouvrir dans votre navigateur Firefox et tester les changements.

---

## 4. Publier et mettre à jour sur GitHub

Une fois vos modifications validées, exécutez ces commandes Git classiques depuis le terminal :

```bash
# Ajouter toutes les modifications au suivi Git
git add .

# Enregistrer vos changements avec un message explicatif
git commit -m "Description de la modification (ex: style: ajustement des marges)"

# Pousser les modifications sur la branche principale
git push origin main
```
