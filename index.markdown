---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: base
title: La librairie des parents - un site de la voie des parents
permalink: /
hero: |
    <style>
        @media (max-width: 768px) {
            .swiper-slide {
                background-position: left !important;
            }
        }
    </style>
    <section class="bg-cover bg-center" style="height: 75vh;">
        <div class="swiper-container" data-settings='{"autoplay":{"delay":3000,"pauseOnMouseEnter":true,"disableOnInteraction":false},"speed":2500,"direction":"horizontal","autoHeight":"","loop":true,"centeredSlides":true,"spaceBetween":0,"slidesPerView":1,"slidesPerGroup":1,"effect":"slide","coverflowEffect":{"rotate":30,"slideShadows":false,"depth":100,"stretch":50,"modifier":1},"fadeEffect":{"crossFade":true},"zoom":"","navigation":{"nextEl":".swiper-button-next","prevEl":".swiper-button-prev"},"pagination":{"type":"bullets","clickable":true,"dynamicBullets":false,"el":".swiper-pagination"},"pauseOnHover":"1","watchSlidesProgress":true,"watchSlidesVisibility":true}'>
            <div class="swiper-wrapper">
                <div class="swiper-slide bg-cover bg-center" style="background-image: url('images/index-hero-bg10.jpg');  background-size: cover; background-position: center; background-repeat: no-repeat; height: 100vh;">
                    <div class="flex items-center justify-center h-full w-full md:w-1/3 md:ml-10">
                        <div class="bg-white p-8 shadow-lg w-full md:w-auto">
                            <h1 class="text-4xl font-extrabold text-gray-900">La Librairie<br>Des<br>Parents</h1>
                            <p class="mt-4 text-xl text-gray-700">Chaque mois, Coralie, co-fondatrice de <a href="https://www.la-voie-des-parents.fr" class="text-indigo-600 hover:text-indigo-400">la voie des parents</a> (et lectrice assidue en chef) choisie un livre qui met les parents au centre de l'histoire.</p>
                            <div class="mt-8">
                                <a href="/lenfant-dormira-bientot-et-vous-aussi-guide-du-sommeil.html" class="inline-block bg-indigo-600 text-white px-8 py-3 rounded-md text-lg font-medium hover:bg-indigo-700">Notre livre sur le sommeil de l'enfant</a>
                            </div>
                        </div>
                    </div>    
                </div>
            </div>
        </div>
    </section>
cards: |
    <section class="py-12 bg-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-white p-6 rounded-lg shadow">
                    <a href="/lenfant-dormira-bientot-et-vous-aussi-guide-du-sommeil.html"><img class="h-60 w-full object-cover rounded mb-4" src="images/livre-sommeil.png" alt="Carte 1"></a>
                    <a href="/lenfant-dormira-bientot-et-vous-aussi-guide-du-sommeil.html"><h2 class="text-2xl font-bold mb-2">L'enfant dormira bientôt, et vous aussi !</h2></a>
                    <p class="text-gray-600">Guide du sommeil de bébé et de l'enfant</p>
                </div>
            </div>
        </div>
    </section>
---
