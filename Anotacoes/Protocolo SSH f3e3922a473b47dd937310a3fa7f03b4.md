# Protocolo SSH

Curso: Introdução ao Git e ao Github
Tags: Prepare-se para a Jornada (Onboard)

### Tutorial para adicionar a chave SSH

[Gerando uma nova chave SSH e adicionando-a ao agente SSH - GitHub Docs](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

1. Crie a chave a partir do terminal (seguindo o tutorial)
2. Adicione a conta no github
3. `eval $(ssh-agent -s)` inicia o processo
4. `ssh-add id_ed25519` Adicione a chave pessoal na caminho `~/.ssh`
5. `git clone` + copia do ssh do repo