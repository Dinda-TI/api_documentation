
### Obter dados do usuário
Url: https://api.appdinda.com.br/v1/api/ia/GetUser

Enviar no **Header** da chamada os seguintes parametros:

    Parametros: aid = accountId
                uid = userId
```javascript {.line-numbers}
Content-Type: application/json
Authorization: Bearer AQUI_VAI_O_TOKEN
Header: aid <value>
        uid <value>  
```
Chamada via **GET** 

Se os dados estiverem ok o sistema retornará o seguinte JSON.
Exemplo de retorno:
```javascript {.line-numbers}
{
    "status": 200,
    "data": [
        {
            "guidId": "656f2477-09f3-47a0-b82d-a89da3b26d01",
            "birthDay": "2020-04-13T00:00:00",
            "gender": "M",
            "familyName": "Souzas",
            "firstName": "Joao",
            "lastName": "Souza",            
            "email": "joao.souza@teste.com"
        }
    ]
}
```
 
