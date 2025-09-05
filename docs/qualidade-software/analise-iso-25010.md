# Análise Detalhada da Norma ISO/IEC 25010

## 1. Introdução à ISO/IEC 25010

A norma **ISO/IEC 25010:2011**, parte da série **ISO/IEC 25000 (SQuaRE - Systems and software Quality Requirements and Evaluation)**, substituiu a antiga ISO/IEC 9126 e representa o modelo de qualidade de produto de software mais atual e abrangente. Ela foi projetada para fornecer uma base para a especificação de requisitos de qualidade, medição e avaliação de produtos de software e sistemas de computação.

A ISO/IEC 25010 define dois modelos de qualidade principais:

1.  **Modelo de Qualidade de Produto (Product Quality Model)**: Composto por oito características que descrevem a qualidade do software a partir de uma perspectiva interna e externa.
2.  **Modelo de Qualidade em Uso (Quality in Use Model)**: Composto por cinco características que descrevem a qualidade do software da perspectiva do usuário final em um contexto de uso específico.

Este documento foca na análise detalhada do **Modelo de Qualidade de Produto**.

## 2. O Modelo de Qualidade de Produto

O modelo de qualidade de produto da ISO/IEC 25010 é composto por oito características de alto nível, que são refinamentos e expansões do modelo da ISO/IEC 9126. Cada característica é subdividida em subcaracterísticas, fornecendo uma visão mais granular e mensurável da qualidade.

### 2.1. Adequação Funcional (Functional Suitability)

Esta característica representa o grau em que um produto ou sistema fornece funções que atendem às necessidades declaradas e implícitas quando usado sob condições especificadas. É uma evolução da "Funcionalidade" da ISO/IEC 9126.

**Subcaracterísticas:**

-   **Completude Funcional (Functional Completeness)**: Grau em que o conjunto de funcionalidades cobre todas as tarefas e objetivos do usuário especificados.
-   **Correção Funcional (Functional Correctness)**: Grau em que o produto ou sistema fornece os resultados corretos com o nível de precisão necessário.
-   **Adequação Funcional (Functional Appropriateness)**: Grau em que as funções facilitam a realização de tarefas e objetivos específicos.

### 2.2. Eficiência de Desempenho (Performance Efficiency)

Esta característica representa o desempenho relativo à quantidade de recursos utilizados sob condições declaradas. Corresponde à "Eficiência" da ISO/IEC 9126.

**Subcaracterísticas:**

-   **Comportamento de Tempo (Time-behaviour)**: Grau em que os tempos de resposta e processamento e as taxas de transferência de um produto ou sistema, ao realizar suas funções, atendem aos requisitos.
-   **Utilização de Recursos (Resource utilization)**: Grau em que as quantidades e tipos de recursos utilizados por um produto ou sistema, ao realizar suas funções, atendem aos requisitos.
-   **Capacidade (Capacity)**: Grau em que os limites máximos de um parâmetro de um produto ou sistema atendem aos requisitos.

### 2.3. Compatibilidade (Compatibility)

Esta é uma nova característica de primeiro nível em relação à ISO/IEC 9126. Representa o grau em que um produto, sistema ou componente pode trocar informações com outros produtos, sistemas ou componentes e/ou executar suas funções necessárias enquanto compartilha o mesmo ambiente de hardware ou software.

**Subcaracterísticas:**

-   **Coexistência (Co-existence)**: Grau em que um produto pode executar suas funções de forma eficiente enquanto compartilha um ambiente e recursos comuns com outros produtos, sem impacto prejudicial em qualquer outro produto.
-   **Interoperabilidade (Interoperability)**: Grau em que dois ou mais sistemas, produtos ou componentes podem trocar informações e usar as informações que foram trocadas.

### 2.4. Usabilidade (Usability)

Representa o grau em que um produto ou sistema pode ser usado por usuários especificados para atingir objetivos especificados com eficácia, eficiência e satisfação em um contexto de uso especificado.

**Subcaracterísticas:**

-   **Reconhecimento de Adequação (Appropriateness recognisability)**: Grau em que os usuários podem reconhecer se um produto ou sistema é apropriado para suas necessidades.
-   **Apreensibilidade (Learnability)**: Grau em que um produto ou sistema pode ser usado por usuários especificados para atingir objetivos de aprendizado especificados com eficácia, eficiência e satisfação em um contexto de uso especificado.
-   **Operacionalidade (Operability)**: Grau em que um produto ou sistema tem atributos que o tornam fácil de operar e controlar.
-   **Proteção contra Erros do Usuário (User error protection)**: Grau em que um sistema protege os usuários contra a ocorrência de erros.
-   **Estética da Interface do Usuário (User interface aesthetics)**: Grau em que a interface do usuário permite uma interação agradável e satisfatória.
-   **Acessibilidade (Accessibility)**: Grau em que um produto ou sistema pode ser usado por pessoas com a mais ampla gama de características e capacidades para atingir um objetivo especificado em um contexto de uso especificado.

### 2.5. Confiabilidade (Reliability)

Representa o grau em que um sistema, produto ou componente executa funções especificadas sob condições especificadas por um período de tempo especificado.

**Subcaracterísticas:**

