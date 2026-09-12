# Arquitetura do DataCross

Este diretório apresenta a arquitetura do **DataCross**, contemplando dois cenários:

1. **Arquitetura para um hospital real**, considerando o fluxo completo de coleta, tratamento, processamento e disponibilização dos dados.
2. **Arquitetura do MVP acadêmico**, utilizada efetivamente no desenvolvimento e nos testes do projeto.

A separação entre os dois cenários é importante porque o MVP foi desenvolvido utilizando dados fictícios e previamente tratados. Dessa forma, algumas etapas necessárias em um ambiente hospitalar real não precisaram ser executadas durante o desenvolvimento acadêmico.

---
## Resumo da arquitetura

A arquitetura do DataCross foi desenvolvida para permitir uma evolução gradual entre o MVP acadêmico e uma futura aplicação em ambiente hospitalar.

No MVP, o projeto trabalha com dados fictícios já tratados, simplificando o fluxo de entrada dos dados. A partir do Autonomous Database, os dados são disponibilizados pela API para o Front End, onde o médico regulador pode analisar os resultados e realizar a validação necessária.

Em uma futura implantação real, a arquitetura poderá incorporar as etapas de extração dos dados hospitalares, processamento e integração direta com os sistemas de regulação.

Assim, o DataCross não busca substituir os sistemas existentes, mas adicionar uma camada inteligente de análise e suporte à decisão, mantendo o profissional de saúde no centro do processo decisório.
