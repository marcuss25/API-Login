![status](https://img.shields.io/badge/Desligado-gray)

# Genius API
_Desenvolvido por: Marcus_

_Desenvolvido por: marcuss25_

**Tenha cuidado ao utilizar o código. Ajuste-o da sua maneira antes de usar em algum projeto.**

## Sobre
Genius é uma API de Login, onde a aplicação faz duas coisas principais:
1. Registra as credenciais do usuário
2. Valida o acesso caso esteja registrado

ela também possui criptografia de senhas e autenticação via token,
além da integração com MySQL, tudo de forma acessível ao público.

Atualmente, o projeto já foi desligado da nuvem, mas o código fonte vai permanecer aberto para quem desejar utilizar.

## Recursos utilizados
* ASP.NET Core
* JWT (JSON Web Token)
* MySQL
* ~~Railway (deploy)~~

## Autenticação
A API usa o JWT para autenticar o usuário. Após o primeiro login, é gerado um token próprio que é vinculado ao usuário no banco de dados. 

## Endpoints:
### /register
Exemplo:  
{  
 name: Marcus  
 surname: Admin  
 email: marcus_admin@email.com  
 password: admin1234  
}

Resultado:
<img width="546" height="102" alt="Screenshot from 2026-05-03 18-46-53" src="https://github.com/user-attachments/assets/a7382aa6-5ce2-40fd-9948-33f514637d54" />

### /login
Exemplo:  
{  
 email: marcus_admin@email.com  
 password: admin1234  
}

Resultado:
<img width="1180" height="133" alt="Screenshot from 2026-05-03 18-51-46" src="https://github.com/user-attachments/assets/54dcced0-0a54-4bdc-9960-095b3a16b51b" />
