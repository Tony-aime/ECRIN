

Vision Produit : Application mobile d'attentions et de surprises connectée à une WebApp sans friction pour le destinataire (via lien SMS).


- Suivi Global de tous les Modules

```dataview
TABLE module AS "Module", statut AS "Statut", priorite AS "Priorité", deadline AS "Échéance", avancement AS "Avancement (%)"
FROM "2_Taches_Livrables"
WHERE projet = "ecrin"
SORT deadline ASC
```




- Focus : Urgences & Priorités Hautes (En Cours)

```dataview
TABLE module AS "Module", deadline AS "Échéance", avancement AS "Avancement (%)"
FROM "2_Taches_Livrables"
WHERE projet = "ecrin" and statut = "En cours" AND priorite = "Haute"
SORT deadline ASC
```



- Activité Récente 

```dataview
LIST
FROM "2_Taches_Livrables"
WHERE file.mtime.day = date(today).day AND file.mtime.month = date(today).month AND file.mtime.year = date(today).year
SORT file.mtime DESC
```
