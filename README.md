# codexchatgpt

Repositório de trabalho para projetos desenvolvidos com apoio do ChatGPT e do Codex.

## Comece por aqui

- [Orientações para agentes](AGENTS.md): contexto, autonomia, validação e entrega.
- [Contexto do projeto](docs/CONTEXTO.md): estado atual, mapa dos arquivos e decisões.
- [Modelo de tarefa](docs/MODELO-TAREFA.md): resultado esperado, evidências e critérios de aceite.
- [Modelo de revisão](.github/pull_request_template.md): resultado, validação e limitações de uma mudança.

## Estado atual

O repositório contém documentação e modelos de trabalho. Ainda não há aplicação, extensão, dependências ou comandos de instalação, execução e testes. Esses itens serão definidos conforme uma implementação concreta.

## Trabalhar com um assistente

Use o repositório como contexto da tarefa e descreva o resultado que deseja. Quando o agente utilizado oferece suporte a `AGENTS.md`, ele pode carregar essas orientações conforme as regras da ferramenta. Em outros chats, forneça explicitamente os arquivos relevantes; o conteúdo do GitHub não se torna memória automática de toda conversa.

Mantenha decisões duráveis em [docs/CONTEXTO.md](docs/CONTEXTO.md). Atualize o documento quando surgirem código, comandos ou uma arquitetura real.

## Arquivos locais

O `.gitignore` exclui padrões comuns de credenciais, dependências e arquivos temporários. Ele não remove segredos já publicados. O `.editorconfig` padroniza codificação e finais de linha para editores compatíveis.

## Limites

Este repositório é público. Use apenas dados de exemplo ou anonimizados. Sua configuração organiza o trabalho do projeto e não modifica a extensão oficial do ChatGPT nem corrige automaticamente a conexão com o Chrome.

## Referência

A estrutura favorece instruções curtas e contexto específico do projeto, conforme a [orientação oficial da OpenAI sobre instruções para agentes](https://developers.openai.com/blog/rethinking-skills-and-prompts-for-gpt-6-astra).
