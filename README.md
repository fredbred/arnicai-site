# arnicai-site

Site vitrine [ArnicAI](https://arnicai.fr) — page statique unique, sans build,
sans dépendance.

- `index.html` — la page complète (design system Herbier, thème clair/sombre,
  mentions légales incluses).
- `.htaccess` — force HTTPS et redirige toutes les variantes
  (`arnicai.com`, `www.*`) vers `https://arnicai.fr` (301).

## Déploiement

Hébergement OVH (cluster100), déployé via l'intégration Git du Manager OVH :
chaque push sur `main` déclenche un déploiement automatique dans le dossier
racine du multisite. Pas de scp, pas de build.

Édité par Bredard Consulting (SASU). Le contenu de ce dépôt est le site
public ; la marque ArnicAI est en cours de dépôt (INPI).
