
### Enviando dados do questionoario
Url: [https://api.appdinda.com.br/v1/api/ia/SendQuestion](https://n8n.7bot.ai/webhook/8516fc7a-ddfe-445c-975d-2425521b7700)

 

Enviar o json abaixo via **POST** 
```javascript {.line-numbers}
{
  "AccountId": "05abbdb8-b453-4e06-9e35-cc79425f3460",
  "UserId": "3828e313-9ecf-4f55-987d-deb66be4a94c",
  "Guid": "bb14d64e-9bc9-4ffb-ae67-97f876f39de9",
  "Data": {
    "Id": 1,
    "TypeName": "DEPENDENTE",
    "TypeCode": "BEBE",
    "Description": "Bebê - 0 a 3 anos",
    "OrderNumber": 1,
    "QuestionItems": [
      {
        "Id": 1,
        "BaseId": 1,
        "Question": "Utiliza fralda?",
        "QuestionType": 1,
        "OrderNumber": 1,
        "QuestionItemOptions": [
          {
            "Id": 1,
            "ItemId": 1,
            "OptionName": "Sim",
            "OptionChecked": true,
            "OptionText": "",
            "OrderNumber": 1,
            "TypeId": 1
          }
        ]
      },
      {
        "Id": 2,
        "BaseId": 1,
        "Question": "Utiliza chupeta?",
        "QuestionType": 1,
        "OrderNumber": 2,
        "QuestionItemOptions": [
          {
            "Id": 4,
            "ItemId": 2,
            "OptionName": "Não",
            "OptionChecked": true,
            "OptionText": "",
            "OrderNumber": 2,
            "TypeId": 1
          }
        ]
      },
      {
        "Id": 3,
        "BaseId": 1,
        "Question": "Utiliza mamadeira?",
        "QuestionType": 1,
        "OrderNumber": 3,
        "QuestionItemOptions": [
          {
            "Id": 6,
            "ItemId": 3,
            "OptionName": "Não",
            "OptionChecked": true,
            "OptionText": "",
            "OrderNumber": 2,
            "TypeId": 1
          }
        ]
      },
      {
        "Id": 4,
        "BaseId": 1,
        "Question": "Faz visitas regulares a especialistas médicos?",
        "QuestionType": 1,
        "OrderNumber": 4,
        "QuestionItemOptions": [
          {
            "Id": 7,
            "ItemId": 4,
            "OptionName": "Sim",
            "OptionChecked": true,
            "OptionText": "",
            "OrderNumber": 1,
            "TypeId": 1
          }
        ]
      },
      {
        "Id": 5,
        "BaseId": 1,
        "Question": "Frequenta creche?",
        "QuestionType": 1,
        "OrderNumber": 5,
        "QuestionItemOptions": [
          {
            "Id": 11,
            "ItemId": 5,
            "OptionName": "Semi-integral",
            "OptionChecked": true,
            "OptionText": "",
            "OrderNumber": 3,
            "TypeId": 1
          }
        ]
      }
    ]
  }
}
```
 

 
