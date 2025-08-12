## Desplegament d'aplicacions web (BOE)
## TEMA 1 – Implantació d’arquitectures web
- **Arquitectures web** → Monolítica, tres capes, microserveis, distribució client-servidor-base de dades.
- **Servidors web i d’aplicacions** → Diferències, instal·lació i configuració bàsica.
- **Virtualització i contenidors** → VMware, VirtualBox, AWS, Docker, Kubernetes.
- **Estructura d’una app web** → HTML, CSS, JS, backend, APIs, base de dades.
- **Documentació** → Registre i guies dels processos realitzats.

🎯 **Objectiu final**: saber desplegar una arquitectura web bàsica en entorns físics, virtuals o contenidors, i documentar-la.

## TEMA 2 – Administració de servidors web
- **Configuració avançada** → Rendiment, seguretat, càrregues altes.
- **Mòduls** → Instal·lació i ús (mod\_ssl, mod\_rewrite...).
- **Hosts virtuals** → Diversos dominis en un sol servidor.
- **Autenticació i control d’accés**.
- **HTTPS i certificats** → Let’s Encrypt, SSL/TLS.
- **Desplegament d’apps** → WordPress, Node.js, etc.
- **Logs** → Eines com Elasticsearch, Kibana.

🎯 **Objectiu final**: passar de muntar un servidor web bàsic a administrar-lo de forma segura i eficient.

## TEMA 3 – Administració de servidors d’aplicacions
- **Arquitectura i configuració bàsica** → Tomcat, WildFly, GlassFish...
- **Gestió d’aplicacions** → Desplegar, actualitzar, monitoritzar.
- **Autenticació d’usuaris** → LDAP, rols, realms.
- **Sessions** → Temps, emmagatzematge i seguretat.
- **Integració amb servidors web** → Reverse proxy, load balancing.
- **Desplegament automatitzat** → CI/CD, estratègies blue/green.
- **Seguretat i documentació**.

🎯 **Objectiu final**: saber desplegar i administrar aplicacions web sobre servidors d’aplicacions, integrats amb webservers.

## TEMA 4 – Servidors de transferència de fitxers
- **Configuració** → FTP, SFTP, FTPS.
- **Usuaris i permisos** → Locals, virtuals, LDAP.
- **Modes de connexió** → Actiu/passiu.
- **Protocols segurs** → SFTP, FTPS, claus i certificats.
- **Ús d’eines CLI i GUI** → FileZilla, WinSCP.
- **Integració amb desplegaments web**.
- **Virtualització i contenidors** per FTP.

🎯 **Objectiu final**: saber muntar i administrar serveis segurs de transferència de fitxers per suportar aplicacions web.

## TEMA 5 – Serveis de xarxa en el desplegament web
- **DNS** → Resolució de noms, registres, configuració.
- **Servei de directoris** → LDAP, autenticació centralitzada.
- **Arxius de configuració** → named.conf, slapd.conf.
- **Autenticació i integració amb aplicacions**.
- **Virtualització i contenidors** per DNS/LDAP.

🎯 **Objectiu final**: administrar serveis de xarxa clau per a la resolució de noms i la gestió d’identitats en aplicacions web.

## TEMA 6 – Documentació, control de versions i CI/CD
- **Eines col·laboratives** → Confluence, Google Docs, Notion.
- **Plantilles i estàndards**.
- **Control de versions** → Git, estratègies avançades.
- **Seguretat en VCS** → Claus SSH, permisos.
- **Integració contínua** → Jenkins, GitLab CI, pipelines.
- **Monitorització de qualitat** → SonarQube, CodeClimate.

🎯 **Objectiu final**: treballar de forma col·laborativa, segura i automatitzada, garantint qualitat i traçabilitat.

Pel que veig, el temari és força complet i cobreix molts conceptes bàsics i intermedis, però sí que té un cert aire **"tradicional"** i pot quedar una mica curt davant dels reptes i tecnologies més actuals en desplegament i administració d’aplicacions web.
Et faig una crítica constructiva, punt per punt, amb propostes de millora.

