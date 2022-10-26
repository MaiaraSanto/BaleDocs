# BaleDocs

Ainda em desenvolvimento
Um bot que ao você mandar uma tecnologia, ele responderá com a sua documentação 🤓

Configurando o ambiente de desenvolvimento.
Estou utilizando a versão 16.13.1 do Node.js

npm install discord.js
npm install discord.js @discordjs/rest discord-api-types
Criando o token do bot para interação com a API do Discord
Developers Potal
Clicar em Applications e criar uma nova, completando com a imagem, nome, descrição e tags que quiser
Vai na aba de Bot e crie um novo, também com a personalização que desejar
Copie o token do bot e cole no código
Crie as permissões necessárias para esse bot interagir no seu servidor (recomendo usar um servidor teste). Ele pedirá um ID, que você encontra na primeira página de Application
.ENV
Esse arquivo possui o token, o ID da aplicação e o ID do servidor, pois depende do seu ambiente de desenvolvimento e testes. Não esqueça de configurar esse arquivo para que o código rode corretamente!

Rodar código
node index.js
Alternativa: node --experimental-json-modules index.js
Acessos
Para que seja possível criar slash commands e utilizar outras ferramentas, é necessário checar se as seguintes permissões estão liberadas:

slash commands pt 1 slash commands pt 2 slash commands pt 3

Em desenvolvimento
Criação de slash commands para as pessoas poderem digitar /, selecionar o comando de docs e ditigar apenas a linguagem que queiram
Criação de um prefixo
