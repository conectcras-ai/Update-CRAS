# Update-CRAS

Publique o conteudo desta pasta no repositorio publico:

https://github.com/conectcras-ai/Update-CRAS

Estrutura esperada:

- manifest.xml
- public.pem
- app/cras-app-1.0.0-all.jar

Versao publicada: 1.0.14. O nome fisico do JAR permanece estavel para atualizar instalacoes existentes.
O manifesto contem tamanho, checksum e assinatura digital.
Esta versao corrige a versao exibida no menu lateral e na tela Sobre, usa um unico download para os layouts instalado e portatil e reforca a validacao da substituicao do JAR.

Para o botao Sobre > Atualizar sistema detectar nova versao, a versao do manifest precisa ser maior que a versao instalada.
