---
layout: landing
title: Exposição Revivendo o Melpômene
description: 
image: assets/images/exposicao/capa.jpg
tile-display: true
peso: 35
permalink: /exposicao/
exposicao:
    - foto: foto1.png  
    - foto: IMG_5482.JPG  
    - foto: IMGP0132.JPG  
    - foto: IMGP0140.JPG  
    - foto: IMGP0142.JPG  
    - foto: IMGP0153.JPG  
    - foto: IMGP0167.JPG  
    - foto: IMGP0183.JPG  
    - foto: IMGP0193.JPG  
    - foto: IMGP0195.JPG  
    - foto: IMGP0206.JPG
    - foto: IMG_5489.JPG  
    - foto: IMGP0134.JPG  
    - foto: IMGP0141.JPG  
    - foto: IMGP0149.JPG  
    - foto: IMGP0158.JPG  
    - foto: IMGP0168.JPG  
    - foto: IMGP0187.JPG  
    - foto: IMGP0194.JPG  
    - foto: IMGP0202.JPG
---

<h2>Convite</h2>
<div class="box alt">
    <div class="row uniform">
        <div class="6u">
            <span class="image">
                <img src="{{ site.baseurl }}/assets/images/exposicao/capa.jpg" alt="Convite para a exposição revivendo o melpômene" height="300" />
                <span class="label">
                O projeto "Revivendo o Melpômene" reuniu uma equipe multidisciplinar de profissionais das áreas de teatro, arquitetura, ciências sociais, história, comunicação e design, que partiu de uma pesquisa histórica e iconográfica para reconstruir as memórias deste importante precursor dos equipamentos culturais da cidade - o Theatro Melpômene, produzindo resultados em diversas plataformas: um livro, uma exposição (com maquetes física e eletrônica, fotos, plantas originais e redesenhadas), uma intervenção cênica e um website, lançados em setembro de 2017, com recursos da Lei Rubem Braga/PMV e Vale.
                </span>
            </span>
        </div>
    </div>
</div>

<h2>Fotografias</h2>
<div class="box alt">
    <div class="row uniform">
        {% for counter in (0..19) %}
        <div class="6u">
            <span class="image">
                <img src="{{ site.baseurl }}/assets/images/exposicao/{{page.exposicao[counter].foto}}" alt="Exposição - Instalação Revivendo o Melpômene" height="300" />
            </span>
        </div>
        {% endfor %}
    </div>
</div>
