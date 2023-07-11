Data: 10/07/2023
Empresa: Abstergo Industries 
Responsável: Silvia Rocha

<h1>Introdução</h1>
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Silvia Rocha. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

<h1>Objetivo Estratégico</h1> 
Este projeto está relacionado ao objetivo estratégico de <b>aumento da eficiência</b> da empresa. Relaciona-se ao objetivo de ampliação do mercado pela transformação da empresa de uma revendedora de produtos farmacêuticos para um grande hub de distribuição de tais produtos.

<h1>Descrição do Projeto</h1>
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

<h2>Etapa 1: Implantação do AWS Elastic Disaster Recovery <sup>1</sup></h2>

* <b>Minimizar o tempo de indisponibilidade e a perda de dados</b> através de uma recuperação confiável de aplicações hospedadas nos equipamentos do datacenter da empresa (ou em nuvem), usando armazenamento econômico, recursos computacionais mínimos e recuperação no caso de um evento de desastre.
* <b>Reduzir o custo de recuperação de desastres</b> com a utilização do serviço AWS Elastic Disaster Recovery com alocação de recursos de rede da Amazon VPC e de recursos computacionais da Amazon EC2.
  * Antes de realizar a migração dos recursos on-premises para a nuvem, é necessário garantir que as aplicações da empresa estejam disponíveis para atender aos pedidos dos compradores.
  * O serviço AWS Elastic Disaster Recovery possibilita garantir um tempo aceitável de recuperação de desastres, com segurança, sem que seja necessário investir em novos equipamentos e softwares para o datacenter da empresa.
* Veja <a href="https://aws.amazon.com/pt/solutions/case-studies/olli-salumeria-case-study/"> aqui como a empresa Olli Salumeria economizou 80% nos custos de recuperação de desastres da infraestrutura do SAP ERP usando AWS</a>.
* Veja <a href="https://aws.amazon.com/es/solutions/case-studies/marzam/">aqui como a distribuidora Marzan economizou 85% em gastos de capital (capex) ao migrar sua infraestrutura de recuperação de desastres para a AWS</a>.

<h2>Etapa 2: Migração dos servidores de aplicação para a nuvem AWS<sup>2</sup></h2> 

* Utilizar o <b>AWS Application Migration Service</b> para automatizar a migração do servidores de aplicação para a nuvem AWS.
* O AWS Application Migration Service é uma solução altamente automatizada de migração de servidores para a nuvem, que simplifica, acelera e reduz os custos de migração.
* O AWS MGN replica os servidores de origem na conta da AWS, criando recursos como instâncias EC2 e serviços EBS.
Uma vez que a migração tenha sido concluída, a empresa poderá se beneficiar rapidamente da diminuição dos custos, da produtividade, da resiliência e da agilidade dos serviços em nuvem da AWS.
Depois de ter suas aplicações migradas para a nuvem, a empresa poderá aperfeiçoá-las, para aproveitar melhor os benefícios oferecidos pelos serviços da AWS.
* Veja <a href="https://www.softwareone.com/pt-br/estudos-de-caso/global/nonprofit/nonprofit-cooperative-simple-for-aws">aqui como uma cooperativa de saúde brasileira economizou 35% em TCO migrando para a nuvem AWS</a>.

<h2>Etapa 3: Monitoramento dos recursos<sup>3, 4</sup></h2> 

* É essencial iniciar o monitoramento do desempenho e dos custos dos recursos alocados na nuvem assim que os mesmos forem criados.
* Acompanhando os indicadores de desempenho, será possível planejar a otimização das aplicações e dos recursos.
* Acompanhando os indicadores de custos, será possível manter-se dentro do orçamento e planejar melhorias que aumentem a eficiência.
* A ferramenta <b>AWS Cloud Watch</b> coleta continuamente dados de desempenho, eventos e métricas selecionadas, mostrando tudo num painel de controle que permite a visualização de todos os recursos e aplicações rodando na nuvem AWS.
* O Amazon CloudWatch facilita a resolução de problemas de mau-funcionamento de aplicações ou perda de desempenho.
Além disso, possibilita a automatização do planejamento da otimização dos recursos, com a consequente redução de custos.
* Junto com a ferramenta <b>AWS Cost & Usage Report</b>, o Amazon CloudWatch permite a visualização dos recursos que estejam superdimensionados e possam ser reduzidos para economia de custos.
* Além disso, a visualização dos dados de utilização, desempenho e custos em painéis de controle facilita a adoção de estratégias de redução das despesas com a nuvem, tais como: uso de <i>instâncias spot, instâncias reservadas ou savings plans</i>.
* Veja <a href = "https://aws.amazon.com/pt/solutions/case-studies/microstrategy-cost-management/?pg=ln&sec=c">aqui como a MicroStrategy cortou 30% dos custos da nuvem AWS usando o AWS Cost & Usage Report</a>



<h1>Conclusão</h1>
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução dos custos de TCO com o aumento da escalabilidade dos seus recursos computacionais, frente ao incremento das operações de venda, o que aumentará a eficiência e a produtividade da empresa. <br>
Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.<br>
Após a migração e o controle dos custos, a empresa terá recursos humanos liberados para investir na inovação dos seus processos e poderá estudar a utilização de outros serviços da AWS que auxiliem nessa evolução, tais como AWS IoT (internet das coisas) e as ferramentas de inteligência artificial.<br><br>

<h1>Fontes</h1>

<sup>1</sup> https://aws.amazon.com/disaster-recovery/<br>
<sup>2</sup> https://aws.amazon.com/pt/application-migration-service/<br>
<sup>3</sup> https://aws.amazon.com/pt/cloudwatch/<br>
<sup>4</sup> https://aws.amazon.com/pt/aws-cost-management/aws-cost-and-usage-reporting/<br>


<h1>Anexos</h1>

Gerenciamento financeiro na nuvem com AWS: https://aws.amazon.com/pt/aws-cost-management/?pg=ln&sec=hs<br>
Arista Group Migrates to AWS To Lower IT Costs: https://aws.amazon.com/pt/solutions/case-studies/arista-group-case-study/?pg=ln&sec=c<br>
Plataforma digital Lynx, da Carrier, desenvolvida em colaboração com a AWS, aplica tecnologia IoT e aprendizado de máquina para conectar a cadeia fria na nuvem, automatizar processos e oferecer insights em tempo real durante toda a jornada da carga: https://aws.amazon.com/pt/campaigns/carrier/



Assinatura do Responsável pelo Projeto:

<i>Silvia Rocha</i>