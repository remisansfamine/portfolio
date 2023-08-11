---
title: Cherry Crisis
date: 2022-06-17 16:00:00 +0200
categories: [Teamwork, ISART Digital]
tags: [opengl, c++, mono, swig, scripting, interfacing, prototyping, optimization, dear imgui, glfw, visual studio, linear algebra, git, gitlab]
authors: [remi_giner, benjamin_marin, lancelot_marechal, rayane_tadjer]
pin: true

img_path: /assets/img/cherrycrisis/
image:
  path: "preview.png"
  alt: Cherry Crisis, taste your limits
---

<h2>L'heure du changement</h2>
Depuis la sortie de Wolfenstein en 92', les jeux 3D en temps réel sont devenus la norme, ils ont dû se démarquer de plein de façons créatives. Mais après 30 ans, on s'en lasse un peu, non ? Ne serait-il pas temps de tout révolutionner ? Le non-euclidien, vous en avez déjà entendu parler ?

{% include embed/youtube.html id='BmKQScNuJ2E' %}

<h2>La solution: la Cerise</h2>
![Espace de Clyde](espace_de_clyde.png){:.left}
<p style="text-align:justify;">
Cherry Crisis est un moteur de jeu permettant de réaliser n'importe quel type de projets 3D. Aussi bien des jeux que des expériences interactives. Grâce à un éditeur pratique et à un système de scripting C# facile d'utilisation, il vous sera permis de tester les limites de votre imagination ! Il vous en faut plus ? Cherry Crisis est LA SOLUTION pour réaliser vos projets non-euclidiens !
</p>


<h2>Les mathématiques d'Euclide</h2>
![Superposition](superposition.gif){:.right}
<p style="text-align:justify;">
On vous vend du rêve. Mais le non-euclidien, qu'est-ce que c'est ? La définition du non-euclidien provient de l'affirmation suivante: Dans un espace euclidien, la distance la plus courte entre deux points est une ligne droite.  De ce fait dans un espace N-E il peut s'agir de tout à l'exception d'une ligne droite.
</p>

<h2>Et si on trichait un peu !</h2>
![Cell view](cell_view.gif){:.left}
<p style="text-align:justify;">
Développé sous OpenGL, la Cerise utilise un rendu de rastérisation, technologie nous empêchant l'utilisation d'un modèle mathématique non-euclidien. Pour parer à cette solution nous avons créé une solution maison: Le Cell-system !

Ce composant du moteur permet la superposition de scènes sur un même espace, et donc l'extension de l'espace 3D que vous utilisez. Il inclut un système de portails permettant une réduction des draw calls.
</p>

<h1>Téléchargement</h1>
<iframe frameborder="0" src="https://itch.io/embed/1639249?bg_color=ffffff&amp;fg_color=00517d&amp;link_color=16adff&amp;border_color=ffffff" width="552" height="167"><a href="https://remisansfamine.itch.io/espace-de-clyde">Espace de Clyde by Rémi, Rayane Tadjer, Lancelot Marechal</a></iframe>


<h1>Plus sur le projet</h1>
![Rigidbody](rigidbody_portal.gif){:.right}
<p style="text-align:justify;">
Cherry Crisis est le deuxième projet de fin d'année sur lequel j'ai travaillé à ISART Digital. En équipe de quatre programmeurs, il nous a été demandé de développer un moteur de jeu en 6 mois. Celui-ci devant permettre de réaliser un jeu en deux semaines. Le moteur devait inclure directement la Core feature du jeu. Défi accepté, Cherry Crisis supporte intégralement les espaces non-euclidiens. Il comporte également un éditeur avancé, un rendu PBR, du scripting C#, un système d'Inputs complexe ainsi que la compression et un chargement multi-threadé des ressources, et plein de petites features sympathiques pour le développement d'un jeu. 
</p>


<h1>Mon expérience</h1>
<p style="text-align:justify;">
Il s'agit du projet le plus ambitieux sur lequel j'ai pu travailler, et celui sur lequel j'ai le plus appris. J'ai pu m'occuper intégralement du scripting du C# et de l'interfacing du C++, cela m'a également permis de toucher à la sérialisation. J'ai aussi mis en place les fondations du moteur de rendu grâce à un système de pipelines avancé. Après 6 mois de travail non-stop pour avoir un résultat quasi-parfait. Je peux affirmer que cela a été très éprouvant et stressant. Mais cela a valu la peine, il s'agit du projet dont je suis le plus fier.
</p>
