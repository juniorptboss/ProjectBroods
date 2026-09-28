# ProjectBroods

Projeto de personalização de um servidor de jogo baseado no **rAthena**, iniciado com a ideia de criar uma experiência para jogar com amigos.

A base do servidor é desenvolvida pela comunidade rAthena. Este repositório reúne essa base e alterações do projeto; não representa um motor de jogo criado do zero.

## Onde está o código

O conteúdo está distribuído entre três branches:

| Branch | Conteúdo |
| --- | --- |
| [`main`](https://github.com/juniorptboss/ProjectBroods/tree/main) | Apresentação do repositório. Não contém o código do servidor. |
| [`master`](https://github.com/juniorptboss/ProjectBroods/tree/master) | Código da base rAthena, configurações, dados e scripts do projeto. |
| [`dev`](https://github.com/juniorptboss/ProjectBroods/tree/dev) | Outra linha de desenvolvimento, com alterações próprias em relação à `master`. |

## Base técnica

A base rAthena utiliza **C++** para o servidor e inclui mecanismos de scripts para personagens não jogáveis (NPCs), configurações e dados do jogo. O uso de **MySQL ou MariaDB**.

## Organização do conteúdo

Na branch `master`, os principais diretórios são:

| Diretório | Conteúdo |
| --- | --- |
| [`src/`](https://github.com/juniorptboss/ProjectBroods/tree/master/src) | Código-fonte do servidor. |
| [`conf/`](https://github.com/juniorptboss/ProjectBroods/tree/master/conf) | Configurações. |
| [`npc/`](https://github.com/juniorptboss/ProjectBroods/tree/master/npc) | Scripts e conteúdo de NPCs. |
| [`db/`](https://github.com/juniorptboss/ProjectBroods/tree/master/db) | Arquivos de dados do jogo. |
| [`sql-files/`](https://github.com/juniorptboss/ProjectBroods/tree/master/sql-files) | Scripts SQL. |
| [`doc/`](https://github.com/juniorptboss/ProjectBroods/tree/master/doc) | Documentação técnica da base. |

## Documentação e créditos

O projeto utiliza a base [rAthena](https://github.com/rathena/rathena). A documentação incluída nas branches de código apresenta os requisitos e as referências de instalação dessa base:

- [README da base na branch master](https://github.com/juniorptboss/ProjectBroods/blob/master/README.md).
- [README da base na branch dev](https://github.com/juniorptboss/ProjectBroods/blob/dev/README.md).

Os créditos e os termos de licença da base estão nos arquivos [AUTHORS](https://github.com/juniorptboss/ProjectBroods/blob/master/AUTHORS) e [LICENSE](https://github.com/juniorptboss/ProjectBroods/blob/master/LICENSE).
