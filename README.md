# AgroVerde

<div name="readme-top">
  <h1 align=center>Projeto Aplicado - FHO</h1>
</div>

## Git e GitHub

 - *[O que é e para que serve ?](#o-que-e-e-pra-que-serve)*

> O **GitHub** é uma plataforma de repositório de códigos, permitindo um trabalho em equipe de forma ágil e eficiente
> 
> O **Git Bash** é uma ferramenta de versionamento de código, que possui automações integradas com o **GitHub**
> 
> Essa duas ferramentas serão nesse trabalho, para podermos trabalhar em equipe de forma produtiva
>
## Instalação do Git Bash

> https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git
>

## Comandos básicos do Git Bash

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

## CONFIGURAÇÃO E INICIALIZAÇÃO

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

>Mostra as diferenças do que foi alterado mas não foi preparado (staged).
~~~sh
git diff
~~~
