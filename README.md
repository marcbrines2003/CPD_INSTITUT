![](/images/Aspose.Words.b9069859-c84a-4c5d-aaec-a1ed4bcca626.001.png)
# PROJECTE CPD INSTITUT
## DEFINICIÓ DE OBJETIUS DEL PROJECTE
Marc Brines Bañuls 
Xavi Garcia Ferrando 

Aquest document conté una explicació detallada dels objectius i requisits relacionats amb el Centre de Processament de Dades (CPD) virtual d’un institut. Inclou una descripció general d’aquests objectius, com ara la centralització de la gestió de la informació, l’optimització dels recursos informàtics i la seguretat de la informació. A més, busca fomentar la innovació educativa, garantir l’escalabilitat i el compliment de les normatives. 

L’estructura d’aquest treball està organitzada en diverses seccions que aborden: 

1. **Requisits funcionals i no funcionals**: Es presenten les tasques específiques que s’exigeixen al CPD, incloent la gestió acadèmica, còpies de seguretat, seguretat en  l’accés, així com els criteris de qualitat, incloent l’economia, l’escalabilitat i la compatibilitat multiplataforma. 
1. **Anàlisi  de  requisits**:  Es  defineixen  les  necessitats  de  maquinari,  com  ara servidors  i  sistemes  d’emmagatzematge,  i  programari,  com  plataformes  de virtualització i eines de col·laboració. 
1. **Capacitats  necessàries:**  Es  detallen  les  especificacions  tècniques,  incloent processament, emmagatzematge i xarxa. 
1. **Cronograma  i  horaris:**  Es  proporciona  als  usuaris  un  pla  de  treball  ben organitzat  que  inclou,  però  no  es  limita,  a  tasques  clarament  definides,  des  de l’establiment dels objectius fins a la implementació del sistema i la formació final. 
1. **Pressupost**: Una estimació de despeses aproximada i detallada. 
# <a name="_page3_x72.00_y72.00"></a>**PLÀNOL COMPLET DELS COMPONENTS** 
![](/images/Aspose.Words.b9069859-c84a-4c5d-aaec-a1ed4bcca626.002.jpeg)

*Fig 1: Estructura dels components que necessitarem.*
# <a name="_page3_x72.00_y395.18"></a>**PLÀNOL ESTRUCTURAT DE COM QUEDARIA EL CPD** 
![](/images/Aspose.Words.b9069859-c84a-4c5d-aaec-a1ed4bcca626.003.jpeg)

*Fig 2: Estructura de la xarxa del CPD.* 

Xavi Garcia Ferrando i Marc Brines Bañuls                                            3 
# <a name="_page4_x72.00_y111.60"></a>**DEFINICIÓ DELS OBJECTIUS DEL PROJECTE** 
` `**Objectius Generals d'un CPD Virtual per a un Institut:** 

- **Centralitzar  la  Gestió  de  la  Informació:**  Mantindre  totes  les  dades  de l'institut  (acadèmiques,  administratives  i  operatives)  organitzades  i accessibles de manera centralitzada i segura. 
- **Optimitzar els Recursos Tecnològics:** Crear un entorn virtual eficient per reduir  costos  operatius,  utilitzant  recursos  tecnològics  virtualitzats  i escalables. 
- **Garantir la Seguretat de les Dades:** Protegir la informació amb mesures de seguretat  com  xifratge,  còpies  de  seguretat  automàtiques  i  plans  de recuperació en cas de desastres. 
- **Donar  Suport  a  l’Educació  Digital  i  la  Innovació:**  Proporcionar infraestructures  tecnològiques  per  a  l’aprenentatge  en  línia,  integrar eines digitals i desenvolupar noves metodologies educatives. 
- **Garantir  l’Escalabilitat  i  la  Disponibilitat:**  Dissenyar  una  infraestructura virtual  que  s'adapta  a les necessitats creixents de l’institut, assegurant un temps d'activitat òptim i capacitat per gestionar pics de demanda. 
- **Complir  amb  Normatives  i  Estàndards:**  Assegurar  que  el  CPD  virtual cumplixca amb les lleis sobre protecció de dades i educació, així com amb estàndards de qualitat en tecnologia i seguretat. 
- **Millorar la Presa de Decisions:** Proporcionar dades i estadístiques en temps real  amb  eines  d’anàlisi,  facilitant  la  planificació  estratègica  i  la  presa  de decisions informades. 
- **Reduir  l’Impacte  Ambiental:**  Minimitzar  el  consum  d’energia  i  la dependència  d'infraestructures  físiques,  alineant-se  amb  polítiques sostenibles i de responsabilitat social. 
- **XARXA ( MACROLAN ):** Aquesta red té la funció d'una vegada enviem una petició des del cpd, anirà fins València, passarà un filtre que hi ha establit, i amb la IP pública, en cas de poderse realitzar, ens tornarà la resposta a la petició. També cal afegir que es una red que abarca molt de terreny ja que 

` `Xavi Garcia Ferrando i Marc Brines Bañuls                                            4 

aquesta  red  cubrix  tots  els  centres  ubicats  a  València.  Aquest  filtre  està establit per tal de no fer mal ús de les xarxes educatives. 
# <a name="_page5_x72.00_y125.40"></a>**REQUISITS FUNCIONALS** 
Descriuen les funcions que ha de proporcionar el CPD del institut: 

**ÁMBIT ACADÈMIC:** 

- **Gestió de dades académiques:** Inclou les notes, historial acadèmic, registre d’assistència, matrícula i la base de dades. 
- **Serveis  educatius:**  implementació  de  eines  d’aprenentatge  com  Aules, Moodle, Office… 

**ÁMBIT ADMINISTRATIU/SEGURETAT:** 

- **Accés  segur:**  autenticació  amb  credencials  per  a  usuaris  (professors  i administraors) 
- **Copies de seguretat:** cal tindre un sistema de backup i una capacitació de restauració ràpida en cas d’incidència. 
- **Monitorització  i  control:**  supervisar  la  xarxa  i  recursos informàtics per a previndre alertes davant possibles atacs o errors. 
# <a name="_page5_x72.00_y439.52"></a>**REQUISITS NO FUNCIONALS** 
Defineix les característiques de qualitat i criteris d’implementació: 

