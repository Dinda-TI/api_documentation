
### Lista de Responsáveis
Url: https://api.appdinda.com.br/v1/api/ia/GetResponsables

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
            "guidId": "3828e313-9ecf-4f55-987d-deb66be4a94c",
            "kinship": "",
            "firstName": "Leandro",
            "lastName": "Costa",
            "initials": "LC",
            "birthDay": "2022-08-06T00:00:00",
            "birthDayFmt": "1 ano",
            "checked": true,
            "relationType": "RESPONSAVEL"
        },
        {
            "guidId": "f2e5b8e6-3259-4034-bff8-a2ac31dca9d4",
            "kinship": "",
            "firstName": "Mara",
            "lastName": "Helena",
            "initials": "MH",
            "birthDay": "1956-04-13T00:00:00",
            "birthDayFmt": "68 anos",
            "checked": true,
            "relationType": "RESPONSAVEL"
        }
    ]
}
```
 
