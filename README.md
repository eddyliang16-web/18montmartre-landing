# 18 Montmartre Parfum - Landing Page

Landing page temporaire prête à être déployée sur GitHub Pages.

## Contenu
- `index.html`
- 10 images utilisées par la landing page
- `CNAME` avec le domaine `www.18montmartre-parfum.com`

## Déploiement GitHub Pages
1. Crée un nouveau dépôt GitHub (public ou privé).
2. Dans le dossier `landing-ghpages`, ajoute le remote GitHub :

```bash
cd landing-ghpages
git remote add origin https://github.com/<ton-user>/<nom-du-repo>.git
```

3. Pousse vers GitHub :

```bash
git push -u origin master
```

4. Active GitHub Pages dans les paramètres du dépôt :
   - Source : `master` branch / `main` branch
   - Dossier : `/ (root)`

5. Attends 5-10 minutes, puis ouvre :
   - `https://<ton-user>.github.io/<nom-du-repo>/`

## Connexion du domaine OVH
1. Dans GitHub, active le domaine personnalisé et vérifie le CNAME.
2. Dans OVH DNS :
   - `A` vers `185.199.108.153`
   - `A` vers `185.199.109.153`
   - `A` vers `185.199.110.153`
   - `A` vers `185.199.111.153`
   - `CNAME` pour `www` vers `<ton-user>.github.io`

## Note
C'est une solution temporaire. Quand Shopify sera prêt, il faudra changer ces DNS pour pointer vers Shopify.
