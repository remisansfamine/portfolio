---
title: Rasterizer
date: 2021-01-06 16:00:00 +0200
categories: [Individual, ISART Digital]
tags: [linear algebra, c++, dear imgui, visual studio, git]
pin: true

img_path: /assets/img/rasterizer/
image:
  path: "preview.gif"
  alt: Logiciel de rendu CPU
---

<h1>Contexte du projet</h1>
<p style="text-align:justify;">
Le projet Rasterizer a été réalisé dans le cadre de mes études de Game Programming à ISART Digital. Il s'agit d'un moteur de rendu full-CPU que j'ai développé durant  ma première année, seul, pendant un peu plus d'un mois. Étant un grand fan de programmation rendu, il s'agit du projet sur lequel j'ai appris le plus de choses, sur lequel j'ai été le plus investi.
</p>

![Gouraud/Phong](gouraud_phong.gif){:.left}
<h2>La rastérisation, quésaco ?</h2>
<p style="text-align:justify;">
Avant d'aborder la définition de rastérisation, établissons ce qu'est un moteur de rendu. Un moteur de rendu est un composant logiciel permettant d'afficher des objets. Il ne s'occupe que de l'affichage. Dans le contexte d'un Rasterizer il s'agit de modèles 3D.

La rastérisation repose surtout sur l'affichage de triangles. Chaque modèle est constitué de triangles qui sont affichés l'un à la suite des autres.
</p>

![Gouraud/Phong](depth_test_blending.gif){:.right}
<h2>Mais encore ?</h2>
<p style="text-align:justify;">

Lors de l'affichage de ces triangles, nous avons un certain nombre d'étapes à mettre en place pour avoir un résultat satisfaisant, comme le Depth Test, le Lighting et le Texturing.

Le Depth Test consiste à trier les triangles lors de l'affichage. Le Lighting permet de simuler des effets de lumière sur un objet. Et le Texturing cherche à rendre des objets plus détaillés à partir d'image.

Durant ce projet j'ai pu développer toutes ces technologies et les pousser à leur limite. En développant par exemple tous les types de texture filtering.

Je me suis également amusé à développer des effets de post-process basique comme le MSAA, le Blur et le Bloom.
</p>

![Gouraud/Phong](postprocess.gif){:.left}
<h1>Mon expérience</h1>
<p style="text-align:justify;">

J'ai tout simplement adoré ce projet d'étude. J'ai pu apprendre énormément de choses, aussi bien au niveau du rendu qu'en programmation générale et dans le développement applicatif.
Je me suis énormément amusé à voir mon moteur évolué: du simple afficheur de triangles jusqu'au programme complexe capable de quasiment tout.
</p>

<h2>Pour aller plus loin</h2>
<p style="text-align:justify;">
N'hésitez surtout pas à jeter un œil au repository de mon projet <a href="https://github.com/remisansfamine/rasterizer">ici</a> !

Vous y trouverez des informations plus détaillées sur les différentes composantes de la rastérisation. Ainsi que des références utiles pour en comprendre les fondements.
</p>