---
title: "Groupe"
date: 2021-02-08T09:57:24+01:00
draft: false
---

## Lorem
Quelques photos en "carousel" défilant automatiquement. On peut modifier la vitesse de défilement. Et appuyer sur les flèches de navigation pour passer à la suivante ou revenir à la précédente.  
Ici un carousel à 3 photos, mais on peut en mettre autant que l'on veut.  
Le temps de défilement de la première photo est plus long que sur les suivantes.
<div class="container mb-5" >
    <div class="row justify-content-center">
        <div class="col-sm-6">
            <div id="myCarousel" class="carousel  slide " data-bs-ride="carousel" >
                <div class="carousel-inner">
                    <div class="carousel-item active" data-bs-interval="3200">
                        <img src=" /media/personnes/enfant-cheval.jpg" class="d-block img-fluid mx-auto w-100" alt="enseignant"  >
                    </div>
                    <div class="carousel-item" data-bs-interval="2000">
                    <img src="/media/personnes/marieno-chevaux.jpg" class="d-block mx-auto w-100" alt="travail" >
                    </div>
                    <div class="carousel-item" data-bs-interval="2000">
                        <img src="/media/chevaux/poneys.jpg" class="d-block mx-auto w-100" alt="travail" alt="personne" >
                    </div>
                </div>
                <a class="carousel-control-prev" href="#myCarousel" role="button" data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="sr-only"></span>
                </a>
                <a class="carousel-control-next" href="#myCarousel" role="button" data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="sr-only"></span>
                </a>
            </div>
        </div>
    </div>
</div>

## Ipsum
Les mêmes photos en carousel fixe
<div class="container mb-5" >
    <div class="row justify-content-center">
        <div class="col-sm-6">
            <div id="myCarouselFixe" class="carousel  slide " data-bs-ride="carousel" data-bs-interval="false">
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src=" /media/personnes/enfant-cheval.jpg" class="d-block img-fluid mx-auto w-100" alt="enseignant"  >
                    </div>
                    <div class="carousel-item">
                    <img src="/media/personnes/marieno-chevaux.jpg" class="d-block mx-auto w-100" alt="travail" >
                    </div>
                    <div class="carousel-item">
                        <img src="/media/chevaux/poneys.jpg" class="d-block mx-auto w-100" alt="travail" alt="personne" >
                    </div>
                </div>
                <a class="carousel-control-prev" href="#myCarouselFixe" role="button" data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="sr-only"></span>
                </a>
                <a class="carousel-control-next" href="#myCarouselFixe" role="button" data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="sr-only"></span>
                </a>
            </div>
        </div>
    </div>
</div>

