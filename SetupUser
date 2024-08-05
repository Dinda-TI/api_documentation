
### Autenticar 
Url: https://api.appdinda.com.br/v1/api/authenticate

Com a **chave(key)** do cliente fornecida pela DINDA siga os passos abaixo.

Enviar no **Header** da chamada os seguintes parametros:
```javascript {.line-numbers}
Content-Type: application/json
```

Enviar o json abaixo:
```javascript {.line-numbers}
{
  "key":"KEY_DO_CLIENTE"
}
```

Você receberá um retorno de um token, ele tem validade de **30 minutos** a partir da obtenção do mesmo, ou seja, sempre que for necessário repita a chamada de autheticacao renovar o token.
```javascript {.line-numbers}
{
    "token": "xxxxxxxxxxxxxxxxx",
    "expired": "xxxxxxxxxx"
}
```
# Setup User
API responsável em enviar a estrutura de configuração do usuário para plataforma Dinda

### SetupUser
Url: https://api.appdinda.com.br/v1/api/setupuser

Enviar no **Header** da chamada os seguintes parametros:
```javascript {.line-numbers}
Content-Type: application/json
Authorization: Bearer AQUI_VAI_O_TOKEN
```
Enviar o json abaixo via **POST** 
```javascript {.line-numbers}
{
    
}
```
**Obs:** E-mails não formatados corretamente serão desconsiderados e não vinculados a captadores e proprieários. 

Se os dados estiverem ok o sistema retornará o seguinte JSON.
Exemplo de retorno:
```javascript {.line-numbers}
{
    "Code": 0,
    "Message": "OK",
    "Data": null
}
```
 
