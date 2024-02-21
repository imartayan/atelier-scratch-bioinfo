# Atelier d'initiation à la bioinformatique en Scratch

[Éditeur Scratch en ligne](https://scratch.mit.edu/projects/editor/)

Pour changer la langue : `Settings > Language > Français`

## Recherche de séquences

- Télécharger [Sequences.sb3](https://github.com/imartayan/atelier-scratch-bioinfo/raw/main/Sequences.sb3)
- Charger le fichier : `Fichier > Importer depuis votre ordinateur`
- Écrire le programme du robot pour rechercher un échantillon d'ADN dans un ensemble de séquences

## Alignement de séquences

- Télécharger [Alignement.sb3](https://github.com/imartayan/atelier-scratch-bioinfo/raw/main/Alignement.sb3)
- Charger le fichier : `Fichier > Importer depuis votre ordinateur`
- Écrire le programme du robot pour aligner un fragment d'ADN dans une longue séquence

## Outils en ligne

### [Alignement avec score](https://alignment.sandbox.bio/)

Essayer d'aligner les deux séquences suivantes :
- `GGACTAGGTTGACTGGGA`
- `GGTTGACTAGGTTGACTA`

Quelles sont les différences entre les alignements Smith-Waterman et Needleman-Wunsch ?

### [Alignement multiple](https://www.ebi.ac.uk/jdispatcher/msa/clustalo)

Sélectionner `DNA` puis copier/coller les séquences suivantes :
```
>seq1
ATGAGTCTCTCTGATAAGGACAAGGCTGCTGTGAAAGCCCTATGG
>seq2
CTGTCTCCTGCCGACAAGACCAACGTCAAGGCCGCCTGGGGTAAG
>seq3
ACAAAAGCAACATCAAGGCTGCCTGGGGGAAGATTGGTGGCCATG
>seq4
GTCTCACTGATAAGGACAAGACCAACGTCATGGCCGCCTGAGGGA
```
Lancer l'alignement avec `Submit`.

### [Recherche de séquences avec BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastn&PAGE_TYPE=BlastSearch)

Copier/coller la séquence suivante dans `Enter Query Sequence` :
```
GTTTATTCTAATTTTCACTAGTTACAAGTTATGTTGCAATGACATTCCTATCTATAAACTATTTCCCACC
```
Lancer la recherche avec `BLAST`.

Chez quels organismes retrouve-t-on cette séquence ? Dans quelle région du génome ?

### [Repliement de protéines](https://alphafold.ebi.ac.uk/)

Chercher `P09848` et visualiser sa structure en 3D.

Quelle est cette protéine ? À quoi sert-elle ?
