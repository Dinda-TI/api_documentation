
### Lista de Funcionários
Url: https://api.appdinda.com.br/v1/api/ia/GetEmployees

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
            "guidId": "91bbe89e-e1bb-477e-987d-74f2ffe25074",
            "kinship": "",
            "firstName": "Marta",
            "lastName": "Silva",
            "initials": "MS",
            "birthDay": "1950-04-13T00:00:00",
            "birthDayFmt": "74 anos",
            "checked": true,
            "relationType": "FUNCIONARIO"
        },
        {
            "guidId": "efaf3b5c-d52e-482d-be5d-0e9dcad9111f",
            "kinship": "",
            "firstName": "Teste1",
            "lastName": "Last01",
            "initials": "TL",
            "birthDay": "2000-08-06T00:00:00",
            "birthDayFmt": "23 anos",
            "checked": true,
            "relationType": "FUNCIONARIO"
        }
    ]
}
```
 
