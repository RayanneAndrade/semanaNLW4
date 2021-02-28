# API para qualificação de serviços #
<p>API criada durante a <strong>NLW 4</strong> para qualificação de serviços através do método <strong>NPS</strong>. A API conta com o envio de um e-mail para o client, com um template HTML personalizado, onde o cliente poderar quantificar, de 0 a 10, o quão satisfeito ficou com o serviço</p>

## Para fazer executar o projeto ##
Primeiro será necessário isntalar as dependências
```bash
$ yarn install
```
ou
```bash
$ npm install
```
Também será necessário criar um arquivo **.env** com as variáveis de ambiente. No projeto tem apenas uma, a **URL_MAIL**, nela é preciso colocar o path de onde sua aplicação será rodada. Se for rodar de forma local o valor de *http://localhost:3333/answers*


