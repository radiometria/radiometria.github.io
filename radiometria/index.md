---
layout: post
date: 2015-09-10 21:54:30
summary: Sobre o Grupo de Pesquisa
thumbnail: gear
title: Sobre o Grupo
---

O [Grupo de Pesquisa em Radiometria](http://dgp.cnpq.br/dgp/espelhogrupo/1937070060304266) funciona na [Universidade Federal de Campina Grande](http://www.ufcg.edu.br/index1.php) (UFCG), sob o [Departamento de Engenharia Elétrica](http://www.dee.ufcg.edu.br/) (DEE) do seu [Centro de Engenharia Elétrica e Informática](http://www.ceei.ufcg.edu.br/) (CEEI).

## Corpo Docente

O _Grupo de Pesquisa em Radiometria_ é formado pelos seguintes docentes.

{% for membro in site.membros %}
* Prof. Dr. [{{ membro.name }}]({{ membro.lattes }}){% endfor %}

## Linhas de Pesquisa

Atualmente, o Grupo de Pesquisa em Radiometria tem as seguintes linhas de pesquisa.

* Coleta de Energia
* Dispositivos de Radio-Frequência
* Metamateriais
* [Modelagem Computacional de Efeitos Eletromagnéticos]({{ site.baseurl }}/linhas/modelagem)
* RFID e Sensoriamento