- **Rendiment:**  ha  de  tindre  un  temps  de  resposta  efectiu  i  la  capacitat  de suportar determinats usuaris sense degradació. 
- **Escalabilitat:** poder augmentar els recursos per a futures necessitats. 
- **Disponibilitat:** garantir un temps de funcionament. 
- **Seguretat:**  compliment  de  la  normativa  GDPR,  sistemes  de  tallafocs  i antivirus, xifrat de dades. 
- **Eficiència energètica:** ús d'equips amb certificació energètica i sistemes de refrigeració adequats. 
- **Manteniment:** Sempre es farà manteniment físic, dins del centre. 
- **Compatibilitat:**  suport  per  a  diferents  plataformes  i  dispositius (Windows, macOS, Android, iOS) 
- **Ubicació física:** instal·lació en una sala segura amb control d'accés físic, 

  condicions òptimes de temperatura i humitat. 

- **Costos:** equilibri entre el cost d'implementació i el benefici aportat. 

**ANÀLISI DE REQUISITS** 
#### **Necessitats de maquinari i programari <a name="_page6_x72.00_y196.19"></a>Maquinari (Hardware)** 
- **Servidors i emmagatzematge** 
- Servidors físics per a gestionar dades i aplicacions. 
- Sistemes d’emmagatzematge per a guardar fitxers, preferiblement amb còpies de seguretat. 
- **Equip de xarxa** 
- Routers, switches i punts Wi-Fi per a garantir una connexió ràpida i estable. 
- **Sistemes de seguretat i energia** 
- Dispositius  de  seguretat  (firewalls)  i  bateries  UPS  per  a  evitar interrupcions per talls de llum. 
- **Dispositius de suport** 
- Ordinadors  o  tauletes  per  a  estudiants  i  professors,  segons  siga necessari.** 
#### <a name="_page6_x72.00_y520.24"></a>**Programari (Software)**
- **Plataformes educatives i de gestió** 
- Moodle, Google Classroom o Microsoft Teams per a l’aprenentatge. 
- Sistemes de gestió acadèmica per a notes, horaris i documentació. 
- **Seguretat i còpies de seguretat** 
- Antivirus i sistemes per a protegir dades. 
- Programes per a fer còpies de seguretat, com Veeam. 
- **Eines de col·laboració** 
- Paquets com Google Workspace o Microsoft 365 per a treballar junts des de qualsevol lloc. 

**MILLORES AL CPD ACTUAL** 

- **Cablejat:** El cablejat actual ja que es una infraestructura vella, cambiariem tot el cablejat que du el cpd, i el que uneix el servidor en aquest. A més de la seua  correcta organització i protecció correspondent que afavorirà la seua protecció i seguretat, ademés de visualment vores més ordenat. 
- **COL·LOCACIÓ D’UN NAS:** Col·locació d’un NAS, amb l’objectiu de guardar informació dels alumnes, ja siguen les seues credencials com per exemple algún treball que hi poden guardar en algún dels ordenadors del centre, com programari que tinguen cada u en el seu lloc de treball, etc. 
- **MILLORA DEL LA UBICACIÓ DEL CPD:** En la ubicació actual, esta molt desprotegit, i es un dels elements que permet que aquest centre seguixca en funcionament. Per tant algunes de les millores podrien ser, ficar parets enves de cristaleres amb la seua porta tancada amb clau, amb accés limitat. També hi han goteres i hi han certes coses que hi entren en aquesta habitació. Fer-li la correspondent obra, com arreglar les goteres i tapar els posibles danys que hi ha a les parets, per tal de augmentar la seguretat així també com la vida d’aquest. 
- **CLIMATITZACIÓ:**  Fent  les  millores  aquestes  quedaria  més  cobert  el  que sería el nostre CPD, per tant com aquest despren molt de calor degut a tot el equip que du, montar una bona climatització amb ventiladors extractors de calor, i també situar aquest en un lloc que no li pqgue el sol directe i que estoga un poc refugiat de la calor, per tal de augmentar el rendiment i la vida de tot l’equip. 
- **ORGANITZACIÓ:**  Actualment, està desordenat, els cables estàn pel mig, hi han  dispositius  i  altres  coses  que  no  s’utilitzen  per  a  res, dins d’aquesta habitació,  per  tant  deixar  sols  el  necesari  per  a  que  funcione  el  CPD, organitzar el cablejat cada un per el seu lloc corresponent, cada equip en el seu lloc, per apart de guanyar espai per a maniobra en cas de manipular el CPD, també guanyem en refrigeració d’aquest i ordre. 
# <a name="_page8_x72.00_y72.00"></a>**CAPACITATS NECESSARIES PER UN CPD VIRTUAL** 
1. **Processament** 
- Servidors potents amb 8-16 nuclis de processador i almenys 64-128 

  GB de RAM per a gestionar aplicacions i usuaris sense problemes. 

2. **Emmagatzematge** 
- Comença amb 2-5 TB d’espai: 
  - SSD  per  a  les  aplicacions  i  bases  de dades que necessiten velocitat. 
  - HDD i còpies de seguretat. 
- Fes còpies de seguretat regulars amb espai addicional per a protegir la informació. 
3. **Xarxa** 
- Necessites almenys 500 Mbps - 1 Gbps de velocitat d'internet per a suportar molts usuaris simultanis. 
- Internament, xarxa amb velocitat d’1 Gbps i punts Wi-Fi ràpids (millor si són Wi-Fi 6). 
- Tingues  un  sistema  de  seguretat  fort  (firewalls)  i  una  connexió  de reserva per si falla la principal. 
# <a name="_page9_x72.00_y72.00"></a>**CRONOGRAMA** 
**INICIAL:** 

![](/images/Aspose.Words.b9069859-c84a-4c5d-aaec-a1ed4bcca626.004.jpeg)

**EN PROCÉS:** 

