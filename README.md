# Update-CRAS

Versão publicada: **1.0.31**.

Inclui a migração central do SCFV para responsável por ID, vínculo e detalhe da origem.
Faça backup verificado do banco e dos anexos no servidor antes de atualizar.
Atualize e reinicie o ConectCRAS no servidor primeiro; confirme o Flyway nos logs
antes de usar o SCFV 1.0.36 nos clientes. Não execute repair/clean para contornar erros.

Validação: 24 testes automatizados sem falhas; histórico de 114 migrações
validado por leitura no laboratório MySQL 8.0.44. Nenhuma migração histórica alterada.

Publique o conteudo desta pasta no repositorio publico:

https://github.com/conectcras-ai/Update-CRAS

Estrutura esperada:

- manifest.xml
- app/cras-app-1.0.0-all.jar

Para o botao Sobre > Atualizar sistema detectar nova versao, a versao do manifest precisa ser maior que a versao instalada.
