# Le Noël des Borieu Rouch Valery Dalcol

Liste de cadeaux de Noël partagée en famille : une chaussette par personne, on réserve, on achète, on emballe.

- `index.html` : la vue principale (qui offre quoi à qui), protégée par le code famille.
- `envies.html` : « Ta lettre au Père Noël », page séparée où chacun dépose ses envies, avec son propre code. Elle ne voit ni qui offre quoi, ni les idées notées par les autres.
- Données dans Supabase (projet `hotte-noel`). Les tables sont fermées : la page passe par des fonctions SQL qui exigent le code famille, transmis dans le lien (`#code`).
- `.github/workflows/keepalive.yml` appelle la base tous les 3 jours pour éviter la mise en pause du projet gratuit.
