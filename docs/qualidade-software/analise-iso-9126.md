# Análise Detalhada da Norma ISO/IEC 9126

## 1. Introdução à ISO/IEC 9126

A norma **ISO/IEC 9126**, intitulada "Software engineering — Product quality", foi um padrão internacional para a avaliação da qualidade de software, publicado originalmente em 1991 e revisado em 2001. Ela estabeleceu um modelo de qualidade que se tornou uma referência fundamental na engenharia de software, definindo um conjunto de características e subcaracterísticas que descrevem e medem a qualidade de um produto de software. O objetivo principal da norma era fornecer uma estrutura para a especificação de requisitos de qualidade, avaliação de produtos de software e melhoria contínua dos processos de desenvolvimento.

O modelo de qualidade da ISO/IEC 9126 é dividido em duas partes principais:

1.  **Qualidade Interna e Externa**: Descreve a qualidade do software a partir de seis características principais, que podem ser avaliadas durante o desenvolvimento (qualidade interna) e durante os testes em um ambiente simulado (qualidade externa).
2.  **Qualidade em Uso**: Descreve a qualidade do software da perspectiva do usuário final, avaliando a eficácia, produtividade, segurança e satisfação em um contexto de uso real.

Este documento foca na análise das seis características de qualidade interna e externa, que formam o núcleo do modelo.

## 2. As Seis Características de Qualidade

A ISO/IEC 9126 define a qualidade de software através de seis características principais, cada uma subdividida em subcaracterísticas. Essas características fornecem uma visão multifacetada da qualidade, permitindo que desenvolvedores, testadores e clientes especifiquem e avaliem o software de forma mais precisa.

### 2.1. Funcionalidade (Functionality)

A funcionalidade refere-se à capacidade do software de prover as funções que atendem às necessidades explícitas e implícitas do usuário quando o software é usado sob condições especificadas. Em outras palavras, é o que o software faz.

**Subcaracterísticas:**

-   **Adequação (Suitability)**: A capacidade do software de prover um conjunto apropriado de funções para tarefas e objetivos específicos do usuário.
-   **Acurácia (Accuracy)**: A capacidade do software de prover resultados ou efeitos corretos ou de acordo com o esperado.
-   **Interoperabilidade (Interoperability)**: A capacidade do software de interagir com um ou mais sistemas especificados.
-   **Segurança de Acesso (Security)**: A capacidade do software de proteger informações e dados de forma que pessoas ou sistemas não autorizados não possam lê-los ou modificá-los, enquanto não nega o acesso a pessoas ou sistemas autorizados.
-   **Conformidade (Compliance)**: A capacidade do software de aderir a padrões, convenções ou regulamentações legais e prescrições similares relacionadas à funcionalidade.

### 2.2. Confiabilidade (Reliability)

A confiabilidade é a capacidade do software de manter um nível de desempenho especificado quando usado sob condições especificadas. Está relacionada à robustez e à capacidade do software de funcionar sem falhas.

**Subcaracterísticas:**

-   **Maturidade (Maturity)**: A capacidade do software de evitar falhas como resultado de defeitos no software.
-   **Tolerância a Falhas (Fault Tolerance)**: A capacidade do software de manter um nível de desempenho especificado em casos de falhas de software ou de violação de sua interface especificada.
-   **Recuperabilidade (Recoverability)**: A capacidade do software de restabelecer seu nível de desempenho e recuperar os dados diretamente afetados em caso de falha.
-   **Conformidade (Compliance)**: Aderência a padrões ou convenções relacionadas à confiabilidade.

### 2.3. Usabilidade (Usability)

A usabilidade refere-se ao esforço necessário para usar o software e à avaliação individual de tal uso por um conjunto de usuários explícito ou implícito. É a facilidade com que o software pode ser usado.

**Subcaracterísticas:**

-   **Inteligibilidade (Understandability)**: A capacidade do software de permitir que o usuário entenda se o software é apropriado e como ele pode ser usado para tarefas e condições particulares de aplicação.
-   **Apreensibilidade (Learnability)**: A capacidade do software de permitir que o usuário aprenda a sua aplicação.
-   **Operacionalidade (Operability)**: A capacidade do software de permitir que o usuário o opere e controle.
-   **Atratividade (Attractiveness)**: A capacidade do software de ser atraente para o usuário.
-   **Conformidade (Compliance)**: Aderência a padrões ou convenções relacionadas à usabilidade.

### 2.4. Eficiência (Efficiency)

A eficiência é a relação entre o nível de desempenho do software e a quantidade de recursos utilizados, sob condições especificadas. Mede quão bem o software utiliza os recursos do sistema.

**Subcaracterísticas:**

