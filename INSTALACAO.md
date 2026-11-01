# Instalação

Escolha o assistente que você já usa. Os recursos de projetos, Gems, GPTs e skills dependem do plano e da versão do app. Confira no seu app o que está disponível.

Antes de tudo, lembre das regras: não cole senha, cartão nem dado de cliente, e leia o que a IA escrever antes de mandar.

## 1. Claude Code

Para quem usa o Claude no computador, pelo terminal.

1. Baixe ou clone este repositório.
2. Para valer em todos os projetos, copie a pasta `.claude/skills/mei` para `~/.claude/skills/mei`.
3. Para valer só em um projeto, copie para a pasta `.claude/skills/mei` dentro dele.
4. Abra o Claude Code e escreva, por exemplo: "Sou MEI e preciso de ajuda com a guia mensal." A skill é ativada sozinha.

## 2. App Claude (site e celular)

Opção A, a mais simples: um Projeto. Se o app do celular não mostrar Projetos, crie pelo navegador e use no celular depois.

1. Abra o Claude e entre em Projetos.
2. Crie um projeto e dê o nome "Ajuda para MEI".
3. Abra as instruções do projeto.
4. Abra o arquivo `instrucoes/claude-projeto.md`, copie o texto abaixo da linha e cole nas instruções.
5. Salve. Toda conversa nova dentro desse projeto já vem com as regras.

Opção B: em alguns planos dá para enviar a pasta `mei` compactada em zip, com o `SKILL.md` dentro dela.

1. No computador, compacte a pasta `mei` (a que contém `SKILL.md` e `referencias`) em um arquivo zip.
2. Procure "Skills" nas configurações do Claude. Essa área pode não existir no celular nem no seu plano.
3. Se existir, envie o zip e ative a skill.

## 3. ChatGPT

Opção A: GPT personalizado ou Projeto.

1. Abra `instrucoes/chatgpt.md` e copie o texto da versão A.
2. No ChatGPT, crie um GPT personalizado ou um Projeto, se o seu plano permitir.
3. Cole o texto no campo de instruções.
4. Salve e converse dentro dele.

Opção B: instruções personalizadas, que valem para todas as conversas.

1. Copie o texto da versão B.
2. Procure a opção de personalização nas configurações. O nome do campo muda com a versão do app.
3. Cole o texto no campo de instruções e salve.

## 4. Gemini

1. Abra `instrucoes/gemini-gem.md` e copie o texto abaixo da linha.
2. No Gemini, abra a lista de Gems e crie uma nova.
3. Dê o nome "Ajuda para MEI" e cole o texto no campo de instruções.
4. Salve e converse com a Gem.

## Dica para o celular

Sem computador por perto, abra este repositório no navegador do celular, toque no arquivo de `instrucoes/` que você precisa, copie o texto e cole no app. Se não conseguir copiar, mande o arquivo para você mesmo por e-mail e copie de lá.

## Teste de uma semana

Use por uma semana numa tarefa só. Se não sentir diferença, não precisa pagar plano nenhum.