![](/images/Aspose.Words.b9069859-c84a-4c5d-aaec-a1ed4bcca626.005.jpeg)
# <a name="_page10_x72.00_y72.00"></a>**HORARI DE TREBALL** 
**FINAL:** 

![](/images/Aspose.Words.b9069859-c84a-4c5d-aaec-a1ed4bcca626.006.jpeg)

**HORARI DE TREBALL DELS SPRINTS:** 

![](/images/Aspose.Words.b9069859-c84a-4c5d-aaec-a1ed4bcca626.007.png)
# <a name="_page11_x72.00_y72.00"></a>**PRESSUPOST NECESSARI PER AL CPD VIRTUAL** 
**SEGURETAT SOCIAL PER ALS TREBALLADORS Valor estimat =** 200-300€ per treballador
#### <a name="_page11_x72.00_y163.96"></a>**1. Maquinari i Infraestructura** 
Si optem per una infraestructura **local**: 

- **Servidors i emmagatzematge:** 2 servidors potents amb SSD i capacitat d’expansió 

  → **30.000 €**. 

- **Xarxa:** Routers, switches i punts Wi-Fi d’alta capacitat (Wi-Fi 6) → **8.000 €**. 
- **Seguretat:** Firewall, sistemes d’autenticació i UPS → **7.000 €**. 

**Total Maquinari:** **45.000 €** 



|**Fase** |**Hores asignades** |**Resultats** |
| - | - | - |
|**Fase 1** |**66h** |Material i llicències adquirits** |
|**Fase 2** |**72h** |Infraestructura inicial montada i probada** |
|**Fase 3** |**96h** |Xarxa i seguretat completament configurades |
|**Fase 4** |**126h** |CPD operatiu i integrat amb eines educatives** |
|**Fase 5** |**66h** |Proves finals fetes i documentació completada** |
|**Fase 6** |**60h** |Lliurament i formació final** |
# <a name="_page12_x72.00_y72.00"></a>**CRONOGRAMA VISUAL:** 


|**TASCA** |**DATA INICI** |**DATA FINAL** |**TREBALLADOR** |
| - | - | - | - |
|Definir objectius |9/01/2025 |9/01/2025 |Tres treballadors |
|Determinar requisits funcionals i no funcionals |9/01/2025 |9/01/2025 |Xavi |
|Anàlisi de requisits |9/01/2025 |9/01/2025 |Samuel |
|Identificació de tasques en el grup |9/01/2025 |9/01/2025 |Marc |
|Elegir un líder |9/01/2025 |9/01/2025 |Tres treballadors |
|Asignar recursos |9/01/2025 |16/01/2025 |Samuel |
|Establir un horari de treball |9/01/2025 |13/01/2025 |Xavi |
|Establir treballs al grup |9/01/2025 |13/01/2025 |Marc |
|Cronograma visual |9/01/2025 |16/01/2025 |Xavi |
|Comprovació de que el cronograma siga adequat |10/01/2025 |16/01/2025 |Samuel |
|Riscos possibles |13/01/2025 |13/01/2025 |Marc |
|Plans contra els possibles riscs |13/01/2025 |13/01/2025 |Xavi |
|Revisió del pla complet |||Tres treballadors |
# <a name="_page13_x72.00_y72.00"></a>**POSIBLES RISCOS AL CPD**
- **Fallo elèctric** 
  - **Interferencies electromagnètiques:** Equips elèctrica propers poden causar interferències y afectar el rendiment dels servidors. 
  - **Sobrecàrregues elèctriques:** Si es connecten massa dispositius al mateix circuit, pot haver una sobrecàrrega i provocar una apagada. 
- **Seguretat** 
  - **Atacs de ransomware:** Programes que secuestren dades i demanen un rescat per lliberar-los. 
  - **Usuaris interns descontents:** Empleats o estudiants amb accés als sistemes poden intentar fer mal bè. 
- **Sobrecalfament:** 
  - **Acumulació de pols:** La pols pot bloquejar els sistemes de ventilació i causar sobrecalfament. 
  - **Falles en sensors de temperatura:** Si els sensors no funcionen correctament, pot no detectar el augment de temperatura a temps. 
- **Falta de manteniment:** 
  - **Falla de discs durs:** Si els discs durs no es revisen constantment, podent fallar i perdre dades importants. 
  - **Desgast de cables:**Cablejat vell o danyat poden causar interrupcions en la conexió. 
- **Errors humans:** 
- **Introducció de hardware no compatible:** Connectar equips que no son compatibles poden causar fallades al sistema. 
- **Falta de formació:** Si el personal no està ben capacitat, poden fer fallades que afecten al CPD. 
# <a name="_page14_x72.00_y72.00"></a>**PLANS CONTRA ELS POSSIBLES RISCOS** 
- **Fallada elèctrica:** 
- Utilitzar cables blindats i aïllament adequat en els equips. 
- Mantindre els equips que generen interferències allunyats dels servidors. 
- **Seguretat**: 
  - Mantindre els sistemes actualitzats amb els últims pegades de seguretat. 
  - Realitzar còpies de seguretat ferqüents i emmagatzemar-les en llocs segurs. 
  - Implementar antivirus i tallafocs. 
- **Sobrecalfament:** 
- Netejar regularment els equips i els sistemes de ventilació. 
- Utilitzar filtres de pols en les entrades d’aire dels equips. 
- **Falta de manteniment:** 
- Implementar una rutina de manteniment preventiu i revisions regulars dels discs durs. 
- Utilitzar tecnologies com RAID per a la redundància i la protecció de dades. 
- **Errors humans:** 
- Realitzar proves de compatibilitat abans d’integrar un nou maquinari. 
- Documentar clarament les especificacions i requisits de compatibilitat dels equips. 
- Implementar simulacions i exercicis pràctics per a millorar les habilitats del personal. 
- Contractar a personal professional i capacitat. 
# **COMPARATIVA DELS DIFERENTS <a name="_page15_x72.00_y106.50"></a>SISTEMES OPERATIUS** 
**WINDOWS SERVER:** 

**VENTAGES:** 

