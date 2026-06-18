# ⏱ Minuteurs & Horloge — Outils de salle de classe

Deux pages web autonomes, sans installation, sans connexion requise, sans aucune donnée collectée.  
Copiables sur une clé USB, ouvrables directement dans un navigateur.

---

## 📄 Les deux outils

### `index.html` — Gestionnaire de minuteurs
**Disponible en ligne : [timer.mesoraux.fr](http://timer.mesoraux.fr)**

Affiche autant de minuteurs que nécessaire sur une grille lisible de la salle.  
Conçu pour suivre plusieurs candidats simultanément lors d'examens ou d'oraux.

**Fonctionnalités :**
- Ajout de minuteurs à la volée avec le nom du candidat
- Démarrage automatique à l'ajout
- Affichage en rouge clignotant et temps négatif en fin de minuteur
- Son discret à l'arrivée à zéro (désactivable)
- Thème clair / sombre
- Durée par défaut configurable
- **État sauvegardé dans l'URL** — la page peut être rechargée ou partagée sans perdre les minuteurs en cours
- Heure courante affichée en grand en haut (synchronisée sur internet si disponible)
- Fonctionne entièrement hors ligne

---

### `clock.html` — Horloge & Timer de salle
**Disponible en ligne : [clock.mesoraux.fr](http://clock.mesoraux.fr)**

Une horloge plein écran, analogique ou numérique, avec un timer et une barre de progression.  
Idéale à projeter en fond de salle pendant une épreuve.

**Fonctionnalités :**
- Horloge analogique (style suisse) ou numérique
- Secondes affichables ou masquables
- Timer avec barre de progression
- Barre de repère positonnable (ex. : marquer la fin de la première heure)
- Thème clair / sombre
- Interface se masque automatiquement après 3 secondes d'inactivité
- Tous les réglages encodés dans l'URL — partageable en un lien
- Fonctionne entièrement hors ligne

---

## 🚀 Utilisation

### En ligne
Ouvrez simplement l'URL dans un navigateur :
- [timer.mesoraux.fr](http://timer.mesoraux.fr)
- [clock.mesoraux.fr](http://clock.mesoraux.fr)

### Sur clé USB / en local
Copiez `index.html` et/ou `clock.html` sur la clé.  
Double-cliquez sur le fichier — il s'ouvre directement dans le navigateur, sans serveur, sans installation.

> L'heure sera prise sur l'horloge du PC si aucune connexion internet n'est disponible.

---

## 🔒 Confidentialité

Ces outils sont **100 % côté navigateur**.  
Aucune donnée n'est transmise, enregistrée ou collectée.  
L'état des minuteurs est stocké uniquement dans l'URL de la page, sur votre machine.

---

## 📜 Licence

Ce projet est distribué sous licence **MIT** — vous êtes libre de l'utiliser, le modifier et le redistribuer, y compris à des fins commerciales, sous réserve de conserver la mention de copyright.  
Voir le fichier [LICENSE](LICENSE) pour le texte complet.

---

*Olivier Boesch © 2026*
