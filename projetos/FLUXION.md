# Fluxion | Jornada conversacional e governança de mensagens

[Voltar ao portfólio](../README.md)

## Problema
Comunicações distribuídas dificultam entender a sequência da jornada, as alternativas de atendimento e quais mensagens estão vinculadas a cada etapa.

## Proposta
Reunir o planejamento da jornada e o acompanhamento registrado em um mapa visual com trilha, mascote e casas interativas.

## Implementado
- Mapa da jornada com casas clicáveis, caminhos alternativos e de falha.
- Filtros para diferentes recortes da jornada e navegação do mascote.
- Mensagens A/B vinculadas às etapas e curva emocional explicitamente planejada.
- Edição de casas, clientes, eventos, mensagens, chamados e experimentos.
- API no servidor, banco persistente, histórico de alterações e validação de vínculos.
- Separação entre operação e demonstração inventada.

## Roteiro para entrevista
1. Mostrar uma casa e sua mensagem vinculada.
2. Explicar como um caminho alternativo nasce de uma casa de origem.
3. Editar uma etapa e conferir o registro persistido.
4. Registrar um evento para um cliente e consultar seu acompanhamento.

## Tecnologia e validação
Interface em React e TypeScript; serviço no servidor e banco Cloudflare D1. Foram realizados testes de autenticação, isolamento de usuários, edição, auditoria, integridade, conflitos e persistência após reabrir o banco. O mapa foi conferido visualmente com dados de teste.

## Limites reais
Percorrer o mapa é uma simulação visual. Os eventos são registrados manualmente. A emoção exibida pertence ao planejamento, não a uma medição do cliente. Não há envio por WhatsApp/Blip, coleta automática, integração CRM/ERP ou avaliação por IA conectada nesta entrega. A aplicação hospedada mantém acesso restrito.

O código completo fica em um repositório separado, sem publicação neste portfólio.
