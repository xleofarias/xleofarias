<h1 align="center">Leonardo Farias das Neves 👋</h1>
<p align="center"><strong>Analista Programador SQL Server Pleno | Desenvolvimento backend em C# e .NET</strong></p>

<p align="center">
  <a href="https://www.linkedin.com/in/leonardo-farias-neves/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square" alt="LinkedIn de Leonardo" /></a>
  <a href="mailto:leonardo.fariasnt@gmail.com"><img src="https://img.shields.io/badge/E--mail-B04736?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Enviar e-mail" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SQL_Server-B32629?style=flat-square" alt="SQL Server" />
  <img src="https://img.shields.io/badge/T--SQL-80333A?style=flat-square" alt="T-SQL" />
  <img src="https://img.shields.io/badge/C%23-56358C?style=flat-square" alt="C#" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square" alt=".NET" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square" alt="Azure" />
  <img src="https://img.shields.io/badge/Docker-166DA5?style=flat-square" alt="Docker" />
</p>

## Sobre mim

Na Procfit, trabalho com SQL Server em sistemas ERP de alta volumetria. Investigo gargalos em produção, ajusto consultas e índices e implemento regras de negócio em T-SQL. Antes, no Grupo Rasio, desenvolvi em equipe telas e rotinas em C# com Windows Forms e ADO.NET para a programação de cargas e veículos.

Nos meus projetos de backend, gosto de investigar como as decisões da aplicação afetam o banco. Na ProdutosAPI, por exemplo, comparei duas formas de percorrer um catálogo para entender o custo de acessar as páginas mais distantes do início.

## Projetos em destaque

### [ProdutosAPI](https://github.com/xleofarias/ProdutosAPI)

API de catálogo em ASP.NET Core e EF Core. Implementei cache em Redis com invalidação por versão e processamento de eventos em um Worker com MassTransit e Azure Service Bus. O projeto inclui testes com xUnit e um pipeline de CI/CD com GitHub Actions.

Em um **benchmark local com 100 mil produtos**, o tempo de resposta no percentil 95 (p95) foi de **136,65 ms** com paginação por offset profundo e **12,12 ms** com paginação por cursor (keyset).

### [SistemaRelatorios](https://github.com/xleofarias/SistemaRelatorios)

Gerador de relatórios assíncrono. A API recebe o pedido e o encaminha pela fila para um Worker. Assim, o cliente pode consultar o andamento sem manter a requisição aberta até o relatório ficar pronto.

Implementei esse fluxo com ASP.NET Core Minimal API, RabbitMQ e MassTransit, com persistência em PostgreSQL via EF Core. A API e o Worker rodam em contêineres Docker.

## Formação e interesses

Sou formado em Análise e Desenvolvimento de Sistemas pela UNISANTA. Estudo sistemas distribuídos e, nas horas livres, também desenvolvo jogos com C# na Unity e Lua no Roblox Studio.

## GitHub em números

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=xleofarias&amp;show_icons=true&amp;theme=dracula&amp;include_all_commits=true&amp;locale=pt-br" alt="Estatísticas de xleofarias no GitHub" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=xleofarias&amp;layout=compact&amp;theme=dracula&amp;locale=pt-br" alt="Linguagens mais usadas nos repositórios de xleofarias" />
</p>
