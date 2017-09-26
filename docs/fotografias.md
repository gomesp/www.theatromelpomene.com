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
    - legenda: "Planta dos cômodos da Casa de Máquinas (sem assinatura e data). Projeto do Theatro Melpômene. Fonte: Arquivo Público do Estado do Espirito Santo – APEES."
      foto: original3.png
    - legenda: "Desenho em vista e corte das colunas metálicas e encaixes. Projeto do Theatro Melpômene, Filinto Santoro, 1895. Fonte: Arquivo Público do Estado do Espirito Santo – APEES."
      foto: original4.png
    - legenda: "Detalhe das colunas de madeira e gesso. Projeto do Theatro Melpômene, Filinto Santoro, 1895. Fonte: Arquivo Público do Estado do Espirito Santo – APEES."
      foto: original5.png
    - legenda: "Croqui de detalhes dos encaixes da madeira e suas fixações metálicas. Projeto do Theatro Melpômene, Filinto Santoro, 1895. Fonte: Arquivo Público do Estado do Espirito Santo – APEES."
      foto: original6.png
    - legenda: "Prancha de detalhes com vista e corte de janela da fachada lateral. Projeto do Theatro Melpômene, Filinto Santoro, 1895. Fonte: Arquivo Público do Estado do Espirito Santo – APEES."
      foto: original7.png
    - legenda: "Croqui da Escada principal de acesso aos camarotes e frisas. Projeto do Theatro Melpômene, Filinto Santoro, 1895. Fonte: Arquivo Público do Estado do Espirito Santo – APEES."
      foto: original8.png
    - legenda: "Vista da parede de acesso do Foyer superior. Projeto do Theatro Melpômene, Filinto Santoro, 1895. Fonte: Arquivo Público do Estado do Espirito Santo – APEES."
      foto: original9.png
projetos:
    - legenda: "Planta baixa pavimento térreo"
      foto: projeto1F.png
    - legenda: "Planta baixa primeiro pavimento"
      foto: projeto2F.png
    - legenda: "Planta baixa segundo pavimento"
      foto: projeto3F.png
    - legenda: "Cortes AA' e BB'"
      foto: projeto4F.png
    - legenda: "Corte CC' e Fachada Frontal"
      foto: projeto5F.png
    - legenda: "Corte DD' e Fachada Lateral"
      foto: projeto6F.png
    - legenda: "Plantas do Passeio e da Coberta"
      foto: projeto7F.png
    - legenda: "Detalhe das Colunas Metálicas e de Madeira"
      foto: projeto8F.png
    - legenda: "Detalhe das Janelas"
      foto: projeto9F.png
    - legenda: "Planta de Situação do Theatro Melpômene em 1895 e Recorte do Planta da Chácara Muniz Freire de 1925"
      foto: projeto10F.png
legendas:
    - legenda: "Cartão postal com reprografia colorida do Theatro Melpômene, 1906. Fonte: Coleções Especiais da Biblioteca Central da Universidade Federal do Espírito Santo - UFES, Acervo Fotográfico MÁRIO ARISTIDES FREIRE, P. 20 Foto 297."
      foto: FIGURA-39F.png
    - legenda: "Cartão postal com fotografia colorizada da região da Praça Costa Pereira em 1905, com o Melpômene em destaque, e a antiga Igreja Matriz ao fundo, na Cidade Alta. Fonte: Publicado por Marcos José Andrade em 09/12/2013, Facebook/Fotos Antigas do Espírito Santo."
      foto: FIGURA-40F.png
    - legenda: "Cartão postal com fotografia colorizada do Theatro Melpômene. Fonte: Publicado em Facebook/Fotos Antigas do Espírito Santo, por Marcos José Andrade em 09/12/2013."
      foto: FIGURA-43F.png
    - legenda: "Vista da cidade sob ponto de vista da Baía de Vitória, onde destacam-se o Theatro Melpômene, e as tores das Igrejas Matriz e São Thiago. Sem data. Fonte: Instituto do Patrimônio Histórico e Artístico Nacional do Espírito Santo (IPHAN-ES), Foto VTR-3316."
      foto: FIGURA-44F.png
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
        {% for counter in (0..7) %}
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
        {% for counter in (0..8) %}
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
        {% for counter in (0..9) %}
        <div class="6u">
            <span class="image">
                <img src="{{ site.baseurl }}/assets/images/projeto/{{page.projetos[counter].foto}}" alt="{{page.projetos[counter].legenda}}" height="300" />
                <span class="label">{{page.projetos[counter].legenda}}</span>
            </span>
        </div>
        {% endfor %}
    </div>
</div>
