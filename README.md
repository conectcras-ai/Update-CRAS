# Update-CRAS

Versão publicada: 1.0.33.

Inclui a migração aditiva V2026_10_08_02__scfv_auditoria_excecao_etaria.sql para histórico das autorizações de exceção do SCFV. Não inventa autoria para vínculos antigos. 26 testes automatizados passaram. Faça backup verificado do banco e dos anexos e atualize primeiro o CRAS no servidor. Confirme a migração no Flyway, depois atualize todos os clientes SCFV para 1.0.40. Não use repair/clean para contornar erros. Esta publicação não executou a migração no MySQL.

Canal: https://github.com/conectcras-ai/Update-CRAS

Arquivos: manifest.xml, public.pem e app/cras-app-1.0.0-all.jar.
O manifesto é assinado e inclui versão, tamanho, checksum e assinatura do binário.
O nome físico do JAR permanece estável para as instalações existentes.
Use Sobre > Verificar / Atualizar agora. A publicação não instala automaticamente nos computadores.
