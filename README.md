# Grille d’analyse de référentiel - CCF

Outil d’aide à l’analyse des référentiels d’évaluation CCF EPS (BAC GT / AEFE, BAC Pro, CAP) pour la commission académique — CAHP Nantes.
N’EPS — by Quentin Delisle.

## Contenu

| Fichier | Rôle |
|---|---|
| `index.html` | L’application complète (interface, critères, intitulés officiels, liste des APSA) |
| `manifest.webmanifest` | Permet d’installer l’application (ordinateur, tablette, téléphone) |
| `sw.js` | Fonctionnement hors connexion |
| `icons/` | Icônes de l’application |
| `.nojekyll` | Indique à GitHub Pages de publier les fichiers tels quels |

## Mise en ligne sur GitHub Pages

1. Créer un dépôt sur GitHub (public, par exemple `grille-ccf`).
2. Bouton **Add file › Upload files** : glisser **tout le contenu** de ce dossier (y compris le dossier `icons` et le fichier `.nojekyll`), puis **Commit changes**.
3. **Settings › Pages** : Source = *Deploy from a branch*, Branch = `main`, dossier `/ (root)`, puis **Save**.
4. Après une à deux minutes, l’application est accessible à l’adresse `https://<votre-identifiant>.github.io/<nom-du-dépôt>/`.

## Mettre à jour

Remplacer `index.html` dans le dépôt, puis dans `sw.js` changer `grille-ccf-v1` en `grille-ccf-v2` (v3, etc.) et déposer aussi ce fichier : les utilisateurs récupèrent ainsi la nouvelle version.

## Données

Aucune donnée d’analyse n’est conservée : fermer ou recharger la page efface l’analyse en cours.
Les modifications faites dans l’onglet **Administration** sont enregistrées uniquement dans le navigateur de l’utilisateur ; utiliser *Exporter / Importer les critères* pour les partager.
