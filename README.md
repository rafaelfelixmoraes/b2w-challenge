# Desafio Backend BIT - SP

## Task 1

### Backend Challenge

Projeto desenvolvido com as seguintes tecnologias:

  - Java 8
  - Framework Spring (boot, mvc)

Para executar o projeto, siga os seguintes passos:

- Realize o clone do repositório dentro da IDE desejada(pessoalmente prefiro o STS =P) e em seguida acesse Arquivo/Importar, selecione a opção Maven/Existing Maven Projects, na próxima tela aponte para o diretório para onde foi feito o clone do projeto do git, e no final clique em Finalizar.

- Em seguida, realize o build do projeto, Clique com o botão direito do mouse sobre a pasta do projeto e navegue até Maven > Update Project. Na próxima tela, clique em OK e aguarde o build do projeto.

- Abra o package com.rafaelfelix.b2wchallenge; 

- Clique na classe B2wChallengeApplication.java 

- Clique com o botão direito do mouse  e navegue para Run As > Java Application. No console, Aguarde o servidor subir, enquanto isso abra o browser (IE, Firefox, Chrome). 

- Após o servidor subir, acesse o endereço: http://localhost:8080/challenge-backend/item?begindate=05-10-2016&finaldate=10-10-2016

- O retorno são os dados consumidos da API de serviço no formato Json conforme <b>response</b> abaixo, filtrados conforme parametros da URL acima.

<b>OBS.: Os parâmetros begindate (data) e finaldate (data) devem ser informados no formato dd-MM-yyyy</b>

#### Response
```
[
  {
    "name": "Impressora",
    "code": "5",
    "date": "2016-10-05T14:30:37.040Z",
    "dimension": {
      "weight": 10.5,
      "height": 10.5,
      "width": 10.5,
      "length": 10.5
    }
  },
  {
    "name": "Fifa2017",
    "code": "6",
    "date": "2016-10-06T14:30:37.040Z",
    "dimension": {
      "weight": 10.5,
      "height": 10.5,
      "width": 10.5,
      "length": 10.5
    }
  },
  .
  .
  .
]
```

## Task 2

### MySQL Challenge

A Resolução da task 2 se encontra dentro do diretório "resolution_task2", na raiz do repositório. Ela possui o arquivo .sql com a query desenvolvida para atender o desafio, juntamente com uma planilha contendo os resultados obtidos pela execução da query nos 4 databases disponibilizados.

## Autor

### Rafael Felix de Moraes. All Rights Reserved

### <a href="mailto:rafaelfelix1433@gmail.com?Subject=Java%20B2W" target="_top">Envie-me um e-mail</a>


