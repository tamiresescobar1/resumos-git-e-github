# Resumos | Git e GitHub 

Repositório para armazenar resumos sobre Git e GitHub 

# 📚 Documentação

- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

# Comandos

| Comando | Descrição |
|------|--------|
|ls | mostra todos arquivos e pastas (ls -l)|
|git commit -m"contaúdo da mensagem de commit" | Gravação de arquivo no git. Esse comando serve para commitar os arquivos no git. O "-m" é referete ao termo "mensseger". Ou seja, mensagem que será gravada no commit |
|ctrl + l ou clear | É o comando que limpa a tela do terminal do git|
|git log | Comando para visualizar os logs dos arquivos gravados no repositório|
|git remote add origin + endereço da pasta no github | Esse comando permite apontar para o repositório no github, ou seja, o usuário cria uma página no github e pode direcionar uma página do seu computador local para a pasta do github sem precisar clonar o repositório|
|git clone + endereço da pasta no github | Esse comando serve para clonar um projeto no github|
|git init | Iniciar repositório git|
|git ignore | Arquivo para ser criado no git e evitar que determinados arquivos sejam adicionados, ou seja, o git vai ignorar os arquivos que estiverem dentro dele. Exemplo: touch .gitignore (Criar arquivo dentro da pasta desterminada), echo "nome do arquivo que vc quer ignorar" >> .gitignore (Escreve dentro do arquivo do gitignore o nome do arquivo que você quer ignorar.) |
|git add .gitignore | Adicionando o gitignore detro do githubIgnorando todos os arquivos de uma extenção: echo "*.log" >> .gitignore. Ignorando um diretório inteiro: echo "pastaignorada/" >> .gitignore|
|git commit -am |"Rastreando/adicionando e commitando ao mesmo tempo um arquivo."|
|git log -n 3 |Comando mostra os três últimos commits|
|git log --oneline | Resumo dos commits feitos no projeto|
|git log --state | Mostra o resumo dos arquivos alterados com o número de linhas alteradas e removidas|
|git rm nomedoarquivo | Esse comando serve para remover/deletar um arquivo do repositório. Todo arquivo removido precisa ser commitado - Não esquecer disso|
|git mv nomeantigo nome_novo | O comando "mv" altera o nome de um arquivo. Ou seja, renomeia o arquivo existente, exemplo: git mv algo01.py algoritmo01.py|
|git checkout -- nomedoarquivo | Esse comando permite desfazer uma alteração em um determinado arquivo, exemplo: echo "Mudança no arquivo!" >> arquivo.txt -> Efetuano mudança no arquivo|
|git checkout -- arquivo.txt | Cancelando a última alteração do arquivo. Lembrando, as alterações só podem ser refeitas se estiverem fora do stage. Ou seja, antes de adicionar o arquivo com o comando -> git add nomedoarquivo|
|git reset --hard | Comando para desfazer todas as modificações que você fez|
|git branch novo_branch | Comando para criar um novo branch|
|git branch | Comando para listar as branchs existentes|
|git checkout novo_branch | Comando para mudar de branch|
|git checkout -b nova_branch | Comando cria uma nova branch e troca para ela ao mesmo tempo|
|git branch -d nova_branch | Comando deleta um branch criada "OBS: Uma branch só pode ser deletada se o usuário não estiver nela. Ou seja, o desenvolvedor deve mudar de branch com o comando "git checkout master" (por exemplo) e deletar a branch que deseja"|
|git branch -D nova_branch | O comando usando o "-D" (letra maiúscula) é usando quando existe commit na branch|
|git branch --no-merged | Comando para identificar se existe alguma branch não mesclada|
|git merge nova_branch -m"Mensagem sobre a mesclagem da branch." | Esse comando mescla a nova_branch ao master|


# Códigos
```
git init 
```
# resumos-git-e-github
