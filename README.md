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

Inspirada no sistema real da embarcação, a interface desenvolvida nesse projeto tem como objetivo auxiliar a pilotar um veículo. Pensando em casos rotineiros como dirigir um carro, é paupável o conforto e segurança fornecidos por informações como velocidade, quantidade de combustível e até mesmo GPS.

## Concepção 

Visando o alvo de aplicação da interface, o sistema deve possuir alta eficiência energética e a interface deve ser acessível para não afetar a performance do piloto. Além disso, 
é interessante que o computador esteja de acordo o hardware implementado no sistema real, e que os sensores a serem adicionados sejam compatíveis com o mesmo.

As grandezas de interesse são: Posição GPS, orientação cardeal, velocidade, tensão e corrente na bateria. O diagrama de blocos abaixo apresenta o sistema e os sensores que devem ser implementados.

![Diagrama concepção](https://github.com/ayresgit/Interface_para_Piloto_de_Embarcacao_Solar/blob/5f6bf20e956930dfbec1722abd79817f228a61f0/Imagens/Diagrama_concep%C3%A7%C3%A3o.PNG)



| Nicho do Piloto | Seção da Direção |
|--------|------|
|![Nicho do piloto](https://github.com/ayresgit/Interface_para_Piloto_de_Embarcacao_Solar/blob/899df3555cb04dffced7e3e54e8f571c010092bf/Imagens/Nicho_do_Piloto.png)|![Diâmetro da Seção da Direção](https://github.com/ayresgit/Interface_para_Piloto_de_Embarcacao_Solar/blob/899df3555cb04dffced7e3e54e8f571c010092bf/Imagens/Di%C3%A2metro_Se%C3%A7%C3%A3o_da_Dire%C3%A7%C3%A3o.png)|

