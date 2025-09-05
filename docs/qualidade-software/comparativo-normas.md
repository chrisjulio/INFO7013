# Comparativo entre as Normas ISO/IEC 9126 e 25010

## 1. Introdução

A transição da **ISO/IEC 9126** para a **ISO/IEC 25010** representa uma evolução significativa na forma como a qualidade de software é modelada e avaliada. Embora ambas as normas compartilhem o objetivo de definir e estruturar a qualidade de produto de software, a ISO/IEC 25010, como parte da série **SQuaRE (Systems and software Quality Requirements and Evaluation)**, oferece um modelo mais refinado, abrangente e alinhado com as demandas do software contemporâneo. Este documento apresenta uma análise comparativa detalhada entre os dois modelos de qualidade.

## 2. Visão Geral da Evolução

A principal motivação para a substituição da ISO/IEC 9126 foi a necessidade de:

-   **Maior Clareza e Menos Ambiguidade**: Redefinir características e subcaracterísticas para evitar sobreposições e interpretações vagas.
-   **Refletir a Realidade Moderna**: Incorporar aspectos de qualidade que se tornaram críticos, como segurança e compatibilidade, como características de primeiro nível.
-   **Estrutura Integrada**: Inserir o modelo de qualidade em uma estrutura mais ampla (SQuaRE) que abrange todo o ciclo de vida da avaliação da qualidade, desde a especificação de requisitos até a medição.
-   **Escopo Ampliado**: Mover o foco de apenas "produtos de software" para "sistemas e produtos de software", reconhecendo a crescente integração e complexidade dos ambientes de TI.

## 3. Comparativo das Características de Qualidade

A mudança mais visível entre as duas normas está na estrutura das características de qualidade. A ISO/IEC 9126 possuía 6 características, enquanto a ISO/IEC 25010 expandiu o modelo para 8 características.

| ISO/IEC 9126 (6 Características) | ISO/IEC 25010 (8 Características) | Análise da Mudança |
| :--- | :--- | :--- |
| **Funcionalidade** | **Adequação Funcional** | Renomeada para maior clareza. A subcaracterística "Segurança de Acesso" foi movida para a nova característica "Segurança". |
| **Confiabilidade** | **Confiabilidade** | Manteve-se como característica principal, com subcaracterísticas mais refinadas como "Disponibilidade". |
| **Usabilidade** | **Usabilidade** | Manteve-se, mas foi significativamente expandida com novas subcaracterísticas como "Proteção contra Erros do Usuário", "Estética da Interface" e "Acessibilidade". |
| **Eficiência** | **Eficiência de Desempenho** | Renomeada para focar em desempenho. A nova subcaracterística "Capacidade" foi adicionada. |
| **Manutenibilidade** | **Manutenibilidade** | Manteve-se, com a adição da subcaracterística "Modularidade" e maior ênfase em "Reusabilidade". |
| **Portabilidade** | **Portabilidade** | Manteve-se, com subcaracterísticas mais claras e a remoção de "Coexistência", que foi movida para "Compatibilidade". |
| *(Subcaracterística da Portabilidade)* | **Compatibilidade** | **NOVA CARACTERÍSTICA**. Elevada de uma subcaracterística para refletir a importância da interoperabilidade e coexistência em sistemas modernos. |
| *(Subcaracterística da Funcionalidade)* | **Segurança** | **NOVA CARACTERÍSTICA**. Elevada de uma subcaracterística para se tornar uma área de foco principal, com subcaracterísticas detalhadas como "Confidencialidade", "Integridade" e "Não Repúdio". |

## 4. Análise Detalhada das Mudanças nas Subcaracterísticas

### Da Funcionalidade para a Adequação Funcional

-   **ISO/IEC 9126**: Adequação, Acurácia, Interoperabilidade, Segurança de Acesso, Conformidade.
-   **ISO/IEC 25010**: Completude Funcional, Correção Funcional, Adequação Funcional.
-   **Análise**: A ISO/IEC 25010 simplificou e focou no propósito central da funcionalidade. "Interoperabilidade" moveu-se para "Compatibilidade" e "Segurança de Acesso" para "Segurança", resolvendo sobreposições.

