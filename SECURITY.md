# Política de Segurança – PortfolioHUB

## Autenticação
- Todas as contas Google e GitHub dos colaboradores devem usar **verificação em duas etapas (2FA)**.
- Documentos e repositórios devem ser acessíveis apenas a usuários autorizados.

## Permissões
- No Google Drive: compartilhamento por e-mail, sem links públicos.
- No GitHub:
  - Branch `main` protegida
  - Revisões obrigatórias para PRs
  - Sem acesso de escrita para colaboradores externos

## Controle de Versão
- Versionamento sem arquivos sensíveis
- Utilização do `.gitignore` para ignorar:
  ```
  node_modules/
  *.log
  *.env
  ```

## Auditoria
- Histórico de alterações rastreado via Git
- Comentários e discussões documentadas via Issues e Pull Requests
