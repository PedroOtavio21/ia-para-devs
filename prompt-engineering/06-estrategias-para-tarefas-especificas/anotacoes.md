# Aula 06 - Técnicas avançadas - Estratpegias para tarefas específicas com IA

## 1. Geração de Código

Use prompts específicos e completos:
- Linguagem (ex.: TypeScript, Python, etc.)
- Nome da função / comportamento esperado
- Restrições, tipo de retorno, estrutura de código
- Pedir explicação ou comentários, se necessário 

### Exemplo:

Você é um desenvolvedor senior expecialista em TypeScript
Implemente em TypeScript a função `removerDuplicatas(arr: number[]): number[]`
Ela deve retornar um novo array sem valores repetidos, mantendo a ordem
Explique brevemente sua abordagem
Coloque comentários sobre o funcionamento

## 2. Depuração de código/debugging

- Fornecer o código que causou o problema
- Explicar o que você está tentando fazer e quando o erro ocorreu
- Fornecer contexto (erros, logs, prints)

### Exemplo:

- Você é um desenvolvedor sênior em JavaScript
- Estou tentando somar os valores de um array, mas o resultado não está correto
- O código abaixo deveria retornar 10 (1 + 2 + 3 + 4), mas retorna NaN
- Por favor, analise o código, identifique o erro e proponha uma correção
- Também explique passo a passo o que está acontecendo:

## 3. Documentação e Explicação

- Diga que o modelo deve documentar ou explicar o código
- Defina o formato da explicação:
    - Linha a linha?
    - Docstring?
    - Markdown?

### Exemplo:

- Explique detalhadamente o que a seguinte função faz
- Comente o código linha a linha e depois escreva um resumo final sobre a utilidade dessa função
    - O público-alvo é iniciante em JavaScript