# GIT E GITHUB NA PRÁTICA

Guia prático para iniciantes.

### Instalação

https://git-scm.com/download - Se você estiver no Linux, poupe tempo, dê um: `sudo apt install git`

### Scenes

 [ x ] Você pode criar pontos na linha do tempo do seu projeto.  <br />
 [ x ] Você tem total controle sobre as mudanças feitas, pode verificá-las

* `git init` - inicializa um repositório no localhost(local onde fica gravado as alterações do projeto). 
* `git add [nome do arquivo.formato do arquivo]` - adiciona um novo ponto na história. 
* `git add .` - adiciona todas as alterações feitas no projeto. 
* `git commit -m "Texto"` - leva a alteração ao repositório. 
O `commit` só envia os arquivos que passaram pelo `git add`.
* `git log` - mostra os pontos na história do projeto. 
* `git status` - mostra alterações no arquivo, edição, remoção, etc... 
* `git show [número do commit]` ou apenas `git show` -  mostra informações de um commit específico.

 [ x ] Começar uma nova funcionalidade no projeto sem inteferir em outra.  <br />
 [ x ] Adiciona novas funcionalidades no seu projeto em produção.  <br />
 [ x ] Deletar o branch da nova funcionalidade, depois que ela já foi aplicada.

* `git branch [nome da ramificação]` - cria uma nova ramificação, fora da master.
* `git checkout [nome da branch]` - muda de uma branch para outra.
* `git branch` - visualiza todas as linhas do tempo criada.

Após passar `ls -al` no ramo `master` pode-se perceber que o `cart.html` não está presente. <br />

* `git merge [nome da ramificação]` - chamando a ramificação para a `master`, une o master e o branch secundário.
* `git branch -D [nome da branch]` - deleta a branch que foi passada.

 [ x ] Colocando o projeto na nuvem.

* `git remote add origin [URL de criação do repositório]` - informa ao repositório local para onde ele deve enviar os arquivos.  <br />
* `git remote -v` - visualiza todos os remotes já feitos. <br />
* `git push -u origin master` - empurra o repositório local para a nuvem do GitHub. <br />
* `git config credential.helper store` - pega o seu login e senha para não precisar escrever mais.  <br />
