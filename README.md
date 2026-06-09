# Synapz — Téléchargement

## ⬇️ Télécharger la dernière version

👉 **[Clique ici pour télécharger](https://github.com/Mahir0wo/synapz-releases/releases/latest)** 👈

---

### Quel fichier choisir ?

| Ton système | Fichier à télécharger |
|-------------|----------------------|
| 🪟 Windows | `synapz_Windows.exe` |
| 🐧 Linux | `synapz_Linux.AppImage` |
| 🍎 Mac M1/M2/M3 | `synapz_macOS_ARM.dmg` |
| 🍎 Mac Intel (avant 2020) | `synapz_macOS_Intel.dmg` |

> **Tu sais pas lequel choisir ?** Prends `.exe` si tu es sur Windows, `.dmg` si tu es sur Mac.

---

## 👤 Créer un compte

Les comptes Synapz sont créés via notre Discord. Rejoins-nous et ouvre un ticket pour obtenir ton accès :

👉 **[Rejoindre le Discord](https://discord.gg/6AbPp7MRNC)**

---

## 🍎 Problème sur Mac M1/M2/M3 — L'app ne s'ouvre pas ?

macOS bloque les applications qui ne sont pas signées par Apple. C'est normal, voilà comment contourner ça :

### Méthode 1 — Clic droit (la plus simple)
1. Fais un **clic droit** sur `Synapz.app` dans ton dossier Applications (ou dans le DMG)
2. Clique sur **Ouvrir**
3. Dans le dialogue qui apparaît, clique de nouveau sur **Ouvrir**

### Méthode 2 — Réglages Système
1. Essaie d'ouvrir l'app normalement (elle sera bloquée)
2. Va dans **Réglages Système** → **Confidentialité et sécurité**
3. Descends jusqu'à voir le message *"Synapz a été bloqué..."*
4. Clique sur **Ouvrir quand même**

### Méthode 3 — Terminal (si les deux autres échouent)
```bash
sudo xattr -rd com.apple.quarantine /Applications/Synapz.app
```
Ensuite relance l'app normalement.

> Ces étapes ne sont nécessaires qu'**une seule fois** à la première ouverture.

---

❓ **Autre problème ?** Rejoins le [Discord](https://discord.gg/6AbPp7MRNC) et ouvre un ticket.