- **Compatibilitat**: Te una integració nativa en ferramentes que s’utilitzen en l’ambit educatiu, com son Microsoft 365, Teams y Active Directory. 
- **Facilitat en la gestió**: Té una interfície gràfica d'usuari amigable i suport per a les diferents tasques en powershell. 
- **Seguretat**: Compleix la normativa de protecció de dades mitjançant ferramentes de encriptació i firewalls avançats. 
- **Escalabilitat**: Té un suport robust, per a la virtualització com pot ser Hyper-V, i configuracions en el núvol (Azure). 
- **Ecosistema educatiu**: Beneficis educatius com llicències especials i descontes per institucions acadèmiques. 
- **Monitorització i còpies de seguretat**: Ferramentes com Veeam i System Centre optimitzen la supervisió i protecció de dades. 

**DESVENTAGES:** 

- **Cost:** Llicències i serveis associats poden ser elevats comparats amb alternatives open-source. 
- **Requisits Hardware:** Demana més recursos, especialment per entorns virtualitzats complexos. 

**LINUX**

**VENTAGES:** 

- **Cost**: Gratuït i open-source, el que redueix significativament el cost inicial. 
- **Flexibilitat i personalització**: Altament configurable per adaptarse a requisits específics del CPD. 
- **Rendiment:** Llauger en recursos, ideal per a servidors de configuracuó de hardware llimitat. 
- **Seguretat**: Sistema robust amb menor exposició al malware i atacs, a més de actualitzacions regulars. 
- **Virtualització**: Suport natiu per a tecnologies com KVM, Proxmox o Xen. 

**DESVENTAGES:** 

- **Curva de aprendizaje**: Pot ser més complexe de gestionar, especialment per a persones amb experiencia llimitada en sistemes de Linux. 
- **Compatibilitat:** Pot requerir configuració adicional per a ferramentes populars com Office o apps propietaries. 
- **Suport**: No conta amb el mateix nivell de suport comercial que windows server. 

**VMware ESXi** 

**VENTAGES:** 

- **Especialització:** Sistema operatiu dissenyat exclusivament per a la virtualització, ideal per a gestionar múltiples màquines virtuals de manera eficient. 
- **Rendiment:** Altament optimitzat per a entorns virtualitzats. 
- **Escalabilitat:** Excelent per a créixer en funció de les necessitats del CPD. 

**DESVENTAGES:** 

- **Cost:** Encara que siga gratis la versió bàsica, les funcions avançades requerixen licencia costosa. 
- **Dependencia**: Enfocà en la virtualització pura, lo que pot llimitar el seu ús i les necessitats adicionals fora de l’entorn virtual 

**MacOS Server** 

**VENTAGES:** 

- **Senzill:** Interfaç intuitiva i fàcil d’utilitzar. 
- **Integració:** Compatible amb ecosistemes Apple, ideal si els dispositius del institut son Mac o iPads. 
- **Rendiment:** Bon rendiment per a xicotetes xarxes locals. 

**DESVENTAGES:** 

- **Cost:** Llicències i hardware associats solen ser bastant cars. 
- **Escalabilitat llimitada**: No és ideal per a grans CPD amb altes demandes de rendiment i complexitat. 

**ELECCIÓ DEL NOSTRE SISTEMA OPERATIU** 

Donat a que el que busquem en aquest projecte es la centralització de les dades, i garantitzar seguretat ademés de fomentar la col·laboració educativa Windows server es  la  millor  opció  en  aquest  cas,  per  la  seva  compatibilitat  amb  ferramentes educatives clau en aquest projecte. No obstant, si el pressupost fora llimitat, Linux sería  la  opció per el seu cost, pero requerirà de personal amb més capacitació, aleshores al cap i a la fí, és recomanable  per al nostre cpd utilitzar Windows Server. 
# <a name="_page18_x72.00_y72.00"></a>**DADES QUE EMMAGATZEMARÀ EL CPD** 
Algunes de les dades que emmagatzemarà i de ahí la creació d’aquest projecte, son: 

**DADES OPERATIVES** 

- **Gestió d’infraestructures:** Registres relacionats amb els equips de xarxa, servidors, sistemes de seguretat i el manteniment de les instal·lacions. 

**COPIES DE SEGURETAT I DADES DEL SISTEMA:** 

- **Copies de seguretat:** Backups de dades crítiques de gestió administrativa. 
- **Registres de monitorització:** Logs del sistema, incloent esdeveniments accesos i rendiment dels sistemes de control per al CPD. 

**DADES PER A LA PRESA DE DECISIONS:** 

- **Estadístiques i informes:** Informació sobre el ús de recursos, anàlisi del rendiment de sistemes o processos administratius per ajudar en la planificació. 

**ARXIUS I COMUNICACIONS INSTITUCIONALS:** 

- **Correus electrònics i comunicacions:** Historial de comunicacions del personal. 
- **Documents i plantilles administratives:** Arxius de treball habituals per al personal 
Xavi Garcia Ferrando, Marc Brines Bañuls                                             




![](/images/Aspose.Words.af545279-911e-46bc-a966-713dfb05dcaf.002.jpeg)




Aquest diagrama mostra la disposició dels servidors, dispositius d’emmagatzematge i components de la xarxa.  

Per al nostre cas, ta topología de xarxa mes correcta seria la **jeràrquica** (arbre) perque permet una xarxa organitzada, segura i eficient per al nostre entorn. 

- Estructura escalable i organitzada. 
  - Xarxa segmenta amb un router principal que es comporta com a punt central de connexió. 
  - El core switch distribuix la connexió de les VLANs. 
- Segmentació mitjançant VLANs. 
- S’utilitzen VLANs per a separar els distints tipus de tràfic: 
- VLAN 10: Professors 
- VLAN 20: Alumnes (ESO/BATX) 
- VLAN 30: Alumnes (Cicles) 
- Zona desmilitaritzada (DMZ). 
  - Allotja servidors web i de correu, protegint la xarxa interna de accessos externs i atacs. 
- Facilitat de creiximent i manteniment. 
- Es fàcil d’agregar més VLANs, servidors o equips. 
# **ELECCIÓ DE PROGRAMES SEGONS** 
# <a name="_page3_x72.00_y98.45"></a>**NECESITATS**
**ADMISTRACIÓ DEL SERVIDOR I DE LA RED** 

