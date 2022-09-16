# Primeiros comandos com Git

Curso: Introdução ao Git e ao Github
Tags: Prepare-se para a Jornada (Onboard)

### Comandos básicos

`git init` iniciar repositório

`git add` mover arquivos/iniciar

`git commit` criar o primeiro commit

Quando damos init a pasta .git é oculta e para vê-la é preciso usar uma flag no comando `ls` `-a` Entrando na pasta git podemos ver as pastas e seus objetos.

Antes de fazer o git add devemos configurar o git com as seguintes linhas:

`git config --global user.email "[igordardenne@gmail.com](mailto:igordardenne@gmail.com)"`
`git config --global [user.name](http://user.name/) igorbione`

`git add *`  Acrescenta tudo oq foi modificado
`git commit -m "commit inicial"`

Qnd vc faz um commit, ele mostra os primeiros numero do SHA1

`git status` mostra as informações dos arquivos

`git config - -list` mostra as configurações associadas ao git

`git remote add origin + url` Adiciona a origem pra poder linkar o rep local e virtual