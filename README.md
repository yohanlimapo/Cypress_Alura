Olá! Seja muito bem vindo!!

:construction: Ainda está em construção este projeto :construction:

Este projeto é com base na aula da Alura para aprender a fazer automação de testes utilizando o Cypress, após aprender a usar, levarei para a empresa atual com alguns testes já realizados.

Beleza, Yohan. E como eu faço para ver funcionando aqui no meu PC?

Antes de mais nada você precisa utilizar este comando para inicializar o arquivo package.json
        npm init

Após isto agora é só rodar os testes! E para isso você pode usar dois comandos:
        npm run test
ou
        npx cypress open

Para rodar os testes, sem abrir a interface do Cypress, basta digitar o comando:
        npx cypress run
E provavelmente vai ficar visualmente feio, para isso você pode utilizar uma biblioteca para deixar mais bonito. No caso utilizamos o mochawesome. Para tanto escreva:
        npx cypress run --reporter mochawesome

Se porventura não vier a funcionar, talvez lhe seja necessário baixar a biblioteca, para isto, baixe utilizando o comando:
        npm i -D mochawesome