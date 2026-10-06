# Vectta | Gestão de implementação de sistemas

[Voltar ao portfólio](../README.md)

![Vectta](../assets/vectta-marca.svg)

## Implantação sem achismo

O Vectta nasceu para resolver um problema recorrente de implementação: quando clientes, requisitos, riscos, testes, pendências, parametrizações e critérios de entrada em operação ficam espalhados, a equipe perde contexto e a implantação passa a depender de memória e acompanhamento manual.

## Proposta de produto

Centralizar a carteira de implantação em uma visão orientada a decisão.

O sistema organiza:

- clientes, contatos e contexto comercial;
- entregas, dependências e responsáveis;
- cronograma e riscos fundamentados;
- requisitos, testes e parametrizações;
- chamados e processos;
- critérios de prontidão antes da entrada em operação;
- indicadores comerciais e de rentabilidade;
- importação e exportação estruturada de dados.

## Demonstração atual

A versão recomendada utiliza Supabase Auth, PostgreSQL e políticas de isolamento de dados.

[Abrir Vectta](https://pldxmxgrgyfwtnhxqaji.supabase.co/functions/v1/vectta)

A demonstração cria uma carteira isolada com **30 empresas fictícias e 210 entregas**, permitindo explorar a organização da implantação sem expor dados reais.

## Segurança e arquitetura

A evolução atual inclui autenticação, isolamento por carteira, validações de entrada, consultas parametrizadas, sessões protegidas e regras de acesso no banco.

A publicação mais recente utiliza Supabase Edge Functions, Supabase Auth e PostgreSQL com RLS, sigla para *Row Level Security*, segurança por linha no banco de dados.

## O que o projeto demonstra

- visão de produto aplicada a implantação;
- transformação de processo operacional em sistema;
- critérios verificáveis de prontidão;
- organização de riscos e dependências;
- experiência da analista como centro da interface;
- preocupação com segurança, isolamento e rastreabilidade;
- evolução de protótipo para uma arquitetura com persistência real.

## Próximos passos

Permissões mais granulares por equipe, anexos privados, recuperação de acesso validada de ponta a ponta, automações externas, integração CRM bidirecional, restauração de backup testada e maior observabilidade.

Dados de demonstração são fictícios.

Atualizado em **06/10/2026**.
