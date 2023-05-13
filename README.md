# Curso Digital: Git / Versionamento
* Salvando modificações no Git
* Dizendo qualquer coisa para poder salvar novamente

* planejei fazer outra alteração do nada

* git init = inicia o git na pasta selecionada
* git status = serve para ver os status
* git diff = verifica diferenças entre o arquivo anterior e o salvo atualmente.
* git add = prepara as alterações feitas no arquivo ou pasta selecionada.
* git diff --staged = comparando com arquivos da área de STAGE / Alteração. *

* git commit -m "add new lines"

* a letra "Q" sai do git log

# AULA DIA 10.05

* Salvando alterações no Git

* Uso do comando "git log"
    o comando retorna todos comandos já feitos no terminal

* uso do comando restore
    ele tira o último save do arquivo.
    
* git restore --staged
    retira o sabe do local de stage

* comando git push
    manda o arquivo para branch
    (git push origin master)

* git remote
    demonstra local da origem remota

* git pull 
    puxa tudo que tem no repositório remoto e junta com este repositório (cuidado com esse comando)

* git fetch
    verifica o que vai ser puxado pelo git pull (caso tenha feito alteração direto no GitHub)
    (usar git diff origin/master para verificar quais as alterações feitas antes de trazer)

# AULA DIA 13/05

* git branch (nome)
    cria uma nova branch com o nome que você colocar dentro

* git log --oneline --decorate
    indica aonde seu HEAD está apontando (aonde você está)

* git checkout "nome da branch"
    te move para a branch que você deseja

# AULA MERGING BRANCHES

* git merge (nome da branch)
    (tem que estar na branch onde você quer receber) o comando puxa os arquivos da branch que você deseja.
    forma de unir duas branchs em uma única.
    (se as pessoas mexerem na mesma linha de código, podem acabar ocorrendo conflitos, o git vai pedir para resolver os conflitos antes de fazer o merge)


