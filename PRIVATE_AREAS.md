# Áreas restritas

Este repositório separa algumas áreas como restritas:

- JavaScript
- TypeScript
- SQL

Isso não cria privacidade real dentro de um repositório público. O GitHub não possui “pasta privada” dentro de repositório público.

A estratégia correta é:

1. Não colocar código sensível nessas pastas.
2. Usar READMEs públicos apenas para descrição geral.
3. Ignorar arquivos privados com `.gitignore`.
4. Criar outro repositório privado para código realmente sensível.
5. Publicar apenas versões demonstrativas, limpas e seguras.

## Regra prática

Se o arquivo contém token, senha, chave, endpoint privado, banco real ou lógica que não deve ser exposta, ele não deve entrar neste repositório.
