# essential20
Repositório do Essential 2.0
Ferramentas do ambiente de desenvolvimento

Qualquer ambiente de desenvolvimento pode ser utilizado, porém, recomendamos a seguinte lista recursos. Eles são amplamente conhecidos e são usados pela maioria dos desenvolvedores do Essential.


Sumário (Recursos básicos)

1. Servidor AMP
1.1 Linux
1.2 Windows
2. Chrome/Firefox
2.1 Chrome
2.2 Firefox
2.3 Plugins
3. SquirrelSQL
4. Eclipse (Qualquer versão)
4.1 Instalação do Eclipse
4.2 Parametrização do Eclipse
4.3 Instalação do plugin Eclipse PDT para PHP
4.4 Configurar o Eclipse para obter o código fonte (GIT)

Observação: Estas são as principais ferramentas recomendadas, porém todas as ferramentas compatíveis com padrões Web, PHP, Mysql e Web podem ser usadas.

1. Servidor AMP
Apache, Mysql e PHP

1.1 Linux: esses 3 produtos estão disponíveis em toda a distribuição Linux por padrão.
1.2 Windows: instale o WampServer 2 (banco de dados Mysql, Apache e PHP que vem no pacote completo). Este servidor WAMP oferece o MySql + Apache + PHP, com a possibilidade de alterar a versão de qualquer um desses componentes com um simples comando.

2. Chrome/Firefox e plugins

2.1 Chrome: Faça o download do Chrome no segunte endereço: http://www.chrome.com
2.2 Firefox: Faça o Firefox 3.0 com plugins:
2.3 Plugins: Firebug + Firecookie + FirePHP, Validator HTML, User Agent Switcher para simular o uso de smartphones.
Selenium IDE, Cert Viewer Plus se você planeja fazer testes com o HTTPS, QuickProxy se você quiser mudar rapidamente as ferramentas proxy (WebScarab). Faça o download no endereço http://www.firefox.com

3. SquirrelSQL (para administração de banco de dados)

Você pode baixá-lo em http://squirrel-sql.sf.net

4. Eclipse e plugins

4.1 Instalação do Eclipse: Recomendamos usar uma versão do Eclipse fornecida no endereço eclipse.org. Exemplo: https://eclipse.org/pdt/. É possível trabalhar com qualquer versão do Eclipse .

4.2 Parametrização do Eclipse

Uma vez instalado o Eclipse, é recomendavel configurar os seguintes parâmetros:

* Windows - Preferences - Gereral - Workspace - Codificação de arquivo de texto -> UTF8
* Windows - Preferences - Gereral - Workspace - Novo delimitador de linha de arquivo de texto -> Unix
* Windows - Preferences - Gereral - Comparare / Patch - Ignorar espaços em branco -> Sim
* Windows - Preferences - Gereral - Editor - Text Editor - Comprimento do delimitador da guia -> 4
* Windows - Preferences - Gereral - Editor - Text Editor - Inserir espaços para guia -> Não
* Windows - Preferences - Gereral - Editor - File Association -> Adicionar * .lang associado ao "Editor de texto"
Observação: Você também pode desativar o recurso em Windows - Preferences - Java - Editor - Content Assist - Auto activation

E se o PDT estiver instalado (veja mais adiante):

* Window - Preferences - General - Workspace - Text file encoding -> UTF8
* Window - Preferences - General - Workspace - New text file line delimiter -> Unix
* Window - Preferences - General - Compare/Patch - Ignore white spaces -> Yes
* Window - Preferences - General - Editor - Text editors - Tab delimiter length -> 4
* Window - Preferences - General - Editor - Text editors - Insert spaces for tab -> No
* Window - Preferences - General - Editor - File Association -> Adicione *.lang associated à "Text Editor"
Observação: Você também pode desativar Windows - Preferences - PHP - Editor - Content Assist - Auto activation

4.3 Instalação do plugin Eclipse PDT para PHP:

Se você instalou a versão do Eclipse e a PDT não está incluída, tudo o que você precisa fazer é acessar a rotina Help -> Install new software -> Add -> Archive to add module:

http://download.eclipse.org/releases/helios (Eclipse 3.6)

http://download.eclipse.org/releases/indigo (Eclipse 3.7)

Caso tenha baixado o Eclipse Juno (4.2) ou do Eclipse Kepler (4.3), acesse Help => Install New Sofware => Work With Kepler => Aguarde até carregar a lista e em seguida acesse => General Purpose Tools selecione PHP developpement tools (PDT) => Install

Após a instalação, você  deve configurar o PDT no Eclipse conforme explicado no capítulo Environment_and_development_tools _-_ Optionnal_components # From_Eclipse

4.4 Configurar o Eclipse para obter o código fonte (GIT)

Após a instalação do Eclipse, você pode se conectar ao repositório GIT para obter a última versão de desenvolvimento.
