# Passo a passo no ciclo de vida Git

Curso: Introdução ao Git e ao Github
Tags: Prepare-se para a Jornada (Onboard)

### Ciclo de vida dos arquivos

**Tudo começa com o `git init` pois ele cria o repositório na sua máquina**

![Untitled](Passo%20a%20passo%20no%20ciclo%20de%20vida%20Git%208e1bb1a5a83344178172667f1589a745/Untitled.png)

Untracked - Arquivos que vc colocou na pasta.
Tracked (Unmodified) - Arquivo que ainda não foi modificado.
Tracked (Modified) - Arquivo modificado (isso é feito comparando o SHA1 após algum tipo de alteração.
Tracked (Staged) - Área transitória em que o arquivo fica "esperando" algum tipo ação que devera ser atualizada por meio de um `git commit`

![Untitled](Passo%20a%20passo%20no%20ciclo%20de%20vida%20Git%208e1bb1a5a83344178172667f1589a745/Untitled%201.png)

Ambiente de dev  ↔ Staging Area → `git commit`  → Local repository → `git push` -> Rem rep  

**O `git add` adiciona o arquivo em stage. Quando quiser colocar vários arquivos, colocar git add ***

**O `git status` ajuda a monitorar o estágio dos arquivos, indicando quais foram alterados e devem ser commitados pro repositório local**

`**git restore` Ao contrário do add, essa função retira os arquivos do stage, descartando as mudanças. Exemplo, se vc fez uma alteração no script mas deseja voltar pra versão anterior ao inves de commitar.**

`**git commit -m "Mensagem para descrever as alterações do commit”`  Salva as alterações** 

`git pull origin main`  Puxa as alterações que estão no servidor, ele indica as mudanças no próprio documento, e vc é capaz de identificar o conflito.