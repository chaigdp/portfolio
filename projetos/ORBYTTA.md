# Orbytta | Administração, implantação e operação demonstrativa

[Voltar ao portfólio](../README.md)

## Tela inicial

![Tela inicial do Orbytta](../assets/orbytta-inicio.jpg)

Captura da interface atual em ambiente local de demonstração.

## Problema
A equipe que implanta sistemas precisa acompanhar clientes, tarefas e chamados, enquanto o cliente consulta sua própria operação e pede ajuda.

## Proposta
Separar três experiências: administração do negócio, operação do cliente e demonstração com dados inventados.

## Implementado
- Administração com clientes, sistemas em implantação, sistemas implantados e central de chamados.
- Acompanhamento de tarefas da implantação.
- Abertura de chamados pelo cliente com indicação da tela de origem.
- Demonstração de cadastro, estoque, vendas, recebíveis e relatórios.
- Empresas demonstrativas independentes e seleção de operação.
- Adaptador para autenticação e banco Supabase, com limites de validação documentados.

## Roteiro para entrevista
1. Mostrar a visão administrativa do negócio.
2. Consultar uma implantação e suas tarefas.
3. Abrir um chamado pela operação do cliente e encontrá-lo na central.
4. Apresentar uma venda fictícia com alteração de estoque na demonstração.

## Tecnologia e validação
Interface web, servidor Node.js, demonstração SQLite e adaptador Supabase. Há testes de isolamento entre empresas, autorização, validação de estoque, venda transacional, repetição de operações, revogação de sessão e apresentação de conteúdo.

## Limites reais
Produto em desenvolvimento. Não é ERP completo ou fiscalmente certificado. Emissão fiscal, homologação, conciliação, recuperação de acesso, cópias de segurança e validação de produção têm lacunas documentadas. Testes com respostas simuladas não substituem a verificação integral da integração externa. A demonstração da farmácia usa dados fictícios.

O código completo fica em um repositório separado, sem publicação neste portfólio.
