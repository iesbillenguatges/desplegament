# El mòdul profesional 0614. Desplegament d'aplicaciones web queda redactat:

### Durada: 50 horas. Continguts bàsics =>

### TEMA 1- Implantació d'arquitecturs web
1. Arquitectures web. Models.
- De què et parlaran: Tipus d’arquitectures web que existeixen (monolítica, de tres capes, microserveis, etc.) i com s’organitzen les aplicacions web.
- Què aprendràs: Entendre com es reparteix el treball entre client, servidor i base de dades, i quin model és més adequat per a cada cas.

2. Servidors web i d'aplicacions. Instal·lació i configuració bàsica.
- De què et parlaran: Diferències entre un servidor web (com Apache, Nginx) i un servidor d’aplicacions (com Tomcat, WildFly).
- Què aprendràs:
    * Instal·lar un servidor web en un entorn local o remot.
    * Configurar-lo per servir pàgines web i aplicacions.
    * Ajustos bàsics de seguretat i rendiment.

3. Tecnologies de virtualització de servidors en la núvol i en contenidors. Instal·lació i configuració bàsica.
- De què et parlaran:
    * Virtualització tradicional (VMware, VirtualBox).
    * Virtualització en el núvol (AWS, Azure, Google Cloud).
    * Contenidors (Docker, Kubernetes).

- Què aprendràs:
    * Crear i gestionar màquines virtuals.
    * Executar aplicacions en contenidors.
    * Entendre com es despleguen serveis web en entorns escalables.

4. Estructura i recursos que formen part d'una aplicació web.
- De què et parlaran: Les parts bàsiques d’una aplicació web: fitxers HTML/CSS/JS, imatges, backend, base de dades, APIs, etc.

- Què aprendràs:
        * Reconèixer l’estructura d’un projecte web.
        * Saber on es guarden i com s’organitzen els recursos.
        * Com es comuniquen el frontend i el backend.

5. Documentació dels processos realitzats.
- De què et parlaran: Bones pràctiques per documentar el que has fet, per a que qualsevol altre pugui repetir el procés.
- Què aprendràs:
    * Escriure documentació tècnica clara.
    * Fer captures de pantalla, passos detallats i notes.
    * Mantenir registres de configuració i instal·lació.

En resum: Al final del tema, hauràs après a muntar des de zero una arquitectura web bàsica, tant en un servidor físic o virtual com en contenidors, entendre com es despleguen aplicacions, i deixar-ho tot documentat perquè siga replicable.

### TEMA 2- Administració de servidors web
1. Configuració avanzada del servidor web
- De què et parlaran: Ajustos més detallats d’un servidor com Apache o Nginx (optimització, seguretat, rendiment).
- Què aprendràs:
        * Canviar configuracions per millorar velocitat.
        * Gestionar càrregues altes de trànsit.
        * Ajustar paràmetres de seguretat i compatibilitat.

2. Môduls: instalació, configuració i ús
- De què et parlaran: Extensions o plugins del servidor web que afegeixen funcionalitats (per exemple, mod_rewrite, mod_ssl).
- Què aprendràs:
        * Instal·lar mòduls addicionals.
        * Configurar-los per fer tasques concretes (redireccions, compressió, seguretat).
        * Saber quins mòduls utilitzar segons la necessitat.

3. Hosts virtuals. Creació, configuració i utilizació
- De què et parlaran: Com fer que un mateix servidor atenga diferents webs amb diferents dominis.
- Què aprendràs:
        * Crear i configurar “virtual hosts” per tenir diverses pàgines al mateix servidor.
        * Gestionar dominis i subdominis.

4. Autenticació i control d'accés
- De què et parlaran: Com protegir zones d’una web o tot el lloc amb usuaris i contrasenyes.
- Què aprendràs:
        * Crear sistemes d’autenticació bàsica.
        * Configurar permisos i restriccions segons IP o rol.

5. El protocolo HTTPS
- De què et parlaran: Què és HTTPS, per què és més segur que HTTP i com funciona el xifrat.
- Què aprendràs:
        * Configurar un servidor perquè treballe amb HTTPS.
        * Entendre la negociació SSL/TLS.

6. Certificats. Servidors de certificats
- De què et parlaran: Tipus de certificats (autofirmats, d’autoritats reconegudes) i com obtenir-los.
- Què aprendràs:
        * Instal·lar certificats SSL.
        * Configurar renovació automàtica amb eines com Let’s Encrypt.
        * Muntar un servidor de certificats propi.

7. Documentació
- De què et parlaran: Com deixar constància clara dels canvis i configuracions.
- Què aprendràs:
        * Escriure manuals de manteniment i procediments.
        * Crear guies de resolució de problemes.

