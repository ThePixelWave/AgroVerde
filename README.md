# AgroVerde

<div name="readme-top">
  <h1 align=center>Projeto Aplicado - FHO</h1>
</div>

## Git e GitHub

 - ### O que é e para que serve ?

> O **GitHub** é uma plataforma de repositório de códigos, permitindo um trabalho em equipe de forma ágil e eficiente
> 
> O **Git Bash** é uma ferramenta de versionamento de código, que possui automações integradas com o **GitHub**
> 
> Essa duas ferramentas serão nesse trabalho, para podermos trabalhar em equipe de forma produtiva
<br>

## Instalação do Git Bash

> https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git
<br>

## O que é uma branch ?
> As branchs são ramificações do mesmo projeto, todas derivadas da **Main**, isso permite que múltiplas pessoas trabalhem no mesmo código
> É importante dar o comando de push na sua branch, **não faça isso na main**

<br>

## Configuração inicial

Configurando informações de usuário usadas em todos os repositórios locais:

>Defina um nome que para ser o seu identificador dentro do código.
~~~sh
git config --global user.name "[nome sobrenome]"
~~~

<br>

>Defina um endereço de email que será associado a cada marcador de histórico.
>De prefência use o mesmo email cadastrado na sua conta do github
~~~sh
git config --global user.email "[email-válido]"
~~~

<br>
 
## Comandos básicos do Git Bash

Clonando os repositórios

>Recupera um repositório inteiro de um local hospedado via URL.
>Essa URL, é vista na página inicial do repositório, em um botão verde chamado **code**
~~~sh
git clone [url]
~~~
<br>

>Criar uma branch
~~~sh
git checkout -b [nome da branch]
~~~
<br>

>Adicionar as alterações
~~~sh
git add.
~~~
<br>

>Subir alterações
~~~sh
git commit -m "Mensagem-básica"
~~~
<br>

>Transmite commits da branch local para a branch remota do repositório.
~~~sh
git push origin [nome da branch]
~~~
<br>

>Baixa e mescla quaisquer commits da branch remota de rastreamento.
~~~sh
git pull origin main 
~~~
<br>

>Mostra as diferenças do que foi alterado 
~~~sh
git diff
~~~
<br>

## Pull request

> Depois de fazer as alteções na sua branch, foi irá usar os comando acima,  depois irá acessar o nosso repositório no **GitHub** e criar a **Pull Request**
<br>

> A **Pull Request** é basicamente é uma solitação para mesclar o seu código com a versão mais atual do projeto
<br>

> Isso previne conflitos ou código duplicado 
