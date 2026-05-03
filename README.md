![status](https://img.shields.io/badge/status-online-brightgreen)
![.NET](https://img.shields.io/badge/.NET-API-blue)

# API-Login

## Link da API:
api-login-genius.up.railway.app

[Clique aqui](https://api-login-genius.up.railway.app/swagger) para testar a api.

## Sobre
Este projeto é uma API de Login onde a aplicação faz duas coisas principais:
1. Registra as credenciais do usuário
2. Valida o acesso caso esteja registrado

A aplicação possui criptografia de senhas e autenticação via token,
além da integração com MySQL, tudo de forma acessível ao público.

## Recursos utilizados
* ASP.NET Core
* JWT (JSON Web Token)
* MySQL
* Railway (deploy)

## Autenticação
A API usa o JWT para autenticar o usuário. Após o login, é gerado um token JWT próprio

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
