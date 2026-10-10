# La hotte des Borieu

Liste de cadeaux de Noël partagée en famille : une chaussette par personne, on réserve, on achète, on emballe.

- Page statique servie par GitHub Pages (`index.html`).
- Données dans Supabase (projet `hotte-noel`). Les tables sont fermées : la page passe par des fonctions SQL qui exigent le code famille, transmis dans le lien (`#code`).
- `.github/workflows/keepalive.yml` appelle la base tous les 3 jours pour éviter la mise en pause du projet gratuit.
