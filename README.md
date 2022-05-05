# Hello-APP CI-CD

Sempre que houver um commit na branch master deste projeto, um Step do Git Actions será acionado para realizar o deploy da aplicação em questão no cluster Kubernetes GKE.

O código do Git Actions se encontra na pasta "Workflow", dentro deste projeto.
As variáveis de ambiente utilizadas do YML do Git Actions, estão setadas via secret no environment do projeto.
