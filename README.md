# Explicador de textos jurídicos (n8n)

**Status: em desenvolvimento**

Autor: Danthe Pinheiro Pereira.

## Problema
Textos jurídicos (artigos de lei, decisões, contratos) usam uma linguagem difícil para quem não é da área, e isso afasta as pessoas do acesso ao direito.

## Solução planejada
Um chat em que a pessoa cola um texto jurídico curto e recebe:
1. um resumo em até 5 linhas, em linguagem simples;
2. o significado dos termos difíceis;
3. um aviso de que é uma explicação educativa, e não parecer jurídico.

A ideia nasceu da minha participação no projeto de extensão "Direito ao Alcance de Todos", em que explico conceitos jurídicos para estudantes de escola.

## Como vai funcionar
Chat do n8n (Chat Trigger) que envia o texto para um agente de IA com instruções (system message) para explicar em linguagem simples, sem inventar leis ou artigos e avisando quando não tiver certeza.

## Situação atual
- O n8n está instalado e rodando no meu computador.
- O fluxo está em construção. A conexão com o modelo de IA ainda está sendo configurada.
- Este é o meu primeiro projeto de automação com IA.

## Ferramentas
- n8n (automação)
- Modelo de IA via API (a configurar)
- GitHub (versionamento)

## Limitações previstas
- A IA pode errar ou simplificar demais. Por isso o aviso de que não substitui um profissional.
- Textos longos ou incompletos podem gerar respostas imprecisas.

## Próximos passos
- Finalizar a conexão com o modelo de IA.
- Testar com 5 textos jurídicos e medir o tempo que a ferramenta economiza em relação a resumir manualmente.
- Gravar um vídeo curto de demonstração.
- Publicar o fluxo exportado neste repositório.
