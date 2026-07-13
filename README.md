# QA na Experiência Digital do Palácio Nacional da Pena

Estudo de caso de Engenharia de Qualidade (QA) aplicado à bilheteira online do **Palácio Nacional da Pena**, em Sintra – Portugal.

O projeto teve como objetivo analisar o fluxo de compra de bilhetes sob a perspectiva da qualidade de software, validando regras de negócio, identificando riscos, avaliando a experiência do utilizador e estruturando uma estratégia de testes para os principais comportamentos da aplicação.

Durante a análise foram aplicadas técnicas de Engenharia de Requisitos, Planejamento de Testes, Particionamento de Equivalência, Análise de Valor Limite (BVA), Testes Exploratórios e Análise de Risco para estruturar e validar os principais fluxos da aplicação.

---

# Visão Geral

| Item | Descrição |
|------|-----------|
| **Sistema analisado** | Bilheteira online do Palácio Nacional da Pena |
| **Tipo de aplicação** | E-commerce |
| **Plataforma** | Web |
| **Tipo de testes** | Testes Manuais |
| **Casos de teste** | 51 |
| **Requisitos documentados** | 8 (REQ_01 a REQ_08) |
| **Técnicas aplicadas** | Engenharia de Requisitos, Planejamento de Testes, BDD, Particionamento de Equivalência, Análise de Valor Limite (BVA), Testes Exploratórios e Análise de Risco |

---

# Contexto

A bilheteira online do Palácio Nacional da Pena possui diferentes regras de negócio relacionadas à venda de ingressos, categorias de visitantes, datas, horários e processo de compra.

Um processo de compra eficiente depende da correta aplicação dessas regras e da consistência das informações apresentadas ao utilizador. Falhas nesse fluxo podem comprometer a experiência do cliente e impactar diretamente a conclusão da compra.

Este estudo de caso teve como objetivo analisar esse fluxo sob a perspectiva da qualidade de software, documentando requisitos, identificando riscos e estruturando uma estratégia de testes para validar os principais comportamentos da aplicação.

---

# Objetivos

- Compreender e documentar os requisitos funcionais da aplicação;
- Planejar uma estratégia de testes baseada em risco;
- Elaborar casos de teste utilizando técnicas de projeto de testes;
- Validar os principais fluxos da bilheteira online;
- Executar testes manuais;
- Identificar defeitos e oportunidades de melhoria;
- Documentar os resultados obtidos durante a análise.

---

# Escopo da Análise

A análise concentrou-se exclusivamente na versão Web da bilheteira online, considerando os fluxos disponíveis durante o período de realização do projeto.

Foram analisados os seguintes processos:

- Seleção do monumento;
- Escolha da experiência;
- Seleção da data e horário;
- Seleção da quantidade e categoria dos bilhetes;
- Aplicação das regras de preço;
- Carrinho de compras;
- Processo de checkout;
- Informações apresentadas ao utilizador;
- Validações de campos e comportamentos inesperados.

---

# Fluxo Principal Analisado

```text
Página Inicial
        │
        ▼
Escolha do Monumento
        │
        ▼
Escolha da Experiência
        │
        ▼
Seleção da Data
        │
        ▼
Seleção do Horário
        │
        ▼
Quantidade de Bilhetes
        │
        ▼
Carrinho de Compras
        │
        ▼
Checkout
        │
        ▼
Confirmação da Compra
```

---

# Metodologias Aplicadas

| Metodologia | Aplicação no Projeto |
|--------------|----------------------|
| Engenharia de Requisitos | Levantamento e documentação dos requisitos funcionais |
| Planejamento de Testes | Definição da estratégia de testes |
| Particionamento de Equivalência | Redução de cenários redundantes |
| Análise de Valor Limite (BVA) | Validação dos limites das regras de negócio |
| Testes Exploratórios | Identificação de comportamentos inesperados |
| Análise de Risco | Priorização dos cenários críticos |
| BDD (Gherkin) | Documentação dos comportamentos esperados |

---

# Ferramentas Utilizadas

| Ferramenta | Finalidade |
|------------|------------|
| Microsoft Excel | Organização dos artefatos de QA |
| Google Sheets | Planejamento e documentação |
| Jira | Planejamento da gestão de defeitos |
| DevTools | Inspeção da interface e validação de responsividade |
| GitHub | Versionamento e documentação do projeto |

---

# Competências Demonstradas

Durante o desenvolvimento deste projeto foram aplicadas competências relacionadas a:

- Engenharia de Requisitos;
- Planejamento de Testes;
- Escrita de Casos de Teste;
- Testes Manuais;
- Particionamento de Equivalência;
- Análise de Valor Limite (BVA);
- Testes Exploratórios;
- Análise de Risco;
- Validação de Regras de Negócio;
- Testes de Usabilidade;
- Documentação Técnica.

---

# Resultados Obtidos

Ao final do projeto foram produzidos:

- Engenharia de requisitos da aplicação;
- Matriz de requisitos (REQ_01 a REQ_08);
- Levantamento inicial de mais de **180 cenários potenciais de teste**;
- Consolidação em **51 casos de teste priorizados**, utilizando técnicas de Particionamento de Equivalência e Análise de Valor Limite (BVA);
- Execução dos testes manuais;
- Registro de evidências e defeitos identificados durante a análise.

---

# Organização dos Artefatos

```
qa-projeto-palacio-da-pena
│
├── README.md
└── Plano_de_Testes_Palacio_da_Pena.xlsx
    ├── Engenharia de Requisitos
    ├── Matriz de Rastreabilidade
    ├── Casos de Teste
    ├── Execução dos Testes
    ├── Evidências
    └── Resultados
```

---

# Conteúdo do Projeto

O arquivo **Plano_de_Testes_Palacio_da_Pena.xlsx** reúne todos os artefatos produzidos durante a análise, incluindo:

- Engenharia de Requisitos;
- Matriz de Rastreabilidade;
- Casos de Teste;
- Execução dos Testes;
- Evidências dos testes realizados;
- Registro dos defeitos encontrados.

---

# Principais Aprendizados

Este projeto reforçou a importância da Engenharia de Requisitos como base para o planejamento de testes e demonstrou como técnicas de projeto de testes podem aumentar a cobertura da aplicação, reduzindo cenários redundantes sem comprometer a qualidade da validação.

Além do desenvolvimento técnico, a análise proporcionou uma compreensão mais ampla da relação entre regras de negócio, experiência do utilizador e qualidade de software.

---

# Considerações Finais

Este estudo de caso reúne as principais etapas de um processo de QA, desde o entendimento dos requisitos até a elaboração dos casos de teste, execução dos testes manuais e documentação dos resultados.

Mais do que validar funcionalidades, o projeto buscou analisar a aplicação sob a perspectiva da qualidade, contribuindo para uma experiência de utilização mais consistente e confiável.