8. Desplegament d'aplicacions sobre servidors web
- De què et parlaran: Com pujar i configurar aplicacions (WordPress, aplicacions Node.js, etc.) perquè funcionin al servidor.
- Què aprendràs:
        * Fer desplegaments segurs i repetibles.
        * Configurar entorns de producció.

9. Despliegament de servidors web mitjançant virtualizació en el núvol i contenidors
- De què et parlaran: Maneres de muntar servidors web ràpidament en entorns virtualitzats o contenidors.
- Què aprendràs:
        * Crear servidors al núvol (AWS, Azure, GCP).
        * Desplegar servidors web en Docker/Kubernetes.

10. Conjunt d'eines de gestió de logs
- De què et parlaran: Eines per a analitzar registres d’ús i d’errors (Elasticsearch, Kibana, Splunk).
- Què aprendràs:
        * Instal·lar i configurar sistemes de logs centralitzats.
        * Utilitzar dades per prendre decisions (optimització, seguretat).
        * Introducció a l’ús de Big Data per l’anàlisi de logs.

En resum: Aquest curs et portarà de saber “muntar” un servidor web a administrar-lo de manera professional: seguretat amb HTTPS, múltiples dominis, gestió d’usuaris, desplegament d’apps, virtualització avançada i ús de logs per millorar rendiment i detectar problemes.

### 3- Administración de servidores de aplicaciones:
1. Arquitectura i configuració bàsica del servidor d’aplicacions
- De què et parlaran: Com està organitzat un servidor d’aplicacions internament: mòduls, serveis, ports, fitxers de configuració.
- Què aprendràs:
        * Instal·lar un servidor d’aplicacions (per exemple, WildFly, GlassFish, Tomcat…).
        * Configurar paràmetres bàsics (puerto, memòria, logs).
        * Entendre la diferència entre servidor web i servidor d’aplicacions.

2. Administrar aplicacions web
- De què et parlaran: Com desplegar, actualitzar i eliminar aplicacions web al servidor.
- Què aprendràs:
        * Pujar arxius .war o .ear (Java) o equivalents en altres plataformes.
        * Gestionar versions i entorns (dev, test, producció).
        * Monitoritzar l’estat de les aplicacions.

3. Autenticació d’usuaris i dominis de seguretat
- De què et parlaran: Mecanismes perquè només usuaris autoritzats accedeixin a parts de l’aplicació.
- Què aprendràs:
        * Configurar usuaris i rols.
        * Integrar autenticació amb LDAP, bases de dades o Single Sign-On.
        * Entendre conceptes de realm, domain, role-based access control.

4. Administració de sessions
- De què et parlaran: Com el servidor gestiona la informació de la sessió d’un usuari.
- Què aprendràs:
        * Configurar temps de caducitat (timeout).
        * Guardar sessions en memòria, base de dades o distribuïdes entre diversos servidors.
        * Bones pràctiques per seguretat i rendiment.

5. Configurar el servidor d’aplicacions per cooperar amb servidors web
- De què et parlaran: Integració amb servidors web com Apache HTTP Server o Nginx.
- Què aprendràs:
        * Configurar reverse proxies.
        * Millorar rendiment amb load balancing.
        * Fer que el servidor web serveixi contingut estàtic i el d’aplicacions contingut dinàmic.

6. Desplegament d’aplicacions
- De què et parlaran: Diferents maneres de posar aplicacions en marxa al servidor.
- Què aprendràs:
        * Desplegament manual i automatitzat.
        * Ús d’eines com scripts, pipelines de CI/CD (Jenkins, GitLab CI…).
        * Estratègies blue/green deployment o rolling updates.

7. Seguretat en el servidor d’aplicacions
- De què et parlaran: Protegir el servidor contra atacs i vulnerabilitats.
- Què aprendràs:
        * Configurar HTTPS, certificats SSL/TLS.
        * Bloquejar ports innecessaris.
        * Aplicar security patches i actualitzacions.

8. Documentació
- De què et parlaran: Importància de registrar la configuració i processos.
- Què aprendràs:
        * Documentar instal·lacions i canvis.
        * Crear guies per a altres administradors.
        * Mantenir un històric d’incidències i configuracions.

9. Desplegament amb virtualització, núvol i contenidors
- De què et parlaran: Com posar en marxa servidors d’aplicacions en entorns moderns.
- Què aprendràs:
        * Crear màquines virtuals amb VMware, VirtualBox o Hyper-V.
        * Desplegar al núvol (AWS, Azure, GCP).
        * Utilitzar Docker i possiblement Kubernetes per contenidors.
        * Fer que el servidor sigui escalable i fàcil de replicar.

