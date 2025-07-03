# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS #

Data: 03/07/2025
Empresa: Abstergo Industries
Responsável: Arédio G. Borges Filho

## Introdução
	Este relatório apresenta o processo de implementação de ferramentas AWS na empresa Abstergo Industries, com o objetivo principal de reduzir custos operacionais e aumentar a eficiência dos sistemas de TI que suportam a distribuição de medicamentos para farmácias no modelo B2B. O projeto foi conduzido por Arédio G. Borges Filho.
	
## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

	Nome da ferramenta: Amazon EC2 Auto Scaling

	Foco da ferramenta: Ajustar automaticamente a quantidade de instâncias EC2 para atender a demanda, evitando desperdício com capacidade ociosa.

	Descrição de caso de uso: Configurar grupos de Auto Scaling para as aplicações web que suportam a plataforma de distribuição, garantindo que apenas o número necessário de servidores esteja ativo, reduzindo gastos com instâncias subutilizadas.

Etapa 2:

	Nome das ferramentas: Amazon S3 e AWS Lambda

	Foco das ferramentas: Armazenamento eficiente e processamento serverless para manipulação de dados e documentos.

	Descrição de caso de uso: Migrar arquivos estáticos e logs para o Amazon S3, que oferece armazenamento barato e escalável. Utilizar funções Lambda para processar eventos (exemplo: limpeza automática de arquivos antigos ou geração de relatórios), evitando custos com servidores dedicados para essas tarefas.

Etapa 3:

	Nome das ferramentas: Amazon RDS e Amazon CloudWatch

	Focos das ferramentas: Banco de dados gerenciado com monitoramento integrado para otimização e alertas proativos.

	Descrição de caso de uso: Migrar bancos de dados para Amazon RDS com escalabilidade e backups automáticos, reduzindo custos de manutenção e riscos de downtime. Utilizar CloudWatch para monitorar métricas e configurar alertas para ajustar recursos antes que ocorra sobrecarga ou uso ineficiente.

## Conclusão
	A implementação das ferramentas Amazon EC2 Auto Scaling, Amazon S3, AWS Lambda, Amazon RDS e Amazon CloudWatch na Abstergo Industries resultou na otimização do uso de recursos computacionais, automação de processos e maior visibilidade operacional. Com isso, espera-se uma redução significativa nos custos de infraestrutura, maior eficiência e agilidade na operação dos sistemas que suportam a cadeia de distribuição farmacêutica. Recomenda-se a continuidade da análise periódica de uso e a exploração de novas tecnologias para maximizar os benefícios.
	
## Anexos
- Guia de configuração do Auto Scaling
- Documentação das funções Lambda implementadas
- Relatório de monitoramento do CloudWatch
- Plano de migração para Amazon RDS

Assinatura do Responsável pelo Projeto:
	Arédio G. Borges Filho
