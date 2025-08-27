# Aula 03 - Anatomia de um Prompt Eficaz

- Um bom prompt temcomponentes claros e bem definidos
- Ele orienta o modelo com precisão e evita respostas genéricas
- Use essa estrutura como um checklist:

## Checklist:

### 1. Contexto / Papel

- Defina o papel da IA para guiar o tom e o nível da resposta
- Ajuda o modelo a "entrar no personagem"
- Ex.: "Você é um desenvolvedor experiente em TypeScript"

### 2. Tarefa Objetiva

- Diga exatamente o que você quer que a IA faça
- Nada de pedidos vagos tipo "Me ajuda com código!"
- Ex.: "Crie uma função que calcule a média de uma lista de números"

### 3. Detalhes e Restrições

Especifique tecnologias, nomes de funções, regras ou formatos

Ex.:
- "A função deve ser feita em TypeScript, se chamar calcularMedia, tratar lista vazia e aceitar apenas números"

### 4. Instruções de saída

Diga como quer a resposta: código, explicação, lista, markdown, etc

Ex.:
- "Forneça o código completo e depois explique em 3 frases o passo-a-passo do funcionamento"

### 5. Exemplos (se necessário)

Inclua exemplos de entrada/saída se quiser guiar o modelo com mais precisão

Útil em tarefas com formatação, regras específicas ou estilo esperado

## Exemplos:

### 1:

Você é um desenvolvedor experiente em TypeScript
Crie uma função chamada `validarEmail(email: string): boolean` que verifique se o e-mail informado é valido
Use uma expressão regular simples, mas eficaz
A função deve retornar true se o e-mail for válido e false caso contrário
Inclua comentários no código explicando cada etapa
Depois, explique em 2 frases como a função funciona

### 2:

Você é um classificador de sentimento de frases curtas
Responda apenas com: Positivo, Negativo ou Neutro
Aqui estão alguns exemplos:
- Frase: 'O atendimento foi excelente!' -> Positivo
- Frase: 'Não gostei do produto, veio com defeito.' -> Negativo
- Frase: 'Chegou no prazo, mas nada demais.' -> Neutro
Agora classifique:
- Frase: 'O serviço atendeu às minhas espectativas' -> ...