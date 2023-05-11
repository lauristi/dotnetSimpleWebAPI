# Console app

O objetivo dessa app foi o de demonstrar a construcao de uma app simples
com boas praticas para utilização de testes unitários.

##### O enunciado original foi retirado de um teste de programação da empresa Localiza, mas
Foram feitas certas implementacoes com adição de testes unitários


### Teste .Net Core / Node.js

##### 1	Propósito

O Objetivo do teste proposto é avaliar as competências técnicas dos candidatos a posições de Software Engineer da Unidas.

##### 2	O problema 
Construa uma aplicação que exponha uma api web que valide se uma senha é válida.
Você tem a liberdade de construir da maneira que julgar mais adequada, desde que se atente ao conjunto de regras e ao que se espera como entregável.

##### 2.1	Regras:

Escreva sua solução usando C# (.net core) ou Nodejs.

Input: Uma senha (string).
Output: Um boolean indicando se a senha é válida.

Para uma senha ser válida ela deve atender as seguintes regras:
- Nove ou mais caracteres
- Ao menos 1 dígito
- Ao menos 1 letra minúscula
- Ao menos 1 letra maiúscula
- Ao menos 1 caractere especial
- Considere como especial os seguintes caracteres: !@#$%^&*()-+
- Não possuir caracteres repetidos dentro do conjunto

IsValid("") // false 
IsValid("aa") // false 
IsValid("ab") // false 
IsValid("AAAbbbCc") // false 
IsValid("AcZp7*baar") // false 
IsValid("AcZp7*baAr") // false
IsValid("AcZp7 bar") // false
IsValid("AcZp7*bar") // true

##### 2.2	O que avaliaremos

•	Abstração, acoplamento, extensibilidade e coesão
•	Design de API
•	Clean Code
•	SOLID