- **Active directory:** Per gestionar usuaris, permisos i polítiques de accés. 
- **DNS y DHCP:** Per gestionar direccions IP y noms de dominis interns. 
- **Group Policy Management:** Per aplicar configuracions als equips de la red. 
- **Hyper-V:** Si es necesita virtualització de servidors. 
- **PowerShell:** Per automatització i gestió avançada del server. 

**SEGURETAT I PROTECCIÓ** 

- **Antivirus service executable:** El que va instal·lat predeterminat (gratis). 
- **Firewall:** No necessitarem d’aquest ja que en la macrolan de conselleria, hi fan servir un. 
- **SIEM:** Per monitoritzar amenaces i events de seguretat. 
- **AOMEI backuper:** Per a fer copies de seguretat de dades crítiques. 
- **DETECCIO DE INTRUSOS** (*suricata*): Per veure si hi ha usuaris no desitjats. 

**ADMINISTRACIÓ I GESTIÓ DE USUARIS** 

- **Microsoft 365:** Per gestió de correus i ferramentes colaboratives. 
- **Worksapce for Education:** Si el intitut gasta el drive, gmail, classroom… 
- **Control de Inventari**: Per a gestionar hardware i software de la institució. 
- **Gestió escolar:** Per a la gestió de alumnes, calificacions i assistencia. 

**FERRAMENTES PER SOPORTS TECTNICS** 

- **Remote Desktop (AnyDesk):** Per soport remot de docents i administratius. 
- **Monitorització de la red:** Per supervisar el rendiment de l’estructura. 
- **Systernals Suite:** Per análisi i diagnostic de problemes en Windows Server. 

**SERVICIS WEB I ALMACENAMENT** 

- **IIS:** Per allotjar pàgines web internes o aplicacions del institut. 
- **Servidor SFTP:** Per transferir archius. 
- **Servidor de archius:** Per gestionar els recursos compartits. 

**VIRTUALITZACIÓ I CONTENEDORS** 

- **VMWare / Proxmox :** Si es requereix virtualitzar més serveis. 
- **Docker i kubernetes:** Per desplegar aplicacions modernes en contenedors

**IDENTIFICACIÓ DE MODELS DELS DISPOSITIUS** 

- **Router principal:** Miktrotik chr 
- **switch:** Cisco IOU L2/3, en windows server que es el nostre sistema operatiu no hi ha un switch dedicat per a aquest, pero es pot gastar Hyper-V amb VLANs per a simular les xarxes separades. 
- **Servidor web:** 
- Windows Server 19/22 amb IIS per al server web 
- Windows  Server  amb  Microsoft  Exchange  Server  per  a  correu electronic 
- **Server  de  archius  (VLAN10):** En aquest gastarem windows server 19/22 amb File Server Role, que permet compartir archius en la xarxa com un NAS. 
- **PCs alumnes:**  
- ESO / Batxillerat: Gastaran lliurex. 
- Professorat: Gastaran Windows, mitjançant un Active Directory. 
- FP: Gastaràn el sistema operatiu de Ubuntu. 
- **PC Administració:** Usarem, com en l’anterior windows 10 i 11 VM amb accés a ferramentes administratives, està en una VLAN separada per a una major seguretat. 
- **Acces  point:**  En  aquest  cas  també  apostarem  per  un  mikrotik chr per a gestionar el wifi. 

En dues ocasions en el nostre projecte hem gastat miktrotiks, ja hem dut proves a terme en aquest router per saber que es de la nostra confiança, hem ficat un switch nou per tal de veure com es el seu funcionament dins del nostre plà de projecte, ja que hem investigat sobre aquest i s’adapta a les nostres necesitats. Seguim en els servidors, que hi gastarem els windows servers ja que es el nostre sistema operatiu elegit, per què per al nostre gust s’adapta a les necessitats a més de tindre un ús més fàcil que els demés sistemes. Els ordenadors tindrem tots ús del windows tant 10 com el 11 per a disfrutar de les seues ferramentes enfocades cara la educació i la facilitat per als usuaris del centre. 
# <a name="_page5_x72.00_y72.00"></a>**POLÍTIQUES DE PRIVACITAT** 
**POLÍTIQUES ENFRONT L’ INSTITUT**: 

- **Finalitat del tractament:** Gestió acadèmica, administrativa, i de comunicació amb les families i avaluació. 
- **Tipus de dades que es recollixen**: Identificatives (nom,DNI…), acadèmiques i imatges de activitats educatives. 
- **Base legal:** Consentiments, obligació legal o interès legítim. 
- **Conservació de les dades:** Temps determinar segons normativa educativa. 
- **Drets dels usuaris:** Accés, rectificació, suspenssió, oposició, portabilitat i limitació. 
- **Comparació de dades**: Amb entitats educatives, administracions públiques o tercers si és necessari (per exemple, les pràctiques de FP). 
- **Mesures de seguretat:** Protecció física i digital per evitar accessos no autoritzats. 
- **üs de plataformes digitals:** Normativa sobre Google Classroom, Moodle, etc. 

**POLÍTIQUES DE PRIVACITAT DEL CPD:** 

- **Control d’accés:** Només personal autoritzat pot accedir als servidors i bases de dades. 
- **Encriptació i protecció:** Xifrat de dades i comunicacions, ús de VPN per a connexions externes. 
- **Monitorització i registres:** Registre d’accessos i auditories de seguretat periòdiques. 
- **Còpies de seguretat:** Backups regulars i emmagatzematges segurs. 
- **Política de destrucció de dades:** Eliminació segura quan ja no siguin necessàries. 
- **Gestió d’incidents:** Protocol en cas de ciberatacs o filtracions de dades. 
- **Compliment normatiu:** Adaptació a les lleis de protecció de dades i bones pràctiques de seguretat informàtica. 

**ALGUNES RECOMANACIONS:** 

