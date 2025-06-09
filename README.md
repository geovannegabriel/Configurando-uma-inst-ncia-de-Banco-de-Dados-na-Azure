Resumo do Lab – Configuração de Instância de Banco de Dados no Microsoft Azure
Este repositório documenta o desafio prático proposto no Bootcamp Microsoft 50 Anos, focado na criação e configuração de uma instância de banco de dados na plataforma Azure. O objetivo é aplicar os conhecimentos adquiridos e registrar aprendizados úteis para futuras implementações.

Objetivo do Desafio
Realizar o provisionamento de uma instância gerenciada de banco de dados no Azure.

Compreender os principais parâmetros de configuração.

Testar o acesso à instância e explorar as opções de monitoramento.

Registrar o processo como material de apoio técnico.

Etapas Realizadas
Acesso ao Portal Azure

Acesso via: https://portal.azure.com

Verificação da assinatura ativa e seleção do diretório.

Criação da Instância de Banco de Dados

Acesso ao serviço "SQL Databases" no menu lateral.

Escolha do grupo de recursos e nome da instância.

Seleção de servidor existente ou criação de um novo servidor SQL (definição de nome, login e senha).

Escolha do nível de desempenho e tipo de armazenamento (DTU ou vCore).

Configuração de Acesso

Definição de regras de firewall para permitir o acesso ao IP local.

Autenticação via SQL Server Management Studio (SSMS) ou Azure Data Studio.

Teste de conexão com os dados de login criados.

Monitoramento e Segurança

Acompanhamento do desempenho via painel do Azure.

Ativação de logs de auditoria, backups automáticos e alertas.

Aplicação de boas práticas como senhas fortes e regras de acesso restritas.

Anotações e Dicas
Use nomenclaturas padronizadas para facilitar a organização dos recursos.

Prefira criar um servidor SQL separado por ambiente (teste, produção, etc).

Mantenha as regras de firewall restritivas, liberando apenas IPs necessários.

Faça backup manual antes de alterações críticas, mesmo com backup automático ativado.

Utilize Azure Advisor e Monitor para recomendações de otimização e análise de desempenho.

Conclusão
A prática de configurar uma instância de banco de dados no Azure proporciona uma base sólida para projetos em ambientes reais. A familiaridade com o portal, opções de segurança e performance é essencial para atuar com soluções baseadas em nuvem de forma eficiente e segura.
