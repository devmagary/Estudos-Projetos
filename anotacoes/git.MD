## Hash codes:
### Para mostrar o SHA1 do Arquivo:
    openssl sha1 nomedoarquivo

### Para objeto blob:
    git hash-object --stdin
    ('blob 9\0conteudo')

## Criar chave ssh:
    ssh-keygen -t ed25519 -C email
    cat chave.pub - Copia a chave ssh e coloca no github/gitlab e entre outros
    eval $(ssh-agent -s)
    ssh-add chaveprivada
    ssh -T git@github.com - teste de conexão

## Config rep:
    git config --global user.email "email"
    git config --global user.name nome
    git config --global --unser digiteaconfig - remover algum paramentro das configs
    git config --list - para mostrar as configurações do git no local

## Iniciando git no ssh:
    git init - inicia um repositorio local
    git add * - ou arquivo/pasta em especifico
    git commit -m "mensagem do commit"
    git remote add origin endereço do ssh git
    git remote -v - para ver os repositorios remotos
    git push origin main - main pode variar pois é a branch


## Reset:
    git reset --hard aquiahash - apaga tuuuudo!
    git reset hash - é o reset soft, ainda posso selecionar oq eu quero
    https://www.youtube.com/watch?v=WNC2TdyeTrc - Pra saber mais
    git revert hash - cria um novo commit revertendo para o commit selecionado