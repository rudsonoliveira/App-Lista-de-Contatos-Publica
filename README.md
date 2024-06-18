# Lista de Contatos

AppListaDeContatos: Gerencie seus contatos com facilidade!
O AppListaDeContatos é um aplicativo web totalmente responsivo que permite gerenciar seus contatos de forma eficiente e intuitiva. Adicione, edite, exclua, pesquise e visualize seus contatos com simplicidade.

### Funcionalidades:

Adicionar contatos: Insira novos contatos com nome, telefone, email.
Editar contatos: Modifique as informações de seus contatos existentes.
Excluir contatos: Remova contatos indesejados da sua lista.
Pesquisar contatos: Localize rapidamente contatos por nome, e-mail ou número de telefone.
Visualizar detalhes do contato: Acesse e visualize informações completas do contato, incluindo nome, telefone, email e endereço.
Com interface administrativa web atualizada em tempo real, e com registro de log (Um log, também conhecido como registro, é um arquivo que registra eventos, atividades ou mudanças em um sistema ou aplicativo.)

Interface administrativa web: [localhost](http://localhost:3000/admin)
Usuário Padrão: admin@admin.com
Senha: admin

Informações:

A aplicação foi criada com base do modelo de bootstrap para gerenciamento de dashboard e dados, Stislas.
https://demo.getstisla.com/
https://github.com/stisla/stisla

O Banco de Dados foi criado no PostgresSQL, e uma imagem do mesmo foi datribuida no Docker.
Alguns icones demostrativos foram retirados do https://iconify.design/.

A aplicação foi criada como projeto universitário para as matérias de Development Design and Patterns, e Segurança da informação e Auditoria da instituição UNIVEM - Centro Universitário Euripides de Marília.
Aplicando padrões e requisitos destas matérias acadêmicas.

Foi desenvolvido pelos alunos:

Genésio Henrique, Gabriel Paião, Ian Felipe e Rudson Oliveira; da turma de Bacharel Ciência da Computação 7º termo (BCC.72024).

Link para maiores informações sobre Developmente Designer and Patterns:
- https://refactoring.guru/pt-br/design-patterns/

Links para maiores informações sobre Segurança da informação e Auditoria:
- https://blog.academiain1.com.br/auditoria-em-seguranca-da-informacao/



Pré-requisitos:
Instalar:
-Docker desktop:
https://www.docker.com/products/docker-desktop/

-Node.JS:
https://nodejs.org/en/
Aplicação roda está rodando na versão: 20.11.0
Link tutorial: https://www.alura.com.br/artigos/como-instalar-node-js-windows-linux-macos?utm_term=&utm_campaign=%5BSearch%5D+%5BPerformance%5D+-+Dynamic+Search+Ads+-+Artigos+e+Conte%C3%BAdos&utm_source=adwords&utm_medium=ppc&hsa_acc=7964138385&hsa_cam=11384329873&hsa_grp=111087461203&hsa_ad=687448474447&hsa_src=g&hsa_tgt=aud-527303763294:dsa-2276348409543&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=CjwKCAjwyJqzBhBaEiwAWDRJVLTbqaGjqFuZHWMAPg6smab04myklaJlNr5b-FPox0AA6he9w5H9dRoC2i0QAvD_BwE

-NVM (Node Version Manager):
Link Tutorial: https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/

Comandos para instalar NVM:
# Instala a ultima versão:

nvm install lts

# Instala versão especifica (substitui o X.Y.Z pelo número da versão):

nvm install vX.Y.Z

# Listar a versão no NVM:

nvm list

# Usar versão especifica NVM (substitui o X.Y.Z pelo número da versão):

nvm use v X.Y.Z

# Instalar o DBeaver para manutenção e gerenciamento do Banco de Dados (DBeaver Community 24.1) : 

Link: https://dbeaver.io/download/

Para ter acesso ao Banco de Dados é necessário logar e atribuir o modelo de linguagem do Banco;
Foi usado o PostgreSQL, por ser open source e de fácil gerenciamento.

#Dados para acesso ao DBeaver:

# Postgres
DB_HOST=127.0.0.1
DB_NAME=intranet
DB_USER=admin
DB_PASS=P@ssw0rd
DB_PORT=5432

# Para rodar a aplicação é necessário instalar algumas extensões no VS Code para vincular o Banco de Dados e melhor visualização e entendimento do Código:

# Para rodar atribuições Linux no Windows:

Nome: WSL
ID: ms-vscode-remote.remote-wsl
Descrição: Open any folder in the Windows Subsystem for Linux (WSL) and take advantage of Visual Studio Code's full feature set.
Versão: 0.88.2
Editor: Microsoft
Link do Marketplace do VS: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl

# Para manusear Containers:

Nome: Dev Containers
ID: ms-vscode-remote.remote-containers
Descrição: Open any folder or repository inside a Docker container and take advantage of Visual Studio Code's full feature set.
Versão: 0.369.0
Editor: Microsoft
Link do Marketplace do VS: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers

# Para construir e manusear aplicações Docker:

Nome: Docker
ID: ms-azuretools.vscode-docker
Descrição: Makes it easy to create, manage, and debug containerized applications.
Versão: 1.29.1
Editor: Microsoft
Link do Marketplace do VS: https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker

# Para visualizar os arquivos, pastas diferenciando os modelos e tipos de linguagem de cada item:

Nome: Material Icon Theme
ID: PKief.material-icon-theme
Descrição: Material Design Icons for Visual Studio Code
Versão: 5.3.0
Editor: Philipp Kief
Link do Marketplace do VS: https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme

Clone o repositório:

Se você possui uma conta GitHub, faça clone do repositório usando o seguinte comando no seu terminal:

Bash
git clone https://github.com/rudsonoliveira/App-ListadeContatos.git
Use o código com cuidado.
content_copy
Se você não possui uma conta GitHub, baixe o zip do repositório diretamente da página do GitHub e extraia o conteúdo para o seu computador.

Abra o projeto no VS Code:

Ciente de todas os parâmetros acima e com o Docker, Node Version Manager (NVM) e Node.JS instalados com suas respectivas versões, execute os comando abaixo no terminal PowerShell:

- npm run dev

Logo execute o comando abaixo para alimentar o Banco de Dados e fazer as Migrações:

- npm run seed

E depois o comando para executar a aplicação:

- npm run start

E abra a aplicação no navegador pela porta 3000:

- http://localhost:3000/ # Interface do usuário!

- http://localhost:3000/admin # Interface do Administrador!


Teste as funcionalidades:

Explore as funcionalidades do aplicativo, adicionando, editando, excluindo, pesquisando e visualizando seus contatos e verificando os registro de log.

Contribuindo com o projeto:

Se você deseja contribuir com o código ou sugerir melhorias para o aplicativo, sinta-se à vontade para abrir um issue no repositório GitHub ou enviar um pull request com suas modificações.

Esperamos que você goste do AppListaDeContatos!



yarn sequelize-cli db:seed:undo

npx sequelize-cli db:seed:all

yarn sequelize-cli seed:generate --name departaments

docker build . -t intranet:1.0.0

docker tag intranet:1.0.0 10.1.4.251:5000/intranet:1.0.0

docker push 10.1.4.251:5000/intranet:1.0.0

Teste
