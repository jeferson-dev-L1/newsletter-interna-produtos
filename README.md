# 📋 Prompt — Newsletter Interna de Novos Produtos

> Template reutilizável de Engenharia de Prompt para criação de newsletters internas sobre novos produtos e funcionalidades digitais.

## 🎯 Sobre o projeto

Este projeto apresenta um prompt estruturado para transformar informações fornecidas pelas áreas de Produto em newsletters internas claras, objetivas, confiáveis e prontas para publicação.

O template foi desenvolvido com foco em:

- Clareza da comunicação;
- Padronização do conteúdo;
- Fidelidade às informações fornecidas;
- Redução do risco de informações inventadas pela IA;
- Facilidade de reutilização;
- Orientação clara sobre próximos passos.

---

## 💡 Problema

Comunicações internas sobre novos produtos podem apresentar problemas como:

- excesso de informações;
- linguagem técnica;
- falta de padronização;
- CTAs pouco claros;
- informações incompletas;
- inconsistências entre diferentes campos;
- criação de informações não fornecidas.

Este projeto utiliza Engenharia de Prompt para estabelecer regras que orientam o modelo na geração de uma comunicação mais consistente e confiável.

---

## 🧠 Solução

O prompt define:

1. **Papel** — estabelece o contexto de atuação da IA;
2. **Objetivo** — determina o resultado esperado;
3. **Regras de comunicação** — define linguagem e tom;
4. **Regras de confiabilidade** — reduz o risco de criação de informações não fornecidas;
5. **Estrutura de saída** — padroniza a newsletter;
6. **Tratamento de informações ausentes** — utiliza `⚠️ Informação pendente`;
7. **Tratamento de links** — preserva URLs fornecidas e sinaliza quando não houver link;
8. **Controle de CTAs** — preserva a intenção da ação informada;
9. **FAQ condicional** — evita respostas baseadas em inferências;
10. **Validação de consistência** — verifica possíveis contradições antes da entrega.

---

## 📐 Estrutura do projeto

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

### 📄 `prompt/`

Contém o template principal de Engenharia de Prompt utilizado para gerar as newsletters.

### 📄 `exemplos/`

Apresenta um exemplo de newsletter gerada a partir dos dados fornecidos ao modelo.

### 📄 `docs/`

Apresenta a metodologia utilizada na construção do prompt, incluindo decisões de estrutura, confiabilidade e validação.

---
## 🚀 Como utilizar

- Abra o arquivo `prompt/template-newsletter.md`.
- Mantenha as regras e a estrutura do template.
- Substitua os dados de exemplo pelas informações reais do produto ou funcionalidade.
- Forneça o prompt a um modelo de IA.
- Revise o resultado gerado.
- Utilize a newsletter após a validação das informações.

---

## 🔒 Princípios de confiabilidade

O prompt estabelece que o modelo deve:

- utilizar exclusivamente os dados fornecidos;
- não inventar informações;
- não fazer suposições;
- não alterar URLs;
- preservar os status informados;
- sinalizar informações ausentes;
- verificar consistência entre os campos.

Quando uma informação necessária não estiver disponível, o modelo deve utilizar:

⚠️ Informação pendente

Quando não houver link disponível:

Não disponível.

---

## 🧪 Exemplo

O arquivo exemplos/newsletter-exemplo.md apresenta uma aplicação prática do template.

O exemplo demonstra a geração de uma newsletter contendo:

- Central de Solicitações 2.0;
- Painel de Indicadores Comerciais;
- Integração SSO do Portal de Benefícios.

---

## 📚 Metodologia

A documentação da metodologia está disponível em:

docs/metodologia.md

O documento apresenta as decisões utilizadas na construção do prompt e os critérios adotados para estrutura, clareza, confiabilidade e validação.

---

## 🛠️ Tecnologias e ferramentas
- Engenharia de Prompt
- Modelos de Inteligência Artificial Generativa
- Markdown
- Git
- GitHub
- Visual Studio Code
---

## 🎯 Objetivo do portfólio

Este projeto demonstra a aplicação prática de Engenharia de Prompt na criação de uma solução estruturada para comunicação interna de produtos digitais.

O foco não está apenas na geração de texto, mas na definição de regras, estrutura, validações e critérios de confiabilidade para orientar o comportamento do modelo.

## 🍴 Fork e reutilização

Este projeto pode ser utilizado como base para estudos, adaptações e novos casos de uso.

Você pode fazer um fork deste repositório, adaptar o template às suas necessidades e criar sua própria versão do projeto.

---

## 📌 Status

Concluído — versão inicial do template.

O projeto pode receber novas versões e melhorias conforme novos casos de uso sejam identificados.

---

## 👤 Autor

Jeferson Silva

Projeto desenvolvido como parte de um desafio prático de Engenharia de Prompt.
