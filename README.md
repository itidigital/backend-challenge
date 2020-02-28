# Descrição
Considere uma senha sendo válida quando a mesma possuir as seguintes definições:
- Nove ou mais caracteres
- Ao menos 1 dígito
- Ao menos 1 letra minúscula
- Ao menos 1 letra maiúscula
- Ao menos 1 caractere especial

Exemplo:  
```
IsValid("") -> false  
IsValid("aa") -> false  
IsValid("ab") -> false  
IsValid("AAAbbbCc") -> false  
IsValid("AbTp9!foo") -> true  
```

## Problema
Construa uma aplicação que exponha uma api web que valide se uma senha é válida.

Input: Uma senha (string).  
Output: Um boolean indicando se a senha é válida.

Você pode fazer na linguagem de programação que considera ter mais conhecimento.

# Pontos que daremos maior atenção
Queremos que você escreva essa solução pensando que ao nos enviar ela estará "pronta para produção". Alguns itens que serão avaliados são:

- Testes de unidade / integração
- Abstração, acoplamento e coesão
- Design de API
- Clean Code
- SOLID

# Para nos enviar a solução
Sua solução deve possuir um README com instruções básicas de como executá-la.

Fique à vontade para explicar no readme qualquer decisão técnica que tenha tomado e considere importante.
