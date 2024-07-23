# grid-exercice
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galerie Photo</title>
    <style>
        .gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            padding: 10px;
            background-color: #f0f0f0;
        }

        .gallery img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="gallery">
        <img src="https://picsum.photos/id/10/200/300" alt="Image 1">
        <img src="https://picsum.photos/id/20/200/300" alt="Image 2">
        <img src="https://picsum.photos/id/30/200/300" alt="Image 3">
        <img src="https://picsum.photos/id/40/200/300" alt="Image 4">
        <img src="https://picsum.photos/id/50/200/300" alt="Image 5">
        <img src="https://picsum.photos/id/60/200/300" alt="Image 6">
        <img src="https://picsum.photos/id/70/200/300" alt="Image 7">
        <img src="https://picsum.photos/id/80/200/300" alt="Image 8">
        <img src="https://picsum.photos/id/90/200/300" alt="Image 9">
    </div>
</body>
</html>

<!-- 
1-Modifier le nombre de colonnes pour avoir 2 ou 4 colonnes au lieu de 3.
2-Changer l'espacement entre les images.
3-Ajouter une bordure autour de chaque image.
4-Implémenter un effet de survol (hover) sur les images.
5-Rendre la galerie responsive en utilisant des media queries. 
-->
