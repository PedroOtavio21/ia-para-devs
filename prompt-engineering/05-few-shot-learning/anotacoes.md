# Aula 05 - Técnicas avançadas - Few-Shot learning e exemplos no prompt

- Útil apra incluir exemplos de entrada + saída no prompt
- Ajuda a IA a entender o formato, padrão e estilo esperado
- Contrasta com Zero-Shot: onde damos só a instrução, sem exemplo nenhum
- É como dizer: "Veja como fiz nos exemplos. Agora faça o mesmo com este outro caso."

## Exemplo 1:

Você é um formatador de JSON (Papel). Com base no exemplo, crie o JSON para o novo usuário (Pedido).

Entrada: (Exemplos)
- "Crie um usuário com nome Ana, idade 28 e e-mail ana@email.com"
Saída:
- {"nome": "Ana", "idade": 28, "email": "ana@email.com"}

Entrada: (Saída esperada)
- "Crie um usuário com nome Pedro, idade 25 e e-mail pedro@email.com"
Saída:
- ??

## Exemplo 2:

Você é um classificador de sentimento.
Classifique frases como Positivo, Negativo ou Neutro.

Exemplo 1:
- Frase: "Eu adoro este produto, é excelente!"
- Saída: Positivo

Exemplo 2:
- Frase: "Estou muito decepcionado, estragou rápido."
- Saída: Negativo

- Frase: "O produto é ok, nada de especial."
- Saída: ??