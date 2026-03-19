<p align="center">
  <img src="https://dash.fakturapp.cc/favicon.svg" width="64" height="64" alt="Faktur" />
</p>

<h1 align="center">Faktur</h1>

<p align="center">
  Facturation professionnelle gratuite avec chiffrement zero-access.
</p>

<p align="center">
  <a href="https://fakturapp.cc"><img src="https://img.shields.io/badge/Site-fakturapp.cc-6366f1?style=flat-square" alt="Site" /></a>
  <a href="https://dash.fakturapp.cc"><img src="https://img.shields.io/badge/App-dash.fakturapp.cc-818cf8?style=flat-square" alt="App" /></a>
</p>

---

Faktur est un logiciel de facturation con&ccedil;u pour les ind&eacute;pendants, micro-entrepreneurs et petites entreprises. Il permet de cr&eacute;er des devis et factures professionnels en quelques clics, avec un chiffrement de bout en bout inspir&eacute; de [Proton](https://proton.me).

### Principes

- **Zero-access** &mdash; Vos donn&eacute;es sont chiffr&eacute;es avec votre mot de passe. M&ecirc;me avec un acc&egrave;s complet au serveur, personne ne peut les lire.
- **Gratuit** &mdash; Pas de plan premium, pas de limite artificielle. Toutes les fonctionnalit&eacute;s sont disponibles pour tous.
- **Simple** &mdash; Interface minimaliste pens&eacute;e pour aller vite. Pas de surplus, pas de complexit&eacute; inutile.
- **Fran&ccedil;ais** &mdash; Con&ccedil;u pour la r&eacute;glementation fran&ccedil;aise (TVA, mentions l&eacute;gales, num&eacute;rotation conforme).

### Repositories

| Repository | Description |
|---|---|
| [fakturapp](https://github.com/faktur/fakturapp) | Application principale &mdash; Backend AdonisJS + Frontend Next.js |
| [faktur-accueil](https://github.com/faktur/faktur-accueil) | Page d'accueil &mdash; Landing page |

### Stack technique

- **Backend** &mdash; AdonisJS 7, PostgreSQL, AES-256-GCM, Argon2id
- **Frontend** &mdash; Next.js 16, React 19, Tailwind CSS v4, Framer Motion
- **Infrastructure** &mdash; Hetzner (Allemagne), Resend, chiffrement au repos

### S&eacute;curit&eacute;

Pour signaler une vuln&eacute;rabilit&eacute;, &eacute;crivez &agrave; **contact@fakturapp.cc**. Ne publiez pas de rapport public avant correction.

Voir la [politique de s&eacute;curit&eacute;](https://github.com/faktur/fakturapp/blob/main/SECURITY.md) pour les d&eacute;tails de l'architecture cryptographique.

### Licence

Les projets Faktur sont distribu&eacute;s sous **Personal Use License**. Usage personnel uniquement.
