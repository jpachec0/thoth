# Segurança

Este documento apresenta uma visão de segurança em nível de produto. Detalhes internos de implementação são privados.

## Controle de Acesso

O THOTH utiliza autenticação para restringir o acesso ao sistema. Páginas e operações internas exigem usuário autenticado.

## Permissões

Operações administrativas são restritas a usuários autorizados. Ações sensíveis, como gerenciamento de usuários e exclusões administrativas, seguem controle de permissão.

## Auditoria

Eventos relevantes podem ser registrados para consulta posterior, permitindo maior rastreabilidade sobre alterações e operações realizadas.

## Proteção de Dados

O sistema foi pensado para uso local/institucional, com banco de dados protegido pelo ambiente de execução e acesso controlado pela aplicação.

## Recomendações Operacionais

- Manter o computador de execução protegido por senha.
- Não compartilhar credenciais administrativas.
- Realizar backups periódicos.
- Evitar expor o sistema diretamente na internet sem revisão adicional de segurança.
- Manter Docker, sistema operacional e navegador atualizados.

## Código-Fonte Privado

O código-fonte, banco de dados, scripts internos, arquivos de configuração sensíveis e regras de implementação não são publicados neste repositório.
