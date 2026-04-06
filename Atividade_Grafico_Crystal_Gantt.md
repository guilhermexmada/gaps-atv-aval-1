# Gestão Ágil de Projetos – TechConnect Solutions
**Sistema de Cadastro de Empresas Parceiras**

---

## Gráfico de Gantt – Cronograma do Projeto (6 meses)

```mermaid
gantt
    title Sistema de Cadastro de Empresas Parceiras – TechConnect Solutions
    dateFormat  YYYY-MM-DD
    axisFormat  %b/%Y

    section Planejamento
    Levantamento de Requisitos          :a1, 2025-01-01, 14d
    Documentação Funcional              :a2, after a1, 14d

    section Design
    Rascunho das Telas                  :b1, after a2, 14d
    Layout Definitivo                   :b2, after b1, 14d

    section Infraestrutura
    Config. Ambiente de Desenvolvimento :c1, after a2, 7d
    Criação do Banco de Dados          :c2, after c1, 7d

    section Desenvolvimento
    Módulo de Login (Autenticação)      :d1, after c2, 21d
    CRUD de Empresas                    :d2, after d1, 21d
    Upload de Logotipo                  :d3, after d2, 14d
    Relatórios PDF e Excel              :d4, after d3, 14d
    Painel Administrativo               :d5, after d4, 14d

    section Testes
    Testes Unitários e de Integração    :e1, after d5, 14d
    Testes de Usabilidade               :e2, after e1, 7d

    section Entrega
    Implantação Final no Servidor       :f1, after e2, 7d
    Entrega ao Cliente                  :milestone, after f1, 0d
```

---

## Matriz Crystal – Situações que Requerem Atenção

```mermaid
quadrantChart
    title Matriz Crystal – Risco x Impacto no Projeto
    x-axis Baixo Risco --> Alto Risco
    y-axis Baixo Impacto --> Alto Impacto

    quadrant-1 CRÍTICO – Agir Imediatamente
    quadrant-2 IMPORTANTE – Monitorar de Perto
    quadrant-3 BAIXA PRIORIDADE – Observar
    quadrant-4 ATENÇÃO – Planejar Mitigação

    Autenticação e Segurança de Acesso: [0.80, 0.90]
    Integridade do Banco de Dados: [0.75, 0.85]
    Prazo de 6 Meses: [0.70, 0.80]
    Upload e Armazenamento de Imagens: [0.60, 0.65]
    Painel Administrativo com Permissões: [0.55, 0.70]
    Relatórios PDF e Excel: [0.45, 0.55]
    Testes de Usabilidade: [0.40, 0.60]
    Interface Responsiva: [0.30, 0.50]
    Controle de Versão no Git: [0.25, 0.40]
    Comunicação da Equipe: [0.20, 0.35]
```

---

## Entregas Incrementais (Crystal Clear)

| # | Entrega | Funcionalidade | Responsável |
|---|---------|---------------|-------------|
| 1 | Entrega 1 | Módulo de Login com Autenticação | Desenvolvedor + QA |
| 2 | Entrega 2 | CRUD de Empresas Ativo | Desenvolvedores |
| 3 | Entrega 3 | Upload de Logotipo integrado ao Cadastro | Desenvolvedor |
| 4 | Entrega 4 | Relatórios em PDF e Excel | Desenvolvedor |
| 5 | Entrega 5 | Painel Administrativo com Permissões | Desenvolvedor + QA |
| 6 | Entrega Final | Sistema Testado, Implantado e Validado | Toda a Equipe |

> A cada entrega parcial, a diretoria será convidada para revisar as funcionalidades, sugerir melhorias e validar os requisitos.
