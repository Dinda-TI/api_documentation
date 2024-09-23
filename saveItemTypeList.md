
### SaveItemTypeList
Url: https://api.appdinda.com.br/v1/api/ia/saveItemTypeList

Enviar no **Header** da chamada os seguintes parametros:

    Parametros: aid = accountId
                uid = userId
```javascript {.line-numbers}
Content-Type: application/json
Authorization: Bearer AQUI_VAI_O_TOKEN
Header: aid <value>
        uid <value>  
```

Enviar o json abaixo via **POST** 
```javascript {.line-numbers}
{
  "code": 100002,  
  "userName": "Leandro",
  "userNumber": "5551993385697",
  "items": [     
    {
        "name": "ITEM UPDATE 01",
        "status" : true
    },
    {
        "name": "ITEM UPDATE 02",
        "status" : true
    }
  ]
}
```
 

Se os dados estiverem ok o sistema retornará o seguinte JSON.
Exemplo de retorno:
```javascript {.line-numbers}
{
   "status": 200
   "data": true
}
```
 
