
### SetupUser
Url: https://api.appdinda.com.br/v1/api/ia/setupuser

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
  "guid": "string", [PARAMETRO 'uid' mesmo do HEADER]
  "birthday": "2024-08-05T21:48:54.029Z",
  "gender": "string",
  "hasDependents": true,
  "familyName": "string",
  "groupFamily": [
    {
      "guid": "string", [OPTIONAL - Quando for atualização informar]
      "firstName": "string",
      "lastName": "string",
      "gender": "string",
      "birthday": "2024-08-05T21:48:54.029Z",
      "profileType": "string",  [RESPONSAVEL / FUNCIONARIO / DEPENDENTE]
      "phone": "string", [Se (RESPONSAVEL / FUNCIONARIO) Obrigatório]      
      "responsableType": "string",  [OPTIONAL]
      "dependentType": "string",  [OPTIONAL]
      "functionType": "string",  [OPTIONAL]
      "specialNeeds": true  [OPTIONAL]
    }
  ]
}
```
 

Se os dados estiverem ok o sistema retornará o seguinte JSON.
Exemplo de retorno:
```javascript {.line-numbers}
{
   
}
```
 
