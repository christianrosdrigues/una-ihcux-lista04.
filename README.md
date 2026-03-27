O que é try-catch?

O try-catch é uma estrutura utilizada em programação para tratar erros (exceções) que podem ocorrer durante a execução do programa.

- O bloco `try` contém o código que pode gerar erro.
- O bloco `catch` captura o erro e permite mostrar uma mensagem amigável ao usuário.
- O `finally` sempre é executado, independentemente de erro ou não.

Relação com UX (Experiência do Usuário)

Este programa aplica a heurística de Nielsen de **Prevenção de Erros**, evitando que o sistema quebre quando o usuário digita dados inválidos.

Em vez de mostrar um erro técnico, o sistema informa claramente o problema e orienta o usuário a corrigir.

Exemplo

- Entrada válida: sucesso
- Entrada inválida: mensagem amigável

## 📸 Evidência
![Execução do sistema](./Impressão 01 (Caminho Feliz.jpeg))
![Execução do sistema](./Imprimir 02 (Caminho do Erro.jpeg))
