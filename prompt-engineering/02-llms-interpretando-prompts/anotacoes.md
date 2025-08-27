# Aula 02 - Como os LLMs interpretam um prompt

- O prompt é transformado em tokens (ex.: palavras, símbolos, pedaços de texto)
- O modelo analisa os tokens dentro de uma janela de contexto (limite de memória)
- Ele prevê o próximo token mais provável com base nos anteriores

## Prática

Prompt vago:
- "Liste funções importantes do JavaScript"

Prompt específico:
- "Liste 5 funções do JavaScript úteis para manipulação de arrays, com exemplos."

### Salve a Dica!

O que você coloca no início do prompt influencia tudo
- Ex.: "Você é um Sênior em JS" -> IA assume tom mais técnico e direto