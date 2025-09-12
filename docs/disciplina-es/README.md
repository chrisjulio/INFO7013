# Disciplina de Engenharia de Software

## Visão Geral

Esta seção contém os materiais e análises dos artigos básicos da disciplina de Engenharia de Software, organizados para complementar e enriquecer a base teórica do projeto INFO7013. Os documentos foram analisados e integrados ao contexto da pesquisa acadêmica em desenvolvimento.

## Artigos Básicos Analisados

### 1. Qualidade de Produto - Wazlawick (Capítulo 11)
**Arquivo**: `cap11_wazlawick(OCR).pdf`

**Conteúdo Principal**:
- Modelo de qualidade ISO/IEC 25010:2011 (SQuaRE)
- Evolução da ISO/IEC 9126 para ISO/IEC 25010
- Características de qualidade interna, externa e de uso
- 8 características principais: Adequação Funcional, Confiabilidade, Usabilidade, Eficiência de Desempenho, Segurança, Compatibilidade, Manutenibilidade, Portabilidade

**Relevância para o Projeto**:
- Complementa a análise comparativa entre normas ISO já desenvolvida
- Fornece detalhes técnicos sobre subcaracterísticas de qualidade
- Suporte teórico para o framework QA-Agile proposto

### 2. Métricas de Produto - Pressman (Capítulo 23)
**Arquivo**: `Cap23_Metricas(OCR).pdf`

**Conteúdo Principal**:
- Princípios de medição em engenharia de software
- Diferenciação entre medidas, métricas e indicadores
- Paradigma Goal/Question/Metric (GQM)
- Desafios na definição de métricas de produto
- Princípios para caracterização e validação de métricas

**Relevância para o Projeto**:
- Base teórica para o documento de métricas modernas desenvolvido
- Metodologia GQM aplicável às propostas metodológicas
- Fundamentação para validação empírica das métricas propostas

### 3. Garantia da Qualidade de Software - Pressman (Capítulo 16)
**Arquivo**: `cap16_pressman.pdf`

**Conteúdo Principal**:
- Elementos da garantia da qualidade de software (SQA)
- Tarefas, objetivos e métricas de SQA
- Padrões, revisões, auditorias e testes
- Gestão de mudanças e coleta de dados de defeitos
- Papel do grupo SQA na organização

**Relevância para o Projeto**:
- Fundamentação para processos de qualidade nas propostas metodológicas
- Base para integração de SQA com metodologias ágeis
- Suporte teórico para o modelo de maturidade QA-Maturity

### 4. Economia da Engenharia de Software - Boehm
**Arquivo**: `Software_Engineering_Economics.pdf`

**Conteúdo Principal**:
- Princípios econômicos aplicados à engenharia de software
- Técnicas de análise de decisão em situações de recursos limitados
- Análise custo-benefício e valor da informação
- Prototipagem como investimento em informação
- Gestão de riscos e incertezas em projetos de software

**Relevância para o Projeto**:
- Base econômica para justificativa das propostas metodológicas
- Fundamentação para análise de ROI das métricas de qualidade
- Suporte teórico para tomada de decisões em desenvolvimento ágil

### 5. Técnicas de Revisão - Capítulo 15
**Arquivo**: `Cap15_Tecnicas_Revisao_compressed(OCR).pdf`

**Conteúdo Principal**:
- Métodos de revisão técnica formal
- Inspeções de código e documentação
- Walkthroughs e revisões por pares
- Métricas de eficácia de revisões

**Relevância para o Projeto**:
- Complementa as práticas de qualidade nas metodologias propostas
- Base para integração de revisões em processos ágeis
- Suporte para métricas de qualidade de processo

### 6. Pressman - Capítulo 14
**Arquivo**: `cap14_pressman_compressed(OCR).pdf`

**Conteúdo Principal**:
- Conceitos fundamentais de qualidade de software
- Fatores de qualidade e critérios de avaliação
- Modelos de qualidade e sua evolução
- Relação entre qualidade de processo e produto