- **Formació:** Personal i alumnes han de rebre informació sobre protecció de dades i bones pràctiques digitals. 
- **Consentiments informats:** Cal obtenir l’autorització de pares o tutors per a l’ús d’imatges o dades sensibles. 
- **Auditories de seguretat:** Realitzar controls periòdics per a detectar possibles vulnerabilitats. 
# <a name="_page6_x72.00_y72.00"></a>**PROTECCIÓ INTERNA I EXTERNA** 
Pla de seguretat informàtica per al CPD de l’institut. Per a garantir la seguretat del nostre CPD, hem de establir unes mesures i controls per tal de millorar la seguretat i protegir les dades. Per això hem de fer el següent: 

- Protecció Permimetral i Xarxa 
- Tallafocs (Firewall): implementar un firewall perimetral entre la xarxa de l’institut i Interent. 
  - Bloquejar ports innecessaris. 
  - Permetre només trànsit essencial 
  - Filtrar tràfic sospitós 
- Sistemes de Detecció i Prevenció d’Intrusions 
  - Atacs de força bruta 
  - Escanejos de ports 
- Segmentació de Xarxa amb VLANs 

  Aplicar ACLs per a evitar que dispositius no autoritzats accedixquen a altres VLANs 

- VLAN 10: Professorat 
- VLAN 20: Alumnes ESO/Batx 
- VLAN 30: Alumnes Cicles 
- DMZ: Servidors exposats a Internet 
- Seguretat dels Servidors del CPD 
- Protecció Física del CPD 
  - Accés restringit amb lector de targetes i càmares de seguretat. 
  - Sensors de temperatura, foc i humitat. 
- Autenticació i Control d’Accés 
  - Contrasenyes robustes i segures amb canvis cada cert temps. 
  - Només personal autoritzat pot administrar els servidors. 
- Còpies de Seguretat i Recuperació 
- Fer backups diaris amb còpies en un servidor extern fora de la ubicació principal. 
- Realitzar simulacres de recuperació de dades cada cert temps. 
- Seguretat dels Dispositius i Usuaris 
- Protecció d’Estacions de Treball 
  - Instal·lar antivirus a tots els equips. 
  - Xifratge de discs 
- Seguretat en la Xarxa Wi-Fi 
- Separar la Wi-Fi de convidats de la Wi-Fi interna 
- Utilitzar WPA3 i desactivar WPS 
- Resposta a Incifdents 
- Pla de Resposta a Incidents 
- Crear un protocol de resposta a incidents amb identificació, contenció, anàlisi, recuperació i informe final 
- Formació 
- Formació per a personal i alumnes 
- Sessions periòdiques sobre pràctiques de seguretat 
- Simulacres de phishing 
- Guia d’ús segur de dispositius i contrasenyes 
  # <a name="_page7_x72.00_y292.84"></a>**PROCEDIMENTS DE CÒPIES I RESTAURACIÓ** 
**COPIES DE SEGURETAT:** 

- En el nostre cas, fem servir l'aplicació de AOMEI backuper, on realitzarem les còpies de seguretat de dades crítiques. 
- Realitzarem backups diaris amb còpies emmagatzemades en un servidor extern, així augmentem la seguretat i integritat de les dades. 
- Considerem com protecció física del CPD amb accés restringit i control de seguretat. 
- Destrucció de dades peer eliminar de manera segura la informació quan ja no siga necessaria. 

**RESTAURACIÓ** 

- En general, fem còpies diaries, la recuperació també la faríem en la mateixa aplicació, mitjançant el software de AOMEI backuper. 
# <a name="_page8_x72.00_y72.00"></a>**PLA EN CAS DE FALLADA** 
Haurà de tenir diverses fases per a garantir la continuïtat del servei i la protecció de les dades.  

- Analitzar els riscos i identificar les fallades: 
  - Identificar els possibles riscos (fallades elèctriques, ciberatacs, desastres naturals, errors de maquinari o programari). 
  - Evaluar l’impacte de cada risc en els serveis de l’institut. 
- Protocol de resposta: 
  - Informar a l’equip tècnic i les autoritats corresponents 
  - Si és una fallada de seguretat, tallar les connexions externes. 
  - Depenent del tipus de fallada, aplicar solucions com la restauració de sistemes. 
- Pla de contingència i continuitat: 
  - Assegurar que hi ha còpies diàries en ubicacions externes al cpd. 
  - Implementar procediments per a la restauració ràpida de dades. 
  - Tindre servidors alternatius o un CPD secundari e altra ubicació. 
  - Utilitzar sistemes SAI i generadors. 
- Pla de recuperació: 
  - Prioritzar la restauració de serveis crítics. 
  - Comprovar la integritat de les dades després de la recuperació. 
  - Realitzar comprovacions periòdiques al pla de recuperació per assegurar que funciona en cas de fallada. 
- Comunicació i notificació: 
  - Informar als usuaris sobre els temps estimats de recuperació 
- Avaluació post-incident i millora : 
- Analitzar les causes de la fallida i determinar les mesures per a previndre futurs problemes. 
- Actualitzar el pla amb les noves millores. 
# <a name="_page9_x72.00_y72.00"></a>MANUAL D’USUARI 
**1 - ACCÉS AL CPD** 

- Només personal autoritzat pot accedir a la sala on estarà el CPD. 
- Càmeres de seguretat, que hi han instal·lades al voltat de l’institut. 
- S’ha de registrar cada accés en el llibre de control d’entrada i d’eixida. 

**2 - NO HI HA ACCÉS REMOT** 

- Totes les tasques d’administració es realitzen presencialment al CPD. 
- No es permet connexió externa als servidors de seguretat. 

**3 - ÚS DELS SERVIDORS I LA XARXA ESTRUCTURA DEL CPD** 

- Xarxa segmentada per VLANs per seguretat i organització. 
  - VLAN 10: Professorat 
  - VLAN 20: Alumnes Eso/Batxillerat 
  - VLAN 30: Alumnes Cicles 
- Servidors principals: 
- Windows Server 19/22 per gestió d’usuaris i arxius. 
- Servidor dels fitxers ( File Server ) amb NAS per emmagatzematge segur. 
- Servidor de base de dades per aplicacions institucionals. 