-   **Comportamento em Relação ao Tempo (Time Behaviour)**: A capacidade do software de prover tempos de resposta e processamento apropriados e taxas de transferência adequadas quando executa sua função, sob condições especificadas.
-   **Utilização de Recursos (Resource Utilization)**: A capacidade do software de usar quantidades e tipos de recursos apropriados quando executa sua função, sob condições especificadas.
-   **Conformidade (Compliance)**: Aderência a padrões ou convenções relacionadas à eficiência.

### 2.5. Manutenibilidade (Maintainability)

A manutenibilidade é a capacidade do software de ser modificado. As modificações podem incluir correções, melhorias ou adaptações do software a mudanças no ambiente, nos requisitos e nas especificações funcionais.

**Subcaracterísticas:**

-   **Analisabilidade (Analyzability)**: A capacidade do software de ser diagnosticado em busca de deficiências ou causas de falhas, ou para identificação de partes a serem modificadas.
-   **Modificabilidade (Changeability)**: A capacidade do software de permitir que uma modificação especificada seja implementada.
-   **Estabilidade (Stability)**: A capacidade do software de evitar efeitos inesperados de modificações no software.
-   **Testabilidade (Testability)**: A capacidade do software de permitir que o software modificado seja validado.
-   **Conformidade (Compliance)**: Aderência a padrões ou convenções relacionadas à manutenibilidade.

### 2.6. Portabilidade (Portability)

A portabilidade é a capacidade do software de ser transferido de um ambiente para outro. O ambiente pode incluir hardware, software ou outros componentes de sistema.

**Subcaracterísticas:**

-   **Adaptabilidade (Adaptability)**: A capacidade do software de ser adaptado para diferentes ambientes especificados sem a aplicação de ações ou meios diferentes daqueles fornecidos para este propósito pelo software considerado.
-   **Instalabilidade (Installability)**: A capacidade do software de ser instalado em um ambiente especificado.
-   **Coexistência (Co-existence)**: A capacidade do software de coexistir com outro software independente em um ambiente comum, compartilhando recursos comuns.
-   **Capacidade para Substituir (Replaceability)**: A capacidade do software de ser usado no lugar de outro software especificado para o mesmo propósito no mesmo ambiente.
-   **Conformidade (Compliance)**: Aderência a padrões ou convenções relacionadas à portabilidade.

## 3. Qualidade em Uso (Quality in Use)

Além das características de qualidade interna e externa, a ISO/IEC 9126-1 introduz o conceito de **qualidade em uso**, que avalia a qualidade do software no ambiente real de operação. A qualidade em uso é o efeito combinado das seis características de qualidade para o usuário final.

As características da qualidade em uso são:

-   **Eficácia (Effectiveness)**: A capacidade do software de permitir que os usuários alcancem os objetivos especificados com acurácia e completeza em um contexto de uso especificado.
-   **Produtividade (Productivity)**: A capacidade do software de permitir que os usuários empreguem uma quantidade apropriada de recursos em relação à eficácia alcançada em um contexto de uso especificado.
-   **Segurança (Safety)**: A capacidade do software de alcançar níveis aceitáveis de risco de dano a pessoas, negócios, software, propriedade ou ambiente em um contexto de uso especificado.
-   **Satisfação (Satisfaction)**: A capacidade do software de satisfazer os usuários em um contexto de uso especificado.

## 4. Limitações e Evolução para a ISO/IEC 25010

Apesar de sua ampla adoção, a ISO/IEC 9126 apresentava algumas limitações:

-   **Subjetividade**: Algumas subcaracterísticas eram difíceis de medir objetivamente.
-   **Sobreposição**: Havia sobreposição entre algumas características (ex: segurança de acesso em funcionalidade e segurança como um todo).
-   **Falta de Clareza**: A distinção entre qualidade interna, externa e em uso nem sempre era clara na prática.

Essas limitações, juntamente com a evolução da indústria de software, levaram ao desenvolvimento da série de normas **ISO/IEC 25000 (SQuaRE - Software Product Quality Requirements and Evaluation)**, com a **ISO/IEC 25010** substituindo diretamente o modelo de qualidade da ISO/IEC 9126. A ISO/IEC 25010 refinou o modelo, introduziu novas características (como segurança e compatibilidade como características de primeiro nível) e forneceu uma estrutura mais robusta para a avaliação da qualidade de software.

## 5. Conclusão

A ISO/IEC 9126 foi um marco na padronização da qualidade de software, fornecendo um vocabulário comum e uma estrutura para a especificação e avaliação da qualidade. Seu modelo de seis características influenciou profundamente a forma como a indústria de software pensa sobre a qualidade, e seus princípios continuam relevantes mesmo após sua substituição pela ISO/IEC 25010. Compreender a ISO/IEC 9126 é essencial para qualquer profissional de engenharia de software que deseje construir produtos de alta qualidade.

---

**Próximo arquivo**: [Análise Detalhada da Norma ISO/IEC 25010](analise-iso-25010.md)