### 4- Instalación y administración de servidores de transferencia de archivos:
1. Configuració del servei de transferència de fitxers. Permisos i quotes
- De què et parlaran: Com instal·lar i configurar un servidor de transferència de fitxers (FTP, SFTP, FTPS…).
- Què aprendràs:
        * Instal·lar serveis com vsftpd, ProFTPD, FileZilla Server…
        * Crear i gestionar carpetes per a cada usuari o grup.
        * Assignar permisos de lectura/escriptura.
        * Configurar quotes d’espai per evitar que un usuari ocupi tot el disc.

2. Tipus d’usuaris i accessos al servei
- De què et parlaran: Diferents formes de gestió d’usuaris.
- Què aprendràs:
        * Usuaris locals del sistema, usuaris virtuals o autenticació contra una base de dades/LDAP.
        * Diferenciar accessos anònims, autenticats i amb rols.
        * Bones pràctiques per restringir l’accés només al necessari.

3. Modes de connexió del client
- De què et parlaran: Diferència entre mode actiu i mode passiu en FTP.
- Què aprendràs:
        * Quan utilitzar cada mode (important per temes de tallafocs i NAT).
        * Configurar el servidor i el client perquè la connexió sigui estable.
        * Com evitar problemes de connexió per ports bloquejats.

4. Protocol segur de transferència de fitxers
- De què et parlaran: Com xifrar les transferències per protegir dades.
- Què aprendràs:
        * Configurar SFTP (basat en SSH) i FTPS (basat en TLS/SSL).
        * Gestionar certificats i claus públiques/privades.
        * Diferències entre protocols segurs i insegurs.

5. Ús de comandes i eines gràfiques
- De què et parlaran: Com treballar amb FTP/SFTP tant per terminal com amb programes visuals.
- Què aprendràs:
        * Comandes bàsiques: ftp, sftp, put, get, ls, chmod, chown…
        * Eines gràfiques com FileZilla, WinSCP.
        * Automatitzar transferències amb scripts.

6. Ús del servei en el desplegament d’aplicacions web
- De què et parlaran: Com aprofitar FTP/SFTP per pujar aplicacions a un servidor web.
- Què aprendràs:
        * Integrar FTP en processos de deploy manual o automatitzat.
        * Bones pràctiques per no interrompre el servei durant la pujada.
        * Organitzar carpetes per entorns (dev/test/prod).

7. Documentació
- De què et parlaran: Com deixar constància de la configuració.
- Què aprendràs:
        * Documentar la configuració del servidor FTP/SFTP.
        * Redactar procediments de creació d’usuaris, permisos i seguretat.
        * Mantenir un registre d’incidències i canvis.

8. Desplegament amb virtualització, núvol i contenidors
- De què et parlaran: Posar en marxa servidors FTP en entorns moderns.
- Què aprendràs:
        * Crear màquines virtuals amb serveis de transferència de fitxers.
        * Desplegar en núvol (AWS, Azure, GCP).
        * Crear contenidors Docker amb serveis FTP/SFTP preconfigurats.
        * Escalar i replicar fàcilment el servei.

### 5- Servicios de red implicados en el despliegue de una aplicación web:

1. Resolutors de noms. Procés de resolució d’un nom de domini

    De què et parlaran:

        Com es converteix un nom amigable com www.example.com en una adreça IP.

        Funcionament de DNS (Domain Name System).

    Què aprendràs:

        Com funciona la jerarquia DNS (arrel, TLD, autoritatius).

        Tipus de consultes DNS: recursives i iteratives.

        Cacheig i propagació dels canvis DNS.

2. Paràmetres de configuració i registres del servidor de noms afectats en el desplegament

    De què et parlaran:

        Com configurar servidors DNS autoritatius o recursius.

        Tipus de registres DNS: A, AAAA, CNAME, MX, TXT, SRV, etc.

    Què aprendràs:

        Crear i modificar zones DNS.

        Gestionar registres per associar dominis a IPs i serveis.

        Paràmetres per optimitzar el rendiment i la seguretat del servidor DNS.

3. Servei de directoris: característiques i funcionalitat

    De què et parlaran:

        Què és un servei de directoris (com LDAP).

        Com s’utilitza per centralitzar la gestió d’usuaris, grups i recursos.

    Què aprendràs:

        Entendre l’estructura jeràrquica d’un directori.

        Aplicacions pràctiques com l’autenticació centralitzada.

4. Arxius bàsics de configuració

    De què et parlaran:

        On i com es configuren servidors DNS i serveis de directoris (fitxers com named.conf, slapd.conf).

    Què aprendràs:

        Editar i personalitzar aquests arxius per adaptar-los a les necessitats del desplegament.

        Recarregar configuracions sense parar el servei.

