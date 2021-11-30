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

Inspirada no sistema real da embarcação, a interface desenvolvida nesse projeto tem como objetivo melhorar o poder de decisão do piloto com informações como: posição, medidas de velocidade, medidas elétricas.

## Concepção 

Visando o alvo de aplicação da interface, o sistema deve possuir alta eficiência energética e a interface deve ser acessível para não afetar a performance do piloto. Além disso, 
o projeto deve estar de acordo com qualquer hardware já implementado no sistema real, assim como respeitar suas limitações (espaço de memória, entradas e saídas, ...).

O diagrama abaixo resume os sensores a serem implementados. Uma vez que esse projeto foca na leitura dos sensores e na programação da interface com seus valores, não serão implementadas baterias como fonte de alimentação. 

![Diagrama de blocos](https://github.com/ayresgit/Interface_para_Piloto_de_Embarcacao_Solar/blob/66c080f19e3e0359c93418ba5f443b55b9d15e1b/Imagens/Diagrama%20de%20blocos.PNG)

O computador escolhido é o RaspberryPI 3 Model B+, por ser o modelo utilizado no sistema real da embarcação.

