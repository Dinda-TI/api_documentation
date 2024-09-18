
### SaveSuggestList
Url: https://api.appdinda.com.br/v1/api/ia/saveSuggestList

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
  "accountId": "05abbdb8-b453-4e06-9e35-cc79425f3460",
  "userId": "3828e313-9ecf-4f55-987d-deb66be4a94c",
  "userType":"DEPENDENTE",
  "name": "Nova lista",  
  "list": [     
    {          
      "name": "Lista 101",
      "items":[
        {
            "name": "item 101"
        },
        {
            "name": "item 102"
        },
        {
            "name": "item 103"
        },
        {
            "name": "item 104"
        }
      ]
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
 