## Punts positius
- **Cobertura àmplia**: Inclou webservers, app servers, DNS, FTP, control de versions, CI/CD, etc.
- **Enfocament progressiu**: Passa de muntar un entorn bàsic a administrar-lo de manera professional.
- **Importància de la documentació**: Ho destaca en tots els temes, cosa que molts cursos obvien.
- **Introducció a virtualització i contenidors**: Encara que bàsica, ja obre la porta a Docker/Kubernetes.

## Limitacions i aspectes a millorar
1. **Tecnologies antigues o minoritàries al món actual**
   1. FTP pur (no segur) i servidors d’aplicacions Java monolítics (WildFly, GlassFish) són cada cop menys comuns en nous projectes.
   1. El món real està més centrat en **APIs, serveis serverless, PaaS, i desplegaments amb GitOps**.
   1. DNS i LDAP són útils, però avui dia moltes empreses ja usen serveis gestionats al núvol en lloc de muntar-los manualment.
1. **Poca presència de DevOps i pràctiques modernes**
   1. Es parla de CI/CD però no gaire d’**Infrastructure as Code** (Terraform, Ansible).
   1. Falta més **observabilitat moderna** (Prometheus, Grafana) a més de l’anàlisi de logs.
1. **Enfocament poc cloud-native**
   1. Es toca AWS/Azure/GCP però de forma molt introductòria.
   1. No s’aprofundeix en **contenidors orquestrats** (Kubernetes, Helm) ni en desplegaments híbrids.
1. **Seguretat tractada de manera bàsica**
   1. HTTPS i autenticació es veuen, però manca **DevSecOps**, escaneig de vulnerabilitats, i bones pràctiques d’enduriment de sistemes (hardening).
1. **Poca orientació a escalar i mantenir sistemes grans**
   1. Es parla d’escalar en contenidors, però no d’**autoescalat, balancejadors gestionats, o gestió multiclúster**.
   1. No s’inclou **automatització de backups, DRP (Disaster Recovery Plans)**.

## Proposta de millora
Si volem portar aquest temari a un nivell més actual, hi afegiria:
### **🔹 Afegir temes nous**
- **Infrastructure as Code (IaC)**: Terraform, Ansible, CloudFormation.
- **Orquestració avançada de contenidors**: Kubernetes, Helm, ingress controllers, secrets management.
- **Monitorització i alertes modernes**: Prometheus, Grafana, Alertmanager.
- **Serverless & Edge Computing**: Lambda, Cloudflare Workers.
- **Ciberseguretat aplicada a DevOps**: Escaneig de vulnerabilitats, secrets scanning, pentesting bàsic.
- **Automatització de desplegaments amb GitOps**: ArgoCD, FluxCD.
- **Gestió de serveis gestionats al núvol** (RDS, Cloud DNS, Identity services).
### **🔹 Actualitzar tecnologies**
- Substituir **FTP** per **SFTP/rsync/transferències segures via pipelines**.
- Menys pes en **servidors d’aplicacions Java clàssics**, més en entorns **API-first** i microserveis.
- Incloure **frameworks i entorns moderns**: Node.js, Spring Boot, .NET Core.
### **🔹 Orientar a casos reals**
- Exercicis basats en **escenaris empresarials reals**: desplegar una app web amb backend, base de dades i frontend separat, amb CI/CD i monitorització.
- Integració amb **repositoris privats** i desplegament a entorns **pre-producció i producció**.


## Desplegament d'aplicacions web (moderna)


## TEMA 1 – Arquitectures i desplegament bàsic d’aplicacions web
- **Arquitectures modernes**
  - Monolític, 3 capes, microserveis, serverless i edge computing.
  - Patrons API-first i orientats a esdeveniments.
