## Plataforma Azure

A plataforma Azure oferece uma série de serviços que podem ser amplamente categorizados em modelos de entrega de infraestrutura como serviço (IaaS), plataforma como serviço (PaaS) e software como serviço (SaaS). Ele oferece suporte a vários sistemas operacionais, pilhas de aplicativos, as plataformas de banco de dados mais populares e soluções de hospedagem de contêineres. Independentemente de seu aplicativo ser construído usando .NET, PHP, Python, Node.JS, Java, MySQL, SQL, MariaDB, Docker, [Kubernetes](https://www.checkpoint.com/pt/cyber-hub/cloud-security/what-is-kubernetes/)- ele pode encontrar um lar no Azure.

 

Ao migrar aplicativos do centro de dados totalmente gerenciado por você para o Azure, você dependerá muito da plataforma para proteger essas cargas de trabalho. O modelo de responsabilidade partilhada para a segurança torna-se assim muito relevante aqui para a demarcação de papéis e responsabilidades.

 

A Microsoft é proprietária da [infraestrutura física](https://docs.microsoft.com/en-us/azure/security/fundamentals/infrastructure) da plataforma Azure e cuida da sua segurança, abrangendo diversos aspectos como centro de dados físico, controle de acesso, treinamento obrigatório de segurança para funcionários, verificação de antecedentes, etc. Mas à medida que implementa cargas de trabalho na plataforma Azure, uma divisão de responsabilidades – entre si e o seu fornecedor – deve ser tida em consideração, conforme resumido abaixo:

 

Conforme ilustrado na imagem acima, algumas responsabilidades de segurança, inclusive do centro de dados físico, da rede e do host, são assumidas pelos [provedores de nuvem](https://www.checkpoint.com/pt/cyber-hub/cloud-security/what-is-cloud-security/what-are-cloud-service-providers/). Mas, dependendo se você estiver usando um modelo IaaS, PaaS ou SaaS, será necessário atender à pilha de aplicativos SO e aos requisitos adicionais de segurança da camada de rede.

## Visão geral da segurança do Microsoft Azure

Os requisitos de segurança de cada organização são únicos e precisariam de extensas personalizações para garantir a segurança de cada carga de trabalho específica. Os vetores avançados de ameaças na nuvem exigem uma abordagem de segurança de confiança zero, onde nada é confiável por padrão e tudo é verificado. Esta abordagem proativa à Segurança de Nuvem ajuda a reduzir a superfície de ataque e a limitar os danos no caso de um ataque.

 

A segurança deve ser implementada em cada camada da pilha de aplicativos, desde computação, armazenamento e rede até controles específicos do aplicativo e gerenciamento de identidade e acesso. A visibilidade do status de segurança do seu ambiente também é importante, pois qualquer atividade maliciosa deve ser detectada em tempo real para proteção ideal.

 

[O Azure](https://docs.microsoft.com/en-us/azure/security/fundamentals/overview) permite a segurança da carga de trabalho por meio de diversas ferramentas e serviços configuráveis que você pode aproveitar para atender às diversas demandas de segurança e aprimorar sua postura de segurança de nuvem. Você também pode usar soluções de segurança de parceiros sempre que aplicável para aumentar ainda mais essa postura.

### Azure Security Center

[O Security Center](https://azure.microsoft.com/en-us/services/security-center/#features) é a solução de gestão de segurança centralizada do Azure que o ajuda a adaptar os seus controlos de segurança a um cenário de ameaças em mudança e a proteger proativamente a sua organização contra vários tipos de ataques. Os serviços do Azure são automaticamente integrados ao Security Center e monitorados em relação às linhas de base de segurança definidas. Políticas padrão e personalizadas podem ser usadas para monitorar o status da sua assinatura do Azure e dos recursos incluídos. Com base na avaliação contínua dos seus ambientes Azure, o Security Center fornece recomendações acionáveis que podem ser usadas para abordar proativamente a segurança de API.

 

A Central de Segurança do Azure também oferece proteção abrangente contra ameaças e usa análise da cadeia de eliminação cibernética para fornecer visibilidade de ponta a ponta do vetor de ataque. Além disso, você pode usar o Microsoft Defender para endpoint para proteger seus servidores Azure. Ele fornece sensores avançados de detecção de violações que se adaptam rapidamente às ameaças em evolução por meio do poder do big data e da análise e fornece inteligência de ameaça superior para proteger suas cargas de trabalho.

 

Além disso, o recurso de integração automatizada para servidores Windows e a visibilidade em painel único facilitam a vida das equipes de segurança de nuvem, reduzindo a sobrecarga operacional. A Central de Segurança do Azure também se integra a soluções como Azure Policy, Azure Monitor Logs e Azure Cloud App Security para segurança aprofundada.

### Gerenciamento de Postura de Segurança de Nuvem (CSPM)

As ameaças na nuvem não são iguais às locais. A nuvem precisa de soluções nascidas na nuvem para garantir a higiene da segurança e que as melhores práticas de segurança estejam sendo implementadas. O Segurança de nuvem Posture Management do Azure ajuda você com isso, permitindo que você gerencie proativamente suas cargas de trabalho de segurança no Azure.

 

A opção “pontuação segura” no Security Center ajuda a quantificar a postura de segurança dos seus ambientes usando vários controles de segurança pré-construídos contra os quais os ambientes são avaliados. Se algum desses controles não for implementado ou se houver alguma configuração incorreta, o Security Center oferece recomendações prescritivas para melhorar sua pontuação. Enquanto isso, a pontuação regulatória da Conformidade avalia as cargas de trabalho em relação a padrões como PCI DSS, HIPAA, CIS do próprio Azure e NIST, ajudando você a avaliar seu status oficial de Conformidade.

 

O Security Center habilita [o CSPM](https://www.checkpoint.com/pt/cyber-hub/cloud-security/what-is-cspm-cloud-security-posture-management/) fornecendo uma visão panorâmica da vulnerabilidade e gerando alertas sobre possíveis ataques. Cada alerta é marcado com um nível de gravidade para que você possa priorizar as atividades de mitigação. Juntamente com cargas de trabalho nativas da nuvem, serviços de IoT e serviços de dados, o Security Center pode proteger máquinas Windows e Linux contra ameaças em ambientes, reduzindo assim a superfície de ataque.

### Segurança de aplicativo da web

Com a expansão dos aplicativos em nuvem, tornou-se cada vez mais difícil monitorar todos os seus aplicativos e garantir transações de dados seguras. O Azure ajuda a resolver esta preocupação através de uma solução de corretor de segurança de nuvem chamada Microsoft Cloud App Security.

 

Essa ferramenta protege contra shadow IT, ajudando você a detectar serviços em nuvem usados por sua organização e identificar quaisquer riscos associados a eles. As políticas integradas do serviço permitem automatizar a implementação de controles de segurança para aplicativos em nuvem, além disso, você pode sancionar ou cancelar a sanção de aplicativos por meio da funcionalidade do catálogo de aplicativos em nuvem, que abrange mais de 16.000 aplicativos e os pontua com base em mais de 80 fatores de risco para que você pode tomar uma decisão informada sobre o tipo de aplicativos que você deseja permitir em sua organização.

 

O nuvem App Security também fornece visibilidade do seu aplicativo e seu status de segurança e controla como os dados trafegam entre eles. Ele também pode detectar comportamentos incomuns para identificar aplicativos comprometidos e acionar a correção automática para reduzir o risco. Você pode avaliar ainda mais seu aplicativo quanto à conformidade regulatória e restringir a movimentação de dados para aplicativos não compatíveis, além de proteger quaisquer dados regulamentados em seus aplicativos contra acesso não autorizado.

 

A integração nativa com outras soluções de segurança da Microsoft fornece inteligência de ameaça incomparável e análises aprofundadas para defender seu aplicativo contra diferentes tipos de ataques na nuvem.

### Container Security

A Central de Segurança do Azure oferece base de segurança e avaliação de ambientes de hospedagem de contêineres, como AKS, bem como VMs que executam o Docker, para identificar possíveis configurações incorretas e brechas de segurança. O fortalecimento dos ambientes Docker é possibilitado pelo monitoramento dos [benchmarks CIS](https://www.cisecurity.org/benchmark/docker/) com recomendações consolidadas no Security Center. Da mesma forma, a monitorização e a deteção avançada de ameaças estão disponíveis para nós e clusters AKS. Você também pode habilitar o complemento de política do Azure para clusters Kubernetes para monitorar solicitações de servidores API Kubernetes em relação às práticas recomendadas definidas antes de atendê-los.

 

Enquanto isso, o Azure Defender protege nós e clusters AKS contra vulnerabilidade e infiltração em tempo de execução, detectando atividades suspeitas, como detecção de web shell, solicitações de conexão de IPs suspeitos, provisionamento de contêineres privilegiados, etc. O Azure Defender também inclui uma integração Qualys para digitalizar imagens extraídas ou enviadas por push. para o Registro de Contêiner do Azure. Quaisquer descobertas são classificadas e exibidas no Security Center, permitindo diferenciar entre imagens íntegras e não íntegras.

### Grupos de segurança de rede (NSGs)

Os NSGs atuam como a primeira linha de defesa da rede para cargas de trabalho ligadas aos VNets do Azure. Ele filtra o tráfego de entrada e saída por meio de cinco regras de tupla usando origem, porta de origem, destino, porta de destino e protocolo. Esses grupos podem ser associados a sub-redes ou às placas NIC da máquina virtual (máquina virtual, VM) e vêm com algumas regras padrão para permitir a comunicação entre redes e o acesso à Internet. Os grupos de segurança de rede também permitem obter controle refinado sobre o tráfego leste-oeste e norte-sul e ajudam a segregar a comunicação dos componentes do seu aplicativo.

### Rede Virtual do Azure

O Azure VNet é o alicerce básico da rede no Azure e ajuda na microssegmentação de cargas de trabalho, permitindo a comunicação segura de cargas de trabalho conectadas com outros recursos do Azure, recursos locais e a Internet. Os recursos num VNet do Azure não podem comunicar com recursos num VNet diferente por padrão, a menos que estejam explicitamente ligados através de opções como Peering, VPN, Link Privado, etc. Outra camada de segurança pode ser adicionada permitindo NSGs em sub-redes dentro do VNet. Além disso, você pode usar a modelagem de tráfego na VNet criando tabelas de rotas personalizadas, por exemplo, se quiser que todo o tráfego seja roteado por meio de um dispositivo virtual de rede para inspeção de pacotes.

### VPN e aplicativo Gateway

A VPN do Azure permite que você se conecte com segurança aos recursos do Azure a partir do centro de dados local por meio de conexão site a site ou de máquinas individuais usando conexão ponto a site. O tráfego para o Azure passa pela Internet, mas através de um túnel criptografado e seguro usando SSTP, OpenVPN ou IPSec. Embora a conexão VPN funcione bem em cenários de filiais, para conectividade garantida apoiada pelos SLAs do Azure, os clientes podem optar pelo ExpressRoute, que é uma conexão dedicada do seu centro de dados local à nuvem do Azure.

 

gateway de aplicativo do Azure é um balanceador de carga que opera na camada de aplicativo (OSI Layer 7) e redireciona o tráfego para recursos no pool de back-end com base em atributos HTTP. Possui um Firewall de aplicativo da web (Web Application Firewall, WAF) ([WAF](https://www.checkpoint.com/pt/cyber-hub/cloud-security/what-is-web-application-firewall/)) que ajuda a proteger seu aplicativo contra ataques comuns, como ataques de injeção de SQL, scripts entre sites, divisão de solicitações HTTP, inclusão remota de arquivos, etc. Ele vem com um conjunto predefinido de regras de segurança, mas também oferece flexibilidade para definir suas próprias regras. O serviço é baseado no [OWASP ModSecurity Core Set](https://owasp.org/www-project-modsecurity-core-rule-set/) e é capaz de se atualizar automaticamente para proteger seu aplicativo contra vulnerabilidades novas e em evolução.

### Gerenciamento de identidade e acesso (IAM)

Num mundo orientado para a nuvem, a Identidade emergiu como o novo perímetro de segurança. O Azure fornece RBAC (controle de acesso baseado em função) habilitado pelo Azure Active Directory (AD) para controlar o acesso ao aplicativo hospedado. Recomenda-se seguir o princípio do menor privilégio (PoLP) para que os usuários recebam apenas o acesso mínimo necessário para o seu trabalho. Esta autorização é decidida pela função atribuída ao usuário, que pode ser uma das funções integradas ou uma função personalizada definida pelo administrador.

 

Você pode fortalecer ainda mais o IAM por meio de opções como acesso Just-in-time (JIT) para VMs, assinatura de acesso compartilhado para armazenamento, Autenticação multifatorial, etc. Também é importante registar e monitorizar a atividade do utilizador através de registos de auditoria do Azure AD e registos de atividades do Azure para identificar identidades comprometidas e utilizadores não autorizados.

## Aprimorando a segurança do Azure

Embora ferramentas e serviços nativos geralmente forneçam um bom ponto de partida, você também precisa de ferramentas com recursos avançados para proteger seu aplicativo contra ameaças em evolução na nuvem. Os seguintes recursos adicionais são essenciais para garantir [segurança de nuvem abrangente](https://www.checkpoint.com/pt/cyber-hub/cloud-security/what-is-cloud-security/):

 

- **Visibilidade:** A detecção de invasões na nuvem em tempo real, a visualização do tráfego de rede e a análise da atividade do usuário que fornecem informações contextuais ajudarão a identificar e mitigar anomalias de forma proativa.
- **Automação:** a integração da automação nas operações de Segurança de Nuvem desde o primeiro dia, por meio de opções como modelos predefinidos e políticas de segurança autoadaptáveis, ajudará a evitar erros humanos e configurações incorretas.
- **Conformidade e Governança:** Relatórios de segurança adaptados para mostrar a Conformidade e a governança em relação aos padrões do setor simplificarão seu processo de geração de relatórios e auditoria.
- **Minimizando configurações incorretas:** a avaliação contínua das configurações do seu ambiente em relação aos padrões de segurança definidos e a automação de fluxos de trabalho e implementações de políticas ajudarão a minimizar configurações incorretas.
- **Inteligência e análise preditiva:** [A caça a ameaças](https://www.checkpoint.com/pt/cyber-hub/cloud-security/what-is-threat-hunting/) e a análise preditiva alimentada por IA podem ajudar a detectar anomalias com mais rapidez e gerar alertas em tempo real sobre atividades maliciosas.
- **Proteção de carga de trabalho/armazenamento (para contêiner e sem servidor):** Amplie seus recursos de segurança para contêineres e sem servidor para proteger cargas de trabalho modernas baseadas em microsserviços.

 

[CloudGuard](https://azuremarketplace.microsoft.com/en-us/marketplace/apps?search=cloudguard&page=1) pode ajudá-lo com todos os itens acima, pois vem pré-construído com esses recursos. Integra-se perfeitamente com as suas ferramentas nativas do Azure e aumenta a segurança dos seus dados e cargas de trabalho hospedadas no Azure.

 

Leia mais sobre como o CloudGuard pode ajudá-lo a atingir seus [objetivos de segurança na nuvem hoje](https://www.checkpoint.com/pt/solutions/microsoft-azure-security/).