# 3 Web 15 mois cours creative coding avancé

## Le cours se compose en 3 étapes :
- Navigation Drag & Drop et Slides de la carte
- Réalité augmentée
- Prototype final

---

## Cours du 22 octobre 2024

### Drag & drop 1
- Déplacer en drag & drop la carte sur l'axe x : exemple dans le ficher `dragndrop01.html`
 
![gif](images/dragndrop1.gif)

### Drag & drop 2
- Déplacer la carte en drag & drop sur tous les axes `dragndrop02.html`

![gif](images/dragndrop02.gif)


### Slides
- Swiper dans les parties de la carte `slides01.html`

![gif](images/swipe.gif)

---

## Cours du 12 et 15 novembre
Utilisation de la librairie [MindAR](https://hiukim.github.io/mind-ar-js-doc/). Les exercices se composent de trois étapes :
- Démo basic provenant de MinAR
- Démo personnalisée avec une seule cible
- Démo personnalisée avec plusieurs cibles détectées les unes après les autres

### Démo personnalisée avec une seule cible

Image cible

![image](images/AR/chene.jpg)

### Démo personnalisée avec plusieurs cibles

La propriété `animation-mixer` sert à jouer l'animation qui est intégrée au fichier 3D au format .gltf. Cette animation est réalisée au préalable avec le logiciel Blender par exemple.

L'animation peut aussi être réalisée avec la propriété `animation` comme dans l'exemple basic :
`animation="property: position; to: 0 0.1 0.1; dur: 1000; easing: easeInOutQuad; loop: true; dir: alternate"`

Image cible 01 (affiche l'objet 3D étoile)

![image01](images/AR/cible01.jpg)

Image cible 02 (affiche l'objet 3D pyramide)

![image02](images/AR/cible02.jpg)
