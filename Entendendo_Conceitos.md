# Entendendo Conceitos

## Repositório

O repositório é um conceito do GIT, que é o local onde os projetos estão gravados, por exemplo, para esse tutorial, tem uma pasta na minha máquina chamada
`git_colaborando` que armazena tudo que é relativo a esse projeto (tutorial), e no GitHub o projeto chama-se `Geohacking-git-lab-hub`. Assim eu posso fazer as alterações necessárias e enviá-las para o GitHub. Podemos criar cópias de um repositório para trabalharmos nele, o que é chamado do `Fork`

## Fork

O Fork (bifurcação) é uma cópia que fazemos de um repositório já existente.
Nesse fork, podemos criar as `Branchs` que vamos trabalhar, seja ajudando a corrigir algum erro de digitação, ou até mesmo criando novas funcionalidades e etc. E podemos trazer o repositório existe, ou o nosso Fork para a nossa máquina, através do `Clone`.

## Clone

O Clone (clonar), nada mais é que pegar o repositório e colocálo em um local físico pra trabalhar. Local esse pode ser um servidor, para poder rodarmos os códigos, ou seus testes, ou a nossa máquina, para podermos usar o código ou realizar alterações, e assim criar as nossas próprias `Branchs`.  
Também podemos fazer o clone de um projeto, de uma branch específica para usarmos para trabalhar, fazer deploy, gerar instaladores e por aí vai.  

## Branch

Branch (galho, ramificação) são derivações do código original, permitindo trabalhar o código sem que o código principal seja afetado.  
Normalmente um repositório possui mais de uma branch, sendo uma delas a principal (MASTER ou MAIN - em repositórios mais recentes), que normalmente recebe o código que vai para a produção (deploy).  
Há alguns projetos que dividem as branchs de acordo com a versão do projeto, por exemplo:

- Branch develop: são recebe a versão de desenvolvimento, que pode conter muitos bugs, é a versão mais recente e menos estável do projeto.
- Branch b<versão 1, 2, 3....>: É vai de acordo com a versão do projeto, e provavlemente recebe o código mais estável daquela versão.

As branchs também podem ser utilizadas para simbolizar o desenvolvimento de alguma função do projeto também (feature Branch), por exemplo:

- Branch geocoding: Indica que nessa branch está sendo o desenvolvimento de uma parte do projeto voltada para realização de geocoding.
- Branch SHP_TO_GPKG: Desenvolvimento de uma ferramenta de conversão de `Shape File` para `Geopackage` no projeto.

No final dos trabalhos, pode ser feito a união da branch onde estavamos trabalhando com a branch principal. Isso se chama `MERGE`

## Merge

Ao finalizarmos o trabalho em uma branch, é necessário fazer a união do código da branch com o principal, isso é chamado de `MERGE` assim podemos verificar se há conflitos com o projeto principal que está em nossa máquina e corrigir, caso haja algum.  
Após corrigir eventuais problemas, é necessário necessário fazer o envio dessas informações para o nosso repositório remoto (esteja ele no Github, Gitlab ou alguma instância do Gitlab) isso é chamado de "Push".

## Push

O `Push` (empurrar) é quando pegamos nossas alterações e as enviamos para o repositorio remoto, permitindo assim que outras pessoas também verifiquem se o que fizemos possui alguma inconformidade, e principalmente, se essas alterações entram em conflito com o que elas estão trabalhando também, o que é muito importante quando se trabalha em equipe. Um Push pode enviar para um repositorio vários `Commits`.

## Commits

Os Commits são as mudanças que ocorreram no projeto, ele recebe o estado atual das modificações, permitindo assim manter o histórico do que foi feito, e essas alterações podem ser enviadas para o repositório remoto através do `Push`, e cada commit precisa de uma mensagem que o descreva. Um commit pode ter uma alteração em um arquivo ou pode ter todas as alterações feitas em todos os arquivos (o que acaba não sendo uma boa coisa), e um push pode ter um ou mais commits dentro dele.

## Pull Request

O Pull Request (ou Merge Request, no Gitlab) é o momento onde enviamos nossas modificações para o projeto principal, para serem revistas pelos participantes do projeto, passar por testes, e se caso não houver nenhum problema, nossas modificações passam a serem aceitas no projeto oficial.

[Fluxo de contribuição ➡️](./Fluxo_de_contribuicao.md)  
[⬅️ Voltar - Introdução](./Intro.md)
