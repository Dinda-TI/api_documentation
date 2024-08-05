
### Lista dos funcionários
Url: https://api.appdinda.com.br/v1/api/config/ListTypeEmployee

Enviar no **Header** da chamada os seguintes parametros:
```javascript {.line-numbers}
Content-Type: application/json
Authorization: Bearer AQUI_VAI_O_TOKEN
```
Chamada via **GET** 

Se os dados estiverem ok o sistema retornará o seguinte JSON.
Exemplo de retorno:
```javascript {.line-numbers}
{
    "status": 200,
    "data": [
         {
            "text": "Acompanhante de Idosos",
            "value": "1"
        },
        {
            "text": "Arrumadeira",
            "value": "2"
        },
        ......
    ]
}
```
 
