# Técnicas do Projeto

Ao longo do desenvolvimento de um sistema de software robusto e alinhado às necessidades dos usuários, é essencial adotar um conjunto bem definido de técnicas que guiem o projeto desde a concepção até a validação dos artefatos finais. Neste documento, são detalhadas as técnicas utilizadas pela equipe ao longo do ciclo de desenvolvimento, incluindo métodos de elicitação, priorização, modelagem, validação e inspeção. Cada técnica foi aplicada com o propósito de garantir que os requisitos fossem capturados com precisão, organizados de forma lógica e transformados em representações funcionais e compreensíveis.

Além disso, são listadas as responsabilidades atribuídas a cada membro da equipe, evidenciando a colaboração e a revisão cruzada como pilares para a qualidade dos resultados. A aplicação consciente dessas técnicas permitiu uma abordagem sistemática, participativa e iterativa, assegurando que os artefatos gerados refletissem  as necessidades das partes interessadas.

## Padrão utilizado

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| -                                            | -                        |-               |
| -                                            | -                        |-               |
 
## Técnicas de Elicitação

São técnicas empregadas para a obtenção dos requisitos necessários ao início do processo de desenvolvimento do sistema.

### [Análise de Documentação](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/elicitacao/tecnicas/analise_documentacao/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [João Pedro](https://github.com/johnaopedro) | Entrevistador            |[Gabriel Flores](https://github.com/Gabrielfcoelho)|
| [Ryan Salles](https://github.com/RA-Salles)  | Secretário/Desenvolvedor |[Gabriel Flores](https://github.com/Gabrielfcoelho)|

### [Entrevista](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/elicitacao/tecnicas/entrevista/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [Amanda Cruz](https://github.com/mandicrz)   | Entrevistadora           |[Ryan Salles](https://github.com/RA-Salles)|
| [Julia Gabriela](https://github.com/JuliaGabP)| Entrevistadora          |[Ryan Salles](https://github.com/RA-Salles)|
| [Gabriel Flores](https://github.com/Gabrielfcoelho)| Secretário/Desenvolvedor|[Ryan Salles](https://github.com/RA-Salles)|

### [Instrospecção](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/elicitacao/tecnicas/introspec%C3%A7%C3%A3o/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
|[Julia Gabriela](https://github.com/JuliaGabP)| Usuária                  |[Ryan Salles](https://github.com/RA-Salles)|
| [João Pedro](https://github.com/johnaopedro) | Usuário                 |[Ryan Salles](https://github.com/RA-Salles)|


### [Questionário](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/elicitacao/tecnicas/questionario/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
|[Julia Gabriela](https://github.com/JuliaGabP)| Criadora do Questionário |[João Pedro Costa](https://github.com/johnaopedro)|
|[Ryan Salles](https://github.com/RA-Salles)   | Criador do Questionário  |[João Pedro Costa](https://github.com/johnaopedro)|

### [Persona](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/elicitacao/personas/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
|[Amanda Cruz](https://github.com/mandicrz)    | Criação das Personas     |[Julia Gabriela](https://github.com/JuliaGabP)|

### [Perfil de  Usuário](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/elicitacao/perfil_usuario/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
|[Amanda Cruz](https://github.com/mandicrz)    | Criação dos Perfis       |[João Pedro Costa](https://github.com/johnaopedro)|

## Técnicas de Priorização

São técnicas empregadas para a priorização dos requisitos elicitados anteriormente.

### [$100 Doláres ](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/elicitacao/priorizacao/100dollars/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [Amanda Cruz](https://github.com/mandicrz)   | Distribuição dos Dólares |[João Pedro](https://github.com/johnaopedro)|
| [Gabriel Flores](https://github.com/Gabrielfcoelho)  | Distribuição dos Dólares  |[João Pedro](https://github.com/johnaopedro)|

### [First Things First](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/elicitacao/priorizacao/first_thing_first/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [Gabriel Flores](https://github.com/Gabrielfcoelho) | Priorização dos Requisitos  | [Ryan Salles](https://github.com/RA-Salles)|

### [MoSCoW](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/elicitacao/priorizacao/moscow/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [Ryan Salles](https://github.com/RA-Salles)  | Entrevistador            |[João Pedro Costa](https://github.com/johnaopedro)|
| [João Igor](https://github.com/JoaoPC10)     | Observador               |[João Pedro Costa](https://github.com/johnaopedro)|
| [Gabriel Flores](https://github.com/Gabrielfcoelho) | Secretário        |[João Pedro Costa](https://github.com/johnaopedro)|

### [Three Level Scale](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/elicitacao/priorizacao/three_level_scale/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [João Pedro Costa](https://github.com/johnaopedro)  | Entrevistador            |[Ryan Salles](https://github.com/RA-Salles)|
| [João Igor](https://github.com/JoaoPC10)     | Observador               |[Ryan Salles](https://github.com/RA-Salles)|
| [Gabriel Flores](https://github.com/Gabrielfcoelho) | Secretário        |[Ryan Salles](https://github.com/RA-Salles)|

## Técnicas de Modelagem Clássicas 

São técnicas empregadas para a modelagem dos requisitos elicitados anteriormente.

### [Casos de Uso](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/caso_de_uso/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [João Igor](https://github.com/JoaoPC10)     | Criação do Caso de Uso 16  |[Gabriel Flores](https://github.com/Gabrielfcoelho)|
| [Gabriel Flores](https://github.com/Gabrielfcoelho)| Criação de Caso de Uso 14|[João Igor](https://github.com/JoaoPC10)|
| [Amanda Cruz](https://github.com/mandicrz)   | Criação de Caso de Uso 15  |[Julia Gabriela](https://github.com/JuliaGabP)|
| [Ryan Salles](https://github.com/RA-Salles)  | Criação dos Casos de uso 4, 5, 8 e 9 |[João Pedro Costa](https://github.com/johnaopedro)|
| [Julia Gabriela](https://github.com/JuliaGabP)| Criação dos Casos de uso 1 à 3, 6 e 7 |[Amanda Cruz](https://github.com/mandicrz)|
| [João Pedro Costa](https://github.com/johnaopedro)| Criação de Casos de Uso 10 à 13  |[Ryan Salles](https://github.com/RA-Salles)|

### [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/especificacao_suplementar/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [João Pedro Costa](https://github.com/johnaopedro)| Criação das Especificações 4 à 7|[Ryan Salles](https://github.com/RA-Salles)|
| [Julia Gabriela](https://github.com/JuliaGabP)| Criação das Especificações 8 à 12|[Ryan Salles](https://github.com/RA-Salles)|

### [Léxico](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/lexico/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
|[Gabriel Flores](https://github.com/Gabrielfcoelho) |Criação dos Léxicos L01 á L11|[Ryan Salles](https://github.com/RA-Salles)|
|[João Igor](https://github.com/JoaoPC10)      |Criação dos Léxicos L12 á L21      |[Ryan Salles](https://github.com/RA-Salles)|
| [João Pedro Costa](https://github.com/johnaopedro)|Criação dos Léxicos relacoionados as UC10, UC11, UC12  |[Ryan Salles](https://github.com/RA-Salles)|

### [Cenários](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/cenarios/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
|[Amanda Cruz](https://github.com/mandicrz)    | Criação de Cenários 14 e 15 |[João Pedro Costa](https://github.com/johnaopedro)|
|[João Igor](https://github.com/JoaoPC10)      | Criação de Cenários  16    |[Gabriel Flores](https://github.com/Gabrielfcoelho)|
|[Julia Gabriela](https://github.com/JuliaGabP)|Criação de Cenários  1, 2, 3, 6 e 7     |[João Pedro Costa](https://github.com/johnaopedro)|
|[Gabriel Flores](https://github.com/Gabrielfcoelho)| Criação de Cenários |[João Pedro Costa](https://github.com/johnaopedro)|
|[Ryan Salles](https://github.com/RA-Salles)   | Criação de Cenários  4, 5, 8 e 9    |[João Pedro Costa](https://github.com/johnaopedro)|
|[João Pedro Costa](https://github.com/johnaopedro)| Criação de Cenários 10 à 13 |[João Pedro Costa](https://github.com/johnaopedro)|


## Técnicas de Modelagem Ágeis

São técnicas empregadas para a modelagem dos requisitos elicitados anteriormente, porém focadas na entrega rápida de uma visualização do funcionamento do sistema para o cliente.

### [Backlog](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/agil/backlog/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
|[Gabriel Flores](https://github.com/Gabrielfcoelho)|Criação de Épicos 3 e 4|[João Igor](https://github.com/JoaoPC10) |
|[Ryan Salles](https://github.com/RA-Salles)   |Entrevistador/Desenvolvedor e Criação de Épicos 1, 2, 5 e 6|[João Igor](https://github.com/JoaoPC10)|
| [João Pedro Costa](https://github.com/johnaopedro) | Desenvolvedor/Secretário   |[João Igor](https://github.com/JoaoPC10)|

### [História de Usuário](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/agil/historia_de_usuario/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
|[Amanda Cruz](https://github.com/mandicrz)    | Criação de Histórias 32 até 37   |[Julia Gabriela](https://github.com/JuliaGabP)|
|[Gabriel Flores](https://github.com/Gabrielfcoelho)| Criação de Histórias 20 até a 25|[Julia Gabriela](https://github.com/JuliaGabP)|
|[João Igor](https://github.com/JoaoPC10)      | Criação de Histórias  1 à 6   |[Julia Gabriela](https://github.com/JuliaGabP)|
|[Julia Gabriela](https://github.com/JuliaGabP)|Criação de Histórias  7 á 12    |[Julia Gabriela](https://github.com/JuliaGabP)|
|[Ryan Salles](https://github.com/RA-Salles)   | Criação de Histórias   26 à 31  |[Julia Gabriela](https://github.com/JuliaGabP)|
|[João Pedro Costa](https://github.com/johnaopedro)| Criação de Histórias 19 a 25|[Julia Gabriela](https://github.com/JuliaGabP)|

### [NFR](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/modelagem/agil/NFR/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [João Igor](https://github.com/JoaoPC10)     | Desenvolvimento RNF16         |[Gabriel Flores](https://github.com/Gabrielfcoelho)|
| [Gabriel Flores](https://github.com/Gabrielfcoelho)| Criação de NFR: NFR 03     |[João Igor](https://github.com/JoaoPC10)|
| [Amanda Cruz](https://github.com/mandicrz)   | Criação de NFR : NFR01 e NFR00          |[Julia Gabriela](https://github.com/JuliaGabP)|
| [Ryan Salles](https://github.com/RA-Salles)  | Criação de NFR:NFR 02 e Desenvlvimento do RNF17  |[João Pedro Costa](https://github.com/johnaopedro)|
| [Julia Gabriela](https://github.com/JuliaGabP)| Criação de NFR          |[Amanda Cruz](https://github.com/mandicrz)|
| [João Pedro Costa](https://github.com/johnaopedro)| Criação de NFR : NFR01    |[Ryan Salles](https://github.com/RA-Salles)|

## Técnicas de Modelagem Funcionais/Interativas

### [Prototipagem](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/prototipo/prototipo/)

São técnicas empregadas com o obejtivo de mostrar ao cliente um protótipo funcional dos requisitos elicitados, com a intenção de guiar o desenvolvimento.

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [Gabriel Flores](https://github.com/Gabrielfcoelho)| Criação de Protótipos 04 e 05  |[João Igor](https://github.com/JoaoPC10)|
| [João Igor](https://github.com/JoaoPC10)     | Criação de Protótipos  02 e 03        |[Gabriel Flores](https://github.com/Gabrielfcoelho)|
| [Amanda Cruz](https://github.com/mandicrz)   | Criação de Protótipos 06           |[Julia Gabriela](https://github.com/JuliaGabP)|
| [Ryan Salles](https://github.com/RA-Salles)  | Criação de Protótipos  09 e 10,     |[João Pedro Costa](https://github.com/johnaopedro)|
| [Julia Gabriela](https://github.com/JuliaGabP)| Criação de Protótipo 01   |[Amanda Cruz](https://github.com/mandicrz)|
| [João Pedro Costa](https://github.com/johnaopedro)| Criação de Protótipos 07 e 08  |[Ryan Salles](https://github.com/RA-Salles)|

## Técnicas de Validação

São técnicas que tem como objetivo obter a opinião do cliente em relação aos protótipos criados, averiguando se os requistos estão de acordo com oque foi pensado pelas partes interessadas.

### [Validação](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/prototipo/prototipo/)

| Responsáveis                                 | Função                   |Secretário/Observador(Revisor)        |
| :------------------------------------------: | :----------------------: |:--------------:|
| [João Igor](https://github.com/JoaoPC10)     | Entrevistador/Desenvolvedor |[Gabriel Flores](https://github.com/Gabrielfcoelho)|
| [Gabriel Flores](https://github.com/Gabrielfcoelho)| Entrevistador/Desenvolvedor|[João Igor](https://github.com/JoaoPC10)|
| [Amanda Cruz](https://github.com/mandicrz)   | Entrevistador/Desenvolvedor|[Julia Gabriela](https://github.com/JuliaGabP)|
| [Ryan Salles](https://github.com/RA-Salles)  | Entrevistador/Desenvolvedor|[João Pedro Costa](https://github.com/johnaopedro)|
| [Julia Gabriela](https://github.com/JuliaGabP)| Entrevistador/Desenvolvedor |[Amanda Cruz](https://github.com/mandicrz)|
| [João Pedro Costa](https://github.com/johnaopedro)| Entrevistador/Desenvolvedor |[Ryan Salles](https://github.com/RA-Salles)|

## Técnicas de Inspeção

São técnicas que tem como objetivo verificar se os artefatos produzidos no decorrer do desenvolvimento estão corretamente empregados.

### [Verificação](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/verificacao/checklist_1/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [Amanda Cruz](https://github.com/mandicrz)   | Criação de Itens para a Verificação       |[Julia Gabriela](https://github.com/JuliaGabP) |
| [Gabriel Flores](https://github.com/Gabrielfcoelho)| Criação de Itens para a Verificação |[João Igor](https://github.com/JoaoPC10)|
| [João Igor](https://github.com/JoaoPC10)   | Criação de Itens para a Verificação         |[Gabriel Flores](https://github.com/Gabrielfcoelho)|
| [Ryan Salles](https://github.com/RA-Salles)  | Criação de Itens para a Verificação       |[João Pedro Costa](https://github.com/johnaopedro)|
| [Julia Gabriela](https://github.com/JuliaGabP)| Criação de Itens para a Verificação      |[Amanda Cruz](https://github.com/mandicrz)|
| [João Pedro Costa](https://github.com/johnaopedro)| Criação de Itens para a Verificação  |[Ryan Salles](https://github.com/RA-Salles)|

### [Inspeção de Fagan](https://requisitos-de-software.github.io/2025.1-Cadastro-Unico/inspecoes/inspecao_de_fagan/etapa1/)

| Responsáveis                                 | Função                   |Revisor         |
| :------------------------------------------: | :----------------------: |:--------------:|
| [Ryan Salles](https://github.com/RA-Salles)  | Moderador/Inspetor       |[Gabriel Flores](https://github.com/Gabrielfcoelho)|
| [João Pedro Costa](https://github.com/johnaopedro) | Autor/Leitor       |[Gabriel Flores](https://github.com/Gabrielfcoelho)|
| [Amanda Cruz](https://github.com/mandicrz)   | Moderador/Inspetor       |[Gabriel Flores](https://github.com/Gabrielfcoelho)|
| [João Igor](https://github.com/JoaoPC10)     | Autor/Leitor             |[Gabriel Flores](https://github.com/Gabrielfcoelho)|


## Histórico de Versão

| Versão |    Data    |      Descrição       |          Autor        |       Revisor       |
| :----: | :--------: | :------------------: | :-------------------: | :-----------------: |
|  1.0   | 04/07/2025 | Criação do Documento e adição das informações respectivas | [João Igor](https://github.com/JoaoPC10)    | [Ryan Salles](https://github.com/RA-Salles) |
