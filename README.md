# DIO | Resumo .NET

Repositório para armazenar resumos das aulas do [bootcamp da DIO sobre .NET](https://web.dio.me/track/avanade-back-end-com-net-e-ia).

## 📙 Git e Github

- [Documentação Git](https://git-scm.com/doc).
- [Documentação Github](https://docs.github.com/pt).

### Criação e commit de arquivos
|Codigo|Explicação|
|------|----------|
|`git config --global user.name "nome da pessoa"`|Altera o nome do usuário|
|`git config --global user.email digitar@email.com`|Alterar o email|
|`git config --global init.defaultBranch "main"`|Alterar main|
|Para somente ver como está algo| basta não adicionar o valor no final|
|`git init`|Torna o diretório um repositório|
|`cd .git`|Para abrir a pasta do git no repositório|
|`git remote add origin http//endereço.url.do.repositório|Para vincular o seu repositório local com o remoto|
|`git status`|Para ver se tem alterações não salvas no seu repositório local|
|`touch README.md`|Criar arquivo .md|
|`git add nome_do_arquivo` (ou . caso seja mais de um)|Adicionar arquivo a área de preparação|
|`git commit -m "nome do commit" `(Como commit inicial)|Comita os aquivos na área de preparação|
|`git log`|ver o histórico dos commits|
### Desfazer Alterações no repositório local
|Código|Explicação|
|--------|-----------|
|`git restore nome_do_aquivo`| Restaura o arquivo para a última versão salva dele|
|`git commit --amend -m"nova mensagem"`|Mudar o nome do último commit|
|`git reset --soft cola_o_rest_do_commit`|Desfazer um commit e manda as alterações dele para a área de preparação|
|`git reset --mixed cola_o_rest_do_commit`|Desfaz um commit e manda as alterações para a área de trabalho|
|`git reset --hard cola_o_rest_do_commit`|Desfaz um commit e exclui as alterações|
|`git reflog`|histórico mais detalhado das alterações|
### Enviar e baixar alterações com o repositório remoto
|Código|Explicação|
|--------|-----------|
|git push -u origin main|Enviar as alterações para o repositório remoto|
|git pull|Pucha as alterações do repositório remoto para o local|
### Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando Conflitos
|Código|Explicação|
|--------|-----------|
|`git checkout -b teste`|Cria uma Branch nova|
|`git checkout nome_da_branch`|para acessar alguma Branch específica|
|`git branch -v`|mostra o último commit de cada Branch|
|`git merge nome_da_branch`|Dentro da branch principal nós usamos esse comendo para mesclar ela com a branch que nós demos o nome|
|`git branch -d nome_da_branch`|Excluir uma branch|
