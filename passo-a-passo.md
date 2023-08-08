# Passo a passo para usar Github

- Primeiro crie uma pasta para o seu projeto;

- Adicione o arquivo em markdown para ser usado no git bash;

- Abra o terminal e adicione o comando **git init** para abrir um repositório vazio;

- Use o comando **git add "nome do seu arquivo"** para adicionar o arquivo.md em stading;

- Para saber se funcionou, basta usar o comando git status;

- Em seguida vamos dar nosso primeiro commit, basta usar o comando **git commit -m "breve descrição do seu commit"**;

- É interessante mudar o nome da branch principal para "main", deve-se utilizar o comando **git branch -M "main"**;

- Antes de adicionarmos o repositório da da nossa máquina no git hub;

- Depois de adicionarmos o repositório no site, colocar o que está na nossa máquina no site usando o comando **git remote add origin "link do repositório do site"** , esse comando só será usado na primeira vez;

- Será aberto uma aba no qual deve-se fazer login no seu perfil do github;

- Se for necessário adicionar mais arquivo, basta criar o arquivo.md e adicionar tudo o que for importante;

- Logo após isso basta usar o comando **git add .** para adicionar todos os novos arquivos e ou para atualizar arquivos que foram recentemente;

- Depois basta usar o comando de commit;

- Para adicionar/atualizar no site basta usar o comando **git push origin main** (Lembrando o nome "origin" é apenas o apelido do repositório, não pode ser utilizado o mesmo apelido para outro repositório) e "main" significa que será adicionado a branch principal;

- Para criar novas branch, primeiro criar a branch com o comando git checkout -b "nome da branch";

- Em seguida crie o arquivo.md para adicionar a nova branch

- Pode-se usar o comando **git add .** ou **git add "nome do arquivo"** para apenas um arquivo específico; 

- Faça o commit e adicione a descrição;

- Logo após isso basta subir o que foi adicionado a branch para a plataforma do github, basta usar o comando **git push origin "nome da nova branch"**

- Para volta ou mudar para outra branch basta usar o comando **git checkout "nome da branch"**

- Quando a nova branch estiver pronta, podemos fundir ela com a branch principal, basta utilizar o comando **git merge "nome da nova branch"**

-  Para atualizar tudo na plataforma basta subir tudo usando o comando **git push origin main**

