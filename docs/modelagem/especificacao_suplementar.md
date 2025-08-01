# Especificação Suplementar

## Funções dos autores

| Nome                                               | Função                                                                                                                                 | 
|----------------------                              |----------------------------------------------------------------                                                                        |
| [João Pedro Costa](https://github.com/johnaopedro) | Criação do documento; Preenchimento das seções 1 à 7; Adição das referências; Correção pelo metodo de inspeção de Fagan. Revisor Geral | 
| [Julia Gabriela](https://github.com/JuliaGabP)     | Criação do documento; Preenchimento das seções 8 à 12                                                                                  | 
| [Ryan Salles](https://github.com/RA-Salles)        | Revisão geral; Ajustes e Manutenção. Expansão da granularidade dos requisitos de usabilidade                                           | 
<center>
    Autor(es): 
    <a href="https://github.com/JuliaGabP" target="_blank">Julia Gabriela</a>
</center>

## Introdução
A Especificação Suplementar é um documento em linguagem natural, cujo objetivo principal é descrever de forma detalhada os requisitos não funcionais de um sistema. Diferentemente dos casos de uso, que focam em funcionalidades e fluxos de interação, a Especificação Suplementar captura aspectos de qualidade, restrições e características que o software deve atender, mas que não são expressos nos diagramas comportamentais.

## Metodologia
Para elaborar a Especificação Suplementar, utiliza-se como guia o modelo FURPS+, que organiza os requisitos não funcionais nas seguintes categorias:

- **Usability (Usabilidade):** facilidade de uso pelo usuário.

- **Reliability (Confiabilidade):** previsão de falhas e capacidade de recuperação.

- **Performance (Desempenho):** tempo de resposta e throughput do sistema.

- **Supportability (Suportabilidade):** manutenibilidade, portabilidade, internacionalização, entre outros

Cada requisito não funcional é descrito em linguagem natural e classificado conforme essas categorias, permitindo aos engenheiros de software entenderem claramente as expectativas de qualidade e as restrições do projeto. Essa especificação serve como complemento aos casos de uso, garantindo que aspectos críticos de usabilidade, confiabilidade, desempenho e manutenção sejam considerados desde as primeiras fases de desenvolvimento.

## Especificação Suplementar - FURPS+

### 1. Introdução

Este documento apresenta a Especificação Suplementar do aplicativo Cadastro Único, detalhando os requisitos que não foram completamente descritos nos casos de uso. O objetivo é registrar requisitos legais, de qualidade (como usabilidade, desempenho, confiabilidade e suportabilidade), além de outros aspectos técnicos e operacionais do sistema.

Abrange também restrições de projeto, interfaces e componentes adquiridos, com o intuito de fornecer um suporte completo à equipe de desenvolvimento.

#### Finalidade

Este documento tem por finalidade especificar os requisitos suplementares não implementados no sistema, para que possam ser planejados, desenvolvidos e integrados às versões futuras do aplicativo Cadastro Único.

#### Escopo

O aplicativo Cadastro Único (abreviado oficialmente como CadÚnico), tem como escopo facilitar atividades relacionadas ao cadastro e identificação de populações necessitadas para melhorar a eficácia e execução de programas sociais. 

Abrange os requisitos funcionais e não funcionais elicitados por técnicas formais, porém ainda não implementados na versão atual do sistema. Estes requisitos são cruciais para a ampliação das funcionalidades voltadas ao público MEI, acessibilidade e suporte técnico.

#### Definições, Acrônimos e Abreviações

Aqui tem-se a tabela 1 com definições, acrônimos e abreviações utilizadas neste documento. É importante ressaltar que os termos utilizados são comuns na área de Engenharia de Software e podem variar conforme o contexto.

<center>
    <b>Tabela 1:</b> Definições, Acrônimos e Abreviações
</center>

| Termo    | Definição                      |
|-------   |-----------                     |
| **RF**   | Requisito Funcional            |
| **RNF**  | Requisito Não Funcional        |
| **MEI**  | Microempreendedor Individual   |
| **LGPD** | Lei Geral de Proteção de Dados |
| **USA**  | Requisito de Usabilidade       |
| **CNF**  | Requisito de Confiabilidade    |
| **DES**  | Requisito de Desempenho        |
| **SUP**  | Requisito de Suportabilidade   |

<center>Fonte: Adaptado de Template da Especificação Suplementar por <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a></center>

#### Visão Geral

Esta especificação apresenta:

- Os requisitos funcionais (Seção 3);  
- Os requisitos de usabilidade relacionados (Seção 4);  
- Os requisitos de confiabilidade, desempenho e suportabilidade (Seções 5 a 7);  
- As restrições de projeto (Seção 8);  
- Os requisitos técnicos e de ambiente (Seção 9);  
- As interfaces previstas, requisitos de licenciamento, anexos e aprovações.

### 2. Identificação do Projeto

Nesta seção, são apresentadas informações gerais sobre o projeto, como nome, versão, data de criação e responsáveis. Abaixo, tem-se a Tabela 2 com as informações do projeto.

<center><b>Tabela 2:</b> Identificação do Projeto</center>



| Campo               | Informação                        |
|---------------------|---------------------------------- |
| Projeto             | Cadúnico – Cadastro Único         |
| Requisitante        | Prof. Andre Barros de Sales       |
| Gerente de Projetos | [Ryan Salles](https://github.com/RA-Salles) |


<center>Fonte: Adaptado de Template da Especificação Suplementar por <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a></center>

### 3. Funcionalidade

Os requisitos funcionais foram elicitados na seção de elicitação e a Tabela 1 da página de [requisitos elicitados](../../elicitacao/requisitos_elicitados) demonstra todos os requisitos priorizados.

### 4. Usabilidade

Nesta seção, são apresentados os requisitos de usabilidade do sistema, que visam garantir uma experiência positiva para o usuário. A usabilidade é um aspecto crítico para a aceitação e eficácia do aplicativo, especialmente considerando o público-alvo. Abaixo está a Tabela 3 com os requisitos de usabilidade.

<center><b>Tabela 3:</b> Requisitos de Usabilidade</center>

| ID         | Descrição Mensurável                                                                                                                                                                                                                                                                                                       | Rastreabilidade                                          | Justificativa                                                                                                 |
|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| **USA01**  | O sistema deve apresentar uma interface intuitiva, com elementos visuais claros, organização lógica das informações e navegação simplificada, de modo que pelo menos 90% dos usuários consigam realizar as principais tarefas (cadastro, consulta e atualização de dados) sem auxílio externo em até 3 minutos.            | [RNF14](../elicitacao/requisitos_elicitados.md#rnf14)    | Facilita o uso por pessoas com baixa familiaridade tecnológica, reduzindo erros e aumentando a satisfação.    |
| **USA02**  | 100% das telas compatíveis com leitores de tela imbutidos nos sistemas operacionais de suporte.                                                                                                                                                                                                                            | [RNF16](../elicitacao/requisitos_elicitados.md#rnf16)    | Garante inclusão digital e atendimento à legislação de acessibilidade (ex: Lei Brasileira de Inclusão).       |
| **USA03**  | Navegação completa por teclado, permitindo que usuários sejam capazes de utilizar a interface sem o uso de um mouse ou, mediante a presença de um leitor de tela funcional, sem a necessidade de enxergar a interface                                                                                                      | [RNF16](../elicitacao/requisitos_elicitados.md#rnf16)    | Garante inclusão digital e atendimento à legislação de acessibilidade (ex: Lei Brasileira de Inclusão).       |
| **USA04**  | contraste mínimo de 4.5:1 entre elementos                                                                                                                                                                                                                                                                                  | [RNF16](../elicitacao/requisitos_elicitados.md#rnf16)    | Garante inclusão digital e atendimento à legislação de acessibilidade (ex: Lei Brasileira de Inclusão).       |
| **USA05**  | Textos alternativos em todas as imagens                                                                                                                                                                                                                                                                                    | [RNF16](../elicitacao/requisitos_elicitados.md#rnf16)    | Garante inclusão digital e atendimento à legislação de acessibilidade (ex: Lei Brasileira de Inclusão).       |
| **USA06**  | Ajuste de tamanho de fonte em pelo menos 3 níveis distintos.                                                                                                                                                                                                                                                               | [RNF16](../elicitacao/requisitos_elicitados.md#rnf16)    | Garante inclusão digital e atendimento à legislação de acessibilidade (ex: Lei Brasileira de Inclusão).       |
| **USA07**  | O sistema deve oferecer suporte a, no mínimo, 2 idiomas (português e inglês), permitindo que o usuário selecione o idioma de preferência em até 2 cliques/taps, com 100% dos textos traduzidos e revisados.                                                                                                                | [RNF18](../elicitacao/requisitos_elicitados.md#rnf18)    | Atende públicos diversos e amplia o alcance do sistema, facilitando o uso por estrangeiros e imigrantes.      |

<center>Fonte: <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a></center>

### 5. Confiabilidade

Nesta seção, são apresentados os requisitos de confiabilidade do sistema, que visam garantir a segurança, privacidade e integridade dos dados. A confiabilidade é essencial para a confiança do usuário no aplicativo e para o cumprimento das normas legais. Abaixo está a Tabela 4 com os requisitos de confiabilidade.

<center><b>Tabela 4:</b> Requisitos de Confiabilidade</center>

| ID        | Descrição Mensurável                                                                                                                                                                                               | Rastreabilidade                                       | Justificativa                                                                                       |
|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| **CNF01** | O sistema deve realizar backup automático das sessões do usuário a cada 5 minutos e permitir restauração completa em até 2 minutos após falha, sem perda de dados inseridos até o último backup.                   | [RNF19](../elicitacao/requisitos_elicitados.md#rnf19) | Minimiza perdas de dados e garante continuidade do serviço em caso de falhas ou quedas de energia.  |
| **CNF02** | O sistema deve garantir disponibilidade mínima de 99,5% ao mês e implementar mecanismos de recuperação automática em até 10 minutos após falhas críticas, com notificação ao usuário em caso de indisponibilidade. | [RNF20](../elicitacao/requisitos_elicitados.md#rnf20) | Garante confiança do usuário e cumprimento de padrões de qualidade exigidos para serviços públicos. |

<center>Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a></center>

### 6. Desempenho

Requisitos que dizem respeito às condições que os requisitos devem operar. A velocidade, limites superiores e inferiores, tempo de resposta, restrições de interface e de funções, etc.

<center><b>Tabela 5:</b> Requisitos de Desempenho</center>

| ID         | Descrição Mensurável                                                                                                                                                                                       | Rastreabilidade                                       | Justificativa                                                                                  |
|--------    |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------                                      |----------------------------------------------------------------------------------------------- |
| **DES01**  | O sistema deve apresentar tempo de resposta inferior a 3 segundos para carregamento de qualquer tela principal (cadastro, consulta, atualização) em 95% das tentativas, sob conexão 3G ou superior.        | [RNF01](../elicitacao/requisitos_elicitados.md#rnf01) | Garante fluidez no uso, reduzindo frustração e abandono do aplicativo.                         |
| **DES02**  | O sistema deve manter funcionamento básico (cadastro e consulta) com latência de até 500ms e perda de até 10% de pacotes, permitindo sincronização posterior dos dados quando a conexão for restabelecida. | [RNF17](../elicitacao/requisitos_elicitados.md#rnf17) | Atende usuários em regiões com internet instável, ampliando o acesso ao serviço.               |

<center>Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a></center>

### 7. Suportabilidade

Envolve os requisitos relacionados ao suporte e manutenção do sistema. Isso inclui requisitos relacionados à facilidade de manutenção, capacidade de ser modificado e atualizado, documentação adequada, facilidade de teste e diagnóstico de problemas.

<center><b>Tabela 6:</b> Requisitos de Suportabilidade</center>

| ID            | Descrição Mensurável                                                                                                                                                                                        | Rastreabilidade                                       | Justificativa                                                                                     |
|--------       |-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| **SUP01**     | O sistema deve garantir acessibilidade geral, incluindo suporte a pelo menos 3 tecnologias assistivas (leitores de tela, comandos por voz, alto contraste) em 100% das funcionalidades.                     | [RNF05](../elicitacao/requisitos_elicitados.md#rnf05) | Facilita manutenção e atualização para públicos diversos, promovendo inclusão digital.            |
| **SUP02**     | O sistema deve ser compatível com funcionamento off-line, permitindo que pelo menos 80% das funcionalidades críticas sejam acessíveis sem conexão, com sincronização automática ao restabelecer a internet. | [RNF07](../elicitacao/requisitos_elicitados.md#rnf07) | Garante continuidade do serviço em áreas remotas ou com conectividade limitada.                   |
| **SUP03**     | O sistema deve permitir transmissão de dados via Conectividade Social, com taxa de sucesso mínima de 98% nas integrações realizadas mensalmente.                                                            | [RNF08](../elicitacao/requisitos_elicitados.md#rnf08) | Assegura integração eficiente com sistemas governamentais, evitando retrabalho e inconsistências. |
| **SUP04**     | O sistema deve integrar-se ao MEI, realizando validação automática de dados em até 2 minutos e atualização em tempo real, com registro de logs de todas as operações de integração.                         | [RNF10](../elicitacao/requisitos_elicitados.md#rnf10) | Facilita manutenção, auditoria e atualização dos dados, garantindo conformidade legal.            |

<center>Autor(es): <a href="https://github.com/johnaopedro" target="_blank">João Pedro</a></center>

### 8. Restrições de Projeto

<center><b>Tabela 7:</b> Requisitos de Restrições de Projeto</center>

| ID      | Nome                                              | Descrição                                                                                                                | Justificativa                                                                                 |
| ------- | ------------------------------------              | ------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------- |
| REQ001  | Infraestrutura Tecnológica Limitada               | O aplicativo deverá ser compatível com dispositivos móveis Android a partir da versão 6.0 (Marshmallow) e com navegadores modernos para acesso via web, considerando o uso por públicos de baixa renda com dispositivos mais antigos. | Grande parte dos usuários do CadÚnico possui celulares com recursos limitados de processamento e memória. |
| REQ002  | Adesão à LGPD                                     | Todos os dados coletados, processados e armazenados pelo aplicativo devem estar em conformidade com a Lei Geral de Proteção de Dados (Lei nº 13.709/2018), garantindo consentimento explícito e controle sobre os dados pessoais do usuário. | O sistema lida com dados sensíveis e precisa atender exigências legais de privacidade.       |
| REQ003  | Integração com Sistemas Governamentais Existentes | A aplicação deverá manter compatibilidade com a base de dados do Governo Federal e com sistemas como o SIBEC, Receita Federal e Conectividade Social da CAIXA, para validação e atualização de informações. | Para evitar redundância de informações e garantir veracidade dos dados.                      |
| REQ004  | Acesso com Baixa Conectividade                    | O projeto deve considerar o uso do aplicativo em regiões com baixa qualidade de internet. Funcionalidades críticas devem ser parcialmente disponíveis no modo offline, com sincronização posterior. | O público-alvo do CadÚnico reside frequentemente em áreas com infraestrutura limitada.      |
| REQ005  | Compatibilidade com Tecnologias Assistivas        | A interface do aplicativo deve ser compatível com leitores de tela, alto contraste, comandos por voz e navegação via teclado, atendendo aos requisitos de acessibilidade. | Inclusão digital de pessoas com deficiência visual ou motora é uma diretriz do governo federal. |
| REQ006  | Atualizações via Lojas Oficiais                   | As atualizações do aplicativo devem ser distribuídas exclusivamente pelas lojas Google Play e App Store, não sendo permitido o uso de APKs externos por questões de segurança. | Minimizar o risco de ataques, fraudes ou instalação de versões corrompidas do aplicativo.   | 

<center>Autor(es): <a href="https://github.com/JuliaGabP" target="_blank">Julia Paulino</a></center>

### 9. Outros Requisitos do Produto

#### 9.1. Padrões Aplicáveis
O aplicativo deverá seguir os seguintes padrões técnicos e de qualidade:

- **ABNT NBR ISO/IEC 25010:2011** – Qualidade de produto de software;
- **WCAG 2.1 (Web Content Accessibility Guidelines)** – Diretrizes de acessibilidade para interfaces;
- **Material Design** – Padrão visual e de interação do Google, para interfaces móveis;
- **OWASP Mobile Security Project** – Diretrizes para segurança de aplicativos móveis;
- **IEEE Std 830-1998** – Requisitos de software e especificação.

#### 9.2. Requisitos do Sistema
- O aplicativo deverá ser compatível com:
  - Android 6.0 (Marshmallow) ou superior;
  - iOS 12.0 ou superior;
  - Navegadores modernos (Chrome, Firefox, Safari, Edge).

- Requisitos mínimos de hardware:
  - 1GB de RAM;
  - 200MB de espaço disponível;
  - Conexão mínima de 3G ou Wi-Fi.

#### 9.3. Requisitos Ambientais
- O sistema deve funcionar em ambientes com variações de conectividade, com tolerância a interrupções momentâneas de rede.
- O aplicativo deve ser otimizado para operar em ambientes com pouca luminosidade (modo escuro) e temperaturas elevadas, comuns em regiões afastadas ou em áreas rurais.
- O sistema web deve ter comportamento responsivo e ser compatível com monitores de baixa resolução (a partir de 1024x768).


### 10. Componentes Comprados

O aplicativo poderá utilizar APIs públicas e serviços de terceiros para ampliar sua funcionalidade. Os seguintes componentes adquiridos ou externos são considerados:

- API da Receita Federal (consulta de CNPJ MEI).
- Serviço de Conectividade Social da CAIXA.
- Frameworks de acessibilidade (como ARIA para web).
- SDKs de mapas georreferenciados para exibição de postos de atendimento.

Todos os componentes deverão possuir documentação oficial, atualizações regulares e estar em conformidade com a LGPD.

### 11. Interfaces  
#### 11.1. Interfaces de Usuário 

A interface do aplicativo será responsiva e acessível, com foco em:

- Navegação intuitiva;
- Compatibilidade com leitores de tela;
- Utilização de padrões de design do Governo Federal (Gov.br);
- Layout adaptável para smartphones e tablets.
  
#### 11.2. Interfaces de Hardware  

O sistema deve ser compatível com dispositivos móveis Android e iOS, utilizando recursos de:

- Geolocalização;
- Câmera para envio de documentos;
- Armazenamento local para modo offline.

#### 11.3. Interfaces de Software  

- Integração com a base do CadÚnico;
- Conectividade com Receita Federal (CNPJ MEI);
- Integração com APIs RESTful;
- Comunicação com servidores Gov.br para autenticação.

#### 11.4. Interfaces de Comunicações

- HTTPS (protocolo seguro) para todas as transações de dados;
- WebSockets para sincronização em tempo real quando disponível;
- Transmissão de dados via Conectividade Social para casos específicos.

### 12. Requisitos de Licenciamento

O sistema deve estar em conformidade com:

- Licença de Software Livre para componentes de código aberto utilizados (ex: MIT, Apache 2.0);
- Termos de uso e distribuição de dados da Receita Federal e CAIXA;
- Políticas de privacidade exigidas pela LGPD.

A redistribuição e modificação do sistema estarão condicionadas aos termos definidos pelo Governo Federal e acordos com os fornecedores de API e dados.

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13a [slide em PDF]. Aprender³, Universidade de Brasília, 2025. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>. Acesso em: 16 maio 2025.

> REPOSITÓRIO DA DISCIPLINA – Aprender 3. Template da Especificação Suplementar. Disponível em: <https://aprender3.unb.br/mod/resource/view.php?id=1390972>. Acesso em: 16 maio 2025.

> WIEGERS, Karl E.; BEATTY, Joy. *Software Requirements*. Microsoft Press, 3ª ed., 2013.

> LGPD – Lei nº 13.709/2018 

As imagens 1 e 2 a seguir foram extraídas do material de apoio da disciplina de Engenharia de Software, fornecido pelos professores Milene Serrano e Maurício Serrano, e ilustram a estrutura e os componentes da Especificação Suplementar.
### Imagem 1: 
<div style="text-align: center;">
    <img src="../../assets/referencias/especificacao_suplementar/especificacao_suplementar.png" alt="especificacao_suplementar">
</div>
Fonte: <a href="SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13a [slide em PDF]. Aprender³, Universidade de Brasília, 2025. Disponível em: https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf" target="_blank">SERRANO, Milene; SERRANO, Maurício</a>

### Imagem 2: 
<div style="text-align: center;">
    <img src="../../assets/referencias/especificacao_suplementar/especificacao_suplementar1.png" alt="especificacao_suplementar1">
</div>
Fonte: <a href="SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13a [slide em PDF]. Aprender³, Universidade de Brasília, 2025. Disponível em: https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf" target="_blank">SERRANO, Milene; SERRANO, Maurício</a>

## Histórico de Versão

| Versão |    Data    |        Descrição                                                                                                                |                   Autor(es)                                                                        |                   Revisor(es)                      |
| :----: | :--------: | :----------------------:                                                                                                        | :----------------------------------------:                                                         | :-----------------------------------------:        |
| 1.0    | 16/05/2025 | Criação do Documento                                                                                                            | [João Pedro Costa](https://github.com/johnaopedro) e [Julia Paulino](https://github.com/JuliaGabP) | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.1    | 16/05/2025 | Criação da introdução e metodologia                                                                                             | [João Pedro Costa](https://github.com/johnaopedro)                                                 | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.2    | 16/05/2025 | Criação da estrutura de especificação suplementar                                                                               | [João Pedro Costa](https://github.com/johnaopedro) e [Julia Paulino](https://github.com/JuliaGabP) | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.3    | 16/05/2025 | Preenchimento das três primeiras seções da especificação                                                                        | [João Pedro Costa](https://github.com/johnaopedro)                                                 | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.4    | 16/05/2025 | Preenchimento das seções 8 à 13                                                                                                 | [Julia Paulino](https://github.com/JuliaGabP)                                                      | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.5    | 17/05/2025 | Preenchimento das seções de: Identificação do Projeto, Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade | [João Pedro Costa](https://github.com/johnaopedro)                                                 | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.6    | 17/05/2025 | Removendo itens errados                                                                                                         | [João Pedro Costa](https://github.com/johnaopedro)                                                 | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.7    | 17/05/2025 | Revisão e formatação final do documento                                                                                         | [João Pedro Costa](https://github.com/johnaopedro)                                                 | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.8    | 18/05/2025 | Correção de erros ortográficos e tabela                                                                                         | [Amanda Cruz](https://github.com/johnaopedro)                                                      | [Ryan Salles](https://github.com/RA-Salles)        |
| 1.9    | 20/05/2025 | Criação da tabela de funções                                                                                                    | [Julia Paulino](https://github.com/JuliaGabP)                                                      | [João Pedro Costa](https://github.com/johnaopedro) |
| 2.0    | 21/05/2025 | Refinamento das descrições de requisitos                                                                                        | [João Pedro Costa](https://github.com/johnaopedro)                                                 | [Julia Paulino](https://github.com/JuliaGabP)      |
| 2.1    | 07/06/2025 | Adição de um ID Único aos requisitos de Usabilidade, Confiabilidade, Desempenho e Suportabilidade.                              | [Ryan Salles](https://github.com/RA-Salles)                                                        | [João Pedro Costa](https://github.com/johnaopedro) |
| 2.2    | 22/06/2025 | Correção pelo metodo de inspeção de Fagan                                                                                       | [João Pedro](https://github.com/johnaopedro)                                                       | [Ryan Salles](https://github.com/RA-Salles)        |
| 2.3    | 22/06/2025 | Expansão da Granularidade dos requisitos de usabilidade                                                                         | [Ryan Salles](https://github.com/RA-Salles)                                                        | [João Pedro](https://github.com/johnaopedro)       |
