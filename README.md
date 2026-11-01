# skill-mei

Ajuda para quem é MEI (microempreendedor individual) usar inteligência artificial no dia a dia. É a versão instalável das dicas de https://thalisantunes.com.br/mei/.

Funciona no Claude, no ChatGPT e no Gemini, inclusive pelo celular. Você instala uma vez e o assistente passa a falar simples, a ajudar em uma tarefa por vez e a não inventar número de imposto.

## Para quem

Para quem tem um negócio pequeno (ateliê, loja, salão, oficina, doceria) e não é da área de tecnologia. Também serve para autônomos.

## O que tem dentro

| Pasta ou arquivo | Para que serve |
|---|---|
| `.claude/skills/mei/SKILL.md` | A skill: como falar com o usuário, regras e roteiro por tarefa |
| `.claude/skills/mei/referencias/` | Um arquivo por tarefa: obrigações, WhatsApp, textos, anúncios, estoque, captura de ideias |
| `instrucoes/claude-projeto.md` | Texto para colar num Projeto do Claude |
| `instrucoes/chatgpt.md` | Texto para um GPT ou Projeto e versão curta para instruções personalizadas |
| `instrucoes/gemini-gem.md` | Texto para uma Gem do Gemini |
| `exemplos/` | Três conversas de exemplo |
| `INSTALACAO.md` | Passo a passo de cada destino |

## Instalação resumida

- **Claude Code**: copie a pasta `.claude/skills/mei` para `~/.claude/skills/` (todos os projetos) ou para a pasta `.claude/skills/` do seu projeto.
- **App Claude (site e celular)**: crie um Projeto e cole `instrucoes/claude-projeto.md` nas instruções. Como alternativa, compacte a pasta `mei` em zip e envie em Configurações, Skills. Depende do plano, confira no app.
- **ChatGPT**: cole `instrucoes/chatgpt.md` (versão A) num GPT personalizado ou num Projeto. A versão B vai nas instruções personalizadas.
- **Gemini**: crie uma Gem e cole `instrucoes/gemini-gem.md`.

Detalhes, com o celular em mente, em [INSTALACAO.md](INSTALACAO.md).

## O que esta skill não faz

Não traz valor de imposto, limite, vencimento nem prazo legal, porque mudam. Para isso o assistente manda você conferir no Portal do Empreendedor (gov.br/mei). Também não pede senha, CPF nem código de verificação.

## Contribuir

Achou erro ou quer sugerir uma tarefa nova? Abra uma issue neste repositório. Escreva em português, com frases simples, e diga qual assistente você usa.

## Licença

MIT. Veja o arquivo [LICENSE](LICENSE).
