CONFIGURAÇÃO DO PROJETO DE TESTES FUNCIONAIS DA AMERICANAS 
1 - Atualizar as Dependências do Projeto Acessar o diretório do projeto sei-teste e atualizar as dependências do maven
utilizando as libs que estão inseridas. 

ALT + F5 para dar update Maven e baixar as dependencia. 

2 - Executar o Servidor de Teste Selenium PS: Em caso de erro "Connection Refused", verificar se a versão do chromedriver informada no parâmetro -Dwebdriver.chrome.driver é compatível com a versão do Chrome instalada

Linux:

java -jar -Dwebdriver.chrome.driver=lib/drivers/chromedriver-2.30 lib/selenium-server-standalone-2.45.0.jar

Windows:

java -jar -Dwebdriver.chrome.driver=lib\drivers\chromedriver-2.30.exe lib\selenium-server-standalone-2.45.0.jar

3 - Executar o Teste Funcional Automatizado

RUN - no ecplipse para executar o testes;
