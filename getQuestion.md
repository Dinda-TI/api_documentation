
### Obter dados do questionoario
Url: https://api.appdinda.com.br/v1/api/ia/GetQuestion

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
{
    "objectGuid":"bb14d64e-9bc9-4ffb-ae67-97f876f39de9",
    "objectType":"DEPENDENTE"
}

Se os dados estiverem ok o sistema retornará o seguinte JSON.
Exemplo de retorno:
```javascript {.line-numbers}
{
    "status": 200,
    "data": {
        "accountId": "05abbdb8-b453-4e06-9e35-cc79425f3460",
        "userId": "3828e313-9ecf-4f55-987d-deb66be4a94c",
        "guid": "bb14d64e-9bc9-4ffb-ae67-97f876f39de9",
        "data": {
            "id": 1,
            "typeName": "DEPENDENTE",
            "typeCode": "BEBE",
            "description": "Bebê - 0 a 3 anos",
            "orderNumber": 1,
            "questionItems": [
                {
                    "id": 1,
                    "baseId": 1,
                    "question": "Utiliza fralda?",
                    "questionType": 1,
                    "orderNumber": 1,
                    "questionItemOptions": [
                        {
                            "id": 1,
                            "itemId": 1,
                            "optionName": "Sim",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 1,
                            "typeId": 1
                        },
                        {
                            "id": 2,
                            "itemId": 1,
                            "optionName": "Não",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 2,
                            "typeId": 1
                        }
                    ]
                },
                {
                    "id": 2,
                    "baseId": 1,
                    "question": "Utiliza chupeta?",
                    "questionType": 1,
                    "orderNumber": 2,
                    "questionItemOptions": [
                        {
                            "id": 3,
                            "itemId": 2,
                            "optionName": "Sim",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 1,
                            "typeId": 1
                        },
                        {
                            "id": 4,
                            "itemId": 2,
                            "optionName": "Não",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 2,
                            "typeId": 1
                        }
                    ]
                },
                {
                    "id": 3,
                    "baseId": 1,
                    "question": "Utiliza mamadeira?",
                    "questionType": 1,
                    "orderNumber": 3,
                    "questionItemOptions": [
                        {
                            "id": 5,
                            "itemId": 3,
                            "optionName": "Sim",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 1,
                            "typeId": 1
                        },
                        {
                            "id": 6,
                            "itemId": 3,
                            "optionName": "Não",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 2,
                            "typeId": 1
                        }
                    ]
                },
                {
                    "id": 4,
                    "baseId": 1,
                    "question": "Faz visitas regulares a especialistas médicos?",
                    "questionType": 1,
                    "orderNumber": 4,
                    "questionItemOptions": [
                        {
                            "id": 7,
                            "itemId": 4,
                            "optionName": "Sim",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 1,
                            "typeId": 1
                        },
                        {
                            "id": 8,
                            "itemId": 4,
                            "optionName": "Não",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 2,
                            "typeId": 1
                        }
                    ]
                },
                {
                    "id": 5,
                    "baseId": 1,
                    "question": "Frequenta creche?",
                    "questionType": 1,
                    "orderNumber": 5,
                    "questionItemOptions": [
                        {
                            "id": 9,
                            "itemId": 5,
                            "optionName": "Não",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 1,
                            "typeId": 1
                        },
                        {
                            "id": 10,
                            "itemId": 5,
                            "optionName": "Meio período",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 2,
                            "typeId": 1
                        },
                        {
                            "id": 11,
                            "itemId": 5,
                            "optionName": "Semi-integral",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 3,
                            "typeId": 1
                        },
                        {
                            "id": 12,
                            "itemId": 5,
                            "optionName": "Integral",
                            "optionChecked": false,
                            "optionText": "",
                            "orderNumber": 4,
                            "typeId": 1
                        }
                    ]
                }
            ]
        }
    }
}
```
 
