# Introdução ao AutoML com PyCaret

**O que é o `PyCaret`?**

_`PyCaret` é uma biblioteca de aprendizado de máquina de código aberto e baixo código (**low-code**) em Python que permite ir desde a preparação de seus dados até a implantação de seu modelo em minutos, na escolha do ambiente de notebook._

Essa definição se encontra no próprio site da biblioteca - é uma tradução bem literal, vou tentar deixar mais claro a definição.

O principal propósito da biblioteca é otimizar as necessidades do profissional e trazer mais "produtividade" e entrega de análises/projetos de ciência de dados, aprendizado de máquinas e etc.

A biblioteca _"encapsula"_ ou melhor possui um `pipeline` de vários modelos e roda-os simultaneamente e por fim, **ranqueia** os modelos conforme um parâmetro definido de avaliação ou não pelo usuário.


> Iremos trabalhar com três cases:     
- um de _regressão_.
    - o dataset `"house"`.
- e outro de _classificação_.
    - o dataset chamado `"employee"`.
- e por fim um de _clusterização_.
    - o dataset `"seeds"`.


O dataset `house ` contém observações sobre casas e, o objetivo é prever o valor de venda da casa.

Já o dataset  `employee` contém observações de funcionários de uma empresa e, o objetivo é prever, dado algumas variáveis se o funcionário irá deixar ou não a empresa.

E por fim o dataset `seeds` contém observações sobre grão de trigo, onde iremos agrupar os mesmos por similaridade, utilizando técnica de aprendizado não-supervisionado.
