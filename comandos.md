# comandos

**Git init**
inicializar repositório vazio na branch master

Git add
Manda arquivos para área de stading para entrar no repositório local para depois ser "publicado" no perfil do site do Github.
- Junto do comando deve-se informar o arquivo que deve ser adicionado ex: Readme.md
- Pode-se também colocar apenas um "." para adicionar todos os **novos** arquivos ou aqueles que **tiveram** alguma alteração.

**Git status**
Mostra o status do repositório atual

**Git commit -m "Descrição do commit"

**Git branch -M "main"**
Para mudar a branch para main

**Git remote add origin**
- Deve ser adicionado o link inicial do repositório para adicionar os arquivos no site do Github
- Nome do repositório padrão é origin, porém não poderá ser usado mais de uma vez, se já existir um repositório chamado origin, outro nome deverá ser adicionado.

**Git push -u origin main**

- Push significa que os arquivos estão sendo empurrados para o site
- Origin é o nome do repositório
- Main é o nome da branch que o arquivo adicionado anteriormente deverá ir.

**Git checkout -b "NOME DA NOVA BRANCH"**

Usado para criar uma nova branch ao repositório

**Git merge**

Usado para fundir branch, pode ser usando tanto main+branch secundária quanto branch+branch
- Deverá ser colocado o nome da branch, especificando as branch que devem se fundir


