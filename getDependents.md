
### Lista de Dependentes
Url: https://api.appdinda.com.br/v1/api/ia/GetDependents

Enviar no **Header** da chamada os seguintes parametros:
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
            "kinship": "Sobrinha",
            "firstName": "Antonia",
            "lastName": "Soares",
            "initials": "AS",
            "birthDay": "2020-04-13T00:00:00",
            "birthDayFmt": "4 anos",
            "checked": true,
            "relationType": "DEPENDENTE"
        },
        {
            "guidId": "234f2477-09f3-47a0-b82d-a89da3b26d03",
            "kinship": "Afilhado",
            "firstName": "Pedro",
            "lastName": "Martins",
            "initials": "PM",
            "birthDay": "2020-08-13T00:00:00",
            "birthDayFmt": "4 anos",
            "checked": true,
            "relationType": "DEPENDENTE"
        }
    ]
}
```
 
