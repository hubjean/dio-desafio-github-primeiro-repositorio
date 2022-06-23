###                 Compartilhamento de Projetos e Versionamento de Códigos - Git/GitHub



O Git é um sistema de versionamento de código distribuído que ajuda a criar e monitorar diversas versões de um código. Num compartilhamento em nuvem na rede pública, o Git pode controlar as versões e propor aos usuários da aplicação um controle sobre seu arquivo, bem como enviar o trabalho feito para as pessoas da rede. Mas fique tranquilo, isso é opcional, quer dizer que também podemos utilizar o arquivo em modo privado, assim o usuário tem total rastreamento e organização do seu projeto.

O GitHub é uma ferramenta de trabalho e rede social onde milhares de programadores das mais variadas tipologias de programação estão inseridos. Nele, é possível ter acesso aos arquivos compartilhados, estudar e ter conexões que podem ou não compartilhar dos mesmos conhecimentos. Para que o GitHub fosse operado da maneira desejável foi desenvolvido pelo Git, a extensão GitHub, que numa linguagem de fácil interpretação permite ao usuário criar, navegar, deletar, armazenar e publicar seus projetos.

Essas aplicações proporcionam:

Controle de versão;

Armazenamento em nuvem;

Trabalho em Equipe;

Reconhecimento.



Abaixo, alguns dos comandos principais do Git para que tenha sucesso na operação de um projeto:

Atenção, alguns dos comandos abaixo podem se alterar a depender do seu sistema operacional. Neste exemplo, utilizamos o Windows como referência

- **git init**  esse é o comando que você irá utilizar para criar um novo projeto de git. O comando irá criar um repositório novo em branco e, a partir daí, será possível armazenar seu código fonte, alterar, salvar etc.

Após o comando git init, descrever a frente o nome do seu trabalho.

Ex: **git init** Arquitetura e Organização de Computadores

- **git clone**  esse comando cria uma cópia exata de um repositório já existente

Após o comando git clone, colar a URL ou chave de seu projeto.

- **git add**  esse comando adiciona os arquivos especificados de código ao seu repositório, sejam arquivos novos ou arquivos anteriores que foram alterados.

Após o comando git add, é necessário especificar na mesma linha o nome do arquivo a ser adicionado ou um * para que todos os arquivos sejam inclusos

Ex:

**$ git add seu_arquivo** (esse comando irá adicionar o arquivo em específico ao repositório)

**$ git add \*** (esse comando irá adicionar todos os arquivos novos e/ou modificados ao repositório)

- **git commit** este comando executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log

É possível adicionar uma mensagem para a execução de um commit

Ex: **$ git commit -m “seu comentário”**

- **git status** retorna o status para o diretório, indicando se há arquivos que não tiveram o commit realizado

Para que toda a operação de envio dos arquivos tenha sucesso é preciso realizar  os comandos **git remote** e **git push**.

O **git remote** estabelece uma conexão entre seu repositório local e um repositório remoto

![git remote](https://drive.google.com/file/d/1m00dans6gxwH7h5mlkYd68e9VH_UNI2a/view?usp=sharing)

**git push**

Esse comando serve para subir suas modificações para um repositório **remoto** conectado anteriormente com git remote.

Exemplo:

**$ git push  <nome_curto> <nome_do_branch>**

![](C:\Users\cjean\Downloads\git push.jpeg)