# chAI | Assistente conversacional de suporte

[Voltar ao portfólio](../README.md)

## Problema
Clientes precisam de orientações claras e de um caminho organizado para abrir um pedido de suporte quando a orientação não resolve.

## Proposta
Oferecer conversa acolhedora, orientações baseadas em uma fonte e confirmação explícita antes de abrir um chamado.

## Implementado na demonstração local
- Conversa com orientações fictícias e seleção de empresas demonstrativas.
- Abertura de chamado mediante confirmação.
- Consulta de histórico e atualização da situação pela equipe demonstrativa.
- Persistência dos registros em SQLite.
- Adaptador para um provedor de IA, dependente de configuração privada.

## Roteiro para entrevista
1. Escolher uma empresa demonstrativa.
2. Enviar uma dúvida sobre estoque.
3. Confirmar a abertura de um chamado.
4. Consultar o registro na área demonstrativa da equipe.

## Tecnologia e validação
Servidor em Python; interface em HTML, CSS e JavaScript. Sete testes automatizados documentados cobrem isolamento, permissões, confirmação e repetição de chamados, validação e contrato simulado de IA.

## Limites reais
A demonstração é local, não um serviço público de produção. Os perfis são demonstrativos. Não há atendimento humano ao vivo, integração com WhatsApp ou conexão com Orbytta. A IA externa requer credenciais privadas e validação real; sem configuração, são utilizadas orientações locais.

O código completo fica em um repositório separado, sem publicação neste portfólio.