5. Autenticació d’usuaris en el servei de directoris

    De què et parlaran:

        Com els serveis de directoris gestionen l’autenticació i l’autorització.

        Protocols com LDAP i Kerberos.

    Què aprendràs:

        Configurar usuaris i grups en LDAP.

        Integrar el servei de directoris amb aplicacions per validar usuaris.

6. Adaptació de la configuració del servidor de directoris per al desplegament de l’aplicació

    De què et parlaran:

        Ajustar la configuració per a que l’aplicació web pugui utilitzar el servei de directoris per gestionar usuaris i permisos.

    Què aprendràs:

        Crear esquemes i rutes per a l’aplicació.

        Millorar la seguretat i el rendiment del servei.

7. Documentació

    De què et parlaran:

        Importància de mantenir un registre detallat de la configuració i canvis.

    Què aprendràs:

        Crear documentació clara i accessible per a futurs administradors.

        Documentar processos d’actualització i incidències.

8. Desplegament de servidors de directoris amb virtualització, núvol i contenidors

    De què et parlaran:

        Com posar en marxa serveis de directoris en entorns virtuals i en el núvol.

        Utilització de Docker, Kubernetes i màquines virtuals per desplegar i escalar aquests serveis.

    Què aprendràs:

        Crear imatges i contenidors amb serveis LDAP configurats.

        Desplegar a plataformes com AWS, Azure o Google Cloud.

        Automatitzar el desplegament i la gestió.

Resum

Aquest curs t’ensenyarà a configurar i administrar els serveis de xarxa essencials perquè una aplicació web funcioni: DNS per a la resolució de noms i serveis de directoris per gestionar identitats i permisos. També aprendràs a desplegar aquests serveis en entorns moderns de virtualització i contenidors.

6- Documentación, sistemas de control de versiones y de integración continua:

1. Eines col·laboratives per generar documentació. Instal·lació, configuració i ús

    De què et parlaran:

        Plataformes i programes per crear i mantenir documentació compartida (ex. Confluence, Google Docs, Notion).

        Com instal·lar i configurar aquestes eines.

    Què aprendràs:

        Col·laborar en temps real.

        Controlar versions dels documents.

        Organitzar la documentació de forma clara i accessible.

2. Creació i utilització de plantilles

    De què et parlaran:

        Com crear plantilles per agilitzar la redacció (ex. guies, informes, manuals).

        Estàndards i bones pràctiques.

    Què aprendràs:

        Establir formats uniformes.

        Utilitzar plantilles per estalviar temps i mantenir la qualitat.

3. Instal·lació, configuració i ús de sistemes de control de versions

    De què et parlaran:

        Conceptes bàsics de control de versions (VCS).

        Instal·lació i ús de Git, SVN o altres eines.

    Què aprendràs:

        Crear repositoris, fer commits, branches i merges.

        Treballar amb repositoris remots (GitHub, GitLab, Bitbucket).

4. Operacions avançades

    De què et parlaran:

        Estratègies avançades per gestionar branques i conflictes.

        Rebase, cherry-pick, revert, stash.

    Què aprendràs:

        Resoldre conflictes.

        Mantenir un historial net i ordenat.

        Millorar el flux de treball en equips grans.

5. Seguretat dels sistemes de control de versions

    De què et parlaran:

        Protecció de la informació del codi font.

        Control d’accés, claus SSH, autenticació multifactor.

    Què aprendràs:

        Configurar permisos.

        Evitar exposició de dades sensibles.

        Auditar canvis i accessos.

6. Instal·lació, configuració i ús de sistemes d’integració contínua (CI)

    De què et parlaran:

        Què és la integració contínua: automatitzar proves i compilacions cada cop que es canvia el codi.

        Eines com Jenkins, GitLab CI, Travis CI, CircleCI.

    Què aprendràs:

        Configurar pipelines per a builds i tests automàtics.

        Integrar amb repositoris de codi.

        Automatitzar desplegaments.

7. Monitorització contínua de les mètriques de qualitat de l’aplicació

    De què et parlaran:

        Com mesurar la qualitat del codi: cobertura de tests, complexitat, vulnerabilitats.

        Eines com SonarQube, CodeClimate.

    Què aprendràs:

        Analitzar i interpretar mètriques.

        Integrar la monitorització dins del procés CI.

        Millorar contínuament la qualitat del projecte.

Resum

Aquest curs t’ajudarà a dominar les eines i processos per treballar en equip, mantenir la documentació actualitzada, gestionar el codi de manera segura i automatitzar proves i desplegaments per garantir la qualitat del programari.
