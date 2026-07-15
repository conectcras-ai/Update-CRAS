# Update-CRAS

Publique o conteudo desta pasta no repositorio publico:

https://github.com/conectcras-ai/Update-CRAS

Estrutura esperada:

- manifest.xml
- public.pem
- app/cras-app-1.0.0-all.jar

Versao publicada: 1.0.15. O nome fisico do JAR permanece estavel para atualizar instalacoes existentes.
O manifesto contem tamanho, checksum e assinatura digital.
Esta versao permite ao servidor copiar com autenticacao a senha tecnica aleatoria e ao cliente informa-la em campo protegido durante a conexao. Nenhuma senha fixa e embutida no codigo ou no instalador.

Para o botao Sobre > Atualizar sistema detectar nova versao, a versao do manifest precisa ser maior que a versao instalada.
