# Update-CRAS

Versão publicada: 1.0.34.

O atualizador inicia pelo WScript gráfico e executa o aplicador PowerShell com janela oculta, preservando a autorização administrativa do Windows. A versão real é lida da configuração empacotada no JAR; o manifesto embutido antigo não provoca mais apresentação/comparação erradas. Inclui a migração de auditoria do SCFV da 1.0.33. Faça backup e atualize primeiro o CRAS servidor, depois o SCFV 1.0.41. A publicação não instala programas nem executa migrações no servidor.

Canal: https://github.com/conectcras-ai/Update-CRAS

Arquivos: manifest.xml, public.pem e app/cras-app-1.0.0-all.jar.
O manifesto é assinado e inclui versão, tamanho, checksum e assinatura do binário.
O nome físico do JAR permanece estável para as instalações existentes.
Use Sobre > Verificar / Atualizar agora. A publicação não instala automaticamente nos computadores.
