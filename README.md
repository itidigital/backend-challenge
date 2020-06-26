# Descrição
Considere uma senha sendo válida quando a mesma possuir as seguintes definições:
- Nove ou mais caracteres
- Ao menos 1 dígito
- Ao menos 1 letra minúscula
- Ao menos 1 letra maiúscula
- Ao menos 1 caractere especial
- Não possuir caracteres repetidos dentro do conjunto

Exemplo:  
```
IsValid("") -> false  
IsValid("aa") -> false  
IsValid("ab") -> false  
IsValid("AAAbbbCc") -> false  
IsValid("AbTp9!foo") -> false  
IsValid("AbTp9!foA") -> false
IsValid("AbTp9!fok") -> true
```

> **_Nota:_**  Espaços em branco não devem ser considerados como caracteres especiais.

## Problema
Construa uma aplicação que exponha uma api web que valide se uma senha é válida.

Input: Uma senha (string).  
Output: Um boolean indicando se a senha é válida.

Embora nossas aplicações sejam escritas em Kotlin e C# (.net core), você não precisa escrever sua solução usando elas. Use a linguagem de programação que considera ter mais conhecimento.

# Pontos que daremos maior atenção
Alguns itens que serão avaliados são:

- Testes de unidade / integração
- Abstração, acoplamento, extensibilidade e coesão
- Design de API
- Clean Code
- SOLID
- Documentação no README da solução

# Para nos enviar a solução
Você tem um tempo limite de 10 dias para o envio da sua solução a partir da data que você recebeu o desafio. Esta etapa é eliminatória, e por isso esperamos que o código reflita essa importância.

Nos envie o link de um repo público com a sua solução.

O repo deve possuir um README com instruções básicas de como executá-la. 

Caso você assuma alguma premissa na sua solução adicione ela no README.

Não esqueça de nos contar um pouco sobre sua solução no README, gostariamos de saber qual foi seu racional nas suas decisões para a solução e se houveram premissas.
