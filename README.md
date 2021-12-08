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

Visando o alvo de aplicação da interface é evidente que o sistema deve possuir alta eficiência energética. É interessante que o computador esteja de acordo o hardware implementado no sistema real, e que os sensores a serem adicionados sejam compatíveis com o mesmo.

As grandezas estipuladas como requisitos são: Posição GPS, orientação cardeal, velocidade, tensão e corrente na bateria. O diagrama de blocos abaixo apresenta o sistema e os sensores que devem ser implementados. Possíveis módulos a serem tilizados: Neo 6M GPS, Bússola HMC5883L, MPU-6050 Acelerômetro e Giroscópio.

![Diagrama concepção](https://github.com/ayresgit/Interface_para_Piloto_de_Embarcacao_Solar/blob/5f6bf20e956930dfbec1722abd79817f228a61f0/Imagens/Diagrama_concep%C3%A7%C3%A3o.PNG)

Para o hardware utilizado para a interface, o dimensionamento da tela deve ser feito cuidadosamente para que exista um equilíbrio entre área de visão ocupada e o tempo que o usuário leva para compreender os dados.

Toda a informação fornecida deve ser simplificada ao máximo para reduzir esforço cognitivo [1, 2]. Além disso, deve estar de acordo com as tarefas que o piloto irá executar. O excesso de informação apresentada pode confundir e/ou distrair o usuário [1], assim, a efetividade das informações para execução dessas tarefas deve ser estudada e sua quantidade deve corresponder à prioridade das mesmas.                                 


## Design

| Imagem das conexões entre os módulos |

### Sensores

| Função | Proposta | Custo? |
|--------|----------|--------|
| GPS | Neo 6M | xx |
| Bússola | HMC5883L | xx |
| Velocidade | MPU-6050 | xx |

| Neo 6M | HMC5883L | MPU-6050 |
|--------|--------|--------|
|![Módulo GPS Neo 6M](https://github.com/ayresgit/Interface_para_Piloto_de_Embarcacao_Solar/blob/main/Imagens/Neo%206M.PNG)|![Módulo Bússola Eletrônica](https://github.com/ayresgit/Interface_para_Piloto_de_Embarcacao_Solar/blob/main/Imagens/HMC5883L.PNG)|![Módulo Acelerômetro e Giroscópio](https://github.com/ayresgit/Interface_para_Piloto_de_Embarcacao_Solar/blob/main/Imagens/MPU-6050.PNG)| 

### Interface

Abaixo estão as fotos da embarcação atual da equipe. Observando o nicho do piloto e a seção dianteira é possível ter uma noção para dimensionar corretamente a tela.
(falta a foto com a parte dianteira montada + direção)

| Nicho do Piloto | Seção da Direção |
|--------|------|
|![Nicho do piloto](https://github.com/ayresgit/Interface_para_Piloto_de_Embarcacao_Solar/blob/899df3555cb04dffced7e3e54e8f571c010092bf/Imagens/Nicho_do_Piloto.png)|![Diâmetro da Seção da Direção](https://github.com/ayresgit/Interface_para_Piloto_de_Embarcacao_Solar/blob/899df3555cb04dffced7e3e54e8f571c010092bf/Imagens/Di%C3%A2metro_Se%C3%A7%C3%A3o_da_Dire%C3%A7%C3%A3o.png)|

Tela escolhida.

## Bibliografia

[1] HAN, Xuan; PATTERSON, Patrick; The effect of information availability in a user interface (UI) on in-vehicle task performance: A pilot study. International Journal of Industrial Ergonomics 61 (2017). Disponível [aqui,](https://reader.elsevier.com/reader/sd/pii/S0169814117302731?token=7DC00FCEEDEFC402D3D6EA906F4603617028E6641A210E748B19B247E6C2FCBBDEB48597B2F2B649EFB50A7646E7A4F1&originRegion=us-east-1&originCreation=20211208114113) acesso feito com o VPN da instituição IFSC.

