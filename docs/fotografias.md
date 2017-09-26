---
layout: landing
title: Memória visual
description: 
image: assets/images/foto-plantas.png
tile-display: true
peso: 30
permalink: /fotografias/
projetos_antigos:
    - legenda: "Desenho da vista da Boca de Cena, Projeto do Theatro Melpômene, Filinto Santoro, 1895. Fonte: Arquivo Público do Estado do Espirito Santo – APEES."
      foto: original1.png
    - legenda: "Planta do passeio do Theatro Melpômene, 1896. Projeto do Theatro Melpômene. Planta do passeio do Theatro, 1986. Autoria do desenho: assinatura ilegível. Prefeitura Municipal de Vitória. Fonte: Arquivo Público do Estado do Espirito Santo – APEES."
      foto: original2.png
projetos:
    - legenda: "Planta baixa pavimento térreo"
      foto: projeto1F.png
    - legenda: "Planta baixa primeiro pavimento"
      foto: projeto2F.png
    - legenda: "Cortes AA' e BB'"
      foto: projeto4F.png
    - legenda: "Corte CC' e Fachada Frontal"
      foto: projeto5F.png
legendas:
    - legenda: "Cartão postal com reprografia colorida do Theatro Melpômene, 1906. Fonte: Coleções Especiais da Biblioteca Central da UFES, Acervo Fotográfico MÁRIO ARISTIDES FREIRE, P. 20 Foto 297."
      foto: FIGURA-39F.png
    - legenda: "Cartão postal com fotografia colorizada do Theatro Melpômene. Fonte: Publicado em Facebook/Fotos Antigas do Espírito Santo, por Marcos José Andrade em 09/12/2013."
      foto: FIGURA-43F.png
    - legenda: "O Theatro Carlos Gomes, inaugurado em 1927, e a Praça Costa Pereira já remodelada, em 1928. Fonte: Acervo Fotográfico do Arquivo Público Municipal de Vitória, Foto 5.364."
      foto: FIGURA-82F.png
    - legenda: "Desenho em bico de pena de André Carloni, representando o Largo da Conceição e o Theatro Melpômene em 1905, Vitória, 1961. Fonte: Coleções Especiais da Biblioteca Central da Universidade Federal do Espírito Santo - UFES, Acervo de Desenhos (bico de pena) de André Carloni."
      foto: FIGURA-83F.png
    - legenda: "Desenho do arquiteto Moacir Fraga de 1969, apresentando o Theatro Melpômene em 1922, “em dia de grande récita”. Fonte: Instituto do Patrimônio Histórico e Artístico Nacional do Espírito Santo (IPHAN-ES), Foto VTR-2611."
      foto: FIGURA-84F.png
    - legenda: "Praça Costa Pereira atualmente. O espaço deixado pelo Theatro Melpômene fica evidente no território. O palco estaria no local do edifício do Hotel/Farmácia/Lanchonete, e a plateia e áreas sociais ficavam no vazio ocupado pela mini-praça e vias de circulação da localidade. O acesso à rua Graciano Neves não seria o mesmo se o teatro ainda estivesse ali. Foto: Colette Dantas"
      foto: FIGURA-85F.png
---

<h2>Fotografias</h2>
<div class="box alt">
    <div class="row uniform">
        {% for counter in (0..5) %}
        <div class="6u">
            <span class="image">
                <img src="{{ site.baseurl }}/assets/images/fotografias/{{page.legendas[counter].foto}}" alt="{{page.legendas[counter].legenda}}" height="300" />
                <span class="label">{{page.legendas[counter].legenda}}</span>
            </span>
        </div>
        {% endfor %}
    </div>
</div>

<h2>Plantas arquitetônicas originais</h2>
<div class="box alt">
    <div class="row uniform">
        {% for counter in (0..1) %}
        <div class="6u">
            <span class="image">
                <img src="{{ site.baseurl }}/assets/images/projeto/{{page.projetos_antigos[counter].foto}}" alt="{{page.projetos_antigos[counter].legenda}}" height="300" />
                <span class="label">{{page.projetos_antigos[counter].legenda}}</span>
            </span>
        </div>
        {% endfor %}
    </div>
</div>

<h2>Plantas arquitetônicas redesenhadas</h2>
<div class="box alt">
    <div class="row uniform">
        {% for counter in (0..3) %}
        <div class="6u">
            <span class="image">
                <img src="{{ site.baseurl }}/assets/images/projeto/{{page.projetos[counter].foto}}" alt="{{page.projetos[counter].legenda}}" height="300" />
                <span class="label">{{page.projetos[counter].legenda}}</span>
            </span>
        </div>
        {% endfor %}
    </div>
</div>
