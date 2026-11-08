# Le problème de Koszul — ENS Ulm, juin 1966

## Pourquoi cette épreuve est-elle restée célèbre ?

En juin 1966, les candidats à l’ENS Ulm avaient six heures pour résoudre ce problème de Jean-Louis Koszul. Jean-Marie Arnaudiès rapporte qu’aucun candidat n’a dépassé la première question. Il rappelle que la convexité, qui permet ici de comprendre la forme du cône, ne figurait alors pas au programme de mathématiques spéciales. [Commentaire d’Arnaudiès, tome 2, problème 42, p. 289](https://fr.scribd.com/document/390270931/Arnaudies-Jean-Marie-Problemes-de-Preparation-a-l-Agregation-de-Mathematiques-2-Algebre-Bilineaire-Et-Geometrie-Groupes-Classiques-Calcul-Differe)

Alain Connes raconte avoir rendu une copie presque blanche et avoir trouvé la solution en quittant la salle. [Son témoignage à l’ENS en 2017](https://savoirs.ens.fr/expose.php?id=3295)

Aujourd’hui, GPT-6 Astra Pro résout ce problème en 20 minutes.

[Voir la vidéo d’Axel Arno sur l’épreuve de 1966](https://www.youtube.com/watch?v=WQIEOBjTQ1o) · [Lire l’énoncé du concours](https://fr.scribd.com/document/603917743/ens-ulm-1966)

## Contenu

Le fichier `ens_ulm_1966_koszul.pdf` contient les trois parties de l'épreuve. Chacune des 13 questions est suivie de sa résolution pas à pas.

Le fichier `ens_ulm_1966_koszul.tex` est la source modifiable du corrigé. Les figures y sont dessinées avec TikZ.

## Recompiler le PDF

Après avoir extrait l'archive, ouvrez un terminal dans le dossier des fichiers et lancez deux fois pdfLaTeX pour mettre à jour les renvois de pages.

```sh
pdflatex ens_ulm_1966_koszul.tex
pdflatex ens_ulm_1966_koszul.tex
```
