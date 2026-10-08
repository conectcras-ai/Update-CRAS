# Update-CRAS

Versão publicada: 1.0.32.

Inclui a migração aditiva V2026_10_08_01__scfv_grupos_multiplos_horarios.sql, preservando horários legados e sessões históricas. 25 testes automatizados passaram. Faça backup verificado do banco e dos anexos e atualize primeiro o CRAS no servidor. Confirme a migração no Flyway antes de usar os novos horários no SCFV 1.0.38. Não use repair/clean para contornar erros. Esta publicação não executou a migração no MySQL.

Canal: https://github.com/conectcras-ai/Update-CRAS

Arquivos: manifest.xml, public.pem e app/cras-app-1.0.0-all.jar.
O manifesto é assinado e inclui versão, tamanho, checksum e assinatura do binário.
O nome físico do JAR permanece estável para as instalações existentes.
Use Sobre > Verificar / Atualizar agora. A publicação não instala automaticamente nos computadores.