**ACCÉS A FITXERS I DADES** 

- Els arxius institucionals estan en el server dels fitxer, només accessibles des dels ordenadors conectats a la xarxa del CPD. 
- Accés a la sala esta restringit segons els permisos: 
- Administradors: Accés complet. 
- Personal autoritzat: Accés limitat a les seues funcions. 

**4 -** **SEGURETAT I PROTECCIÓ DE DADES** 

- Tallafocs intern ja que l’altre el té la macrolan que ens dona l’internet des de conselleria. 
- SIEM per a monitorització de seguretat a temps real. 
- Xifratge de dades en emmagatzematge i transmissions internes. 
- Control d’auditories per a detectar accessos sospitosos. 
- Política de canvi de contrasenyes cada cert temps. 
# <a name="_page10_x72.00_y72.00"></a>GUIA D’ADMINISTRACIÓ DEL CPD 
**1 - INFRAESTRUCTURA DEL CPD** 

**COMPONENTS PRINCIPALS** 

- Router principal: Mikrotik CHR 
- Switch de xarxa: Cisco IOU L2 per a gestionar les diferents VLANs 
- Sistema d’emmagatzematge: NAS dedicat amb windows server. 
- SAI ( UPS ) per evitar apagades sobtades i pèrdua de dades. 

**MANTENIMENT FÍSIC** 

- Revisió mensual de l’estat de cables i connexions. 
- Control de temperatura i humitat per evitar sobreescalfament. 
- Neteja regular per evitar problemes. 

**2 - POLÍTIQUES DE SEGURETAT** 

**RESTRICCIONS I PROTOCOLS D’ACCÉS** 

- Només personal autoritzat pot accedir al CPD. 
- No hi ha connexió remota als servidors ni accés extern. 
- Política de canvis de contrasenyes cada cert temps. 
- Restricció d’ús de dispositius USB en els servidors per evitar malware. 

**3 - CÒPIES DE SEGURETAT I RESTAURACIÓ** 

**BACKUPS I PROTECCIÓ DE DADES** 

- Còpies de seguretat diàries amb AOMEI Backupper. 
- Almenys una còpia externa semanal emmagatzemada en un disc dur extern. 
  - Disc dur extern: Kingston XS2000 Portable SSD 4TB USB 3.2 
- Proves de restauració periòdiques per a garantir la recuperació de dades en cas d’incendi o algún altre problema. 

**4 - MONITORITZACIÓ I RESPOSTA A INCIDENTS** 

**SISTEMES DE SUPERVISIÓ** 

- SIEM per detectar accessos no autoritzats. 
- Suricata ( detecció d’intrusos ) per bloquejar intents de ciberatacs. 
- Alertes automàtiques en cas d’intents d’accés no autoritzat. 

**PROCEDIMENTS** 

- En cas de intrusió o atac, es bloqueja l’accés i s’investiga l’oritgen. 
- Si es detecta falla del sistema, es procedeix a restaurar la ultima còpia. 
- Qualsevol incident ha de ser registrat i notificat als responsables.** 
# **DOCUMENTACIÓ DEL CPD FÍSIC DE <a name="_page11_x72.00_y98.45"></a>L’INSTITUT** 
**1- Introducció** 

Aquest document descriu l’estructura, la configuració i les decisions preses per a l’implementació del CPD físic de l’institut. L’objectiu principal és garantir la seguretat, eficiència i escalabilitat del sistema asegurant que només el personal autoritzat i qualificat puga accedir. 

**2- Arquitectura del CPD** 

**2.1. Infraestructura de Xarxa** 

L’arquitectura de xarxa es basa en un model jeràrquic segmentat per VLANs per garantir una millor seguretat i gestió. 

**2.1.1. Topologia de xarxa** 

- Xarxa jeràrquica (arbre) 
- Router principal: Mikrotik CHR. 
- Switch principal: Cisco IOU L2/3 per a gestió de VLANs 
- Segmentació de xarxa per VLANS: 
- VLAN 10: Professorat 
- VLAN 20: Alumnes Eso/Batx 
- VLAN 30: Alumnes Cicles 
2. **Servidors principals** 
- Windows Server 2019/22 per a la gestió d’usuaris i arxius. 
- Servidor de fitxers (File Server Role) amb NAS dedicat. 
- Servidor de bases de dades per a aplicacions institucionals. 
- Servidor web per a allotjament d’aplicacions internes. 
3. **Connexió i seguretat** 
- No hi ha accés remot per garantir la seguretat. 
- Accés físic restringit mitjançant targetes d’identificació. 
- Firewall perimetral per bloquejar accessos externs no autoritzats. 
- SIEM i Suricata per a la monitorització de seguretat i detecció d’intrusions. 

**3 - CONFIGURACIÓ DEL CPD** 

1. **Configuració de Windows Server** 
- Active Directory ( AD ): 
  - Gestió de permisos i rols d’usuari. 
  - Group Policy Management per a aplicar configuracions de seguretat. 
- DHCP i DNS: 
  - DHCP per a l’assignació dinàmica d’adreces IP. 
  - DNS intern per a la resolució de noms dins de la xarxa. 
- Servidor de fitxers: 
- Compartiments d’arxius segurs per departaments. 
- Accés restringit segons els permisos. 
2. **Configuració de seguretat.** 
- Firewall activat per controlar ports i protocols. 
- SIEM per monitoritzar la seguretat en temps real. 
- Antivirus empresarial i encriptació de dades sensibles. 
- Còpies de seguretat diàries amb AOMEI Backupper. 
3. **Protecció física** 
- Accés restringit amb targetes d’identificació i videovigilància. 
- Sensors de temperatura i humitat per evitar sobreescalfament. 
- Sistema SAI ( UPS ) per evitar apagades sobtades. 

**4 - DECISIONS DE DISSENY I IMPLEMENTACIÓ** 

