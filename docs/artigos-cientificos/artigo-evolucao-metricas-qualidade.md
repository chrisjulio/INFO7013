---



title: 'Evolução das Métricas de Qualidade de Software: Uma Revisão Sistemática da ISO/IEC 9126 para a ISO/IEC 25010'
author: 'Seu Nome, Nome do Orientador'
date: 'Setembro 2025'
abstract: |
  A qualidade de software é um pilar fundamental da Engenharia de Software, e sua medição tem evoluído para acompanhar as crescentes demandas da indústria. Este artigo apresenta uma revisão sistemática da literatura sobre a evolução das métricas de qualidade de software, com foco na transição da norma ISO/IEC 9126 para a ISO/IEC 25010. Analisamos as mudanças estruturais, a expansão das características de qualidade e o refinamento das métricas, destacando as implicações práticas para desenvolvedores, gerentes e pesquisadores. Nossos resultados revelam uma maior ênfase em segurança, compatibilidade e usabilidade na nova norma, refletindo as tendências tecnológicas e as expectativas dos usuários. Concluímos com uma discussão sobre as direções futuras da medição de qualidade de software e as oportunidades de pesquisa na área.
keywords: 'qualidade de software, ISO/IEC 9126, ISO/IEC 25010, métricas de software, engenharia de software, revisão sistemática'
---





## 1. Introduction

A qualidade de software deixou de ser um diferencial competitivo para se tornar um requisito essencial para o sucesso de qualquer produto ou serviço digital. Em um mercado cada vez mais concorrido e com usuários mais exigentes, a capacidade de entregar software confiável, eficiente, seguro e fácil de usar é fundamental. Nesse contexto, a medição da qualidade de software através de métricas padronizadas desempenha um papel crucial, permitindo que as organizações avaliem, controlem e melhorem seus produtos de forma sistemática.

As normas da série ISO/IEC têm sido a principal referência para a medição da qualidade de software por décadas. A norma ISO/IEC 9126, publicada em 1991, estabeleceu um modelo de qualidade amplamente adotado, definindo seis características principais: funcionalidade, confiabilidade, usabilidade, eficiência, manutenibilidade e portabilidade. No entanto, com a rápida evolução da tecnologia e das práticas de desenvolvimento, tornou-se necessário atualizar este modelo para refletir as novas realidades do mercado.

Em 2011, a ISO/IEC 25010 foi publicada como parte da série de normas SQUARE (Software Product Quality Requirements and Evaluation), substituindo a ISO/IEC 9126. A nova norma introduziu mudanças significativas, expandindo o modelo de qualidade para oito características, com a adição de segurança e compatibilidade, e refinando as subcaracterísticas e métricas existentes. Essa evolução reflete a crescente importância da segurança da informação, da interoperabilidade entre sistemas e da experiência do usuário.

Este artigo tem como objetivo realizar uma revisão sistemática da literatura sobre a evolução das métricas de qualidade de software, com foco na transição da norma ISO/IEC 9126 para a ISO/IEC 25010. Buscamos responder às seguintes questões de pesquisa:

- **QP1**: Quais são as principais diferenças estruturais e conceituais entre as normas ISO/IEC 9126 e ISO/IEC 25010?
- **QP2**: Como a evolução das características de qualidade reflete as mudanças nas prioridades da indústria de software?
- **QP3**: Quais são as implicações práticas da adoção da ISO/IEC 25010 para desenvolvedores, gerentes e pesquisadores?

As contribuições esperadas deste trabalho são:

- Uma análise comparativa detalhada das duas normas, destacando as principais mudanças e melhorias.
- Uma síntese das tendências evolutivas na medição da qualidade de software.
- Um guia prático para a compreensão e aplicação da norma ISO/IEC 25010.
- A identificação de lacunas e oportunidades para pesquisas futuras na área.





## 2. Background

A busca pela qualidade em software é tão antiga quanto a própria disciplina da Engenharia de Software. Desde os primórdios da computação, a necessidade de garantir que os programas funcionassem corretamente e atendessem às expectativas dos usuários tem sido uma preocupação constante. No entanto, a formalização da medição da qualidade de software como uma área de estudo e prática só começou a ganhar força a partir da década de 1970.

### 2.1. Modelos de Qualidade de Software

Os primeiros modelos de qualidade de software, como o de McCall (1977) e o de Boehm (1978), foram pioneiros em propor uma estrutura hierárquica para a avaliação da qualidade, decompondo-a em fatores, critérios e métricas. Esses modelos estabeleceram as bases para a criação de um vocabulário comum e de uma abordagem mais sistemática para a medição da qualidade.

### 2.2. A Norma ISO/IEC 9126

Publicada em 1991, a norma ISO/IEC 9126 representou um marco na padronização da medição da qualidade de software. Ela definiu um modelo de qualidade de produto composto por seis características principais, que se tornaram amplamente conhecidas e utilizadas na indústria:

