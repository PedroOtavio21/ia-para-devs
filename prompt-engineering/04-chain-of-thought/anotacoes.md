# Aula 04 - Técnicas avançadas - Chain Of Tought

## Chain-Of-Thought: Raciocínio passo a passo

- Técnica que força o modelo a pensar em etapas
- Em vez de dar a resposta direto, ele mostra o caminho do raciocínio
- Aumenta a clareza, confiabilidade e explicação da resposta

### Como aplicar no Prompt

Use instruções como:
- "Pense passo a passo"
- "Vamos por partes"
- "Explique seu raciocínio antes da resposta final"

### Exemplo:

Você é um desenvolvedor expecialista em TypeScript. (Papel da IA)
Preciso de uma função que verifique se uma string é um palíndromo. (Pedido)
Vamos resolver passo a passo: (Explicação de pedido)

1. Explique o que é um palíndromo
2. Descreva a lógica que será usada
3. Implemente a função `isPalindromo(str: string): boolean`
4. Explique o que o código faz 