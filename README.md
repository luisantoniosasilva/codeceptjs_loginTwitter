﻿# codeceptjs_loginTwitter
Uma aplicação de teste automatizado na plataforma web do Twitter desenvolvida com o framework [CodeceptJS](https://codecept.io/).

## Observação ⚠
Neste projeto poderá conter algumas informações divergentes e más práticas referente ao framework devido ao fato de eu estar iniciando o estudos a respeito do CodeceptJS
 
 ## Sobre
Este projeto está sendo desenvolvido como meio de estudo do framework [CodeceptJS](https://codecept.io/). Um framework de teste end to end com uma sintaxe similar ao BDD (Behavior Driven Development).
Para este projeto foi utilizado o helper do WebDriver.
 
 ## Estrutura
 Este projeto utiliza em sua estrutura o BDD e o PageObjects, dessa forma sua estrtura consiste em:
 -> .\features: Onde está localizado nosso cenário de teste escrito em gherkin
 -> .\pages: Onde está localizado o mapeamento de elementos e os métodos que serão utilizados
 -> .\step_definitions: Onde está localizado a escrita dos nossos steps
 
 ## Execução
 Para execução desse projeto se faz necessário:
 1. Clonar este projeto em sua máquina com ``git clone``
 2. no arquivo .\features\basic.feature modificar a informação de "user" e "password" para uma informação válida a modo que o login seja executado com êxito
 3. Executar o comando ``npx codeceptjs run --features --steps``
