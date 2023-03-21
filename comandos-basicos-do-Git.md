##     Iniciando Comandos Básicos do Git



## *Primeiros comandos básicos do Git*

* Iniciar o Git
* Iniciar o versionamento de código
* criar um commit 

### *Criando um repositório*

  Para criar um repositório usaremos os comandos:

* Git Init
* Git Add
* Git Commit

**Git Init:** cria um repositório.

**Git add *:** esse comando irá adicionar todos os arquivos novos e/ou modificados ao repositório.

**Git add seu_arquivo:** esse comando adiciona o arquivo em específico ao repositório.

**Git status:** monitora o estado dos arquivos.

**Git Commit:** São os objetos do Git que dão significado ás alterações, e que esses objetos em si carregam uma mensagem de texto juntamente com outros metadados como: autor, a hora do commit foi criado,

**Git Remote:** o comando Git remote estabelece uma conexão entre seu repositório local e um repositório remoto.

### *Transferindo nosso repositório local para repositório remoto*

O comando que usaremos para levar nosso repositório local para repositório remoto é o *Git Push*, a palavra *Push* significa justamente *empurrar* em inglês, e é exatamente o que faremos, então usaremos o comando: ***git push origin master***e automaticamente esse repositório vai para o perfil do GitHub de acordo com as nossas credenciais cadastradas no Git.

  Mais um comando que usamos no curso é o ***Git pull origin***. O comando git pull é usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais. 

  Também é possível trazer um repositório do GitHub para nosso repositório local usando o comando **Git Clone** juntamente com o URL do repositório remoto que desejamos *clonar* em nossa máquina. Essa função nos permite trabalhar em equipe, podendo realizar alterações e melhorias no código.