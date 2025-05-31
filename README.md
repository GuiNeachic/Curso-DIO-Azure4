# Curso-DIO-Azure4
Como por motivos desconhecidos a minha assinatura Azure para estudantes foi desativada, eu não  consegui realizar o projeto. Então escrevi um texto Sobre o GitHub, Azure DevOps, Versionamento e Backups.

 GitHub e Azure DevOps: O que são?
-->GitHub
-É uma plataforma de hospedagem de código-fonte baseada no sistema de controle de versão Git.
-Permite que desenvolvedores trabalhem de forma colaborativa, versionem o código e façam revisões com facilidade.
-Utilizado por milhões de projetos open source e privados.

-->Azure DevOps
-Plataforma da Microsoft que oferece uma série de ferramentas para gerenciamento de ciclo de vida de software.
->Inclui:
-Repositórios Git (semelhante ao GitHub).
-Pipelines de CI/CD (integração e entrega contínua).
-Boards (Kanban/scrum).
-Test Plans e Artifacts.
-Ideal para times que já usam o ecossistema da Microsoft (ex: Azure, Visual Studio, Active Directory).

-->Controle de Versão (Versionamento)
->Ambas as plataformas utilizam o sistema Git, que oferece:
-> Histórico Completo
-Cada alteração no código é registrada como um commit.
-Você pode ver quem alterou o quê, quando e por quê.
->Branches (Ramificações)
-Permite trabalhar em múltiplas versões do projeto simultaneamente (ex: desenvolvimento, correções, novas funcionalidades).
-Depois, essas versões podem ser integradas (via merge ou pull request).
->Reversão de Erros
-Se algo quebrar, é fácil voltar para uma versão anterior do código.
->Colaboração
-Vários desenvolvedores podem contribuir no mesmo projeto sem sobrescrever o trabalho dos outros.

-->Backups (na prática)
->Apesar de GitHub e Azure DevOps não serem serviços de backup tradicionais, eles funcionam como um backup distribuído do código-fonte, por meio de:
->Armazenamento na Nuvem
-O código está hospedado remotamente, protegido contra perda local.
->Histórico de Commits
-Todo o histórico do projeto é salvo e acessível.
->Clones Locais
-Cada desenvolvedor tem uma cópia completa do repositório em sua máquina.
->Restauração Rápida
-Se algo der errado, você pode restaurar versões anteriores com facilidade.