**Relevância para o Projeto**:
- Fundamentação teórica para definições de qualidade
- Base conceitual para o framework QA-Agile
- Suporte para análises comparativas de modelos

### 7. Wazlawick - Seção 9.5
**Arquivo**: `9.5_Wazlawick(OCR).pdf`

**Conteúdo Principal**:
- Aspectos específicos de modelagem e design
- Práticas de engenharia de software
- Metodologias de desenvolvimento

**Relevância para o Projeto**:
- Complementa os fundamentos teóricos dos autores seminais
- Suporte para análises de modelos de processo
- Base para propostas metodológicas

## Integração com o Projeto INFO7013

### Contribuições para Análises Comparativas
Os artigos fornecem:
- Detalhamento técnico das normas ISO/IEC 9126 e 25010
- Comparações entre diferentes abordagens de qualidade
- Evolução histórica dos conceitos de qualidade de software

### Suporte às Propostas Metodológicas
Os documentos oferecem:
- Fundamentação teórica para o framework QA-Agile
- Base científica para a metodologia SMART-Quality
- Princípios para o modelo de maturidade QA-Maturity
- Arquitetura conceitual para QualityOps

### Enriquecimento das Métricas Modernas
Os artigos contribuem com:
- Princípios de medição validados academicamente
- Metodologias para definição de métricas (GQM)
- Critérios de validação e caracterização de métricas
- Exemplos práticos de aplicação

### Fortalecimento da Base Teórica
Os documentos complementam:
- Análise dos fundamentos teóricos (Pressman, Wazlawick)
- Perspectivas econômicas (Boehm)
- Práticas de garantia da qualidade
- Técnicas de revisão e validação

## Próximos Passos

### Análise Detalhada
- [ ] Extrair conceitos-chave de cada documento
- [ ] Identificar convergências e divergências entre autores
- [ ] Mapear contribuições específicas para cada proposta metodológica

### Integração ao Conteúdo
- [ ] Incorporar citações relevantes aos artigos científicos em desenvolvimento
- [ ] Atualizar análises comparativas com novos insights
- [ ] Enriquecer propostas metodológicas com fundamentação adicional

### Validação Cruzada
- [ ] Verificar consistência entre diferentes fontes
- [ ] Identificar lacunas na literatura analisada
- [ ] Propor sínteses inovadoras baseadas na análise conjunta

## Estrutura de Arquivos

```
/docs/disciplina-es/
├── README.md                           # Este documento
├── artigos-basicos/                    # PDFs originais
│   ├── cap11_wazlawick(OCR).pdf
│   ├── Cap23_Metricas(OCR).pdf
│   ├── cap16_pressman.pdf
│   ├── Software_Engineering_Economics.pdf
│   ├── Cap15_Tecnicas_Revisao_compressed(OCR).pdf
│   ├── cap14_pressman_compressed(OCR).pdf
│   └── 9.5_Wazlawick(OCR).pdf
├── analises-detalhadas/                # Análises específicas (a criar)
├── sinteses-tematicas/                 # Sínteses por tema (a criar)
└── integracao-projeto/                 # Mapeamento para propostas (a criar)
```

## Impacto no Projeto

### Fortalecimento Acadêmico
- Base teórica mais sólida e diversificada
- Múltiplas perspectivas sobre qualidade de software
- Fundamentação econômica para justificativas

### Enriquecimento das Propostas
- Maior rigor científico nas metodologias propostas
- Validação teórica das abordagens desenvolvidas
- Integração de práticas consolidadas

### Melhoria dos Artigos Científicos
- Referencial teórico mais abrangente
- Citações de fontes primárias relevantes
- Argumentação mais robusta e fundamentada

---

**Última atualização**: Setembro 2025  
**Responsável**: Equipe de Pesquisa INFO7013  
**Status**: Análise inicial concluída, integração em andamento

