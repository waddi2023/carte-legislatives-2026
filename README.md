# Carte des candidats aux législatives 2026

Carte interactive des 92 circonscriptions locales et des 12 circonscriptions régionales du Maroc, avec les têtes de liste des principaux partis, pour le scrutin du 23 septembre 2026. Habillage Challenge.ma.

Tout tient dans un seul fichier, `index.html`. Les données, les contours et les logos y sont intégrés. D3 et TopoJSON sont chargés depuis cdnjs, la police depuis Google Fonts.

## Intégrer la carte dans un article

Hébergez `index.html`, puis insérez :

```html
<iframe src="https://VOTRE-DOMAINE/carte-legislatives-2026/index.html"
        width="100%" height="1500" style="border:0" loading="lazy"
        title="Carte des candidats aux législatives 2026"></iframe>
```

Liens directs :

- vers une circonscription : `index.html#rabat-chellah`
- vers une liste régionale : `index.html#region-casa`

## Sources

- **Découpage.** Décret n° 2-11-603 du 19 octobre 2011 (BO n° 5992), inchangé pour 2026. Les 90 sièges régionaux sont répartis par la loi organique n° 27-11 modifiée (BO n° 6987).
- **Contours.** © contributeurs OpenStreetMap (ODbL), recomposés commune par commune et arrondissement par arrondissement.
- **Candidats.** Compilation Médias24 (base du 17 septembre 2026). © Médias24 : reproduction interdite sans autorisation écrite. Ces données doivent être autorisées ou remplacées avant toute publication.
- **Noms transcrits.** Les noms publiés uniquement en arabe sont transcrits en caractères latins. 13 ont été reconstitués à partir d'une source corrompue et 3 sont marqués « nom à confirmer ».
- **Logos.** Symboles électoraux recadrés d'après les logos officiels (Wikimedia Commons et Wikipédia). Ils restent la propriété des partis.

## Visibilité

Le dépôt est public. GitHub Pages n'est pas activé.
