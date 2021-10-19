# Arquitetura da Solução

Nesta seção são apresentados os detalhes técnicos da solução criada pela equipe, tratando dos componentes que fazem parte da solução e do ambiente de hospedagem da solução. 

## Diagrama de componentes

Os componentes que fazem parte da solução são apresentados na Figura que se segue. 

![image](https://user-images.githubusercontent.com/90807404/137996728-7a97469f-a530-42b1-b881-6a47519fdac8.png)

A solução implementada conta com os seguintes módulos: 

•	Navegador: Interface básica do sistema

o	Página Web: Conjunto de arquivos HTML, CSS, Java Script e imagens que implementam as funcionalidades do sistema. 

o	Local Storage: Armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON

•	News API: plataforma que permite o compartilhamento das tarefas no Facebook.

•	Hospedagem: Local na internet onde as páginas são mantidas e acessas pelo navegador. 

## Hospedagem

O site utiliza a plataforma do Microsoft Azure como ambiente de hospedagem do site do projeto. O site é mantido no ambiente da URL: 

https://portal.azure.com/#blade/HubsExtension/ArgQueryBlade/query/%2F%2F%20Execute%20a%20consulta%20para%20ver%20os%20resultados.%0A/formatResults/true 

A publicação do site no Microsoft Azure é feita por meio de uma submissão do projeto (push) via GitHub para o repositório remoto que se encontra no endereço: 

https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2021-2-e1-proj-web-t8-organizador-de-tarefas
