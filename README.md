# Descrição
Considere uma senha sendo válida quando a mesma possuir as seguintes definições:
- Nove ou mais caracteres
- Ao menos 1 dígito
- Ao menos 1 letra minúscula
- Ao menos 1 letra maiúscula
- Ao menos 1 caractere especial
- Não possuir caracteres repetidos

Exemplo:  
```
IsValid("") -> false  
IsValid("aa") -> false  
IsValid("ab") -> false  
IsValid("AAAbbbCc") -> false  
IsValid("AbTp9!foo") -> false  
IsValid("AbTp9!fok") -> true
```

## Problema
Construa uma aplicação que exponha uma api web que valide se uma senha é válida.

Input: Uma senha (string).  
Output: Um boolean indicando se a senha é válida.

Embora nossas aplicações sejam escritas em Kotlin e C# (.net core), você não precisa escrever sua solução usando elas. Use a linguagem de programação que considera ter mais conhecimento.

# Pontos que daremos maior atenção
Queremos que você escreva essa solução pensando que ao nos enviar ela estará "pronta para produção". Alguns itens que serão avaliados são:

- Testes de unidade / integração
- Abstração, acoplamento, extensibilidade e coesão
- Design de API
- Clean Code
- SOLID

# Para nos enviar a solução
Nos envie o link de um repo público com a sua solução.

O repo deve possuir um README com instruções básicas de como executá-la.

Explique no README as decisões técnicas do design da aplicação. 
