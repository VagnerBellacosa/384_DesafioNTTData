

# O que são microsserviços?

Publicado 1 de maio de 2023•*6* minutos (tempo de leitura)



Copiar URL

## Ir para seção

[O que é são microsserviços?](https://www.redhat.com/pt-br/topics/microservices/what-are-microservices#o-que-é-são-microsserviços)[Desenvolvimento de aplicações mais eficiente](https://www.redhat.com/pt-br/topics/microservices/what-are-microservices#desenvolvimento-de-aplicações-mais-eficiente)[Microsserviços ou arquitetura monolítica?](https://www.redhat.com/pt-br/topics/microservices/what-are-microservices#microsserviços-ou-arquitetura-monolítica)[Microsserviços ou SOA?](https://www.redhat.com/pt-br/topics/microservices/what-are-microservices#microsserviços-ou-soa)[Benefícios](https://www.redhat.com/pt-br/topics/microservices/what-are-microservices#benefícios)[Desafios](https://www.redhat.com/pt-br/topics/microservices/what-are-microservices#desafios)[Ferramentas e tecnologias que viabilizam os microsserviços](https://www.redhat.com/pt-br/topics/microservices/what-are-microservices#ferramentas-e-tecnologias-que-viabilizam-os-microsserviços)[Como a Red Hat pode ajudar](https://www.redhat.com/pt-br/topics/microservices/what-are-microservices#como-a-red-hat-pode-ajudar)

## Microsserviços

Os microsserviços são um estilo de [arquitetura de aplicações](https://www.redhat.com/pt-br/topics/application-development-and-delivery/o-que-e-arquitetura-da-aplicacao) em que um conjunto independente de serviços se comunica por meio de [APIs](https://www.redhat.com/pt-br/topics/api/what-are-application-programming-interfaces).

Pense na última vez em que você visitou uma loja online. Provavelmente, você usou a barra de pesquisa do site para procurar produtos. Essa pesquisa representa um serviço. Talvez você até tenha visto recomendações de produtos relacionados, ou adicionado um item ao seu carrinho de compras. Ambos também são serviços. Junte todos esses microsserviços e você terá uma aplicação em pleno funcionamento.

## Desenvolvimento de aplicações mais eficiente

Uma arquitetura de microsserviços representa uma abordagem [nativa em nuvem](https://www.redhat.com/pt-br/topics/cloud-native-apps) à criação de software, em que cada função principal de uma aplicação pode existir de maneira independente. 

Quando os elementos de uma aplicação são segregados dessa maneira, as equipes de desenvolvimento e de operações podem trabalhar juntas, sem interferir uma no trabalho da outra. Isso significa mais desenvolvedores trabalhando simultaneamente na mesma aplicação, reduzindo o tempo gasto com desenvolvimento.

 

![imagem](https://www.redhat.com/cms/managed-files/monolithic-vs-microservices.png)

## Recursos da Red Hat

[Leia mais](https://www.redhat.com/pt-br/resources)

## Arquitetura de microsserviços ou arquitetura monolítica?

A abordagem tradicional de criação de aplicações se concentra no modelo monolítico. Em uma arquitetura monolítica, todas as funções e serviços de uma aplicação são acoplados e funcionam como uma única unidade. Quando você adiciona a aplicação ou a aprimora de qualquer maneira, a complexidade da arquitetura aumenta. Assim, é mais difícil otimizar uma função separada sem desmantelar toda a aplicação. Além disso, se você precisar expandir um processo, a aplicação toda também deverá ser escalada.

Já nas arquiteturas de microsserviços, as aplicações são criadas de modo que cada função principal é executada de maneira independente. Assim, as equipes de desenvolvimento podem criar e atualizar novos componentes para atender às mudanças nas necessidades empresariais sem interromper a aplicação na totalidade.

## Arquitetura de microsserviços ou arquitetura orientada a serviço (SOA)?

A arquitetura de microsserviços é uma evolução da [arquitetura orientada a serviço (SOA)](https://www.redhat.com/pt-br/topics/cloud-native-apps/what-is-service-oriented-architecture). Ambas as abordagens são similares porque dividem aplicações grandes e complexas em componentes menores mais fáceis de trabalhar. Devido às semelhanças, as pessoas costumam acreditar que a SOA e a arquitetura de microsserviços são a mesma coisa. A principal característica que os diferencia é o escopo: a SOA é uma abordagem de arquitetura adotada pela empresa na totalidade, enquanto os microsserviços são uma estratégia de implementação da equipe de desenvolvimento para cada aplicação.

## Benefícios da arquitetura de microsserviços

Com microsserviços, você pode aumentar a eficiência das suas equipes e tarefas rotineiras com o desenvolvimento distribuído. Além disso, é possível desenvolver vários microsserviços ao mesmo tempo. Isso significa mais desenvolvedores trabalhando simultaneamente na mesma aplicação, reduzindo o tempo gasto com desenvolvimento.

### Mais agilidade

Como os ciclos de desenvolvimento são menores, a arquitetura de microsserviços é compatível com implantações e atualizações mais ágeis.

### Alta escalabilidade

À medida que a demanda por determinados serviços aumenta, você pode fazer implantações em vários servidores e infraestruturas para atender às suas necessidades.

### Resiliência

Se criados corretamente, os serviços independentes não afetam uns aos outros. Em outras palavras, se uma parte falhar, o restante da app continuará funcionando, ao contrário do modelo monolítico.

### Facilidade de implantação

As apps baseadas em microsserviços são mais modulares e menores do que as monolíticas tradicionais, então não tem por que se preocupar com essas implantações. Isso requer uma coordenação maior, que pode ser alcançada com uma [camada de service mesh](https://www.redhat.com/pt-br/topics/microservices/what-is-a-service-mesh), mas as vantagens podem ser inúmeras.

### Acessibilidade

Como a app maior é decomposta em partes menores, os desenvolvedores têm mais facilidade para entendê-las, atualizá-las e aprimorá-las. Isso resulta em ciclos de desenvolvimento mais rápidos, principalmente quando também são empregadas [metodologias de desenvolvimento ágil](https://www.redhat.com/pt-br/topics/devops/what-is-agile-methodology), como o [DevOps.](https://www.redhat.com/pt-br/topics/devops)

### Open source

Graças às APIs com suporte a múltiplas linguagens, a equipe de desenvolvimento pode escolher a melhor linguagem e tecnologia para a função necessária.

## Possíveis desafios relacionados aos microsserviços

A flexibilidade oferecida pelos microsserviços cria uma determinada urgência em implantar novas mudanças, ou seja, criar novos padrões. Na engenharia de softwares, um “padrão” se refere a qualquer solução baseada em algoritmo conhecida por funcionar. Um “antipadrão” são erros comuns cometidos com a intenção de resolver um problema, mas que podem piorar a situação em longo prazo.

Além das mudanças na cultura e nos processos, a complexidade e a eficiência são outros dois grandes desafios da arquitetura baseada em microsserviços. Ao trabalhar com uma arquitetura de microsserviços, é importante ficar de olho nesses antipadrões comuns.

1. **Escalabilidade:** expandir qualquer função no processo de desenvolvimento do ciclo de vida de software pode trazer desafios, principalmente nas primeiras etapas. Durante a configuração inicial, é importante identificar as dependências entre os serviços e reconhecer possíveis gatilhos que inviabilizem a compatibilidade retroativa. Quando chega a hora da implantação, é essencial investir na [automação](https://www.redhat.com/pt-br/topics/automation), porque fazer esse trabalho manualmente é muito difícil devido à complexidade dos microsserviços.
2. **Geração de logs:** com os sistemas distribuídos, são necessários logs centralizados para unificar tudo. Caso contrário, é impossível gerenciar a escala.
3. **Monitoramento:** é essencial ter uma visualização centralizada do sistema para identificar as origens dos problemas.
4. **Depuração:** a depuração remota por meio do [ambiente de desenvolvimento integrado (IDE)](https://www.redhat.com/pt-br/topics/middleware/what-is-ide) local não é viável e não funciona com dezenas ou centenas de serviços. Infelizmente, no momento não há uma única resposta sobre como realizar depurações.
5. **Conectividade:** faça a detecção de serviços, seja de maneira centralizada ou integrada.

## Ferramentas e tecnologias que viabilizam os microsserviços

**Containers e Kubernetes** 
O [Kubernetes](https://www.redhat.com/pt-br/topics/containers) é uma plataforma de orquestração de containers onde os componentes separados de uma aplicação podem ser atualizados sem afetar o restante do stack de tecnologia. Por isso, ele é perfeito para automatizar o gerenciamento, escalabilidade e implantação das aplicações de microsserviços.

**APIs**
Uma interface de programação de aplicações (API) é a parte de uma aplicação que fica encarregada da comunicação com outras aplicações. Na infraestrutura das arquiteturas de microsserviços, as APIs desempenham um papel fundamental: possibilitar que diferentes serviços de um microsserviço compartilhem informações e funcionem como um só.

**Transmissão de eventos**
Um evento é definido como qualquer atividade que ocorre em um serviço do microsserviço. Por exemplo, quando alguém adiciona um item ao carrinho de compras online ou o remove de lá.

Os eventos compõem as transmissões de eventos, que refletem a mudança no comportamento de um sistema. Com o monitoramento dos eventos, as organizações podem tirar melhores conclusões com base nos dados e no comportamento dos usuários. Por meio do [processamento de fluxo do evento](https://www.redhat.com/pt-br/topics/integration/o-que-e-transmissao-de-dados), é possível tomar medidas imediatas. Ele pode ser usado diretamente com as cargas de trabalho operacionais em tempo real. As empresas estão aplicando a transmissão de eventos a tudo, da análise de fraudes à manutenção das máquinas.

**Computação serverless**
[A computação serverless](https://www.redhat.com/pt-br/topics/cloud-native-apps/what-is-serverless) é um modelo de desenvolvimento nativo em nuvem onde os desenvolvedores podem criar e executar aplicações, contando com um [provedor de nuvem responsável pelo](https://www.redhat.com/pt-br/topics/cloud-computing/what-are-cloud-providers)[provisionamento](https://www.redhat.com/pt-br/topics/automation/what-is-provisioning), manutenção e escala da [infraestrutura](https://www.redhat.com/pt-br/topics/cloud-computing/what-is-it-infrastructure) do servidor. Os desenvolvedores só precisam empacotar o código em containers para fazer a implantação. Ele ajuda as empresas a acelerarem a inovação, pois a aplicação é abstraída da infraestrutura subjacente.

## Como a Red Hat pode ajudar

Com as soluções open source da Red Hat, é possível desmembrar as aplicações monolíticas em microsserviços, além de gerenciá-los, orquestrá-los e processar os dados criados por eles. 

**Red Hat OpenShift**
[Red Hat® OpenShift®](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift) é uma plataforma baseada no Kubernetes que viabiliza os microsserviços oferecendo uma maneira uniforme de conectar, gerenciar e observar as aplicações baseadas em microsserviços. Essa plataforma é compatível com aplicações nativas em nuvem, legadas e em containers, além daquelas que estão sendo refatoradas em microsserviços. O OpenShift é integrado ao [Red Hat Application Services](https://www.redhat.com/pt-br/products/application-foundations) e pode ser usado com ferramentas de automação existentes, como Git e Jenkins. Ele também incorpora um [sistema operacional Linux](https://www.redhat.com/pt-br/topics/linux) empresarial para oferecer mais segurança em todo o cluster. 

Esteja você otimizando aplicações legadas, fazendo a migração para a nuvem ou criando soluções totalmente novas baseadas em microsserviços, o Red Hat OpenShift oferece a essas aplicações uma plataforma mais segura e estável em toda a infraestrutura.

**Red Hat Runtimes**

[Red Hat Runtimes](https://www.redhat.com/pt-br/products/application-runtimes/features) é um conjunto de bases de runtimes predefinidos e em containers para microsserviços. Ele é compatível com uma grande variedade de linguagens e frameworks usados no design de arquiteturas de microsserviços, como Quarkus, Spring Boot, MicroProfile e Node.js. Além disso, o Red Hat Runtimes inclui serviços de apoio que aceleram o acesso aos dados com o Red Hat Data Grid, além de proteção para as APIs dos microsserviços com o single sign-on da Red Hat.

**Red Hat Integration**

[Red Hat Integration](https://www.redhat.com/pt-br/products/integration) é um conjunto abrangente de tecnologias de integração e mensageria para conectar aplicações e dados em infraestruturas híbridas. Trata-se de uma solução ágil, em containers e orientada a APIs. Essa solução oferece recursos de composição e orquestração de serviços, conectividade de aplicações e transformação de dados, transmissão de mensagens em tempo real e gerenciamento de APIs. Tudo isso combinado a uma plataforma nativa em nuvem e a uma cadeia de ferramentas compatíveis com toda a variedade de desenvolvimento de aplicações modernas.

Os desenvolvedores podem usar ferramentas como serviços de arrastar e soltar e padrões internos de integração para criar microsserviços. Enquanto isso, os usuários de negócios podem utilizar ferramentas baseadas na web para desenvolver APIs que integram diferentes microsserviços.

[Por que escolher a Red Hat para o gerenciamento de APIs?](https://www.redhat.com/pt-br/topics/integration/por-que-escolher-red-hat-para-o-gerenciamento-de-apis)





Hub

## Blog da Red Hat

Tudo relacionado à Red Hat: soluções, treinamentos e certificações Red Hat, casos de sucesso de clientes, novidades dos nossos parceiros e notícias sobre projetos das comunidades open source.

[Leia mais](https://www.redhat.com/pt-br/blog)

## Teste as soluções da Red Hat

Você sabia que a Red Hat oferece versões de teste gratuitas de suas soluções? Aproveite e obtenha experiência prática, prepare-se para uma certificação da Red Hat ou avalie na prática se a solução é adequada para ao caso de uso.

[Leia mais](https://www.redhat.com/pt-br/products/trials)

## Leia mais

### What is the Kubernetes Java client?

The Kubernetes Java client is a client library that enables the use of the Java programming language to interface with Kubernetes.

[Leia o artigo](https://www.redhat.com/pt-br/topics/cloud-computing/what-is-kubernetes-java-client)

### Kubernetes na AWS: comparação entre K8s autogerenciado e plataforma de aplicações gerenciada

Conheça as vantagens de usar o Kubernetes (K8s) na AWS e entenda as diferenças entre o Kubernetes autogerenciado e uma plataforma de aplicações gerenciada.

[Leia o artigo](https://www.redhat.com/pt-br/topics/containers/kubernetes-on-aws)

### O que é hosted control plane?

Hosted control plane refere-se ao plano de gerenciamento desacoplado que permite o controle e gerenciamento consolidados dos principais componentes do plano de controle.

[Leia o artigo](https://www.redhat.com/pt-br/topics/containers/what-are-hosted-control-planes)

## Containers: leitura recomendada

### Conteúdo relacionado

- Blog post

  [Domine a complexidade com o Red Hat Enterprise Linux 9.5](https://www.redhat.com/pt-br/blog/red-hat-enterprise-linux-95-release)

- Datasheet

  [Red Hat OpenShift for IBM zSystems and IBM LinuxONE](https://www.redhat.com/pt-br/resources/openshift-ibm-z-linuxone-datasheet)

- Datasheet

  [Red Hat OpenShift for IBM Power](https://www.redhat.com/pt-br/resources/openshift-ibm-power-systems-datasheet)

- Datasheet

  [Red Hat OpenShift Data Foundation: armazenamento persistente e gerenciamento de dados de cluster do Red Hat OpenShift](https://www.redhat.com/pt-br/resources/openshift-data-foundation-datasheet)

### Artigos relacionados

- [O que é KubeVirt?](https://www.redhat.com/pt-br/topics/virtualization/what-is-kubevirt)
- [O que é o Podman Desktop?](https://www.redhat.com/pt-br/topics/open-source/o-que-e-o-podman-desktop)
- [Red Hat OpenShift Virtualization: virtualização nativa em containers](https://www.redhat.com/pt-br/topics/containers/what-is-container-native-virtualization)
- [What is the Kubernetes Java client?](https://www.redhat.com/pt-br/topics/cloud-computing/what-is-kubernetes-java-client)
- [Kubernetes na AWS: comparação entre K8s autogerenciado e plataforma de aplicações gerenciada](https://www.redhat.com/pt-br/topics/containers/kubernetes-on-aws)
- [O que é hosted control plane?](https://www.redhat.com/pt-br/topics/containers/what-are-hosted-control-planes)
- [Edge computing: implante na edge com o Red Hat OpenShift](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/edge-computing)
- [Kubernetes: importância da segurança](https://www.redhat.com/pt-br/topics/containers/kubernetes-security)
- [Uso do Kubernetes em Inteligência Artificial e Machine Learning](https://www.redhat.com/pt-br/topics/cloud-computing/how-kubernetes-can-help-ai)
- [O que é arquitetura orientada a serviços (SOA)?](https://www.redhat.com/pt-br/topics/cloud-native-apps/what-is-service-oriented-architecture)
- [Stateful e stateless](https://www.redhat.com/pt-br/topics/cloud-native-apps/stateful-vs-stateless)
- [O que é Quarkus?](https://www.redhat.com/pt-br/topics/cloud-native-apps/what-is-quarkus)
- [O que é conteinerização?](https://www.redhat.com/pt-br/topics/cloud-native-apps/what-is-containerization)
- [O que é Kubeflow?](https://www.redhat.com/pt-br/topics/cloud-computing/what-is-kubeflow)
- [OpenShift vs Openstack: quais são as diferenças?](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/openshift-vs-openstack)
- [Segurança de containers: tudo o que você precisa saber](https://www.redhat.com/pt-br/topics/security/container-security)
- [o que é Buildah?](https://www.redhat.com/pt-br/topics/open-source/o-que-e-buildah)
- [A diferença entre o Kubernetes e o OpenStack](https://www.redhat.com/pt-br/topics/containers/diferenca-entre-o-kubernetes-e-o-openstack)
- [YAML | O que é YAML?](https://www.redhat.com/pt-br/topics/automation/what-is-yaml)
- [Docker | O que é Docker e como ele funciona?](https://www.redhat.com/pt-br/topics/containers/what-is-docker)
- [Image Builder - O que é image builder e como usar?](https://www.redhat.com/pt-br/topics/linux/what-is-an-image-builder)
- [Red Hat OpenShift vs OKD](https://www.redhat.com/pt-br/topics/containers/red-hat-openshift-okd)
- [Red Hat OpenShift e Kubernetes: qual é a diferença?](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/red-hat-openshift-kubernetes)
- [O que é alta disponibilidade e recuperação de desastres para containers?](https://www.redhat.com/pt-br/topics/containers/o-que-e-alta-disponibilidade-e-recuperacao-de-desastres-para-containers)
- [Por que executar o Apache Kafka no Kubernetes?](https://www.redhat.com/pt-br/topics/open-source/por-que-executar-o-apache-kafka-no-kubernetes)
- [Spring Framework no Kubernetes com o Red Hat OpenShift](https://www.redhat.com/pt-br/technologies/red-hat-openshift/spring-no-kubernetes-com-o-red-hat-openshift)
- [O que é uma golden image?](https://www.redhat.com/pt-br/topics/linux/what-is-a-golden-image)
- [O que são os serviços de nuvem do Red Hat OpenShift?](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/what-are-red-hat-openshift-managed-services)
- [O que é um registro de containers?](https://www.redhat.com/pt-br/topics/cloud-native-apps/what-is-a-container-registry)
- [Podman: tudo o que você precisa saber sobre esta ferramenta](https://www.redhat.com/pt-br/topics/containers/what-is-podman)
- [O que é Skopeo?](https://www.redhat.com/pt-br/topics/containers/what-is-skopeo)
- [Para que servem os operadores do Red Hat OpenShift?](https://www.redhat.com/pt-br/technologies/red-hat-openshift/para-que-servem-os-operadores-do-red-hat-openshift)
- [Como usar o Helm com o Red Hat OpenShift](https://www.redhat.com/pt-br/technologies/red-hat-openshift/como-usar-o-helm-com-o-red-hat-openshift)
- [Práticas recomendadas de segurança do Kubernetes](https://www.redhat.com/pt-br/topics/containers/kubernetes-security-best-practices)
- [Orquestração de containers do Windows no Red Hat OpenShift](https://www.redhat.com/pt-br/technologies/red-hat-openshift/orquestracao-de-containers-do-windows-no-red-hat-openshift)
- [O que é um container Linux?](https://www.redhat.com/pt-br/topics/containers/o-que-e-um-container-linux)
- [O que são sandboxed containers?](https://www.redhat.com/pt-br/topics/containers/sandboxed-containers)
- [O que é orquestração de containers?](https://www.redhat.com/pt-br/topics/containers/what-is-container-orchestration)
- [Red Hat Ansible Automation Platform e Red Hat OpenShift: como funcionam juntos?](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/ansible-on-openshift)
- [Computação de alto desempenho com o Red Hat OpenShift](https://www.redhat.com/pt-br/technologies/red-hat-openshift/computacao-de-alto-desempenho-com-o-red-hat-openshift)
- [Vantagens da segurança nativa do Kubernetes](https://www.redhat.com/pt-br/topics/containers/advantages-of-kubernetes-native-security)
- [O que é KubeLinter?](https://www.redhat.com/pt-br/topics/containers/what-is-kubelinter)
- [Considerações sobre conformidade do Kubernetes e containers](https://www.redhat.com/pt-br/topics/security/consideracoes-sobre-conformidade-do-kubernetes-e-containers)
- [Introdução à segurança do Kubernetes](https://www.redhat.com/pt-br/topics/containers/intro-kubernetes-security)
- [Microsserviços e integração de TI no setor de saúde](https://www.redhat.com/pt-br/topics/containers/microsservicos-e-integracao-de-ti-no-setor-de-saude)
- [Gerenciamento de clusters Kubernetes](https://www.redhat.com/pt-br/technologies/red-hat-advanced-cluster-management-kubernetes/gerenciamento-de-clusters-kubernetes)
- [Red Hat OpenShift na infraestrutura de TI da IBM](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/what-is-red-hat-openshift-on-IBM-IT-infrastructure)
- [Red Hat OpenShift: benefícios, oportunidades e casos de sucesso](https://www.redhat.com/pt-br/technologies/red-hat-openshift/red-hat-openshift-para-lideres-empresariais)
- [Gerenciamento de custos do Kubernetes](https://www.redhat.com/pt-br/technologies/red-hat-openshift/gerenciamento-de-custos-do-kubernetes)
- [Red Hat OpenShift | Tipos de implantações disponíveis](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/deploy-red-hat-openshift)
- [Red Hat OpenShift em plataformas VMware](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/vmware)
- [Red Hat OpenShift para desenvolvedores](https://www.redhat.com/pt-br/technologies/red-hat-openshift/red-hat-openshift-para-desenvolvedores)
- [Desenvolvimento Java nativo em Kubernetes com Quarkus](https://www.redhat.com/pt-br/technologies/red-hat-application-foundations/por-que-desenvolver-aplicacoes-java-com-o-quarkus-no-red-hat-openshift)
- [Red Hat OpenShift para as operações de TI](https://www.redhat.com/pt-br/technologies/red-hat-openshift/red-hat-openshift-para-operacoes-de-ti)
- [O que é Kubernetes empresarial?](https://www.redhat.com/pt-br/topics/containers/o-que-e-kubernetes-empresarial)
- [Cargas de trabalho SAP no Red Hat OpenShift](https://www.redhat.com/pt-br/technologies/red-hat-openshift-container-platform/sap-no-red-hat-openshift)
- [O que é o controle de acesso baseado em função (RBAC)](https://www.redhat.com/pt-br/topics/containers/o-que-e-o-controle-de-acesso-baseado-em-funcao-rbac)
- [VNF e CNF: qual a diferença?](https://www.redhat.com/pt-br/topics/cloud-native-apps/vnf-and-cnf-whats-the-difference)
- [O que foram o CoreOS e o CoreOS container Linux](https://www.redhat.com/pt-br/technologies/red-hat-openshift/o-que-foram-o-coreos-e-o-coreos-container-linux)
- [Aprenda o básico sobre o Kubernetes](https://www.redhat.com/pt-br/topics/containers/aprenda-o-basico-sobre-o-kubernetes)
- [API Kubernetes: entenda o que é e como funciona](https://www.redhat.com/pt-br/topics/containers/api-kubernetes)
- [O que é gerenciamento de clusters do Kubernetes?](https://www.redhat.com/pt-br/topics/containers/what-is-kubernetes-cluster-management)
- [O que é um operador Kubernetes?](https://www.redhat.com/pt-br/topics/containers/o-que-e-um-operador-kubernetes)
- [O que é uma implantação Kubernetes?](https://www.redhat.com/pt-br/topics/containers/o-que-e-uma-implantacao-kubernetes)
- [Por que escolher a versão do Quarkus da Red Hat?](https://www.redhat.com/pt-br/topics/application-development-and-delivery/por-que-escolher-versao-da-red-hat-do-quarkus)
- [¿Qué es Kubernetes?](https://www.redhat.com/pt-br/topics/containers/what-is-kubernetes)
- [Introdução à arquitetura do Kubernetes](https://www.redhat.com/pt-br/topics/containers/kubernetes-architecture)
- [O que é Container-as-a-service (CaaS)?](https://www.redhat.com/pt-br/topics/cloud-computing/what-is-caas)
- [Introdução aos padrões para Kubernetes](https://www.redhat.com/pt-br/topics/containers/introducao-aos-padroes-do-kubernetes)
- [O que é um cluster do Kubernetes?](https://www.redhat.com/pt-br/topics/containers/what-is-a-kubernetes-cluster)
- [Containers e máquinas virtuais (VMs): qual a diferença?](https://www.redhat.com/pt-br/topics/containers/containers-vs-vms)
- [O que é Jaeger?](https://www.redhat.com/pt-br/topics/open-source/o-que-e-jaeger)
- [O que é Clair?](https://www.redhat.com/pt-br/topics/open-source/o-que-e-clair)
- [Red Hat OpenShift Serverless: conheça todas as vantagens](https://www.redhat.com/pt-br/topics/microservices/why-choose-openshift-serverless)
- [O que é o Knative?](https://www.redhat.com/pt-br/topics/microservices/what-is-knative)
- [O que é etcd?](https://www.redhat.com/pt-br/topics/open-source/o-que-e-etcd)
- [Microsserviços: por que usar soluções Red Hat?](https://www.redhat.com/pt-br/topics/containers/por-que-escolher-red-hat-para-adocao-de-microsservicos)
- [Plataforma de container Linux da Red Hat](https://www.redhat.com/pt-br/topics/containers/why-choose-red-hat-containers)
- [O que é um pod do Kubernetes? [DO NOT OVERWRITE PT-BR PAGE\]](https://www.redhat.com/pt-br/topics/containers/o-que-e-um-pod-do-kubernetes)

[Leia mais sobre este tópico](https://www.redhat.com/pt-br/topics/containers)

## 

[![Red Hat logo](https://static.redhat.com/libs/redhat/brand-assets/2/corp/logo--on-dark.svg)](https://www.redhat.com/pt-br)



















Soluções e portfólios[Red Hat AI](https://www.redhat.com/pt-br/products/ai)[Red Hat Enterprise Linux](https://www.redhat.com/pt-br/technologies/linux-platforms/enterprise-linux)[Red Hat OpenShift](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift)[Red Hat Ansible Automation Platform](https://www.redhat.com/pt-br/technologies/management/ansible)[Red Hat Cloud Services](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/cloud-services)[Veja todos os produtos](https://www.redhat.com/pt-br/technologies/all-products)Ferramentas[Treinamento e certificação](https://www.redhat.com/pt-br/services/training-and-certification)[Minha conta](https://www.redhat.com/wapps/ugc/protected/personalInfo.html)[Suporte ao cliente](https://access.redhat.com/)[Recursos para desenvolvedores](https://developers.redhat.com/)[Encontre um parceiro](https://catalog.redhat.com/partners)[Red Hat Ecosystem Catalog](https://catalog.redhat.com/)[Documentação](https://docs.redhat.com/pt)Experimente, compre e venda[Central de testes de soluções](https://www.redhat.com/pt-br/products/trials)[Red Hat Store](https://www.redhat.com/en/store)[Console](https://cloud.redhat.com/)Comunicação[Contate o setor de vendas](https://www.redhat.com/pt-br/contact/sales)[Contate o atendimento ao cliente](https://www.redhat.com/pt-br/contact/customer-service)[Contate o setor de treinamento](https://www.redhat.com/pt-br/services/training-and-certification/contact-us)[Redes sociais](https://www.redhat.com/pt-br/about/social)

Sobre a Red Hat

A Red Hat é líder em fornecer tecnologias de nuvem híbrida aberta que compõem uma base consistente para aplicações transformadoras de TI e inteligência artificial (IA).[ Parceira de confiança das empresas da Fortune 500](https://www.redhat.com/pt-br/about/company), a Red Hat oferece tecnologias de nuvem, desenvolvimento, Linux, automação e plataforma de aplicações, além de [serviços premiados](https://access.redhat.com/recognition).

- [Nossa empresa](https://www.redhat.com/pt-br/about/company)
- [Nosso modelo de trabalho](https://www.redhat.com/pt-br/about/our-culture)
- [Casos de sucesso de clientes](https://www.redhat.com/pt-br/success-stories)
- [Relações com analistas](https://www.redhat.com/pt-br/about/analysts)
- [Notícias](https://www.redhat.com/pt-br/about/newsroom)
- [Compromisso com o open source](https://www.redhat.com/pt-br/about/open-source)
- [Nosso impacto social](https://www.redhat.com/pt-br/about/community-social-responsibility)
- [Vagas disponíveis](https://www.redhat.com/pt-br/jobs)

Selecione um idioma

![img](https://static.redhat.com/libs/redhat/rh-iconfont/4/svg/web-icon-globe.svg)Português

## 



[Sobre a Red Hat](https://www.redhat.com/pt-br/about/company)[Oportunidades de emprego](https://www.redhat.com/pt-br/jobs)[Eventos](https://www.redhat.com/pt-br/events)[Escritórios](https://www.redhat.com/pt-br/about/office-locations)[Fale com a Red Hat](https://www.redhat.com/pt-br/contact)[Blog da Red Hat](https://www.redhat.com/pt-br/blog)[Inclusão na Red Hat](https://www.redhat.com/pt-br/about/our-culture/inclusion)[Cool Stuff Store](https://coolstuff.redhat.com/)[Red Hat Summit](https://www.redhat.com/en/summit)

© 2025 Red Hat, Inc.[Declaração de privacidade](https://www.redhat.com/pt-br/about/privacy-policy)[Termos de uso](https://www.redhat.com/pt-br/about/terms-use)[Todas as políticas e diretrizes](https://www.redhat.com/pt-br/about/all-policies-guidelines)[Acessibilidade digital](https://www.redhat.com/pt-br/about/digital-accessibility)Preferências de cookies



[Skip to content](https://www.redhat.com/pt-br/topics/microservices/what-are-microservices#rhb-main-content)



<details id="hamburger" open="" style="box-sizing: border-box; align-content: center; block-size: 83px; display: flex; grid-area: unset; place-items: center; background-color: initial; box-shadow: none; padding: 0px;"><div id="details-content" role="list" style="box-sizing: border-box; display: flex; align-items: center; block-size: 83px; flex-direction: row; justify-content: flex-start;"><slot style="box-sizing: border-box;"></slot></div></details>



- [Tópicos ](https://www.redhat.com/pt-br/topics)
- 
- [ Containers ](https://www.redhat.com/pt-br/topics/containers)
- 
-  O que são microsserviços?
- 

<iframe class="drift-frame-chat" scrolling="no" title="Drift Widget Chat Window" allow="autoplay; encrypted-media; fullscreen;" frameborder="0" src="https://js.driftt.com/core/chat?d=1&amp;region=US&amp;driftEnableLog=false&amp;pageLoadStartTime=1749841970559" aria-hidden="true" tabindex="-1" style="box-sizing: border-box; display: block; min-width: 0px; max-width: 100%; min-height: 0px; max-height: none; color-scheme: light only; border: none; background: transparent; width: 400px !important; height: 0px;"></iframe>

<iframe class="drift-frame-controller" scrolling="no" title="Drift Widget Chat Controller" allow="autoplay; encrypted-media; fullscreen;" frameborder="0" src="https://js.driftt.com/core?d=1&amp;embedId=vtgnfrnufv54&amp;eId=vtgnfrnufv54&amp;region=US&amp;forceShow=false&amp;skipCampaigns=false&amp;sessionId=8205ead1-e6b1-4624-ba27-685eee3a3639&amp;sessionStarted=1749841987.221&amp;campaignRefreshToken=5785149e-41db-4ae7-b55e-7ad0cb0b877e&amp;hideController=false&amp;pageLoadStartTime=1749841970559&amp;mode=CHAT&amp;driftEnableLog=false&amp;loadStrategy=ON_INTERACTIVE&amp;secureIframe=false&amp;u=https%3A%2F%2Fwww.redhat.com%2Fpt-br%2Ftopics%2Fmicroservices%2Fwhat-are-microservices" style="box-sizing: border-box; display: block; min-width: 0px; max-width: 100%; min-height: 0px; max-height: none; bottom: 24px; color-scheme: light only; border: none; background: transparent; width: 311.5px; height: 80px;"></iframe>

