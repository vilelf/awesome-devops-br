# awesome-devops-br
Lista de recursos (links, livros, Q&amp;A) discutidos no canal do Telegram Devops-BR (https://t.me/devopsbr)
## Table of Contents
* [Awesome Devops BR](#awesome-devops-br)
  * [Por Onde Começar](#por-onde-começar)
  * [Ferramentas](#ferramentas)
  * [Livros](#livros)
  * [Q&amp;A](#q--a)
  * [Bookmarks](#bookmarks)
  * [Segurança](#segurança)
  * [Blogs técnicos de grandes empresas](#blogs-técnicos-de-grandes-empresas)

## Por onde começar

- [gutocarvalho](https://archive.gutocarvalho.net/hugo/2016/09/06/por-onde-iniciar-os-estudos-sobre-devops/) - Por onde iniciar os estudos sobre Devops?
- [origens](https://archive.gutocarvalho.net/hugo/2016/06/02/origens-da-cultura-devops/) - Origens da cultura Devops
- [quora](https://www.quora.com/What-are-the-best-resources-for-learning-about-DevOps) - What are the best resources for learning about Devops?
- [opsschool](http://www.opsschool.org/en/latest/) - Learn to be an operations engineer
- [jedi](http://www.jedi.be/blog/2010/02/12/what-is-this-devops-thing-anyway/) - What is this devops thing?
- [newrelic](https://blog.newrelic.com/2014/05/16/devops-name/) - Devops origins
- [newrelic-devops](https://blog.newrelic.com/2017/01/26/how-new-relic-does-devops/) - How New Relic does Devops
- [what-is-devops](https://medium.com/@cindysridharan/what-is-devops-5b0181fdb953) - What is Devops
- [devops-topologies](http://web.devopstopologies.com/) - Artigo que apresenta exemplos do que é e do que não é devops

## Ferramentas

- [netdata](http://my-netdata.io/) - Ferramenta de monitoramento
- [hystrix](https://github.com/Netflix/Hystrix/wiki/How-it-Works) - Biblioteca do Netflix que implementa mecanismos de tolerância a falhas
- [sentry](https://sentry.io/welcome/) - Ferramenta de tracking de erros
- [chocolatey](https://chocolatey.org/) - Ferramenta de pacotes para windows
- [testinfra](https://testinfra.readthedocs.io/en/latest/) - Ferramenta para teste de infra
- [vault-ui](https://github.com/nyxcharon/vault-ui) - UI para o hashicorp vault
- [vault-web](https://github.com/AMeng/vault-web) - UI para o hashicorp vault
- [hygieia](https://github.com/capitalone/Hygieia) - Hygieia, um dashboard para agregar informações
- [flywaydb](https://flywaydb.org/) - Ferramenta para migração de bancos
- [linux-performance-tools](https://www.reddit.com/r/linux/comments/4x4smu/linux_performance_tools_full_version_draft/) - Excelente gráfico de ferramentas para profiling no Linux
- [fabio](https://github.com/fabiolb/fabio) - A fast, modern, zero-conf load balancing HTTP(S) router for deploying microservices managed by consul
- [supervidord](http://supervisord.org/) - Supervisor: A Process Control System
- [traefik](https://docs.traefik.io/) - A modern HTTP reverse proxy and load balancer made to deploy microservices with ease
- [jenkins](https://jenkins.io/projects/blueocean/) - Jenkins, ferramenta de CI e CD
- [envoy](https://medium.com/@cindysridharan/envoy-953c340c2dca) - Envoy, a network proxy
- [cloudcraft-aws-diagrams](https://cloudcraft.co/) - Cloudcraft – Draw AWS diagrams
- [pinpoint-apm](https://github.com/naver/pinpoint) - Pinpoint - APM Opensource
- [chaosmonkey](https://github.com/Netflix/chaosmonkey) - Resiliency tool that helps applications tolerate random instance failures.
- [namecom](https://www.name.com/) - Registro de nomes
- [dnssimple](https://dnsimple.com/) - Registro de nomes DNS
- [dynatrace](https://www.dynatrace.com/) - Dynatrace - APM
- [rollbar](https://rollbar.com/) - Rollbar - Monitoramento de erros
- [smartbear](https://smartbear.com/) - SmartBear - Ferramenta de testes, monitoramento e APM
- [databaselabs](https://www.databaselabs.io/) - Postgres Database as a Service

## Livros

**The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win** (*Kevin Behr, George Spafford, Gene Kim*): Uma narrativa sobre a introdução de DevOps em uma empresa fícticia - que em certos momentos farão você cogitar a possibilidade do Gene Kim ser um espião trabalhando ao seu lado devido as grandes semelhanças com _qualquer empresa de TI_. Será impossível não se identificar de forma assustadora com os personagens do livro e dar pequenos sorrisos ao encontrar versões "da vida real" dos mesmos.

**The DevOps Handbook: How to Create World-Class Agility, Reliability, and Security in Technology Organizations** (*Gene Kim, Jez Humble, Patrick Debois, and John Willis*): Está com a sensação de que o projeto unicórnio do Phoenix Project é pura ficcão? Não sabe como colocar o "Three Ways" em prática ou por onde começar? Este livro vai te ajudar a entender DevOps e ilustrar o case de grandes organizações completamente transformadas ou impulsionadas por DevOps, Lean, Agile, TPS e etc.

> **Citações**:

* *"In DevOps, we typically define our technology value stream as the process required to convert a business hypothesis into a technology-enabled service that delivers value to the customer."*

* *"Agile often serves as an effective enabler of DevOps, because of its focus on small teams continually delivering high quality code to customers."*

* *"DevOps isn’t about automation, just as astronomy isn’t about telescopes."*

* *"Because value is created only when our services are running in production, we must ensure that we are not only delivering fast flow, but that our deployments can also be performed without causing chaos and disruptions such as service outages, service impairments, or security or compliance failures."*

* *"Instead of a culture of fear, we have a high-trust, collaborative culture, where people are rewarded for taking risks."* 

**Release It!: Design and Deploy Production-Ready Software** (*Michael T. Nygard*): Porque a Amazon não fica indisponível na Black Friday e meu site não fica em pé com um aumento de 20% na carga por causa de um cupom novo? Qual o custo dessa indisponibilidade para a minha empresa? Como reverter essa situação? Porque a distância entre `feature-complete` e `production-ready` é tão grande? Se você *não* estiver familiarizado com os termos "Inversão de SLA", "Circuit Breaker", "Zero downtime deployments", "Falhas em cascata", "Bulkheads", "Unbalanced Capacities", "Unbounded Result Sets", leia-este-livro-agora.

> **Citações**:

* *"First, you need to accept that fact that despite your best laid plans, bad things will still happen. Second, realize that “Release 1.0” is not the end of the development project but the beginning of the system’s life on its own.*"

* *"Software design today resembles automobile design in the early 90s: disconnected from the real world."*

* *"Systems spend much more of their life in operation than in development—at least, the ones that don’t get canceled or scrapped do."*

* *"Don't avoid one-time development expenses at the cost of recurring operational expenses."*

* *"Team assignments are the first draft of the architecture. (See ​Conway’s Law​.) It’s a terrible irony that these very early decisions are also the least informed."*

* "*Denying the inevitability of failures robs you of your power to control and contain them."*

**Continuous Delivery: Reliable Software Releases Through Build, Test, and Deployment Automation** (*Jez Humble, David Farley*): Todas as funcionalidades foram implementadas, mas ainda serão necessárias semanas ou meses para seu software ser entregue. Como manter meu software sempre pronto para produção? Quais práticas utilizar? Quais não utilizar? Quais os benefícios? Embutir qualidade no processo de desenvolvimento e antecipar riscos é potencialmente o melhor investimento a ser feito no seu software!

> **Citações**:

* *"A working software application can be usefully decomposed into four components: executable code, configuration, host environment, and data."*

* *"Configuration management refers to the process by which all artifacts relevant to your project, and the relationships between them, are stored, retrieved, uniquely identified, and modified."*

* *"In software, when something is painful, the way to reduce the pain is to do it more frequently, not less."*

* *"It should always be cheaper to create a new environment than to repair an old one"*

* *"The repeatability and reliability derive from two principles: automate almost everything, and keep everything you need to build, deploy, test, and release your application in version control."*

**Site Reliability Engineering: How Google Runs Production Systems** (*Betsy Beyer, Chris Jones, Jennifer Petoff, Niall Richard Murphy*): Coletanêa de artigos do time de SRE do Google, ilustrando a origem do termo, cultura, princípios e práticas internas, da formação de time até valiosas lições de como potencializar o feedback de sistemas em produção para o desenvolvimento - e sem deixar de lado conceitos como gerenciamento de mudança, monitoramento, planejamento de capacidade e resposta a incidentes.

> **Citações**:

* *"Software engineering has this in common with having children: the labor before the birth is painful and difficult, but the labor after the birth is where you actually spend most of your effort."*

* *"SRE is what happens when you ask a software engineer to design an operations team."*

* *"One could equivalently view SRE as a specific implementation of DevOps with some idiosyncratic extensions."*

* *"The most relevant metric in evaluating the effectiveness of emergency response is how quickly the response team can bring the system back to health — that is, the MTTR."* 

> **Notas**:

- Disponível gratuitamente [online](https://landing.google.com/sre/book/index.html)

- [Review completo por Fernando Ike](https://medium.com/@fernandoike/site-reliability-engineer-sre-b9440f02ca26)


## Q&A

## Bookmarks

- [continuous-integration](http://www.martinfowler.com/articles/continuousIntegration.html) - Artigo Martin Fowler integração contínua
- [continuous-delivery](http://martinfowler.com/bliki/ContinuousDelivery.html) - Artigo Martin Fowler "continuous delivery"
- [deployment-pipeline](http://martinfowler.com/bliki/DeploymentPipeline.html) - Artigo Martin Fowler sobre deployment pipeline
- [git-branching](http://pcottle.github.io/learnGitBranching/) - A interactive Git visualization tool to educate and challenge!
- [git-branching-successful](http://nvie.com/posts/a-successful-git-branching-model/) - Como trabalhar com branches
- [git-branching-merging](https://www.simple-talk.com/opinion/opinion-pieces/branching-and-merging-ten-pretty-good-practices/) - Branching and Merging: Ten Pretty-Good Practices
- [git-guide](http://rogerdudler.github.io/git-guide/) - Simple Git guide
- [serverless](http://zanon-io.github.io/serverless-presentation/slides/index.html#1) - Serverless presentation
- [puppet x ansible](http://gutocarvalho.net/blog/2016/06/02/puppet-vs-ansible/) - Comparativo Puppet x Ansible
- [highscalability](http://highscalability.com/) - Excelente site para referência em arquiteturas reais
- [scaling-nagios](http://www.slideshare.net/lozzd/leveling-up-monitoring-a-decade-of-automating-and-scaling-nagios)
- [devops-antipatterns](http://www.slideshare.net/fernandoike/dev-ops-anti-patterns) - Apresentação Fernando Ike
- [serverless-concepts](http://martinfowler.com/articles/serverless.html) - Artigo Martin Fowler
- [uber-postgresql-mysql](http://rhaas.blogspot.com.br/2016/08/ubers-move-away-from-postgresql.html) - Artigo sobre a mudança de SGDB do Uber
- [devops-enterprise](http://www.slideshare.net/marceloancelmo/devops-enterprise-devops-meetup-zurich) - Apresentação sobre a adoção de Devops em grandes corporações
- [spotify-scaling](http://www.slideshare.net/davidpoblador/scaling-operations-at-spotify) - Scaling operations at Spotify
- [remote-jobs-brazil](https://github.com/lerrua/remote-jobs-brazil) - Uma listagem de algumas empresas que aceitam trabalho remoto no Brasil
- [remote-jobs](https://github.com/lukasz-madon/awesome-remote-job) - Awesome remote jobs
- [htop-distilled](https://peteris.rocks/blog/htop/#memory-usage-virt-res-shr-mem) - Excelente explicação sobre as informações do utilitário htop
- [devops-periodic-table](https://xebialabs.com/periodic-table-of-devops-tools/) - "Tabela periódica" de ferramentas Devops
- [circuit-breaker](https://martinfowler.com/bliki/CircuitBreaker.html) - Artigo Martin Fowler sobre o mecanismo "circuit-break"
- [software-devlopers-readlist](https://stevewedig.com/2014/02/03/software-developers-reading-list/) - Lista com boas referências para leitura
- [10-monitoring-talks](https://techbeacon.com/10-monitoring-talks-every-developer-should-watch) - Lista de 10 apresentações sobre monitoramento que todo desenvolvedor deve assistir
- [12-factor](https://12factor.net/) - Metodologia para desenvolver aplicações modernas e escaláveis
- [ansible-windows](http://some.ops4devs.info/) - Artigo de automação com ansible no windows
- [terraform x cloudformation](https://www.terraform.io/intro/vs/cloudformation.html) - Comparação do Terraform com Cloudformation e outras ferramentas de nuvem
- [8practices-containers-apps](https://opensource.com/life/16/9/8-best-practices-building-containerized-applications) - Melhores práticas para construção de aplicações baseadas em containeres
- [learncodethehardway](https://learncodethehardway.org/) - Site para aprender a programar
- [12-licoes-performance-tests](http://www.bugbang.com.br/12-licoes-aprendidas-em-testes-de-performance-server-side/) - Lições aprendidas em testes de performance
- [destilando-jmeter](http://www.bugbang.com.br/destilando-jmeter-i-introducao-e-conceitos/) - Destilando Jmeter (ferramenta de teste de performance)
- [why-google-uses-single-repository](https://cacm.acm.org/magazines/2016/7/204032-why-google-stores-billions-of-lines-of-code-in-a-single-repository/fulltext) - Why Google Stores Billions of Lines of Code in a Single Repository
- [evolution-of-container-usage-netflix](http://techblog.netflix.com/2017/04/the-evolution-of-container-usage-at.html) - The Evolution of Container Usage at Netflix
- [play-with-docker](http://training.play-with-docker.com/) - Excelentes labs para estudar docker
- [not-run-database-inside-container](http://patrobinson.github.io/2016/11/07/thou-shalt-not-run-a-database-inside-a-container/) - Artigo com considerações sobre porque não rodar databases em containers
- [3-Git-Commands-i-use-every-day](https://dev.to/gonedark/3-git-commands-i-use-every-day) - Artigo com 3 comandos git que o autor usa todo dia
- [when-to-make-git-commit](https://jason.pureconcepts.net/2017/01/when-to-make-git-commit/) - Artigo com 2 regras que o autor usa para saber quando fazer um commit
- [how-to-write-a-git-commit-message](https://chris.beams.io/posts/git-commit/) - Dicas de como fazer uma boa mensagem de commit
- [the-guilt-of-not-testing-everything](https://dev.to/ozymandias547/the-guilt-of-not-testing-everything) - Artigo sobre a sensação de culpa quando se acredita que o teste criado não cobre todas as possibilidades
- [productivity-secrets](https://dev.to/codeforcashbook/productivity-secrets-for-success-as-a-freelance-consultant) - Artigo com dicas para aumento de produtividade
- [performance-testing](https://dzone.com/articles/a-complete-guide-to-performance-testing-types-test) - Guia sobre teste de performance
- [secret-management](https://medium.com/on-docker/secrets-and-lie-abilities-the-state-of-modern-secret-management-2017-c82ec9136a3d) - Review de sistemas de gerenciamento de secrets
- [testando-sua-infraestrutura](https://medium.com/desenvolvimento-%C3%A1gil/testando-sua-infraestrutura-de-forma-rapida-e-facil-f11fb2f4be89) - Testando sua infraestrutura de forma rápida e fácil
- [precisamos-falar-sobre-teste-de-infra](http://techfree.com.br/2017/01/precisamos-falar-sobre-teste-automatizado-de-infraestrutura/) - Precisamos falar sobre teste automatizado de infraestrutura
- [nova-metodologia](https://medium.com/desenvolvimento-%C3%A1gil/a-nova-metodologia-69b8f8a379c7) - A Nova Metodologia (tradução do texto "[The New Methodology](https://www.martinfowler.com/articles/newMethodology.html)" de Martin Fowler)
- [padroes-a-evitar](https://medium.com/@thoughtworksbr/5-padroes-para-evitar-em-seu-projeto-de-desenvolvimento-de-software-481b5bcfdf78) - 5 padrões para evitar em seu projeto de Desenvolvimento de Software
- [maneiras-de-atuar-positivamente](https://medium.com/dos-margaritas/5-maneiras-de-atuar-positivamente-em-projetos-de-desenvolvimento-de-software-e9b2d4103ac5) - 5 maneiras de atuar positivamente em projetos de Desenvolvimento de Software
- [how-i-went-from-zero-to-sanfrancisco-sw-engineer-in-12-months](https://medium.freecodecamp.com/how-i-learned-to-code-and-earned-a-job-in-silicon-valley-changing-my-life-along-the-way-a3af854855fa) - Como se tornar um desenvolvedor no Freecodecamp
- [linuxkit](https://infoslack.com/devops/linuxkit) - Artigo introdutório sobre o LinuxKit
- [5-best-practices-for-containers-in-production](https://techbeacon.com/5-best-practices-container-orchestration-it-production) - Five best practices for containers in production
- [devops-conferences](http://devopsconferences.org/) - Lista de eventos Devops pelo mundo
- [julia-evans](http://jvns.ca/) - Blog técnico com a sysadmin Julia Evans
- [charity-majors](http://charity.wtf/) - Blog de uma Production Engineering Manager do Facebook
- [rachel-by-the-bay](http://rachelbythebay.com/w/) - Software, technology, sysadmin war stories, and more
- [the-technical-blog-of-james](https://ttboj.wordpress.com/) - Technical articles, writeups and discussion!
- [is-serverless-the-new-visual-basic](http://highscalability.com/blog/2017/5/15/is-serverless-the-new-visual-basic.html) - Is Serverless the New Visual Basic?
- [-o-que-eu-preciso-saber-para-subir-um-cluster-swarm](http://techfree.com.br/2017/05/o-que-eu-preciso-saber-para-subir-um-cluster-docker-swarm/) - O QUE EU PRECISO SABER PARA SUBIR UM CLUSTER DOCKER SWARM
- [15-things-you-shoud-know-about-ansible](http://codeheaven.io/15-things-you-should-know-about-ansible/) - 15 Things You Should Know About Ansible
- [devops-conferences](http://devopsconferences.org/) - Devops Conferences
- [access-and-secret-management-in-cloud-services](https://www.infoq.com/presentations/lyft-security-cloud) - Access and Secret Management in Cloud Services
- [the-state-of-modern-secret-management](https://medium.com/on-docker/secrets-and-lie-abilities-the-state-of-modern-secret-management-2017-c82ec9136a3d) - Secrets and LIE-abilities: The State of Modern Secret Management (2017)
- [sw-management-with-powershell-chocolatey](https://www.slideshare.net/ferventcoder/software-management-with-powershell-dsc-and-chocolatey-powershell-summit-2017) - Software Management with PowerShell DSC and Chocolatey
- [container-performance-analysis](https://www.slideshare.net/brendangregg/container-performance-analysis) - Container Performance Analysis
- [run-stuff-deploy-stuff](https://www.slideshare.net/KrisBuytaert/run-stuff-deploy-stuff-jax-london-2017-edition) - Run stuff, Deploy Stuff, Jax London 2017 Edition
- [why-you-shouldnt-use-env-variables-for-secret-data](https://diogomonica.com/2017/03/27/why-you-shouldnt-use-env-variables-for-secret-data/) - Why you shouldn't use ENV variables for secret data
- [unikernels-docker-e-o-futuro-da-infraestrutura-imutavel](https://infoslack.com/devops/unikernels-docker-e-o-futuro-da-infraestrutura-imutavel) - Unikernels, Docker e o futuro da infraestrutura imutável
- [ops-and-operability](https://vimeo.com/205526857) - Ops and operability
- [logs-and-metrics](https://medium.com/@cindysridharan/logs-and-metrics-6d34d3026e38) - Logs and Metrics
- [working-at-netflix-2017](http://www.brendangregg.com/blog/2017-05-16/working-at-netflix-2017.html) - Working at Netflix 2017
- [s3-vs-glacier-a-simple-backup-strategy-in-the-cloud](http://cloudacademy.com/blog/amazon-s3-vs-amazon-glacier-a-simple-backup-strategy-in-the-cloud/) - Amazon S3 vs Amazon Glacier: a simple backup strategy in the cloud
- [expondo-a-porta-de-um-servico-no-swarm](http://techfree.com.br/2017/05/expondo-a-porta-de-um-servico-no-swarm/) - Expondo a porta de um serviço no Swarm
- [kubernetes-vs-mesos-vs-swarm](http://blog.outlyer.com/kubernetes-vs.-mesos-vs.-swarm) - Kubernetes vs. Mesos vs. Swarm — An Opinionated Discussion
- [persistindo-dados-glusterfs](http://www.mundodocker.com.br/persistindo-dados-glusterfs/) - Persistindo dados - GlusterFS
- [post-mortems](https://github.com/danluu/post-mortems) - Lista de post mortems
- [awesome-sre](https://github.com/dastergon/awesome-sre) - A curated list of awesome Site Reliability and Production Engineering resources
- [enough-with-the-microservices](https://aadrake.com/posts/2017-05-20-enough-with-the-microservices.html) - Enough with the microservices
- [threads-em-python-e-claro](http://www.diego-garcia.info/2016/02/18/threads-em-python-e-claro) - Artigo sobre a utilização de threads em Python
- [do080-deploying-containerized-applications](https://www.redhat.com/en/services/training/do080-deploying-containerized-applications-technical-overview) - Deploying Containerized Applications Tech Overview (DO080)
- [do007-ansible-essentials](https://www.redhat.com/en/services/training/do007-ansible-essentials-simplicity-automation-technical-overview) - Ansible Essentials Technical Overview video series course
- [you-are-not-google](https://blog.bradfieldcs.com/you-are-not-google-84912cf44afb) - you are not google
- [apache-vs-nginx-practical-considerations](https://www.digitalocean.com/community/tutorials/apache-vs-nginx-practical-considerations) - Apache vs Nginx: Practical Considerations
- [globo-com-delivers-live-video-streaming-to-500000-viewers-with-nginx](https://www.nginx.com/blog/globo-com-delivers-live-video-streaming-to-500000-viewers-with-nginx/) - Globo.com Uses NGINX to Stream Media to 500,000+ Viewers
- [why-netflix-chose-nginx-as-the-heart-of-its-cdn](https://www.nginx.com/blog/why-netflix-chose-nginx-as-the-heart-of-its-cdn/) - Why Netflix Chose NGINX as the Heart of Its CDN - NGINX
- [books-for-sre](https://gist.github.com/infoslack/0a87dac10636553ae4f3d22e7a8ebfa7) - Books for SRE/System Engineer
- [firing-people](https://zachholman.com/talk/firing-people) - Firing People
- [introducing-aardvark-and-repokid](https://medium.com/netflix-techblog/introducing-aardvark-and-repokid-53b081bf3a7e) - Introducing Aardvark and Repokid
- [command-line-tools-can-be-235x-faster-than-your-hadoop-cluster](https://aadrake.com/command-line-tools-can-be-235x-faster-than-your-hadoop-cluster.html) - Command-line Tools can be 235x Faster than your Hadoop Cluster
- [qual-futuro-dos-sysadmins](http://techfree.com.br/2017/06/qual-futuro-dos-sysadmins/) - Qual o futuro dos Sysadmins (Gomex)
- [microservices-prerequisites](http://philcalcado.com/2017/06/11/calcados_microservices_prerequisites.html) - Microservices Prerequisites
- [devops-bootcamp](http://devopsbootcamp.osuosl.org/index.html) - Devops Bootcamp
- [infraestrutura-agil-tem-que-morrer](https://www.fernandoike.com/2017/06/17/infraestrutura-%C3%A1gil-tem-que-morrer) - Infraestrutura ágil tem que morrer
- [devops-or-goodops](https://product.voxmedia.com/2012/5/4/5426766/devops-or-goodops) - Devops or Goodops?
- [for-inclusive-culture-maybe-less-is-more](https://hackernoon.com/for-inclusive-culture-maybe-less-is-more-87b663662cea) - For an Inclusive Culture, Try Working Less
- [whats-a-service-mesh-and-why-do-i-need-one](https://blog.buoyant.io/2017/04/25/whats-a-service-mesh-and-why-do-i-need-one/) - What's a service mesh? And why do I need one?

## Segurança

- [dev-sec.io](http://http://dev-sec.io/) - Hardening Framework
- [devopssec](https://www.oreilly.com/learning/devopssec-securing-software-through-continuous-delivery) - Livro sobre segurança de sw com CD
- [awesome-devsecops](https://github.com/devsecops/awesome-devsecops) - Awesome list devopssec
- [selinux-seccomp](http://some.ops4devs.info/) - Análise de algumas ferramentas  de auditoria e segurança

## Blogs técnicos de grandes empresas

* [Airbnb Engineering](http://nerds.airbnb.com/)
* [Atlassian Developers](https://developer.atlassian.com/blog/)
* [Autodesk Engineering](http://cloudengineering.autodesk.com/blog/)
* [AWS Blog](https://aws.amazon.com/blogs/aws/)
* [Bitly Engineering Blog](http://word.bitly.com/)
* [Box Blogs](https://www.box.com/blog/engineering/)
* [Cloudera Developer Blog](http://blog.cloudera.com/blog/)
* [Dropbox Tech Blog](https://tech.dropbox.com/)
* [Engineering at Quora](http://engineering.quora.com/)
* [Ebay Tech Blog](http://www.ebaytechblog.com/)
* [Evernote Tech Blog](https://blog.evernote.com/tech/)
* [Etsy Code as Craft](http://codeascraft.com/)
* [Facebook Engineering](https://www.facebook.com/Engineering)
* [Flickr Code](http://code.flickr.net/)
* [Foursquare Engineering Blog](http://engineering.foursquare.com/)
* [GitHub Engineering Blog](http://githubengineering.com/)
* [Google Research Blog](http://googleresearch.blogspot.com/)
* [Groupon Engineering Blog](https://engineering.groupon.com/)
* [Heroku Engineering Blog](https://engineering.heroku.com/)
* [Hubspot Engineering Blog](http://product.hubspot.com/blog/topic/engineering)
* [High Scalability](http://highscalability.com/)
* [Instagram Engineering](http://instagram-engineering.tumblr.com/)
* [Intel Software Blog](https://software.intel.com/en-us/blogs/)
* [Jane Street Tech Blog](https://blogs.janestreet.com/category/ocaml/)
* [LinkedIn Engineering](http://engineering.linkedin.com/blog)
* [Microsoft Engineering](https://engineering.microsoft.com/)
* [Microsoft Python Engineering](https://blogs.msdn.microsoft.com/pythonengineering/)
* [Netflix Tech Blog](http://techblog.netflix.com/)
* [Paypal Developer Blog](https://devblog.paypal.com/category/engineering/)
* [Pinterest Engineering Blog](http://engineering.pinterest.com/)
* [Quora Engineering](https://engineering.quora.com/)
* [Reddit Blog](http://www.redditblog.com/)
* [Salesforce Engineering Blog](https://developer.salesforce.com/blogs/engineering/)
* [Slack Engineering Blog](https://slack.engineering/)
* [Spotify Labs](https://labs.spotify.com/)
* [Twilio Engineering Blog](http://www.twilio.com/engineering)
* [Twitter Engineering](https://engineering.twitter.com/)
* [Uber Engineering Blog](http://eng.uber.com/)
* [Yahoo Engineering Blog](http://yahooeng.tumblr.com/)
* [Yelp Engineering Blog](http://engineeringblog.yelp.com/)
* [Zynga Engineering Blog](https://www.zynga.com/blogs/engineering)
