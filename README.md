Bom dia Donathan

--------------------------------------------------------------------------------
------------------------------  GIT e Proxy GIT --------------------------------

git config --global user.name "Maria Eduarda"
git config --global user.email "silvamariaeduarda92@gmail.com"

git config --global http.proxy http://USUARIO:SENHA@rb-proxy-ca1.bosch.com:8080
git config --global https.proxy https://USUARIO:SENHA@rb-proxy-ca1.bosch.com:8080


git init - inciar repositorio
git add NOMECODIGO - avisar que quando eu der o comite é nesse arquivo
git add . #todos os arquivos
git comit -m "DESCRIÇÃO DE COMIT"
git add . guarda tudo que foi criado/modificado
git log - mostra todos os commit 
git log --oneline - coloca menos informações sobre os commmits
git checkout HASH - voltar para algum commit
git checkout master - volta posição original
git checkout -b NOME -> criar nova branch
git merge NOME DA BRANCH - precisa estar na maaster para dar marge
git branch - mostra as branchs
git log --graph -> mostra desenho 

git push origin master #onde eu vou empuraar meus arquivos 


painel de controle > contas de usuario > gerenciar credenciais do windows > achar github
 

**copoiar git remote add origin https://github.com/aeduardamariaa/aulaGIT.git do GITHUB para que seja guardado lá