-   **Maturidade (Maturity)**: Grau em que um sistema, produto ou componente atende às necessidades de confiabilidade sob operação normal.
-   **Disponibilidade (Availability)**: Grau em que um sistema, produto ou componente está operacional e acessível quando necessário para uso.
-   **Tolerância a Falhas (Fault tolerance)**: Grau em que um sistema, produto ou componente opera como pretendido, apesar da presença de falhas de hardware ou software.
-   **Recuperabilidade (Recoverability)**: Grau em que, em caso de interrupção ou falha, um produto ou sistema pode recuperar os dados diretamente afetados e restabelecer o estado desejado do sistema.

### 2.6. Segurança (Security)

Esta é outra nova característica de primeiro nível, elevada de uma subcaracterística da Funcionalidade na ISO/IEC 9126. Representa o grau em que um produto ou sistema protege informações e dados para que pessoas ou outros produtos ou sistemas tenham o grau de acesso a dados apropriado às suas autorizações.

**Subcaracterísticas:**

-   **Confidencialidade (Confidentiality)**: Grau em que um produto ou sistema garante que os dados sejam acessíveis apenas àqueles autorizados a ter acesso.
-   **Integridade (Integrity)**: Grau em que um sistema, produto ou componente impede o acesso não autorizado ou a modificação de programas ou dados de computador.
-   **Não Repúdio (Non-repudiation)**: Grau em que as ações ou eventos podem ser provados como tendo ocorrido, de modo que os eventos ou ações não possam ser repudiados posteriormente.
-   **Responsabilidade (Accountability)**: Grau em que as ações de uma entidade podem ser rastreadas exclusivamente até a entidade.
-   **Autenticidade (Authenticity)**: Grau em que a identidade de um sujeito ou recurso pode ser provada como sendo a que se alega.

### 2.7. Manutenibilidade (Maintainability)

Representa o grau de eficácia e eficiência com que um produto ou sistema pode ser modificado por mantenedores.

**Subcaracterísticas:**

-   **Modularidade (Modularity)**: Grau em que um sistema ou programa de computador é composto de componentes discretos, de modo que uma alteração em um componente tenha um impacto mínimo em outros componentes.
-   **Reusabilidade (Reusability)**: Grau em que um ativo pode ser usado em mais de um sistema, ou na construção de outros ativos.
-   **Analisabilidade (Analysability)**: Grau de eficácia e eficiência com que é possível avaliar o impacto de uma alteração pretendida em um produto ou sistema, diagnosticar as deficiências ou causas de falhas de um produto, ou identificar as partes a serem modificadas.
-   **Modificabilidade (Modifiability)**: Grau em que um produto ou sistema pode ser modificado de forma eficaz e eficiente sem introduzir defeitos ou degradar a qualidade do produto existente.
-   **Testabilidade (Testability)**: Grau de eficácia e eficiência com que os critérios de teste podem ser estabelecidos para um sistema, produto ou componente e os testes podem ser realizados para determinar se esses critérios foram atendidos.

### 2.8. Portabilidade (Portability)

Representa o grau de eficácia e eficiência com que um sistema, produto ou componente pode ser transferido de um ambiente de hardware, software, operacional ou de uso para outro.

**Subcaracterísticas:**

-   **Adaptabilidade (Adaptability)**: Grau em que um produto ou sistema pode ser adaptado de forma eficaz e eficiente para diferentes ou evolutivos ambientes de hardware, software, operacionais ou de uso.
-   **Instalabilidade (Installability)**: Grau de eficácia e eficiência com que um produto ou sistema pode ser instalado e/ou desinstalado com sucesso em um ambiente especificado.
-   **Capacidade para Substituir (Replaceability)**: Grau em que um produto pode substituir outro produto de software especificado para o mesmo propósito no mesmo ambiente.

## 3. Comparação com a ISO/IEC 9126

A ISO/IEC 25010 representa uma evolução significativa em relação à ISO/IEC 9126:

-   **Novas Características**: **Segurança** e **Compatibilidade** foram promovidas a características de primeiro nível, refletindo sua crescente importância no software moderno.
-   **Refinamento de Subcaracterísticas**: Muitas subcaracterísticas foram renomeadas, redefinidas ou adicionadas para fornecer maior clareza e precisão.
-   **Estrutura SQuaRE**: A norma faz parte de uma série mais ampla (SQuaRE) que fornece uma estrutura mais completa para a gestão da qualidade, incluindo requisitos, medição e avaliação.
-   **Foco em Sistemas**: O escopo foi expandido de "produto de software" para "sistemas e produtos de software", reconhecendo a complexidade dos sistemas modernos.

## 4. Conclusão

A ISO/IEC 25010 fornece um modelo de qualidade robusto, abrangente e atualizado, que serve como uma ferramenta essencial para a engenharia de software moderna. Ao definir claramente as características e subcaracterísticas da qualidade, a norma permite que as organizações especifiquem requisitos de qualidade de forma não ambígua, meçam a qualidade de forma objetiva e, em última análise, entreguem produtos e sistemas que atendam às expectativas dos usuários e das partes interessadas. A compreensão e aplicação deste modelo são fundamentais para o sucesso de qualquer projeto de software que preze pela qualidade.

---

**Arquivo anterior**: [Análise Detalhada da Norma ISO/IEC 9126](analise-iso-9126.md)
**Próximo arquivo**: [Comparativo entre as Normas ISO/IEC 9126 e 25010](comparativo-normas.md)