### Usabilidade

-   **ISO/IEC 9126**: Inteligibilidade, Apreensibilidade, Operacionalidade, Atratividade, Conformidade.
-   **ISO/IEC 25010**: Reconhecimento de Adequação, Apreensibilidade, Operacionalidade, Proteção contra Erros do Usuário, Estética da Interface do Usuário, Acessibilidade.
-   **Análise**: A ISO/IEC 25010 modernizou a visão de usabilidade, incluindo aspectos cruciais como proteção contra erros, a experiência estética e, fundamentalmente, a **acessibilidade**, refletindo a importância do design inclusivo.

### Manutenibilidade

-   **ISO/IEC 9126**: Analisabilidade, Modificabilidade, Estabilidade, Testabilidade, Conformidade.
-   **ISO/IEC 25010**: Modularidade, Reusabilidade, Analisabilidade, Modificabilidade, Testabilidade.
-   **Análise**: A introdução de **Modularidade** e a ênfase em **Reusabilidade** alinham a manutenibilidade com práticas modernas de arquitetura de software, como componentização e microserviços.

## 5. Comparativo do Modelo de Qualidade em Uso

O modelo de Qualidade em Uso também evoluiu, ganhando mais detalhes e clareza.

| ISO/IEC 9126 (4 Características) | ISO/IEC 25010 (5 Características) | Análise da Mudança |
| :--- | :--- | :--- |
| **Eficácia** | **Eficácia** | Manteve-se como a capacidade de atingir objetivos com acurácia e completeza. |
| **Produtividade** | **Eficiência** | Renomeada de "Produtividade" para "Eficiência" (em uso), para evitar confusão com a eficiência de desempenho do produto. Refere-se aos recursos gastos pelo usuário. |
| **Segurança** | **Ausência de Risco** | Renomeada de "Segurança" (em uso) para "Ausência de Risco" (Freedom from Risk), para evitar confusão com a característica de segurança do produto. Foca em riscos econômicos, de saúde e ambientais. |
| **Satisfação** | **Satisfação** | Manteve-se, mas foi expandida com subcaracterísticas como "Utilidade", "Confiança", "Prazer" e "Conforto". |
| *(Não existente)* | **Cobertura de Contexto** | **NOVA CARACTERÍSTICA**. Representa o grau em que um produto pode ser usado com eficácia, eficiência, ausência de risco e satisfação tanto em contextos de uso especificados quanto em contextos além daqueles inicialmente previstos. |

## 6. Conclusão: Por que a ISO/IEC 25010 é Superior?

A ISO/IEC 25010 não é apenas uma atualização, mas uma reestruturação fundamental que oferece um modelo de qualidade mais lógico, completo e aplicável ao cenário tecnológico atual.

-   **Melhor Organização**: A promoção de **Segurança** e **Compatibilidade** a características de primeiro nível resolve ambiguidades e reflete a realidade dos sistemas distribuídos e conectados.
-   **Foco no Usuário Moderno**: A expansão da **Usabilidade** para incluir acessibilidade e proteção contra erros demonstra uma compreensão mais madura da interação humano-computador.
-   **Visão de Futuro**: A adição de **Cobertura de Contexto** na qualidade em uso reconhece que os sistemas são frequentemente usados de maneiras imprevistas, incentivando um design mais robusto e flexível.
-   **Integração com SQuaRE**: A norma faz parte de um ecossistema completo (ISO/IEC 25000) que guia desde a definição de requisitos até a avaliação, tornando o processo de gestão da qualidade mais coeso e sistemático.

Em suma, enquanto a ISO/IEC 9126 lançou as bases, a ISO/IEC 25010 construiu sobre elas uma estrutura mais sólida, detalhada e preparada para os desafios da engenharia de software do século XXI.

---

**Arquivo anterior**: [Análise Detalhada da Norma ISO/IEC 25010](analise-iso-25010.md)
**Próximo arquivo**: [Aplicação Prática das Normas de Qualidade](aplicacao-pratica.md)