- **Funcionalidade**: A capacidade do software de prover as funcionalidades que satisfazem as necessidades explícitas e implícitas do usuário.
- **Confiabilidade**: A capacidade do software de manter um nível de desempenho especificado sob condições estabelecidas.
- **Usabilidade**: A capacidade do software de ser compreendido, aprendido, operado e atraente para o usuário.
- **Eficiência**: A capacidade do software de apresentar um desempenho adequado, relativo à quantidade de recursos utilizados.
- **Manutenibilidade**: A capacidade do software de ser modificado, incluindo correções, melhorias ou adaptações.
- **Portabilidade**: A capacidade do software de ser transferido de um ambiente para outro.

### 2.3. A Série de Normas SQUARE e a ISO/IEC 25010

Com o passar do tempo, a ISO/IEC 9126 começou a apresentar limitações para lidar com as novas complexidades do software moderno. A série de normas SQUARE (Software Product Quality Requirements and Evaluation) foi desenvolvida para abordar essas limitações, e a ISO/IEC 25010, publicada em 2011, tornou-se a peça central dessa nova série, substituindo a ISO/IEC 9126.

A ISO/IEC 25010 expandiu o modelo de qualidade para oito características, adicionando **Segurança** e **Compatibilidade** e refinando as demais. Essa mudança refletiu a crescente preocupação com a proteção de dados, a interoperabilidade entre sistemas e a experiência do usuário em um mundo cada vez mais conectado.





## 3. Methodology

Para responder às nossas questões de pesquisa, realizamos uma revisão sistemática da literatura, seguindo as diretrizes propostas por Kitchenham (2004). O processo foi dividido em três fases principais: planejamento, execução e análise.

### 3.1. Planejamento da Revisão

Nesta fase, definimos o protocolo da revisão, incluindo as questões de pesquisa, a estratégia de busca, os critérios de inclusão e exclusão, e o processo de extração de dados.

#### 3.1.1. Questões de Pesquisa

As questões de pesquisa que nortearam este trabalho foram:

- **QP1**: Quais são as principais diferenças estruturais e conceituais entre as normas ISO/IEC 9126 e ISO/IEC 25010?
- **QP2**: Como a evolução das características de qualidade reflete as mudanças nas prioridades da indústria de software?
- **QP3**: Quais são as implicações práticas da adoção da ISO/IEC 25010 para desenvolvedores, gerentes e pesquisadores?

#### 3.1.2. Estratégia de Busca

A busca foi realizada nas seguintes bases de dados eletrônicas:

- IEEE Xplore
- ACM Digital Library
- SpringerLink
- ScienceDirect

A string de busca utilizada foi:

```
("software quality" OR "quality model") AND ("ISO 9126" OR "ISO/IEC 9126") AND ("ISO 25010" OR "ISO/IEC 25010")
```

#### 3.1.3. Critérios de Inclusão e Exclusão

Os critérios de inclusão foram:

- Artigos que comparam diretamente as normas ISO/IEC 9126 e ISO/IEC 25010.
- Artigos que analisam a evolução das métricas de qualidade de software.
- Artigos publicados em periódicos ou conferências revisados por pares.
- Artigos publicados entre 2010 e 2025.

Os critérios de exclusão foram:

- Artigos que não abordam diretamente as normas em questão.
- Artigos que não estão disponíveis em texto completo.
- Artigos em idiomas diferentes do inglês ou português.

### 3.2. Execução da Revisão

A execução da revisão envolveu a aplicação da estratégia de busca, a seleção dos estudos primários e a extração dos dados.

#### 3.2.1. Seleção dos Estudos

A seleção dos estudos foi realizada em duas etapas. Primeiro, os títulos e resumos dos artigos encontrados foram lidos para verificar sua relevância. Em seguida, os artigos selecionados foram lidos na íntegra para confirmar sua adequação aos critérios de inclusão.

#### 3.2.2. Extração de Dados

Para cada estudo selecionado, extraímos as seguintes informações:

- Título, autores, ano e fonte de publicação.
- Objetivos do estudo.
- Metodologia utilizada.
- Principais resultados e conclusões.
- Comparações entre as normas ISO/IEC 9126 e ISO/IEC 25010.

### 3.3. Análise e Síntese dos Dados

Os dados extraídos foram analisados e sintetizados de forma qualitativa. Utilizamos a análise de conteúdo para identificar temas e padrões recorrentes nos estudos selecionados. A síntese dos resultados foi organizada de acordo com as questões de pesquisa.




## 4. Results

A análise dos estudos selecionados permitiu identificar as principais diferenças entre as normas ISO/IEC 9126 e ISO/IEC 25010, bem como a evolução das características de qualidade de software.

### 4.1. Análise Comparativa das Normas

A principal mudança da ISO/IEC 9126 para a ISO/IEC 25010 foi a expansão do modelo de qualidade de seis para oito características. A tabela a seguir resume as principais diferenças:

