# Interface para Piloto de Embarcação Solar

Instituto Federal de Educação, Ciência e Tecnologia de Santa Catarina - Campus Florianópolis

Departamento Acadêmico de Eletrônica Curso de Engenharia Eletrônica

Projeto Integrador III

Aluno:

* Gabriel Ayres Rodrigues
 
## Sumário

1. Introdução
2. Concepção
3. Design
4. Implementação
5. Operação
6. Referências

## Introdução 

O Desafio Barco Solar (DSB) é uma competição de embarcações elétrica da qual o IFSC participa, a equipe da instituição é conhecida como Zênite Solar. O barco começa a competição com baterias carregadas e, durante o período de aproximadamente uma semana, só podem ser recarregadas pelos painéis fotovoltaicos.

Inspirada no sistema real da embarcação, a interface desenvolvida nesse projeto tem como objetivo auxiliar a pilotar um veículo. Pensando em casos rotineiros, como dirigir um carro, é paupável o conforto e segurança fornecidos por informações como velocidade, quantidade de combustível e até mesmo GPS.

## Concepção 

Visando o alvo de aplicação da interface, o sistema deve possuir alta eficiência energética e a interface deve ser acessível para não afetar a performance do piloto. Além disso, 
o projeto deve estar de acordo o hardware implementado no sistema real, assim como respeitar suas limitações (espaço de memória, entradas e saídas, ...).

As grandezas de interesse são: Posição GPS, orientação cardeal, velocidade, e sensores de tensão e corrente para baterias. O diagrama abaixo resume os sensores a serem implementados. 

![Diagrama concepção](https://github.com/ayresgit/Interface_para_Piloto_de_Embarcacao_Solar/blob/ce7a079fa91f62da34a3c3bfb89e7f4de6a3df2e/Imagens/Diagrama_concep%C3%A7%C3%A3o.PNG)

Esse projeto foca na leitura dos sensores e na programação da interface com seus valores, portanto, não serão implementadas baterias como fonte de alimentação. 

O computador escolhido é o RaspberryPI 3 Model B+, por ser o modelo utilizado no sistema real da embarcação.

