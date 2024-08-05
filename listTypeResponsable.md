
### Lista de responsáveis
Url: https://api.appdinda.com.br/v1/api/config/ListTypeResponsable

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
            "text": "Afilhado(a)",
            "value": "11"
        },
        {
            "text": "Avô(ó)",
            "value": "6"
        },
        {
            "text": "Esposo(a)",
            "value": "5"
        },
        ......
    ]
}
```
 
