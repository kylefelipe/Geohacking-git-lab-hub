# Introdução

Colaborando em projetos GIS com GIT.
Vamos usar aqui o Github para fazer contribuições, mas as dicas podem ser úteis nas mais variadas plataformas para hospedagem de projetos e versionamento de código (Como o gitlab, bitbucket...)

## Git != Git(Hub|Lab)

É comum muita gente confundir GITHUB com [GIT](https://pt.wikipedia.org/wiki/Git), devido a similaridade do nome a popularidade das utilizações de ambas as ferramentas, mas há uma diferença entre ambas.

## O que é GIT

> Git, gíria britânica para "cabeça dura"

Git é uma ferramenta Livre e aberta, desenvolvida por [Linus Torvalds](https://pt.wikipedia.org/wiki/Linus_Torvalds). Durante muito tempo ele controlou as colaborações do [Kernel Linux](https://pt.wikipedia.org/wiki/Linux_(n%C3%BAcleo)) que ele desenvolvia usando um sistema chamado BitKeeper, que teve o acesso gratuito revogado devido a problemas no próprio projeto BitKeeper, e com isso, muitos colaboradores estavam desistindo de ajudar no desenvolvimento do Linux.  
Diante disso, Torvalds começou a trabalhar em um sistema distribuido, o problema era que na época, não existia nenhum software livre que atendia a essa necessidade, e nem tinham boa performace quanto a isso.  
A idéia do git é que cada desenvolvedor tenha a sua própria cópia do código (sistema distribuido), com a memória de todas as alterações feitas (versionamento), e facilidade de apliações de modificações (patches | contribuições) feitas por diferentes pessoas, e isso iria permitir que vários usuários trabalhassem em um mesmo arquivo, e depois todas as alterações poderiam ser agrupadas em um repositório central.  
Nesse repositório também fica guardado todo o histórico de contribuições, podendo saber o que foi modificado e por quem.  
O Git pode ser operado pelo terminal através da própria ferramenta CLI que possui (o git), mas existem muitas ferramentas com interface de usuário (GUI) para trabalhar o controle de versão com o GIT, e até mesmo exensões para IDEs e editores de texto (como o VS Code) que integram a ferramenta.

## O que é GitHub

O [Github](https://pt.wikipedia.org/wiki/Linus_Torvalds) é uma plataforma online utilizada para hospedar os códigos, é usado como um repositório remoto, e que usa o GIT como ferramenta de versionamento, isso numa maneira bem simples de explicar o que ele é.  
Lá podemos guardar nossos códigos e expor o repositório para toda a internet ou manter ele privado, apenas para um grupo de pessoas, organização e etc.  
Básicamente, uma rede social de desenvolvimento.  
O interessante da plataforma é, que várias pessoas podem colaborar ao mesmo tempo em um mesmo projeto, sem a necessidade de ficarem trocando e-mails com as alterações que cada um fez. E se mais alguém entrar no projeto, basta conceder acesso, ou aceitar as modificações propostas por eles.

O Github tem também uma série de integrações com outras ferramentas, que permitem rodar testes de códigos, fazer o deploy de aplicações automáticamente e até mesmo enviar mensagens de alterações do projeto em locais como o Discord.  
Após a aquisição do GitHub pela gigante Microssoft, o GitHub ganhou uma interface de linha de comando (CLI) para que os usuários pudessem fazer praticamente todas as ações que fazem hoje através da página do sistema através do terminal (O GH CLI).

De agora em diante, vamos chamar o GitHub carinhosamente de G.H.

## E o Gitlab?

Bom, o Gitlab, ao contrário do G.H permite que os usuários tenham a sua prória instancia para gerênciar os repositórios, e o G.H tem os seus próprios servidores para armazenar os códigos. E ao contrário do G.H não possue uma ferramenta CLI.

## Outras ferramentas

Existem muitas ferramentas e sistemas de versionamento (procure por [SVN](https://pt.wikipedia.org/wiki/Subversion) e [Bitbucket](https://pt.wikipedia.org/wiki/Bitbucket))

[Entendendo o Repositório ➡️](./Entendendo_Conceitos.md)  
[⬅️ Voltar para página principal](https://github.com/kylefelipe/Geohacking-git-lab-hub)