| Característica | ISO/IEC 9126 | ISO/IEC 25010 | Mudanças e Melhorias |
| :--- | :--- | :--- | :--- |
| **Funcionalidade** | Adequação, Acurácia, Interoperabilidade, Segurança de Acesso | Adequação Funcional (Completude, Correção, Pertinência) | Refinamento e maior detalhamento das subcaracterísticas. |
| **Confiabilidade** | Maturidade, Tolerância a Falhas, Recuperabilidade | Confiabilidade (Maturidade, Disponibilidade, Tolerância a Falhas, Recuperabilidade) | Adição da subcaracterística de Disponibilidade. |
| **Usabilidade** | Inteligibilidade, Apreensibilidade, Operacionalidade, Atratividade | Usabilidade (Reconhecimento de Adequação, Apreensibilidade, Operacionalidade, Proteção contra Erros, Estética da Interface, Acessibilidade) | Expansão significativa, com foco na experiência do usuário e acessibilidade. |
| **Eficiência** | Comportamento de Tempo, Utilização de Recursos | Eficiência de Desempenho (Comportamento de Tempo, Utilização de Recursos, Capacidade) | Adição da subcaracterística de Capacidade. |
| **Manutenibilidade** | Analisabilidade, Modificabilidade, Estabilidade, Testabilidade | Manutenibilidade (Modularidade, Reusabilidade, Analisabilidade, Modificabilidade, Testabilidade) | Adição de Modularidade e Reusabilidade, e remoção de Estabilidade. |
| **Portabilidade** | Adaptabilidade, Instalabilidade, Coexistência, Capacidade para Substituir | Portabilidade (Adaptabilidade, Instalabilidade, Capacidade para Substituir) | Remoção da subcaracterística de Coexistência, que foi movida para Compatibilidade. |
| **Segurança** | (Subcaracterística da Funcionalidade) | Segurança (Confidencialidade, Integridade, Não Repúdio, Responsabilidade, Autenticidade) | Elevada a uma característica principal, com subcaracterísticas bem definidas. |
| **Compatibilidade**| (Não existente) | Compatibilidade (Coexistência, Interoperabilidade) | Nova característica, agrupando subcaracterísticas de outras áreas. |

### 4.2. Evolução das Características de Qualidade

A evolução das características de qualidade reflete as mudanças nas prioridades da indústria de software. A maior ênfase em **Segurança** é uma resposta direta ao aumento das ameaças cibernéticas e à necessidade de proteger dados sensíveis. A criação da característica **Compatibilidade** reflete a importância da interoperabilidade em um ecossistema de software cada vez mais integrado. A expansão da **Usabilidade** demonstra a crescente valorização da experiência do usuário como um fator crítico de sucesso.




## 5. Discussion

A evolução da ISO/IEC 9126 para a ISO/IEC 25010 representa um passo significativo na maturidade da medição da qualidade de software. As mudanças introduzidas não são meramente cosméticas, mas refletem uma compreensão mais profunda e abrangente do que constitui um software de qualidade no século XXI.

### 5.1. Implicações Práticas

Para os **desenvolvedores**, a nova norma oferece um guia mais claro e detalhado para a construção de software de alta qualidade. A ênfase em segurança e compatibilidade desde as fases iniciais do desenvolvimento pode ajudar a evitar problemas custosos no futuro. Para os **gerentes de projeto**, a ISO/IEC 25010 fornece um framework mais robusto para a definição de requisitos de qualidade e para o monitoramento do processo de desenvolvimento. Para os **pesquisadores**, a nova norma abre novas oportunidades de pesquisa, como o desenvolvimento de métricas mais precisas para as novas subcaracterísticas e a investigação do impacto da adoção da norma na prática.

### 5.2. Limitações e Desafios

Apesar dos avanços, a implementação da ISO/IEC 25010 ainda apresenta desafios. A complexidade do modelo de qualidade pode ser um obstáculo para equipes menores ou com menos maturidade em processos. Além disso, a medição de algumas subcaracterísticas, como a estética da interface ou a autenticidade, ainda é um campo em aberto, com poucas métricas objetivas e padronizadas.




## 6. Conclusion

Esta revisão sistemática da literatura confirmou que a transição da norma ISO/IEC 9126 para a ISO/IEC 25010 representa uma evolução significativa na forma como a qualidade de software é concebida e medida. A nova norma é mais abrangente, detalhada e alinhada com as demandas do software contemporâneo, oferecendo um framework mais robusto para a garantia da qualidade.

As principais contribuições deste trabalho foram a análise comparativa detalhada entre as duas normas, a síntese das tendências evolutivas na medição da qualidade e a discussão das implicações práticas para a indústria e a academia. Identificamos também lacunas e oportunidades para pesquisas futuras, como o desenvolvimento de métricas para as novas subcaracterísticas e a investigação do impacto da adoção da norma em diferentes contextos organizacionais.

Como trabalhos futuros, pretendemos realizar estudos de caso para avaliar a aplicação da ISO/IEC 25010 em projetos reais e desenvolver um modelo de maturidade para auxiliar as organizações na adoção da norma.


