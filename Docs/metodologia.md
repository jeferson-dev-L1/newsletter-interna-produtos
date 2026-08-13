# 📐 Metodologia — Newsletter Interna de Novos Produtos

## 1. Visão geral

Este projeto apresenta um template reutilizável de prompt desenvolvido para gerar newsletters internas sobre novos produtos e funcionalidades digitais.

A proposta é transformar informações fornecidas pelas áreas de Produto em uma comunicação clara, objetiva, confiável e pronta para publicação.

O prompt foi estruturado para reduzir ambiguidades, evitar a criação de informações não fornecidas e manter um padrão consistente entre diferentes edições da newsletter.

---

## 2. Problema identificado

Comunicações internas sobre novos produtos podem apresentar alguns problemas recorrentes:

- excesso de informações;
- linguagem excessivamente técnica;
- ausência de informações importantes;
- inconsistência entre diferentes comunicações;
- CTAs pouco claros;
- informações inventadas ou inferidas pela IA;
- dificuldade para localizar rapidamente o que mudou;
- repetição desnecessária de informações de suporte.

O prompt foi desenvolvido para tratar esses pontos por meio de regras explícitas de comunicação, confiabilidade e estrutura de saída.

---

## 3. Objetivo do prompt

O objetivo principal é orientar um modelo de IA na criação de newsletters internas que permitam ao colaborador identificar rapidamente:

- o que mudou;
- por que a mudança é relevante;
- quem deve utilizar o produto ou funcionalidade;
- como acessar ou utilizar;
- qual ação deve ser realizada;
- onde encontrar informações adicionais ou suporte.

---

## 4. Estrutura do prompt

O prompt foi dividido em diferentes partes para facilitar sua compreensão e reutilização.

### 🎭 Papel

Define o papel assumido pelo modelo:

> Especialista em Comunicação Interna de Produtos Digitais.

Essa definição estabelece o contexto de atuação da IA e orienta o estilo da comunicação.

### 🎯 Objetivo

Define o resultado esperado e estabelece que a newsletter deve utilizar exclusivamente as informações fornecidas nos dados de entrada.

### 📐 Regras

As regras foram organizadas em quatro grupos principais:

#### Comunicação

Define o idioma, tom de voz e estilo da newsletter.

#### Clareza

Orienta o modelo a utilizar títulos curtos, frases objetivas e bullets, evitando excesso de informações técnicas.

#### Confiabilidade

Reduz o risco de o modelo inventar ou completar informações ausentes.

Quando uma informação necessária não estiver disponível, o prompt orienta o uso de:

**⚠️ Informação pendente**

Para links não disponíveis, utiliza:

**Não disponível.**

#### CTA

Define como as chamadas para ação devem ser utilizadas, preservando a intenção informada nos dados de entrada.

---

## 5. Estrutura padronizada da saída

A newsletter possui uma estrutura fixa:

1. Abertura;
2. Novidades da semana;
3. Resumo executivo;
4. FAQ rápido, quando houver informações suficientes;
5. Encerramento.

Cada novidade também possui campos padronizados:

- O que é;
- Por que isso importa;
- Para quem é;
- Como acessar/usar;
- Status;
- Links úteis;
- CTA interno.

Essa estrutura facilita a leitura e permite comparar diferentes produtos ou funcionalidades.

---

## 6. Controle de informações

Um dos principais objetivos do prompt é reduzir alucinações ou informações criadas pelo modelo.

Para isso, foram estabelecidas regras como:

- utilizar somente os dados fornecidos;
- não inventar benefícios;
- não inventar funcionalidades;
- não inventar links;
- não alterar URLs;
- não fazer suposições sobre informações ausentes;
- preservar os status informados;
- sinalizar informações ausentes.

Além disso, o prompt determina uma etapa de validação antes da geração da newsletter.

---

## 7. Validação de consistência

O prompt orienta o modelo a verificar se as informações apresentadas em diferentes campos são consistentes entre si.

A validação considera principalmente:

- status;
- público;
- forma de acesso;
- CTA;
- links;
- informações de suporte.

Essa etapa busca evitar contradições dentro da própria newsletter.

---

## 8. Tratamento de siglas

Quando uma sigla aparece pela primeira vez, o prompt determina que seu significado seja apresentado juntamente com a sigla.

Exemplo:

**Login único (SSO)**

Essa regra melhora a compreensão do conteúdo por colaboradores que não possuem conhecimento técnico sobre determinado produto.

---

## 9. FAQ condicional

O FAQ não é obrigatório em todas as edições.

O prompt determina que a seção somente seja criada quando existirem informações suficientes nos dados de entrada.

Isso evita que a IA crie perguntas e respostas baseadas em suposições.

Quando não houver informações suficientes, a seção deve ser omitida.

---

## 10. Princípio utilizado

O projeto segue um princípio central:

> Uma boa newsletter não é a que fala mais. É a que faz o colaborador entender o que mudou e saber o que fazer a seguir.

Por isso, quando existe conflito entre adicionar mais informações e manter a comunicação objetiva e confiável, o prompt prioriza:

**clareza + objetividade + fidelidade aos dados fornecidos.**

---

## 11. Resultado esperado

O resultado é um template reutilizável que pode receber diferentes conjuntos de informações de produtos e gerar newsletters seguindo uma estrutura consistente.

O modelo não deve apenas produzir um texto bem escrito, mas respeitar regras de:

- estrutura;
- linguagem;
- confiabilidade;
- consistência;
- tratamento de informações ausentes;
- CTAs;
- links;
- siglas;
- FAQ.

---

## 12. Estrutura do projeto

```text
newsletter-interna-produtos/
│
├── README.md
│
├── prompt/
│   └── template-newsletter.md
│
├── exemplos/
│   └── newsletter-exemplo.md
│
└── docs/
    └── metodologia.md

```
