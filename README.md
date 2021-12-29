# API-your-blog-pessoal 

> Esta API REST foi desenvolvida enquanto eu estava participando do bootcamp da Generation Brasil (Java Web Full Stack). Implementei alguns campos para uma melhor imersão durante o consumo com o Angular.
> Se trata, acima de tudo, de um CRUD (Create, Read, Update, Delete)

## Projeto feito com três entidades (Models) que se relacionam de tal maneira:
<img src='https://i.imgur.com/KO5K6G5.png'>

## Tecnologias usadas no desenvolvimento: 
<table>
  <tr>
    <td>Java</td>
    <td>Spring</td>
    <td>MySQL</td>
  </th>
  <tr>
    <td>11</td>
    <td>2.5.6</td>
    <td>8.0</td>
  </th>
</table>

## Como executar o aplicativo localmente:
- No arquivo *application.properties* que fica em 'src/main/resources', e altere de *'prod'* para *'dev'*;
- Certifique-se que no arquivo *application-dev.properties* seu *username* e *password* sejam válidos para que seja possível o acesso ao MySQL (altere caso necessário)
- Feito isso, vá no arquivo *BlogPessoalApplication.java* que fica em src/main/java dentro do package *com.generation.blogPessoal*, clique com o botão direito do mouse e faça os seguintes passos: [ Run as --> selecione Java Application ]
- Após executar, abra o navegador no endereço *http://localhost:8080/* com o usuario: 'boaz' e senha: 'boaz'.
- Pronto, API execultando Localmente.