1. **Elecció del Sistema Operatiu** 
- Windows server 19/22 per la seua compatibilitat amb les eines administratives i educatives. 
- NAS per emmagatzematge segur i escalable. 
2. **Restricciño de l’accés remot** 
- Per garantir la seguretat, no es permet cap accés remot. 
- Totes les operacions administratives es realitzen al CPD físic. 
3. **Escalabilitat i futur CPD** 
- L’arquitectura permet afegir nous servidors i serveis segons les necessitats. 
- Es preveu la possibilitat d’intgrar més VLANs per a futurs departaments. 
- Opcions d’expansió de l’emmagatzemantge mitjançant nous discs NAS. 

**5 - MONITORITZACIÓ I RESPOSTA D’INCIDENTS** 

1. **Sistemes de Supervisió** 
- SIEM per a detectar accessos no autoritzats. 
- Suricata per a la detecció d’intrusos. 
- Logs d’auditoria per registrar totes les accions administratives. 
2. **Protocols de Resposta a Incidents** 
- Bloquig inmediat en cas de detecció d’intrusió. 
- Restauració de dades des de l’última còpia de seguretat si es detecta corrupció o pèrdua de dades. 
- Notificació als responsables i registre d’incidents. 

Aquest  apartat  detalla  la  configuració  del  nostre  CPD  físic  de  l’institut,  amb  un enfocament  en  seguretat,  organització  i  eficiència.  Garantim  que  l’accés  estiga restringit, amb protocols adequats i estrictes per a la gestió i protecció de les dades del centre. 

**TASQUES I TRELLO:** 

Les tasques, en aquest segon sprint, com solament som 2, han sigut repartides a parts iguals, aquest és el procés que ha dut el nostre trello: 

1. Identificació de tasques a realitzar. 
1. Asignació de tasques per cada membre de l’equip. 
1. Desplaçament de cada tasca segons el seu estat. 

**TRELLO INICIAL:** 

![](/images/Aspose.Words.af545279-911e-46bc-a966-713dfb05dcaf.003.jpeg)

**TRELLO DURANT EL PROCÉS:** 

![](/images/Aspose.Words.af545279-911e-46bc-a966-713dfb05dcaf.004.jpeg)



## INSTAL·LACIÓ DEL SERVER

Primer que res, tinguent el nostre esquema clar que volem plasmar al treball, mirem les necessitats i eines que anem a gastar.  
Una vegada fet així, instal·lem en un pen el nostre Proxmox, que serà on instal·lem els nostres tres servidors:

- Formatejar unitat USB rufus amb el sistema operatiu de Proxmox
- Instalar en un equip amb disc dur net
- Seguir els passos de instalació i establir un nom d’usuari, contrassenya i adreça IP
- Connectar remotament amb un segon equip en una red interna
- Obri el navegador al segon equip i introduir la IP donada pel servidor
- Apareixerà la interfície de Proxmox i ens loguegem amb les nostres credencials

---

## PROXMOX-ISO

Importem al disc local del Proxmox les següents ISO:

- Windows Server
- Ubuntu Server
- Lliurex Server

Inicialment treballàvem amb un servidor Proxmox, però degut a problemes d’emmagatzematge i xarxa hem passat a VBox.

---

## VIRTUALBOX

Degut a limitacions tècniques amb Proxmox, hem passat a VirtualBox per treballar millor i simular el projecte.

### Creació de les màquines virtuals:

- **Router**: configuracions de xarxa i VLANs
- **Lliurex**: servidor dels clients
- **Ubuntu**: servidor dels clients
- **Windows**: servidor dels clients
- **Windows_client**: representa al professorat
- **Ubuntu_client**: representa alumnat de cicles i FP
- **Lliurex_client**: representa alumnat de ESO i Batxillerat

![](/images/Imagen de WhatsApp 2025-04-10 a las 10.25.56_5ca88b95.jpg)

### Descàrrega de les ISO:

- [Windows](https://www.microsoft.com/es-es/evalcenter/download-windows-server-2022)
- [Ubuntu](https://ubuntu.com/download/server)
- [Lliurex](https://wiki.edu.gva.es/lliurex/tiki-index.php?page=lliuwin)

---

## ROUTER INSTAL·LACIÓ

Configurem la xarxa amb una màquina de router **OpenWrt** en VirtualBox.

Les credencials del router han de ser les del nostre grup.

---

## LANS AFEGIDES

- **LAN 1**: Windows  
- **LAN 2**: Ubuntu  
- **LAN 3**: Lliurex

Afegim les targetes de xarxa corresponents a cada màquina virtual:

- Targeta mv Lliurex
- Targeta mv Ubuntu Server
- Targeta mv Windows

---

## WAN

La WAN connecta l’institut amb l’exterior a través de la **MACROLAN** de la Conselleria.

Aquesta xarxa:

- Actua com a filtre
- Millora la seguretat
- Controla el tràfic que entra i ix d’Internet

Exemple: accés a Microsoft Teams → CPD → WAN → MACROLAN → Internet

---

## IP DE LES MV

Comprovem que les màquines virtuals tenen IP:

- Ubuntu
- Windows

---

## TALLAFOCS ACTIUS

No cal instal·lar un tallafocs perimetral, ja que la MACROLAN ja filtra el tràfic cap a Internet.

També hem aplicat tallafocs interns en cada màquina virtual.

### OPTIMITZAR RENDIMENT I CONTROLAR EL TRÀFIC

#### Segmentació per VLANs

- VLAN 10: Professorat
- VLAN 20: Alumnes ESO/Batxillerat
- VLAN 30: Alumnes de Cicles Formatius

Hi ha una **DMZ** per als servidors exposats a Internet.

#### Tallafocs i filtratge

- Cada màquina té un tallafocs actiu
- La MACROLAN actua com a tallafocs perimetral

#### Monitoratge actiu del tràfic

Utilitzem sistemes com **SIEM** i **Suricata** per:

- Monitoritzar tràfic en temps real
- Detectar comportaments sospitosos
- Llançar alertes

> *No s’ha pogut aplicar per falta de coneixements i temps*

---

## TRELLO

### INICIAL:

*(imatge o estructura inicial no detallada)*

### FINAL:

*(imatge o estructura final no detallada)*

---



**TRELLO FINAL:** 


Xavi Garcia Ferrando Marc Brines Bañuls 


