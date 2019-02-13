# ExemploAngular

Uma aplicação em Angular consumindo uma API REST

Para executar este modelo deve-se baixar e executar o codigo que contem a API Rest de Serviços:
https://github.com/MaviaLima/Servicos24Help.git

# ATENÇÃO
Deve-se realizar alguns cadastros para que se construa uma massa de dados.
Caso na execução do Angular ocorra um erro de CORS (CORS header ‘Access-Control-Allow-Origin’ missing).
Ex.: 'Cross-Origin Request Blocked: The Same Origin Policy disallows reading the remote resource at https://localhost:8080' 
o que me salvou foi a extensão chrome: [chrome.google.com/webstore/detail/allow-control-allow-origin/…. 
As extensões de navegador tem menos restrições para realizarem requisições
Para o GoogleChrome deve-se incluir e habilitar esta extensão.

# EndPoints REST:
Lista de Serviços - GET
/rest/servicos

Para salvar o servico - POST
/rest/servico


