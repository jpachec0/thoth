# Seguranca

Este documento apresenta uma visao de seguranca em nivel de produto. Detalhes internos de implementacao sao privados.

## Controle de Acesso

O THOTH utiliza autenticacao para restringir o acesso ao sistema. Paginas e operacoes internas exigem usuario autenticado.

## Permissoes

Operacoes administrativas sao restritas a usuarios autorizados. Acoes sensiveis, como gerenciamento de usuarios e exclusoes administrativas, seguem controle de permissao.

## Auditoria

Eventos relevantes podem ser registrados para consulta posterior, permitindo maior rastreabilidade sobre alteracoes e operacoes realizadas.

## Protecao de Dados

O sistema foi pensado para uso local/institucional, com banco de dados protegido pelo ambiente de execucao e acesso controlado pela aplicacao.

## Recomendacoes Operacionais

- Manter o computador de execucao protegido por senha.
- Nao compartilhar credenciais administrativas.
- Realizar backups periodicos.
- Evitar expor o sistema diretamente na internet sem revisao adicional de seguranca.
- Manter Docker, sistema operacional e navegador atualizados.

## Codigo-Fonte Privado

O codigo-fonte, banco de dados, scripts internos, arquivos de configuracao sensiveis e regras de implementacao nao sao publicados neste repositorio.
