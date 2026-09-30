# Nexora | Acompanhamento de implantação de sistemas

[Voltar ao portfólio](../README.md)

## Problema
Uma analista precisa acompanhar várias implantações, identificar pendências e saber quais entregas impedem a conclusão de cada cliente.

## Proposta
Centralizar a carteira de implantações, os critérios de conclusão e as dependências entre entregas.

## Implementado
- Cadastro e edição de clientes, etapas, escopo, datas e responsáveis.
- Entregas com prioridade, bloqueio, dependência, prazo e criticidade.
- Indicadores de carteira, conclusões por período e duração média.
- Histórico de alterações, exportação CSV e guia de uso.
- Demonstração com 30 empresas inventadas e 210 entregas.
- Carteiras isoladas por visitante e contas pessoais com persistência.

## Roteiro para entrevista
1. Abrir a carteira de demonstração.
2. Identificar uma implantação com entrega crítica pendente.
3. Explicar o bloqueio de conclusão e as dependências.
4. Atualizar a entrega e verificar o histórico.

## Tecnologia e validação
React, TypeScript, serviço Cloudflare Workers e banco D1. Senhas derivadas por PBKDF2, sessões com proteção no navegador, validação de origem e consultas isoladas por carteira. Testes locais verificaram entrada, cadastro, persistência, isolamento, histórico e impedimentos de conclusão.

## Limites reais
A primeira versão prioriza a área da analista. Acompanhamento do cliente, permissões por equipe, recuperação de e-mail, anexos e integração com Orbytta ainda exigem implementação. Não representa uma operação comercial integralmente validada.

O código completo fica em um repositório separado, sem publicação neste portfólio.
