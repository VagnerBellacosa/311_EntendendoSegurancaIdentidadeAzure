# Introdução à segurança do Azure



Neste artigo

[Visão geral](https://learn.microsoft.com/pt-br/azure/security/fundamentals/overview#overview)

[Resumo dos recursos de segurança do Azure](https://learn.microsoft.com/pt-br/azure/security/fundamentals/overview#summary-of-azure-security-capabilities)

[Operations](https://learn.microsoft.com/pt-br/azure/security/fundamentals/overview#operations)

[Aplicativos](https://learn.microsoft.com/pt-br/azure/security/fundamentals/overview#applications)



## Visão geral

Sabemos que a segurança é o primeiro trabalho na nuvem e o quanto é importante que você encontre informações precisas e atualizadas sobre a segurança do Azure. Uma das melhores razões para usar o Azure para seus aplicativos e serviços é aproveitar sua ampla variedade de ferramentas e recursos de segurança. Essas ferramentas e recursos ajudam a tornar possível criar soluções seguras na plataforma segura do Azure. O Microsoft Azure fornece confidencialidade, integridade e disponibilidade dos dados do cliente, ao mesmo tempo que também permite uma responsabilidade transparente.

Este artigo fornece uma visão abrangente da segurança disponível com o Azure.



### Plataforma do Azure

O Azure é uma plataforma de serviço de nuvem pública que dá suporte a uma ampla seleção de sistemas operacionais, linguagens de programação, estruturas, ferramentas, bancos de dados e dispositivos. Ele pode executar contêineres do Linux com a integração com o Docker, criar aplicativos com JavaScript, Python, .NET, PHP, Java e Node.js e criar back-ends para dispositivos iOS, Android e Windows.

Os serviços de nuvem pública do Azure dão suporte às mesmas tecnologias com as quais milhões de desenvolvedores e profissionais de TI já contam e nas quais confiam. Ao se basear ou migrar ativos de TI para um provedor de serviços de nuvem pública, você está confiando na capacidade dessa organização de proteger seus aplicativos e dados com os serviços e os controles que ela oferece para gerenciar a segurança de seus ativos baseados em nuvem.

A infraestrutura do Azure foi projetada desde a instalação até os aplicativos para hospedar milhões de clientes simultaneamente e fornece uma base confiável com a qual as empresas podem atender aos seus requisitos de segurança.

Além disso, o Azure oferece uma ampla variedade de opções de segurança configuráveis e a capacidade de controlá-las, de forma que você possa personalizar a segurança para atender aos requisitos exclusivos das implantações de sua organização. Este documento ajuda você a entender como as funcionalidades de segurança do Azure podem ajudá-lo a atender a esses requisitos.

 Observação

O foco principal deste documento são os controles voltados para o cliente que você pode usar para personalizar e aumentar a segurança de seus aplicativos e serviços.

Para obter informações sobre como a Microsoft protege a plataforma do Azure, consulte [Segurança de infraestrutura do Azure](https://learn.microsoft.com/pt-br/azure/security/fundamentals/infrastructure).



## Resumo dos recursos de segurança do Azure

Dependendo do modelo de serviço de nuvem, a responsabilidade de quem gerencia a segurança do aplicativo ou serviço varia. Há recursos disponíveis na Plataforma Azure para ajudar você a cumprir essas responsabilidades por meio de recursos internos, e soluções de parceiros que podem ser implantadas em uma assinatura do Azure.

Os recursos internos são organizados em seis áreas funcionais: Operações, Aplicativos, Armazenamento, Rede, Computação e Identidade. Os detalhes adicionais sobre os recursos e funcionalidades disponíveis na Plataforma do Azure nessas seis áreas são fornecidos por meio de informações de resumo.



## Operations

Esta seção fornece outras informações sobre os principais recursos em operações de segurança, e informações de resumo sobre esses recursos.



### Microsoft Sentinel

O [Microsoft Azure Sentinel](https://learn.microsoft.com/pt-br/azure/sentinel/overview) é uma solução escalonável e nativa da nuvem que oferece SIEM (gerenciamento de eventos de informações de segurança) e SOAR (orquestração de segurança, automação e resposta). O Microsoft Sentinel oferece análise inteligente de segurança e inteligência contra ameaças em toda a empresa, com uma solução para detecção de ataques, visibilidade de ameaças, procura proativa e resposta a ameaças.



### Microsoft Defender para Nuvem

O [Microsoft Defender para Nuvem](https://learn.microsoft.com/pt-br/azure/security-center/security-center-introduction) ajuda você a impedir, detectar e responder a ameaças com maior visibilidade e controle sobre a segurança dos seus recursos do Azure. Ela permite o gerenciamento de políticas e o monitoramento da segurança integrada entre suas assinaturas do Azure, ajuda a detectar ameaças que poderiam passar despercebidas e funciona com uma enorme variedade de soluções de segurança.

Além disso, o Defender para nuvem ajuda com operações de segurança, fornecendo um único painel que mostra alertas e recomendações que podem ser agidos imediatamente. Geralmente, você pode resolver problemas com um único clique no console do Defender para nuvem.



### Azure Resource Manager

O [Azure Resource Manager](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/overview) permite trabalhar com os recursos da sua solução como um grupo. Você pode implantar, atualizar ou excluir todos os recursos da sua solução em uma única operação coordenada. Use um [modelo do Azure Resource Manager](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/templates/overview) para a implantação, e esse modelo pode ser útil para diferentes ambientes, como teste, preparação e produção. O Gerenciador de Recursos fornece recursos de segurança, auditoria e marcação para ajudá-lo a gerenciar seus recursos após a implantação.

As implantações baseadas em modelos do Azure Resource Manager ajudam a melhorar a segurança das soluções implantadas no Azure devido às configurações de controle de segurança padrão, e podem ser integradas às implantações baseadas em modelo padronizadas. Isso reduz o risco de erros de configuração de segurança que podem ocorrer durante as implantações manuais.



### Application Insights

O [Application Insights](https://learn.microsoft.com/pt-br/azure/azure-monitor/app/app-insights-overview) é um serviço de Gerenciamento de Desempenho de Aplicativos (APM) extensível para desenvolvedores da Web. Com o Application Insights, você pode monitorar seus aplicativos Web ativos e detectar automaticamente as anomalias no desempenho. Ele inclui ferramentas de análise avançadas para ajudar você a diagnosticar problemas e entender o que os usuários realmente fazem com seu aplicativo. Ele monitora seus aplicativos em todo o tempo de execução, tanto durante o teste quanto depois de publicado ou implantado.

O Application Insights cria gráficos e tabelas que mostram, por exemplo, em que horas do dia você tem mais usuários, o nível de capacidade de resposta do aplicativo e quão bem ele é atendido por quaisquer serviços externos dos quais depende.

Se houver travamentos, falhas ou problemas de desempenho, você pode pesquisar os dados de telemetria em detalhes para diagnosticar a causa. E o serviço enviará a você emails se houver alterações na disponibilidade e no desempenho de seu aplicativo. Assim, o Application Insight torna-se uma ferramenta de segurança importante, pois ajuda com a disponibilidade na tríade de segurança de disponibilidade, integridade e confidencialidade.



### Azure Monitor

O [Azure Monitor](https://learn.microsoft.com/pt-br/azure/monitoring-and-diagnostics/) oferece a visualização, consulta, roteamento, alertas, dimensionamento automático e automação nos dados da assinatura do Azure ([Logs de Atividade](https://learn.microsoft.com/pt-br/azure/azure-monitor/essentials/platform-logs-overview)) e de cada recurso individual do Azure( [Logs de Recurso](https://learn.microsoft.com/pt-br/azure/azure-monitor/essentials/platform-logs-overview)). Use o Azure Monitor para receber alertas sobre eventos relacionados à segurança que são gerados nos logs do Azure.



### Logs do Azure Monitor

[Logs do Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/logs/log-query-overview) – Fornece uma solução de gerenciamento de TI para infraestrutura local e em nuvem de terceiros (como AWS), além dos recursos do Azure. Os dados do Azure Monitor podem ser roteados diretamente para os logs do Azure Monitor para que você possa ver métricas e logs de todo o ambiente em um único lugar.

Os logs do Azure Monitor podem ser uma ferramenta útil na análise forense e em outras análises de segurança, pois a ferramenta permite que você pesquise rapidamente grandes quantidades de entradas relacionadas à segurança com uma abordagem de consulta flexível. Além disso, os [logs de firewall e de proxy locais podem ser exportados para o Azure e disponibilizados para análise usando os logs do Azure Monitor.](https://learn.microsoft.com/pt-br/azure/azure-monitor/agents/agent-windows)



### Assistente do Azure

O [Assistente do Azure](https://learn.microsoft.com/pt-br/azure/advisor/advisor-overview) é um consultor de nuvem personalizado que ajuda você a otimizar suas implantações do Azure. Ele analisa a configuração dos recursos e a telemetria do uso. Depois, recomenda soluções para ajudar a melhorar o [desempenho](https://learn.microsoft.com/pt-br/azure/advisor/advisor-performance-recommendations), [segurança](https://learn.microsoft.com/pt-br/azure/advisor/advisor-security-recommendations) e [confiabilidade](https://learn.microsoft.com/pt-br/azure/advisor/advisor-high-availability-recommendations) de seus recursos enquanto procura oportunidades para [reduzir a despesa geral do Azure](https://learn.microsoft.com/pt-br/azure/advisor/advisor-cost-recommendations). O Assistente do Azure fornece recomendações de segurança, o que pode melhorar consideravelmente sua postura de segurança geral para soluções implantadas no Azure. Essas recomendações são obtidas da análise de segurança executada pelo [Microsoft Defender para nuvem.](https://learn.microsoft.com/pt-br/azure/security-center/security-center-introduction)



## Aplicativos

A seção fornece outras informações sobre os principais recursos em segurança do aplicativo e informações de resumo sobre esses recursos.



### Teste de penetração

Nós não fazemos [teste de penetração](https://learn.microsoft.com/pt-br/azure/security/fundamentals/pen-testing) do seu aplicativo para você, mas entendemos que você deseja e precisa executar testes nos seus próprios aplicativos. Isso é bom, porque quando você aumenta a segurança de seus aplicativos, você ajuda a tornar todo o ecossistema do Azure mais seguro. Embora a notificação à Microsoft das atividades de teste de penetração não seja mais necessária, os clientes ainda devem estar de acordo com as [Regras de Participação em Testes de Penetração no Microsoft Cloud](https://www.microsoft.com/msrc/pentest-rules-of-engagement).



### Firewall do aplicativo Web

O WAF (firewall de aplicativo Web) no [Gateway de Aplicativo do Azure](https://learn.microsoft.com/pt-br/azure/application-gateway/features#web-application-firewall) protege os aplicativos Web contra ataques comuns baseados na Web, como injeção de SQL, ataques de scripts entre sites e sequestros de sessão. Ele vem pré-configurado com proteção contra as ameaças identificadas pelo [OWASP (Projeto Aberto de Segurança em Aplicativo Web) como as 10 vulnerabilidades mais comuns](https://owasp.org/www-project-top-ten/).



### Autenticação e autorização no Serviço de Aplicativo do Azure

A [Autenticação/Autorização do Serviço de Aplicativo](https://learn.microsoft.com/pt-br/azure/app-service/overview-authentication-authorization) é um recurso que oferece uma maneira para seu aplicativo conectar usuários de forma que você não precise alterar o código no back-end do aplicativo. Ele fornece uma maneira fácil de proteger o aplicativo e trabalhar com dados por usuário.



### Arquitetura de segurança em camadas

Como os [Ambientes do Serviço de Aplicativo](https://learn.microsoft.com/pt-br/azure/app-service/environment/app-service-app-service-environment-intro) fornecem um ambiente de runtime isolado implantado em uma [Rede Virtual do Azure](https://learn.microsoft.com/pt-br/azure/virtual-network/virtual-networks-overview), os desenvolvedores podem criar uma arquitetura de segurança em camadas fornecendo níveis diferentes de acesso à rede para cada camada de aplicativo. Um desejo comum é ocultar os back-ends de API do acesso à Internet geral e só permitir que as APIs sejam chamadas por aplicativos Web upstream. Os [NSGs (grupos de segurança de rede)](https://learn.microsoft.com/pt-br/azure/virtual-network/virtual-network-vnet-plan-design-arm) podem ser usados em sub-redes da Rede Virtual do Azure contendo Ambientes do Serviço de Aplicativo para restringir o acesso público aos aplicativos da API.



### Diagnóstico de servidor Web e diagnóstico de aplicativos

Os [aplicativos da Web do Serviço de Aplicativo](https://learn.microsoft.com/pt-br/azure/app-service/troubleshoot-diagnostic-logs) fornecem funcionalidade de diagnóstico para registrar em log informações tanto do servidor da Web quanto do aplicativo da Web. Estes estão logicamente separados em diagnóstico de servidor Web e diagnóstico de aplicativos. O servidor Web inclui dois grandes avanços em diagnóstico e solução de problemas de sites e aplicativos.

O primeiro são informações de estado em tempo real sobre pools de aplicativos, processos de trabalho, sites, domínios de aplicativo e solicitações em execução. O segundo são os eventos de rastreamento detalhados que rastreiam uma solicitação por todo o processo de solicitação e resposta.

Para habilitar a coleta desses eventos de rastreamento, o IIS 7 pode ser configurado para capturar automaticamente os logs de rastreamento completos, em formato XML, para qualquer solicitação específica com base no tempo decorrido ou em códigos de resposta do erro.



## Armazenamento

A seção fornece outras informações sobre os principais recursos em segurança de armazenamento do Azure e informações de resumo sobre esses recursos.



### RBAC do Azure (controle de acesso baseado em função do Azure)

Você pode proteger a conta de armazenamento com o[Azure RBAC (controle de acesso baseado em função do Azure)](https://learn.microsoft.com/pt-br/azure/role-based-access-control/overview). Restringir o acesso com base nos princípios de segurança de [divulgação restrita àqueles diretamente interessados](https://en.wikipedia.org/wiki/Need_to_know) e no [privilégio mínimo](https://en.wikipedia.org/wiki/Principle_of_least_privilege) é fundamental para as organizações que desejam impor políticas de segurança para acesso a dados. Esses direitos de acesso são concedidos atribuindo a função do Azure apropriada a grupos e aplicativos em determinado escopo. Você pode usar as [funções internas do Azure](https://learn.microsoft.com/pt-br/azure/role-based-access-control/built-in-roles), como Colaborador da Conta de Armazenamento, para atribuir privilégios aos usuários. O acesso às chaves de armazenamento para uma conta de armazenamento usando o modelo do [Azure Resource Manager](https://learn.microsoft.com/pt-br/azure/storage/blobs/security-recommendations#data-protection) pode ser controlado por meio do Azure RBAC.



### Assinatura de acesso compartilhado

Uma [SAS (Assinatura de Acesso Compartilhado)](https://learn.microsoft.com/pt-br/azure/storage/common/storage-sas-overview) fornece acesso delegado aos recursos da sua conta de armazenamento. A SAS significa que você pode conceder a um cliente permissões limitadas para objetos em sua conta de armazenamento por determinado período e com um conjunto específico de permissões. Você pode conceder essas permissões limitadas sem precisar compartilhar as chaves de acesso da conta.



### Criptografia em trânsito

A criptografia em trânsito é um mecanismo de proteção de dados quando eles são transmitidos entre redes. Com o Armazenamento do Azure, você pode proteger dados usando:

- [Criptografia de nível de transporte](https://learn.microsoft.com/pt-br/azure/storage/blobs/security-recommendations), como HTTPS ao transferir dados dentro ou fora do Armazenamento do Azure.
- [Criptografia na transmissão](https://learn.microsoft.com/pt-br/azure/storage/blobs/security-recommendations), como a [criptografia SMB 3.0](https://learn.microsoft.com/pt-br/azure/storage/blobs/security-recommendations) para [compartilhamentos de Arquivo do Azure](https://learn.microsoft.com/pt-br/azure/storage/files/storage-dotnet-how-to-use-files).
- Criptografia do cliente, que permite criptografar os dados antes que eles sejam transferidos para o armazenamento e descriptografá-los após serem transferidos para fora do armazenamento.



### Criptografar em repouso

Para muitas organizações, a criptografia de dados em repouso é uma etapa obrigatória no sentido de garantir a soberania, a privacidade e a conformidade dos dados. Há três recursos de segurança de armazenamento do Azure que fornecem criptografia de dados que estão “em repouso”:

- [Criptografia do Serviço de Armazenamento](https://learn.microsoft.com/pt-br/azure/storage/common/storage-service-encryption) permite solicitar que o serviço de armazenamento criptografe automaticamente os dados ao gravá-los no Armazenamento do Azure.
- [Client-side Encryption](https://learn.microsoft.com/pt-br/azure/storage/common/storage-client-side-encryption) também fornece o recurso de criptografia em repouso.
- A [Azure Disk Encryption para VMs do Linux](https://learn.microsoft.com/pt-br/azure/virtual-machines/linux/disk-encryption-overview) e a [Azure Disk Encryption para VMs do Windows](https://learn.microsoft.com/pt-br/azure/virtual-machines/linux/disk-encryption-overview) permitem criptografar os discos do sistema operacional e discos de dados usados por uma máquina virtual IaaS.



### Análise de Armazenamento

O [Azure Storage Analytics](https://learn.microsoft.com/pt-br/rest/api/storageservices/fileservices/storage-analytics) executa o registro em log e fornece dados de métrica para uma conta de armazenamento. Você pode usar esses dados para rastrear solicitações, analisar tendências de uso e diagnosticar problemas com sua conta de armazenamento. A análise de armazenamento registra informações detalhadas sobre solicitações bem-sucedidas e com falha para um serviço de armazenamento. Essas informações podem ser usadas para monitorar solicitações individuais e diagnosticar problemas com um serviço de armazenamento. As solicitações são registradas em uma base de melhor esforço. Os seguintes tipos de solicitações autenticadas são registrados:

- Solicitações bem sucedidas.
- Solicitações com falha, incluindo o tempo limite, limitação, rede, autorização e outros erros.
- Solicitações que usam uma SAS (Assinatura de Acesso Compartilhado), incluindo solicitações bem-sucedidas e com falha.
- Solicitações para dados de análise.



### Habilitar clientes com base no navegador usando CORS

[CORS (Compartilhamento de recursos entre origens)](https://learn.microsoft.com/pt-br/rest/api/storageservices/fileservices/cross-origin-resource-sharing--cors--support-for-the-azure-storage-services) é um mecanismo que permite que os domínios troquem permissões para acessar recursos uns dos outros. O Agente do Usuário envia cabeçalhos adicionais para garantir que o código JavaScript carregado de um determinado domínio tenha permissão para acessar os recursos localizados em outro domínio. Depois, o último domínio responde com cabeçalhos adicionais, permitindo ou negando o acesso do domínio original aos seus recursos.

Agora, os serviços de armazenamento do Azure oferecem suporte a CORS, para que depois de definir as regras de CORS para o serviço, uma solicitação autenticada corretamente feita no serviço de um domínio diferente será avaliada para determinar se é permitida de acordo com as regras que você especificou.



## Rede

A seção fornece outras informações sobre os principais recursos em segurança de rede do Azure e informações de resumo sobre esses recursos.



### Controles de camada de rede

O controle de acesso à rede é o ato de limitar a conectividade de entrada ou saída de sub-redes ou dispositivos específicos e representa o aspecto fundamental da segurança de rede. O objetivo do controle de acesso à rede é certificar-se de que suas máquinas virtuais e seus serviços são acessíveis apenas aos usuários e dispositivos para os quais você deseja que tenham esse acesso.



#### Grupos de segurança de rede

Um [NSG (Grupo de Segurança de Rede)](https://learn.microsoft.com/pt-br/azure/virtual-network/virtual-network-vnet-plan-design-arm#security) é um firewall básico de filtragem de pacotes com estado e permite o controle do acesso baseado em uma sequência de 5 tuplas. Os NSGs não fornecem inspeção da camada de aplicativo nem controles de acesso autenticado. Eles podem ser usados para controlar o tráfego entre sub-redes dentro de uma Rede Virtual do Azure e o tráfego entre uma Rede Virtual do Azure e a Internet.



#### Firewall do Azure

O [Firewall do Azure](https://learn.microsoft.com/pt-br/azure/firewall/overview) é um serviço de segurança de firewall de rede inteligente e nativo de nuvem que fornece proteção contra ameaças para suas cargas de trabalho de nuvem em execução no Azure. É um firewall como serviço totalmente com estado com alta disponibilidade interna e escalabilidade de nuvem irrestrita. Ele fornece inspeção de tráfego de leste a oeste e de norte a sul.

O Firewall do Azure é oferecido em dois SKUs: Standard e Premium. O [Firewall do Azure Standard](https://learn.microsoft.com/pt-br/azure/firewall/features) fornece filtragem L3-L7 e feeds de inteligência contra ameaças diretamente da Segurança Cibernética da Microsoft. O [Firewall do Azure Premium](https://learn.microsoft.com/pt-br/azure/firewall/premium-features) fornece funcionalidades avançadas que incluem IDPS baseado em assinatura para permitir a detecção rápida de ataques procurando padrões específicos.



#### Controle de rota e túnel forçado

A capacidade de controlar o comportamento de roteamento em suas Redes Virtuais do Azure é uma funcionalidade crítica de controle de acesso e segurança de rede. Por exemplo, se você quiser ter certeza de que todo o tráfego de entrada e saída da Rede Virtual do Azure passa por esse dispositivo de segurança virtual, será necessário conseguir controlar e personalizar o comportamento do roteamento. É possível fazer isso configurando as Rotas Definidas pelo Usuário no Azure.

As [Rotas Definidas pelo Usuário](https://learn.microsoft.com/pt-br/azure/virtual-network/virtual-networks-udr-overview#custom-routes) permitem que você personalize os caminhos de entrada e saída de máquinas virtuais individuais ou sub-redes a fim de garantir a rota mais segura possível. [túnel forçado](https://learn.microsoft.com/pt-br/azure/vpn-gateway/vpn-gateway-forced-tunneling-rm) é um mecanismo que pode ser usado para garantir que seus serviços não tenham permissão para iniciar uma conexão com dispositivos na Internet.

Isso é diferente de poder aceitar conexões de entrada e responder a elas. Os servidores Web front-end precisam responder à solicitação dos hosts da Internet e, portanto, o tráfego originado da Internet tem permissão de entrada nesses servidores Web, que, por sua vez, podem responder.

O túnel forçado é normalmente usado para forçar o tráfego de saída para a Internet a fim de passar por firewalls e proxies de segurança locais.



#### Dispositivos de segurança de rede virtual

Embora os Grupos de Segurança de Rede, as Rotas Definidas pelo Usuário e o túnel forçado forneçam um nível de segurança nas camadas de rede e de transporte do [modelo OSI](https://en.wikipedia.org/wiki/OSI_model), em algumas ocasiões você pode querer habilitar a segurança em níveis superiores da pilha. É possível acessar esses recursos avançados de segurança de rede por meio de uma solução de dispositivo de segurança de rede de parceiro do Azure. Você pode encontrar as soluções mais atuais de segurança de rede de parceiros do Azure visitando o [Azure Marketplace](https://azure.microsoft.com/marketplace/) e pesquisando por “segurança” e “segurança de rede”.



### Rede Virtual do Azure

Uma rede virtual do Azure (VNet) é uma representação da sua própria rede na nuvem. É um isolamento lógico da malha de rede do Azure dedicada à sua assinatura. Você pode controlar os blocos de endereços IP, as configurações de DNS, as políticas de segurança e as tabelas de rotas na rede. Você pode segmentar a VNet em sub-redes e colocar as VMs (máquinas virtuais) de IaaS do Azure e/ou os [Serviços de nuvem (instâncias de função de PaaS)](https://learn.microsoft.com/pt-br/azure/cloud-services/cloud-services-choose-me) em Redes Virtuais do Azure.

Além disso, você pode conectar a rede virtual à sua rede local usando uma das [opções de conectividade](https://learn.microsoft.com/pt-br/azure/vpn-gateway/) disponíveis no Azure. Em linhas gerais, você pode expandir sua rede no Azure, com controle total sobre os blocos de endereços IP, com benefícios de escala empresarial proporcionados pelo Azure.

A rede do Azure dá suporte a vários cenários de acesso remoto seguro. Entre eles estão:

- [Conectar estações de trabalho individuais a uma Rede Virtual do Azure](https://learn.microsoft.com/pt-br/azure/vpn-gateway/vpn-gateway-howto-point-to-site-rm-ps)
- [Conectar a rede local a uma Rede Virtual do Azure com uma VPN](https://learn.microsoft.com/pt-br/azure/vpn-gateway/vpn-gateway-about-vpngateways)
- [Conectar a rede local a uma Rede Virtual do Azure com uma conexão WAN dedicada](https://learn.microsoft.com/pt-br/azure/expressroute/expressroute-introduction)
- [Conectar Redes Virtuais do Azure entre si](https://learn.microsoft.com/pt-br/azure/vpn-gateway/vpn-gateway-vnet-vnet-rm-ps)



### Gerenciador de Rede Virtual do Azure

[O Gerenciador de Rede Virtual do Azure](https://learn.microsoft.com/pt-br/azure/virtual-network-manager/overview) fornece uma solução centralizada para proteger as suas redes virtuais em escala. Ele usa [regras de administração de segurança](https://learn.microsoft.com/pt-br/azure/virtual-network-manager/concept-security-admins) para definir e aplicar centralmente políticas de segurança para suas redes virtuais em toda a organização. As regras de administração de segurança têm precedência sobre as regras do grupo de segurança de rede (NSGs) e são aplicadas na rede virtual. Isso permite que as organizações apliquem políticas básicas com regras de administração de segurança, ao mesmo tempo que permite que as equipes downstream adaptem os NSGs de acordo com suas necessidades específicas nos níveis de sub-rede e NIC. Dependendo das necessidades da sua organização, você pode usar ações de regra **Permitir**, **Negar** ou **Sempre permitir** para impor políticas de segurança.

Expandir a tabela

| Ação de regra       | Descrição                                                    |
| :------------------ | :----------------------------------------------------------- |
| **Permitir**        | Permite o tráfego especificado por padrão. Os NSGs downstream ainda recebem esse tráfego e podem negá-lo. |
| **Sempre Permitir** | Permita sempre o tráfego especificado, independentemente de outras regras com prioridade mais baixa ou NSGs. Isso pode ser usado para garantir que o agente de monitoramento, o controlador de domínio ou o tráfego de gerenciamento não sejam bloqueados. |
| **Deny**            | Bloqueie o tráfego especificado. Os NSGs a jusante não avaliarão este tráfego depois de ter sido negado por uma regra de administração de segurança, garantindo que as suas portas de alto risco para redes virtuais existentes e novas estão protegidas por padrão. |

No Gerenciador de Rede Virtual do Azure, [grupos de rede](https://learn.microsoft.com/pt-br/azure/virtual-network-manager/concept-network-groups) permitem-lhe agrupar redes virtuais para gestão centralizada e aplicação de políticas de segurança. Os grupos de rede são um agrupamento lógico de redes virtuais com base nas suas necessidades do ponto de vista da topologia e da segurança. Você pode atualizar manualmente a associação de rede virtual de seus grupos de rede ou pode [definir instruções condicionais com o Azure Policy](https://learn.microsoft.com/pt-br/azure/virtual-network-manager/concept-azure-policy-integration) para atualizar dinamicamente grupos de rede para atualizar automaticamente sua associação de grupo de rede.



### Link Privado do Azure

O [Link Privado do Azure](https://azure.microsoft.com/services/private-link/) lhe permite acessar os serviços de PaaS do Azure (por exemplo, Armazenamento do Azure e Banco de Dados SQL) e serviços de parceiros/de propriedade de clientes hospedados no Azure em um [ponto de extremidade privado](https://learn.microsoft.com/pt-br/azure/private-link/private-endpoint-overview) em sua rede virtual. A configuração e o consumo usando o Link Privado do Azure são consistentes entre os serviços de parceiro de PaaS do Azure, de propriedade do cliente e de parceiros compartilhados. O tráfego da sua rede virtual para o serviço do Azure sempre permanece na rede de backbone do Microsoft Azure.

Os [pontos de extremidade privados](https://learn.microsoft.com/pt-br/azure/private-link/private-endpoint-overview) permite que você possa garantir os recursos essenciais dos serviços do Azure somente para suas redes virtuais. O ponto de extremidade privado do Azure usa um endereço de IP privado da VNet para conectá-lo de maneira privada e segura a um serviço fornecido pelo Link Privado do Azure, trazendo efetivamente o serviço para sua VNet. Expor sua rede virtual à Internet pública não é mais necessário para consumir serviços no Azure.

Você também pode criar seu próprio serviço de link privado na rede virtual. O [Serviço de Link Privado do Azure](https://learn.microsoft.com/pt-br/azure/private-link/private-link-service-overview) é a referência para o seu próprio serviço que é fornecido pelo Link Privado do Azure. Seu serviço que está sendo executado por trás do Azure Standard Load Balancer pode ser habilitado para acesso ao Link Privado para que os consumidores de seu serviço possam acessá-lo de forma privada em suas próprias VNets. Os clientes podem criar um ponto de extremidade privado dentro da rede virtual e mapeá-lo para esse serviço. Expor seu serviço à Internet pública não é mais necessário para consumir serviços no Azure.



### Gateway de VPN

Para enviar o tráfego de rede entre sua Rede Virtual do Azure e seu site local, será necessário criar um gateway de VPN para sua Rede Virtual do Azure. Um [gateway de VPN](https://learn.microsoft.com/pt-br/azure/vpn-gateway/vpn-gateway-about-vpngateways) é um tipo de gateway de rede virtual que envia o tráfego criptografado em uma conexão pública. Você também pode usar gateways de VPN para enviar o tráfego entre as Redes Virtuais do Azure pela malha de rede do Azure.



### ExpressRoute

O Microsoft Azure [ExpressRoute](https://learn.microsoft.com/pt-br/azure/expressroute/expressroute-introduction) é uma conexão WAN dedicada que permite que você estenda suas redes locais até a nuvem da Microsoft por meio de uma conexão privada dedicada, facilitada por um provedor de conectividade.

![ExpressRoute](https://learn.microsoft.com/pt-br/azure/security/fundamentals/media/overview/azure-security-figure-1.png)

Com o ExpressRoute, você pode estabelecer conexões com os serviços de nuvem da Microsoft, como o Microsoft Azure, o Office 365 e o CRM Online. A conectividade pode ocorrer de uma rede “qualquer para qualquer” (VPN IP), uma rede Ethernet ponto a ponto ou uma conexão cruzada virtual por meio de um provedor de conectividade em uma colocalização.

As conexões de ExpressRoute não passam pela Internet pública e, portanto, podem ser consideradas mais seguras do que soluções de VPN. Isso permite que as conexões de ExpressRoute ofereçam mais confiabilidade, mais velocidade, latências menores e muito mais segurança do que as conexões típicas pela Internet.



### Gateway de Aplicativo

O [Gateway de Aplicativo](https://learn.microsoft.com/pt-br/azure/application-gateway/overview) do Microsoft Azure fornece um [ADC (Controlador de Entrega de Aplicativos)](https://en.wikipedia.org/wiki/Application_delivery_controller) como um serviço, oferecendo vários recursos de balanceamento de carga de camada 7 para o aplicativo.

![Gateway de Aplicativo](https://learn.microsoft.com/pt-br/azure/security/fundamentals/media/overview/azure-security-figure-2.png)

Ele permite que você otimize a produtividade do Web farm descarregando a terminação TLS com uso intensivo de CPU para o Gateway de Aplicativo (também conhecido como “descarregamento de TLS” ou “ponte TLS”). Ele também fornece outros recursos de roteamento de Camada 7, incluindo distribuição round robin do tráfego de entrada, afinidade de sessão, roteamento com base no caminho de URL e a capacidade de hospedar vários sites por trás de um único Gateway de Aplicativo baseado em cookie. O Gateway de Aplicativo do Azure é um balanceador de carga de camada 7.

Ele fornece o failover e solicitações HTTP de roteamento de desempenho entre diferentes servidores, estejam eles na nuvem ou no local.

O aplicativo fornece muitos recursos do Controlador de Entrega de Aplicativos (ADC), incluindo o balanceamento de carga de HTTP, a afinidade de sessão baseada em cookies, o descarregamento de [TLS](https://learn.microsoft.com/pt-br/azure/web-application-firewall/ag/tutorial-restrict-web-traffic-powershell), as sondas de integridade personalizadas, suporte para vários sites e muitos outros.



### Firewall do Aplicativo Web

O Firewall do aplicativo Web é um recurso do [Gateway de Aplicativo do Azure](https://learn.microsoft.com/pt-br/azure/application-gateway/overview) que fornece proteção para aplicativos Web que utilizam o gateway de aplicativo para as funções ADC (controle de entrega de aplicativos) padrão. O firewall do aplicativo Web faz isso protegendo-os contra a maioria das 10 vulnerabilidades mais comuns da Web segundo o OWASP.

![Firewall do Aplicativo Web](https://learn.microsoft.com/pt-br/azure/security/fundamentals/media/overview/azure-security-figure-3.png)

- Proteção contra injeção de SQL
- Proteção Contra Ataques Comuns da Web, como a injeção de comandos, as solicitações HTTP indesejadas, a divisão de resposta HTTP e o ataque de inclusão de arquivo remoto
- Proteção contra violações de protocolo HTTP
- Proteção contra anomalias de protocolo HTTP, como ausência de host de agente do usuário e de cabeçalhos de aceitação
- Prevenção contra bots, rastreadores e scanners
- Detecção de problemas de configuração de aplicativo comuns (ou seja, Apache, IIS etc.)

Um firewall do aplicativo Web para proteger contra ataques da Web simplifica muito o gerenciamento de segurança e oferece mais garantia para o aplicativo contra ameaças de invasões. Uma solução WAF também pode reagir a uma ameaça de segurança mais rapidamente ao aplicar um patch contra uma vulnerabilidade conhecida em um local central do que a proteção de cada um dos aplicativos Web individuais. Os gateways de aplicativos existentes podem ser facilmente convertidos em um gateway de aplicativo com o firewall do aplicativo Web.



### Gerenciador de Tráfego

O [Gerenciador de Tráfego do Microsoft Azure](https://learn.microsoft.com/pt-br/azure/traffic-manager/traffic-manager-overview) permite controlar a distribuição do tráfego do usuário para pontos de extremidade do serviço em diferentes datacenters. Os pontos de extremidade de serviço com suporte no Gerenciador de Tráfego incluem VMs do Azure, Aplicativos Web e Serviços de Nuvem. Você também pode usar o Gerenciador de Tráfego com pontos de extremidade externos e não do Azure. O Gerenciador de Tráfego usa o DNS (Sistema de Nome de Domínio) para direcionar solicitações de cliente para o ponto de extremidade mais apropriado com base em um [método de roteamento de tráfego](https://learn.microsoft.com/pt-br/azure/traffic-manager/traffic-manager-routing-methods) e a integridade dos pontos de extremidade.

O Gerenciador de Tráfego oferece uma variedade de métodos de roteamento de tráfego para atender às necessidades de diferentes aplicativo, [monitoramento](https://learn.microsoft.com/pt-br/azure/traffic-manager/traffic-manager-monitoring) de integridade do ponto de extremidade e failover automático. O Gerenciador de Tráfego é resistente a falhas, incluindo a falha de toda a região do Azure.



### Azure Load Balancer

O [Azure Load Balancer](https://learn.microsoft.com/pt-br/azure/load-balancer/load-balancer-overview) oferece alta disponibilidade e desempenho de rede para seus aplicativos. É um balanceador de carga do tipo Camada 4 (TCP, UDP) que distribui o tráfego de entrada entre as instâncias de serviço íntegras definidas em um conjunto de balanceadores de carga. O Azure Load Balancer pode ser configurado para:

- Balancear carga de tráfego de entrada na Internet para máquinas virtuais. Essa configuração é conhecida como [balanceamento de carga público](https://learn.microsoft.com/pt-br/azure/load-balancer/components#frontend-ip-configurations).
- Balanceie o tráfego de carga entre as máquinas virtuais em uma rede virtual, entre as máquinas virtuais nos serviços de nuvem ou entre os computadores locais e as máquinas virtuais em uma rede virtual entre as instalações. Essa configuração é conhecida como [balanceamento de carga interno](https://learn.microsoft.com/pt-br/azure/load-balancer/components#frontend-ip-configurations).
- Encaminhe o tráfego externo para uma máquina virtual específica



### DNS interno

Você pode gerenciar a lista de servidores DNS usados em uma VNet no Portal de Gerenciamento ou no arquivo de configuração de rede. O cliente pode adicionar até 12 servidores DNS para cada VNet. Ao especificar servidores DNS, é importante verificar se os servidores DNS do cliente estão listados na ordem correta para o ambiente de seu cliente. As listas de servidores DNS não funcionam em round robin. Elas são usadas na ordem em que foram especificadas. Se o primeiro servidor DNS na lista puder ser alcançado, o cliente usará esse servidor DNS independentemente de ele estar funcionando corretamente. Para alterar a ordem de servidor DNS para a rede virtual de seu cliente, remova os servidores DNS da lista e adicione-os na ordem desejada pelo cliente. O DNS oferece suporte ao aspecto de disponibilidade da tríade de segurança "CIA".



### DNS do Azure

O sistema de nomes de domínio, ou DNS, é responsável por converter (ou seja, resolver) um nome do site ou serviço para seu endereço IP. O [DNS do Azure](https://learn.microsoft.com/pt-br/azure/dns/dns-overview) é um serviço de hospedagem para domínios DNS, fornecendo resolução de nomes usando a infraestrutura do Microsoft Azure. Ao hospedar seus domínios no Azure, você pode gerenciar seus registros DNS usando as mesmas credenciais, APIs, ferramentas e cobrança que seus outros serviços do Azure. O DNS oferece suporte ao aspecto de disponibilidade da tríade de segurança "CIA".



### NSGs de logs do Azure Monitor

Você pode habilitar as seguintes categorias de log de diagnóstico para NSGs:

- Evento: contém entradas para as regras NSG que são aplicadas às VMs e funções de instância com base no endereço MAC. O status para essas regras é coletado a cada 60 segundos.
- Contador de regras: contém entradas de quantas vezes cada regra NSG é aplicada para negar ou permitir tráfego.



### Microsoft Defender para Nuvem

[O Microsoft Defender para Nuvem](https://learn.microsoft.com/pt-br/azure/security-center/security-center-introduction) analisa continuamente o estado de segurança dos seus recursos do Azure para as práticas recomendadas de segurança de rede. Quando o Defender para Nuvem identifica possíveis vulnerabilidades de segurança, ela cria [recomendações](https://learn.microsoft.com/pt-br/azure/security-center/security-center-recommendations) que guiam você pelo processo de configuração dos controles necessários para fortalecer e proteger seus recursos.



## Computação

A seção fornece outras informações sobre os principais recursos nessa área e informações de resumo sobre esses recursos.



### Computação confidencial do Azure

A [computação confidencial do Azure](https://learn.microsoft.com/pt-br/azure/confidential-computing/overview-azure-products) fornece a parte final ausente do quebra-cabeça da proteção de dados. Ela permite que você mantenha seus dados criptografados o tempo todo. Enquanto está em repouso, enquanto está em movimento pela rede e agora, mesmo quando está carregado na memória e em uso. Além disso, ao tornar o [Attestion Remoto](https://learn.microsoft.com/pt-br/azure/attestation/overview) possível, ele permite que você verifique criptograficamente se a VM provisionada foi inicializada com segurança e está configurada corretamente, antes de desbloquear seus dados.

O espectro de opções varia desde a habilitação de cenários de "lift-and-shift" de aplicativos existentes até um controle total dos recursos de segurança. Para IaaS (Infraestrutura como Serviço), você pode usar [máquinas virtuais confidenciais da plataforma AMD SEV-SNP](https://learn.microsoft.com/pt-br/azure/confidential-computing/confidential-vm-overview) ou enclaves de aplicativos confidenciais para máquinas virtuais que executam [SGX (Software Guard Extensions) da Intel.](https://learn.microsoft.com/pt-br/azure/confidential-computing/application-development) Para plataforma como serviço, temos várias opções [baseadas em contêiner](https://learn.microsoft.com/pt-br/azure/confidential-computing/choose-confidential-containers-offerings), incluindo integrações com [Serviço de Kubernetes do Azure (AKS)](https://learn.microsoft.com/pt-br/azure/confidential-computing/confidential-nodes-aks-overview).



### Antimalware e antivírus

Com o Azure IaaS, você pode usar o software antimalware dos fornecedores de segurança, como Microsoft, Symantec, Trend Micro, McAfee e Kaspersky, para proteger suas máquinas virtuais contra arquivos maliciosos, adware e outras ameaças. O [Microsoft Antimalware](https://learn.microsoft.com/pt-br/azure/security/fundamentals/antimalware) para Serviços de Nuvem e Máquinas Virtuais do Azure é uma funcionalidade de proteção que ajuda a identificar e remover vírus, spyware e outros softwares mal-intencionados. O Microsoft Antimalware fornece alertas configuráveis quando um software mal-intencionado ou indesejado conhecido tenta se instalar ou executar nos sistemas do Azure. Microsoft Antimalware também pode ser implantado usando o Microsoft Defender para nuvem



### Módulos de segurança de hardware

A autenticação e a criptografia não melhoram a segurança, a menos que as próprias chaves estejam bem protegidas. Você pode simplificar o gerenciamento e a segurança dos seus principais segredos e chaves armazenando-os no [Azure Key Vault](https://learn.microsoft.com/pt-br/azure/key-vault/general/overview). O Key Vault oferece a opção de armazenar suas chaves em módulos de segurança de hardware (HSMs) certificados de acordo com os padrões [FIPS 140 validados](https://learn.microsoft.com/pt-br/azure/key-vault/keys/about-keys#compliance). Suas chaves de criptografia do SQL Server para backup ou [Transparent Data Encryption](https://learn.microsoft.com/pt-br/sql/relational-databases/security/encryption/transparent-data-encryption) podem ser armazenadas no Cofre de Chaves com quaisquer chaves ou segredos dos seus aplicativos. As permissões e o acesso a esses itens protegidos são gerenciados pelo [Microsoft Entra ID](https://learn.microsoft.com/pt-br/azure/active-directory/).



### Backup de máquinas virtuais

O [Backup do Azure](https://learn.microsoft.com/pt-br/azure/backup/backup-overview) é uma solução que protege os dados do seu aplicativo com zero investimento de capital e custos operacionais mínimos. Erros de aplicativo podem corromper seus dados e erros humanos podem introduzir bugs em seus aplicativos, o que pode causar problemas de segurança. Com o Backup do Azure, suas máquinas virtuais executando Windows e Linux estão protegidas.



### Azure Site Recovery

Uma parte importante da estratégia de [BCDR (continuidade dos negócios/recuperação de desastre)](https://learn.microsoft.com/pt-br/azure/availability-zones/cross-region-replication-azure) de sua organização é descobrir como manter as cargas de trabalho corporativas e aplicativos em execução durante interrupções planejadas e não planejadas. O [Azure Site Recovery](https://learn.microsoft.com/pt-br/azure/site-recovery/site-recovery-overview) ajuda a orquestrar a replicação, failover e recuperação dos aplicativos e cargas de trabalho para que eles estejam disponíveis a partir de um local secundário, caso o local principal fique inativo.



### TDE de VM do SQL

TDE (Transparent Data Encryption) e CLE (criptografia de nível de coluna) são recursos de criptografia do SQL Server. Essa forma de criptografia exige que os clientes gerenciem e armazenem as chaves criptográficas usadas para a criptografia.

O serviço Cofre da Chave do Azure (AKV) foi criado para melhorar a segurança e o gerenciamento dessas chaves em um local seguro e altamente disponível. O SQL Server Connector permite que o SQL Server use essas chaves do Azure Key Vault.

Se você estiver executando o SQL Server em máquinas locais, existem etapas a serem seguidas para acessar o Azure Key Vault da instância do SQL Server local. Mas, para o SQL Server em VMs do Azure, você pode economizar tempo usando o recurso Integração do Azure Key Vault. Com alguns cmdlets do Azure PowerShell para habilitar esse recurso, você poderá automatizar a configuração necessária para que uma VM do SQL acesse seu cofre da chave.



### Criptografia de disco da VM

A [Azure Disk Encryption para VMs do Linux](https://learn.microsoft.com/pt-br/azure/virtual-machines/linux/disk-encryption-overview) e a [Azure Disk Encryption para VMs do Windows](https://learn.microsoft.com/pt-br/azure/virtual-machines/linux/disk-encryption-overview) ajudam você a criptografar seus discos de máquina virtual IaaS. Ele aplica o recurso BitLocker do Windows padrão do setor e o recurso DM-Crypt do Linux para fornecer uma criptografia de volume para o sistema operacional e os discos de dados. A solução é integrada ao Azure Key Vault para ajudá-lo a controlar e gerenciar as chaves de criptografia de disco e os segredos em sua assinatura de Key Vault. A solução também garante que todos os dados em discos da máquina virtual sejam criptografados em repouso no armazenamento do Azure.



### Rede Virtual

As máquinas virtuais precisam de conectividade de rede. Para dar suporte a esse requisito, o Azure exige que as máquinas virtuais sejam conectadas a uma Rede Virtual do Azure. Uma Rede Virtual do Azure é um constructo lógico criado na malha de rede física do Azure. Cada [Rede Virtual do Azure](https://learn.microsoft.com/pt-br/azure/virtual-network/virtual-networks-overview) lógica é isolada das todas as outras Redes Virtuais do Azure. Esse isolamento ajuda a garantir que o tráfego de rede nas implantações não esteja acessível para outros clientes do Microsoft Azure.



### Atualizações de patch

As atualizações de patch fornecem a base para encontrar e corrigir problemas em potencial e simplificam o processo de gerenciamento de atualizações de software, tanto reduzindo o número de atualizações de software que você deve implantar em sua empresa quanto aumentando a capacidade de monitorar a conformidade.



### Gerenciamento de política de segurança e emissão de relatórios

O [Defender para nuvem](https://learn.microsoft.com/pt-br/azure/security-center/security-center-introduction) ajuda você a impedir, detectar e responder a ameaças, e fornece maior visibilidade e controle sobre a segurança dos seus recursos do Azure. Ela permite o gerenciamento de políticas e o monitoramento da segurança integrada entre suas assinaturas do Azure, ajuda a detectar ameaças que poderiam passar despercebidas e funciona com uma enorme variedade de soluções de segurança.



## Gerenciamento de identidade e de acesso

A proteção de sistemas, aplicativos e dados começa com controles de acesso baseados em identidade. Os recursos de gerenciamento de identidades e acesso integrados aos produtos e serviços comerciais da Microsoft ajudam a proteger as informações pessoais e corporativas contra o acesso não autorizado, mas as disponibilizam aos usuários legítimos, quando e onde eles precisarem.



### Proteção da identidade

A Microsoft usa várias tecnologias e práticas de segurança em seus produtos e serviços para gerenciar a identidades e o acesso.

- A [Autenticação Multifator](https://azure.microsoft.com/services/multi-factor-authentication/) exige que os usuários usem vários métodos para obter acesso, localmente e na nuvem. Ela fornece uma autenticação forte com uma gama de opções de verificação simples, e proporciona ao usuários um processo de logon simples.
- O [Microsoft Authenticator](https://aka.ms/authenticator) fornece uma experiência de autenticação multifator fácil de usar que funciona com o Microsoft Entra ID e com as contas Microsoft, além de incluir o suporte para wearables e aprovações baseadas em impressões digitais.
- A [Aplicação de políticas de senha](https://learn.microsoft.com/pt-br/azure/active-directory/authentication/concept-sspr-policy) aumenta a segurança de senhas tradicionais impondo requisitos de comprimento e complexidade, rotação periódica forçada e bloqueio de conta depois de falhas nas tentativas de autenticação.
- A [autenticação baseada em token](https://learn.microsoft.com/pt-br/azure/active-directory/develop/authentication-vs-authorization) permite a autenticação via Microsoft Entra ID.
- O [Azure RBAC (controle de acesso baseado em função do Azure)](https://learn.microsoft.com/pt-br/azure/role-based-access-control/built-in-roles) permite que você conceda acesso com base na função atribuída do usuário, facilitando a concessão apenas do acesso necessário para os usuários realizarem seus trabalhos. Você pode personalizar o Azure RBAC de acordo com o modelo de negócios e a tolerância a riscos da sua organização.
- O [Gerenciamento de identidade integrado (identidade híbrida)](https://learn.microsoft.com/pt-br/azure/active-directory/hybrid/plan-hybrid-identity-design-considerations-overview) permite que você mantenha o controle do acesso dos usuários em data centers internos e plataformas de nuvem, criando uma identidade de usuário único para autenticação e autorização para todos os recursos.



### Aplicativos e dados seguros

O [Microsoft Entra ID](https://azure.microsoft.com/services/active-directory/), uma solução abrangente de gerenciamento de identidade e acesso na nuvem, ajuda a proteger o acesso a dados em aplicativos locais e na nuvem, além de simplificar o gerenciamento de usuários e grupos. Ele combina os principais serviços de diretório, controle de identidade avançado, segurança e gerenciamento de acesso ao aplicativo, facilitando para os desenvolvedores a compilação do gerenciamento de identidade baseado em políticas em seus aplicativos. Para aprimorar seu Microsoft Entra ID, você pode adicionar recursos pagos usando as edições Microsoft Entra Basic, Premium P1 e Premium P2.

Expandir a tabela

| Recursos gratuitos/comuns                                    | Recursos básicos                                             | Recursos do Premium P1                                       | Recursos do Premium P2                                       | Ingresso no Microsoft Entra – apenas para recursos relacionados ao Windows 10 |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| [Objetos de diretório](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Gerenciamento de usuários/grupos (adicionar/atualizar/excluir)/Provisionamento baseado em usuário, Registro de dispositivos](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [SSO (logon único)](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Autoatendimento para alteração de senha para usuários de nuvem](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Connect (mecanismo de sincronização que estende os diretórios locais para o Microsoft Entra ID)](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Relatórios de segurança/uso](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis) | [Gerenciamento/provisionamento de acesso baseado em grupo](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Redefinição de senha por autoatendimento para usuários de nuvem](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Identidade visual da empresa (personalização de páginas de logon/painel de acesso)](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Proxy de Aplicativo](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [SLA de 99,9%](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis) | [Autoatendimento para gerenciamento de grupo e aplicativo/Autoatendimento para adições de aplicativos/Grupos dinâmicos](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Autoatendimento para redefinição/alteração/desbloqueio de senha com write-back local](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Autenticação Multifator (local e na nuvem [Servidor de MFA\])](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [MIM CAL + Servidor MIM](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Cloud App Discovery](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Connect Health](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Substituição automática de senha para contas de grupo](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis) | [Proteção de identidade](https://learn.microsoft.com/pt-br/azure/active-directory/identity-protection/overview-identity-protection), [Privileged Identity Management](https://learn.microsoft.com/pt-br/azure/active-directory/privileged-identity-management/pim-configure) | [Ingresso de um dispositivo ao Microsoft Entra ID, SSO na Área de Trabalho, Microsoft Passport para Microsoft Entra ID, recuperação do BitLocker pelo administrador](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis), [Registro automático de MDM, Autoatendimento para recuperação do BitLocker, Administradores locais adicionais para dispositivos Windows 10 via ingresso no Microsoft Entra](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis) |

- O [Cloud App Discovery](https://learn.microsoft.com/pt-br/cloud-app-security/set-up-cloud-discovery) é um recurso premium do Microsoft Entra ID que permite identificar os aplicativos em nuvem usados pelos funcionários em sua organização.
- O [Microsoft Entra ID Protection](https://learn.microsoft.com/pt-br/azure/active-directory/identity-protection/overview-identity-protection) é um serviço de segurança que usa recursos de detecção de anomalias do Microsoft Entra ID para fornecer uma visão consolidada sobre detecções de riscos e possíveis vulnerabilidades que poderiam afetar as identidades de sua organização.
- O [Microsoft Entra Domain Services](https://azure.microsoft.com/services/active-directory-ds/) permite ingressar VMs do Azure em um domínio sem precisar implantar controladores de domínio. Os usuários entram nessas VMs usando suas credenciais corporativas do Active Directory e podem acessar tranquilamente os recursos.
- O [Azure Active Directory B2C](https://azure.microsoft.com/services/active-directory-b2c/) é um serviço de gerenciamento de identidade global, altamente disponível para aplicativos voltados para o consumidor que pode ser dimensionado para centenas de milhões de identidades e ser integrado em várias plataformas móveis e da Web. Seus clientes podem entrar em todos os seus aplicativos por meio de experiências personalizáveis que usam contas de mídia social existentes, ou você pode criar novas credenciais autônomas.
- A [Colaboração B2B do Microsoft Entra](https://learn.microsoft.com/pt-br/azure/active-directory/external-identities/what-is-b2b) é uma solução de integração de parceiro seguro que dá suporte a relações entre empresas, permitindo que os parceiros de negócios acessem de maneira seletiva seus aplicativos e dados corporativos usando suas identidades autogerenciadas.
- O [ingresso no Microsoft Entra](https://learn.microsoft.com/pt-br/azure/active-directory/devices/overview) permite estender os recursos de nuvem para dispositivos Windows 10 a fim de proporcionar um gerenciamento centralizado. Ele permite que os usuários se conectem à nuvem corporativa ou organizacional por meio do Microsoft Entra ID e simplifica o acesso a aplicativos e recursos.
- O [proxy de aplicativo do Microsoft Entra](https://learn.microsoft.com/pt-br/azure/active-directory/app-proxy/application-proxy) fornece SSO e acesso remoto seguro para aplicativos Web hospedados no local.



## Próximas etapas

- Entenda sua [responsabilidade compartilhada na nuvem](https://learn.microsoft.com/pt-br/azure/security/fundamentals/shared-responsibility).
- Saiba como [o Microsoft Defender para Nuvem](https://learn.microsoft.com/pt-br/azure/security-center/security-center-introduction) pode ajudá-lo a prevenir, detectar e responder a ameaças com maior visibilidade e controle sobre a segurança de seus recursos do Azure.