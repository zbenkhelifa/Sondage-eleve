# Sondage anonyme — Climat de classe

Un formulaire de sondage anonyme, prêt à déployer gratuitement sur GitHub Pages, connecté à [Web3Forms](https://web3forms.com/) pour recevoir les réponses par mail — sans back-end, sans base de données.

## ⚠️ À faire avant de déployer

Ce fichier contient une clé d'accès Web3Forms dans `index.html` :

```html
<input type="hidden" name="access_key" value="...">
```

**Remplace-la par ta propre clé** (gratuite sur [web3forms.com](https://web3forms.com/)), sinon les réponses de tes élèves seront envoyées à la boîte mail de la personne qui a créé ce dépôt à l'origine — pas à la tienne.

## Utilisation

1. Clique sur **Use this template** en haut de cette page pour créer ta propre copie.
2. Ouvre `index.html`, remplace la clé d'accès par la tienne.
3. Personnalise les questions si besoin.
4. Va dans **Settings → Pages**, choisis la branche `main` et le dossier `/ (root)`.
5. Ton sondage est en ligne à `https://tonpseudo.github.io/nom-du-repo`.

## Licence

Ce projet est sous licence MIT — libre de réutilisation, modification et partage. Voir [LICENSE](./LICENSE).

---

Idée originale par Zahire Benkhelifa ([Code09](https://www.linkedin.com/)) — rédigé avec Claude.
