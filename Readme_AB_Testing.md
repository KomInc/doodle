# A/B Testing 

## Introduction

The A/B testing goal is to determine which versions from two versions of a same aplication is the more appealing to the users.
For that we are going to show to each user one version selected 
L'A/B testing consistent � comparer deux versions d'une m�me application en faisant tester chaques versions � un grand nombre d'utiliseurs.
On le fait de mani�re totalement transparente, en envoyant les utilisateur vers l'une des deux versions de mani�re totalement arbitraire.
On va ensuite r�colter les donn�es correspondantes au(x) crit�re(s) que l'on cherche � am�liorer, afin de pouvoir quelle version est la plus int�ressante pour nous.

## Pr�sentation d'un plan de route pour le r�aliser

### �tape 0 : r�cup�rer Doodle � partir du git fournit en cours
git clone https://github.com/selabs-ur1/doodle.git

### �tape 1 : download GrowthBook

```
git clone https://github.com/growthbook/growthbook.git
cd growthbook
docker-compose up -d
```

### �tape 2 : Ajouter la librairie GrowthBook dans le code de base

```
https://docs.growthbook.io/lib/js
```

### �tape 3 : g�n�rer la modification souhait�e

```
```

### �tape 4 : faire tourner les diff�rentes versions et sauvegard�s les statistiques de chacunes

### �tape 5 : Visualiser, et monitorer l'impact des variations � l'aide de GrowthBook

https://www.youtube.com/watch?v=NCIEe1me9oE


M�trics calcul�e : nombre de cliques sur le bouton + temps pass�e sur la page comportant le bouton