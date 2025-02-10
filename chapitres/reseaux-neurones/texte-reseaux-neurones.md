# Les réseaux de neurones

## Neurones de McCulloch et Pitts

McCulloch et Pitts (MP) sont les premiers a proposer un neurone artificiel (plus ou moins) inspiré par les neurones biologiques. La figure suivante montre un schéma du neurone de MP.

<figure>
  <img src="images/neurone_mp_schema.jpg" alt="Description de l'image" width="400">
</figure>

Les seules valeurs possibles en entrée sont binaires : 0 ou 1. Comme pour les neurones biologiques, ce neurone possède une entrée inhibitrice (identifiée par un petit cercle à l'extrémité de la connection). Les entrée $x_i$ reçues par le neurone sont simplement additionnées et comparées à une valeur seuil $\theta$, ce qui détermine la sortie :

$$
y=
\begin{cases}
0 \iff \sum x_{i} < 0\\
1 \iff \sum x_{i} \geq 0
\end{cases}
$$

## Perceptron de Rosenblatt

Directement inspiré par les travaux de MP, le psychologue Rosenblatt imagine un nouveau type de neurone. Il retire l'entrée inhibitrice et rend possible les entrées de toutes valeurs ; de plus, il ajoute une pondération à chaque entrée qui multiplie cette dernière.

## Réseaux profonds

Si Rosenblatt avait imaginé accumuler des neurones sur plusieurs couches, il n'avait pas été en mesure d'élaborer une technique pour les entraîner.

## Exemple : chats et chiens

Un problème simple et classique pour illustrer le fonctionnement d'un réseau de neurones est le jeu de données chats et chiens.

## Représentation universelle

La propriété la plus importante d'un réseau profond est le théorème de représentation universelle.