- **Servidors web** (Apache, Nginx, Caddy) i **reverse proxies**.
- **Plataformes d’execució**: Node.js, .NET Core, Spring Boot.
- **Virtualització i contenidors**
  - Docker: creació d’imatges, gestió de volums i xarxes.
  - Kubernetes bàsic: pods, deployments, ingress, secrets.
- **Entorns al núvol**
  - AWS, Azure, GCP: creació d’instàncies, balancejadors i DNS.
- **Estructura d’un projecte web modern**
  - Frontend SPA, backend API, base de dades, fitxers estàtics, pipelines.
- **Documentació** amb eines col·laboratives (Notion, Confluence).

## TEMA 2 – Administració avançada de servidors web
- **Configuració per alt rendiment**: cache, compresió, CDN, HTTP/3.
- **Seguretat**: headers segurs, protecció contra DoS, WAF bàsic.
- **Virtual hosts / ingress**: múltiples dominis amb SSL.
- **HTTPS amb Let’s Encrypt i cert-manager en Kubernetes**.
- **Desplegament d’aplicacions**
  - Contingut estàtic vs dinàmic.
  - Blue/green i rolling deployments.
- **Logs i monitorització web**: ELK stack, Loki, Grafana.

## TEMA 3 – Plataformes d’aplicacions i integració amb webservers
- **Servidors d’aplicacions moderns**
  - Tomcat, Spring Boot standalone, .NET Core Kestrel.
- **Desplegament i gestió d’apps**
  - Docker, Helm Charts, secrets management.
- **Autenticació i autorització**
  - OAuth2, OpenID Connect, Keycloak, integració amb SSO.
- **Administració de sessions i persistència distribuïda**.
- **Integració amb Nginx/Traefik com a reverse proxy**.
- **Observabilitat**: mètriques Prometheus, traces amb OpenTelemetry.

## TEMA 4 – Transferència i sincronització de fitxers
- **Protocols segurs**: SFTP, rsync sobre SSH, MinIO per object storage.
- **Gestió d’usuaris i permisos**: locals, LDAP, IAM del núvol.
- **Automatització de transferències** amb scripts i pipelines CI/CD.
- **Bones pràctiques en desplegaments zero-downtime**.
- **Ús de serveis gestionats** (AWS S3, Azure Blob Storage) en lloc de FTP tradicional.

## TEMA 5 – Serveis de xarxa per aplicacions web
- **DNS modern**
  - Configuració de zones, TTL, registres bàsics i avançats.
  - DNS gestionat (Route53, Cloud DNS).
- **Serveis d’identitat**
  - LDAP, Keycloak, Azure AD, AWS Cognito.
- **Configuració i integració amb apps**: autenticació centralitzada, RBAC.
- **Infraestructura com a codi per xarxa**: Terraform per DNS i identitat.

## TEMA 6 – Documentació, control de versions i DevOps
- **Documentació col·laborativa**: plantilles, estàndards, versions.
- **Control de versions amb Git**
  - Flux GitFlow i trunk-based development.
  - Gestió de secrets en repositoris (Vault, SOPS).
- **CI/CD modern**
  - GitLab CI, GitHub Actions, ArgoCD (GitOps).
  - Integració amb Kubernetes i entorns multi-stage.
- **Seguretat en DevOps**
  - Escaneig de vulnerabilitats (Trivy, Snyk).
  - Secrets scanning i compliance.
- **Monitorització de qualitat**: SonarQube, CodeClimate.

## Principals millores respecte al temari original
- Menys enfocament en tecnologies obsoletes (FTP pur, servidors Java grans com GlassFish).
- Més èmfasi en **contenidors, Kubernetes i GitOps**.
- Seguretat integrada a totes les fases (**DevSecOps**).
- Orientació clara al **núvol i serveis gestionats**.
- Afegit **observabilitat moderna** (mètriques, logs, traces).
- Incorporació de **Infrastructure as Code**.

