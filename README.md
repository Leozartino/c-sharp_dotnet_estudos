# Resumo sobre os Artigos do conteúdo C# e ecossistema .NET


![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white) 



## O que é o .NET Framework?

No artigo: **Quais são as diferenças entre .NET Framework e .NET core** ([link do artigo](https://luby.com.br/net/quais-sao-as-diferencas-entre-net-core-e-net-framework/)), é dito que o .NET Framework foi criado em 2002 com o propósito de desenvolvimento para aplicações windows que posteriormente foi escalado para aplicações na WEB, Windows forms e entre outros. Contudo, ele acabou sendo descontinuado devido alguns problemas de segurança como a assinatura de SHA-1 e que podem gerar graves problemas de invasores e violadores destas aplicações.

## O que é o .NET Core?

Já o .NET core é cross-plataform, isso significa que ele pode "rodar" em várias plataformas, como Linux based, Windows, MacOS e no próprio Windows, sua criação foi em 2016 e visou também resolver problemas que o .NET Framework tinha com relação a encriptação SHA-1.


## .NET Core vs .NET Framework para aplicativos de servidor

Existem algumas diferenças mais na aplicação e contexto de quando usar um ou outro, mas em termos de código não há tantas mudanças. Ambas suportam construir aplicações do lado do servidor, porém as temos de enteder algums diferenças em quando podemos utilizar cada um:

### Use o .NET para o aplicativo de servidor quando:

- Você tiver necessidades de plataforma cruzada.
- Você está direcionando para os microserviços.
- Você está usando contêineres do Docker.
- Você precisar de alto desempenho e sistemas escalonáveis.
- Você precisar de versões do .NET correspondentes a cada aplicativo.

###  Use o .NET Framework para o aplicativo para servidores se:

- Seu aplicativo usar o .NET Framework atualmente (a recomendação é estender em vez de migrar).
- Seu aplicativo usa bibliotecas de terceiros ou pacotes de NuGet não disponíveis para .net.
- Seu aplicativo usa .NET Framework tecnologias que não estão disponíveis para o .net.
- Seu aplicativo usa uma plataforma que não dá suporte ao .NET.

## .NET Framework: tecnologias não disponíveis.

1. Algumas tecnologias .NET Framework não estão disponíveis no .net. A lista a seguir mostra as tecnologias mais comuns não encontradas no .NET:

2. ASP.NET Web Forms aplicativos: ASP.NET Web Forms estão disponíveis apenas no .NET Framework. O ASP.NET Core não pode ser usado para Web Forms do ASP.NET.

3. Aplicativos de páginas da Web do ASP.NET: as páginas da Web do ASP.NET não estão incluídas no ASP.NET Core.

4. Implementação de serviços do WCF. Mesmo quando há uma biblioteca de cliente WCF para consumir serviços WCF do .net, a implementação do servidor WCF está disponível atualmente apenas no .NET Framework.

5. Os serviços relacionados ao fluxo de trabalho: Windows Workflow Foundation (WF), os serviços de fluxo de trabalho (WCF + WF em um único serviço) e WCF Data Services (anteriormente conhecidos como "ADO.NET Data services") estão disponíveis apenas no .NET Framework.

6. Suporte a idiomas: Visual Basic e F # atualmente têm suporte no .net, mas não para todos os tipos de projeto. Para obter uma lista de modelos de projeto com suporte, consulte Opções de modelo para o dotnet new.


## License
[MIT](https://choosealicense.com/licenses/mit/)
