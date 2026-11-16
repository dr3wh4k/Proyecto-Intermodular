# A1. Análisis de la empresa y definición del proyecto

## 1. Descripción de la empresa

CyberNova es una empresa del sector de la informática y la ciberseguridad que ofrece servicios destinados a proteger los sistemas informáticos y los datos de otras empresas.

Sus principales actividades son el análisis forense digital, las auditorías de seguridad, las pruebas de penetración o pentesting, la formación en ciberseguridad y el análisis de grandes volúmenes de datos para detectar posibles amenazas.

La empresa utiliza tecnologías de análisis de datos para mejorar la detección de incidentes, anticiparse a los ataques y reducir el tiempo necesario para responder ante problemas de seguridad.

- **Misión:** proteger los sistemas y datos de los clientes mediante servicios de ciberseguridad, análisis forense, auditorías y formación.

- **Visión:** convertirse en una empresa de referencia en ciberseguridad, ofreciendo servicios fiables y mejorando continuamente sus sistemas y métodos de trabajo.

- **Clientes:** grandes empresas, corporaciones y pymes con necesidades tecnológicas y de seguridad avanzadas.

- **Tamaño:** el plan empresarial inicial contempla una plantilla de 30 trabajadores repartidos entre la sede central de Alcoi (12 trabajadores) y las sedes de Barcelona (6), Madrid (6) y Vigo (6).


## 2. Organización y sedes

Según el escenario del proyecto intermodular, CyberNova contará con cuatro sedes en España:

| Sede | Función |
|---|---|
| Alcoi | Sede central de la empresa |
| Barcelona | Sede de trabajo y prestación de servicios |
| Madrid | Sede de trabajo y prestación de servicios |
| Vigo | Sede de trabajo y prestación de servicios |

Las cuatro sedes tendrán una organización similar y deberán poder comunicarse entre sí mediante redes privadas, utilizando direccionamiento IP privado para acceder a los servicios compartidos.

Cada sede estará dividida en dos edificios.

### Edificio 1
- Recepción.

- Gerencia y administración.

- Departamento SAT.

- Centro de Procesamiento de Datos (CPD).

- Cobertura Wi-Fi.


### Edificio 2
- Sala de vigilancia.

- Departamento comercial.

- Producción.

- Almacén.

- Cobertura Wi-Fi.


En el CPD de cada sede habrá **3 servidores físicos que alojarán 6 servidores virtuales**. La estructura permitirá distribuir los servicios, facilitar su administración y aprovechar los recursos disponibles.

## 3. Departamentos y funciones

| Departamento | Funciones principales | Información que gestiona |
|---|---|---|
| Ciberseguridad e Informática | Análisis forense, auditorías, pentesting, Big Data, soporte técnico y protección de sistemas | Registros de seguridad, informes técnicos, alertas, incidencias y datos de clientes |
| Recursos Humanos | Contratación, gestión de personal, formación interna y políticas de confidencialidad | Datos personales, contratos, formación y documentación laboral |
| Finanzas y Administración | Contabilidad, facturación, presupuestos y control de gastos e ingresos | Facturas, presupuestos, datos contables y documentación administrativa |
| Marketing y Comunicación | Imagen corporativa, campañas, redes sociales, comunicación con clientes y difusión de información de seguridad | Datos comerciales, contactos, campañas y contenidos de comunicación |

### Distribución prevista de la plantilla

| Departamento | Alcoi | Barcelona | Madrid | Vigo | Trabajadores |
|---|---:|---:|---:|---:|---:|
| Ciberseguridad e Informática | 6 | 4 | 4 | 4 | 18 |
| Recursos Humanos | 2 | 0 | 1 | 1 | 4 |
| Finanzas y Administración | 2 | 1 | 1 | 0 | 4 |
| Marketing y Comunicación | 2 | 1 | 0 | 1 | 4 |
| **Total** | **12** | **6** | **6** | **6** | **30** |

### Relación entre los departamentos y las áreas operativas de cada sede
Las áreas operativas distribuidas entre el Edificio 1 y el Edificio 2 se integran y coordinan con los cuatro departamentos de la siguiente forma:

- **Producción (Edificio 2):** depende del departamento de **Ciberseguridad e Informática**; es el área técnica donde los especialistas ejecutan las auditorías, el pentesting, el análisis forense y el procesamiento de Big Data para los clientes.
- **Departamento SAT (Edificio 1) y Almacén (Edificio 2):** integrados en **Ciberseguridad e Informática**; el SAT administra el CPD (Edificio 1), resuelve incidencias de todos los departamentos y gestiona en el Almacén el inventario de equipos y repuestos con la validación de compras de **Finanzas y Administración**.
- **Sala de vigilancia (Edificio 2):** opera en coordinación directa con **Ciberseguridad e Informática y el SAT**, supervisando de forma continua tanto la seguridad física de los edificios como los paneles de alertas de red y disponibilidad del CPD.
- **Gerencia, Administración y Recepción (Edificio 1):** albergan a los departamentos de **Finanzas y Administración** y **Recursos Humanos**, centralizando la dirección, la gestión laboral/contable y el control de acceso de visitas.
- **Departamento comercial (Edificio 2):** pertenece a **Marketing y Comunicación**; capta clientes y se coordina con **Producción** para definir el alcance técnico de los servicios contratados y con **Finanzas y Administración** para su presupuestación y facturación.

## 4. Necesidades tecnológicas detectadas

| Área | Necesidad | Problema o riesgo | Prioridad |
|---|---|---|---|
| Red entre sedes | Comunicación privada entre Alcoi, Barcelona, Madrid y Vigo | No se podrían compartir servicios de forma segura sin conectividad adecuada | Alta |
| CPD | Tres servidores físicos y seis virtuales por sede | Una infraestructura insuficiente podría dificultar el funcionamiento de los servicios | Alta |
| Ciberseguridad e Informática | Monitorización, análisis de registros y herramientas de seguridad | Dificultad para detectar incidentes y responder rápidamente | Alta |
| SAT | Sistema de gestión y seguimiento de incidencias | Pérdida de información o retrasos en la resolución de problemas | Alta |
| Administración y RR. HH. | Gestión centralizada de documentación y datos | Accesos no autorizados, duplicación o pérdida de información | Alta |
| Marketing y Comercial | Acceso controlado a información de clientes y servicios | Exposición de datos o dificultades para compartir información actualizada | Media |
| Producción y Almacén | Acceso a recursos compartidos y control de material | Desorganización de recursos y dificultades de coordinación | Media |
| Comunicaciones | Correo, mensajería y videoconferencia corporativos | Dificultad para coordinar trabajadores y sedes | Media |
| Seguridad de la información | Copias de seguridad, control de acceso y protección de datos | Pérdida de información, accesos indebidos o interrupciones | Alta |
| Servicios externos | Web corporativa y portal de clientes | Dificultad para presentar servicios y compartir informes de forma segura | Media |

## 5. Oportunidades de negocio del sector y mejoras internas

### 5.1. Oportunidades de negocio en el sector de la ciberseguridad
La evolución actual del sector permite identificar oportunidades reales de negocio que justifican contar con esta infraestructura:

- **Cumplimiento normativo obligatorio (Directiva NIS2, ENS y RGPD):** el aumento de exigencias legales obliga a pymes y grandes empresas a auditar sus sistemas regularmente. Contar con un portal de clientes seguro (Extranet) e infraestructura disponible permite comercializar auditorías periódicas y consultoría de cumplimiento.

- **Servicios de seguridad gestionada (SOC externo para pymes):** muchas empresas no pueden mantener un departamento propio de seguridad. La centralización de registros y herramientas entre las cuatro sedes permite ofrecer monitorización remota continua bajo suscripción mensual.

- **Respuesta descentralizada ante incidentes y ransomware:** ante el incremento de ciberataques, tener sedes interconectadas en Alcoi, Barcelona, Madrid y Vigo con entornos virtualizados permite ofrecer asistencia forense rápida y cercana al cliente afectado.

- **Formación corporativa online:** la plataforma web permite comercializar cursos de concienciación y prevención de ataques (como phishing) para empleados de otras empresas.


### 5.2. Problemas y oportunidades de mejora interna
- **Centralizar los servicios:** facilitar el acceso controlado a recursos compartidos desde las cuatro sedes.

- **Mejorar la comunicación:** permitir la comunicación entre sedes mediante redes privadas.

- **Aumentar la seguridad:** aplicar controles de acceso, segmentación de red, protección perimetral y monitorización.
He comprobado que el proyecto presenta una buena definición de la empresa, sus necesidades y las oportunidades de negocio. Valoro especialmente la relación entre los problemas detectados y la infraestructura propuesta. Sin embargo, debéis concretar mejor la organización de los trabajadores entre sedes, aclarar los departamentos operativos y establecer requisitos más medibles, especialmente en disponibilidad, copias de seguridad y cobertura de red. También debes unificar el nombre de la empresa en toda la documentación.
- **Mejorar la disponibilidad:** utilizar virtualización, copias de seguridad y mecanismos de recuperación ante fallos.

- **Facilitar la administración:** organizar servidores y servicios para simplificar su mantenimiento.

- **Agilizar la respuesta a incidentes:** centralizar registros y facilitar la detección de amenazas.

- **Preparar el crecimiento:** diseñar una infraestructura ampliable.


Estas mejoras ayudarán a CyberNova a prestar sus servicios de ciberseguridad y a mantener protegida su propia infraestructura.

## 6. Definición del proyecto

- **Nombre:** Diseño del sistema informático empresarial de CyberNova.

- **Finalidad:** diseñar una infraestructura informática segura, organizada y ampliable para desarrollar la actividad de CyberNova desde sus cuatro sedes.

- **Necesidades que resuelve:** comunicación entre sedes, organización de servicios, protección de la información, acceso a recursos compartidos, administración centralizada y continuidad del servicio.

- **Usuarios destinatarios:** los 30 trabajadores internos de los cuatro departamentos, los clientes autorizados (a través de la Extranet) y los usuarios externos que consulten la web pública.

- **Alcance del proyecto:**

  - **Ámbito físico y organizativo:** abarca las cuatro sedes (Alcoi, Barcelona, Madrid y Vigo), los dos edificios que forman cada sede, sus CPD (con 3 servidores físicos y 6 virtuales por sede) y todas las áreas de trabajo.
  - **Ámbito funcional:** cubre la infraestructura de red local e intersede, el almacenamiento compartido por departamentos, la gestión de usuarios, el sistema de incidencias del SAT, la monitorización y las copias de seguridad.
  - **Límites del alcance:** en esta fase se define la arquitectura funcional y los requisitos del sistema; no incluye todavía la compra de hardware, el direccionamiento IP exacto ni la implantación física, que se abordarán en las siguientes fases.

Se tendrá en cuenta la separación entre tres zonas:

- **Internet o zona pública:** servicios accesibles desde el exterior, como la web corporativa.

- **Extranet:** servicios destinados a clientes y colaboradores autorizados, como el portal de clientes.

- **Intranet:** servicios internos destinados exclusivamente al personal de CyberNova.


## 7. Características y requisitos del sistema

Para responder a las necesidades detectadas sin limitarse a enumerar tecnologías, se establecen los siguientes requisitos funcionales (RF) y no funcionales (RNF). Cada requisito indica la necesidad de la sección 4 que cubre, por qué se fija ese valor y una prueba concreta con resultado medible para comprobarlo:

| Código | Requisito | Necesidad que cubre | Justificación | Criterio de verificación (Cómo se comprueba) | Prioridad |
|---|---|---|---|---|---|
| **RF-01** | El sistema permitirá la comunicación privada entre las redes de Alcoi, Barcelona, Madrid y Vigo mediante enlaces privados cifrados con una latencia inferior a 50 ms. | Red entre sedes | Sin enlaces privados no se pueden compartir servicios entre sedes de forma segura. El cifrado protege los datos de clientes en tránsito por Internet y 50 ms permite usar con fluidez los servicios compartidos (directorio, tickets, monitorización) y la videoconferencia entre sedes. | Prueba de conectividad privada (ping e intercambio de archivos entre subredes de distintas sedes) verificando un 0 % de pérdida de paquetes, latencia < 50 ms y que la ruta (traceroute) viaja por el túnel privado. Además, una captura de tráfico en el enlace público debe mostrar solo tráfico cifrado (por ejemplo, ESP o equivalente) y ningún contenido legible. | Alta |
| **RF-02** | El sistema conectará los dos edificios de cada sede con enlaces de al menos 1 Gbps y ofrecerá cobertura Wi-Fi (WPA2/WPA3-Enterprise) en todas las áreas de trabajo. | Comunicaciones (acceso a los servicios del CPD desde ambos edificios) | Los servicios del CPD están en el Edificio 1 y se usan desde el Edificio 2 (Producción, comercial), por lo que 1 Gbps evita cuellos de botella con archivos de análisis y copias. Un nivel de señal ≥ -65 dBm es un umbral habitual para un uso fiable de voz y vídeo, y WPA2/WPA3-Enterprise identifica a cada usuario con sus credenciales corporativas. | Prueba de velocidad (iperf) en el enlace cableado entre Edificio 1 y 2 (≥ 1 Gbps) y medición del nivel de señal Wi-Fi ≥ -65 dBm en todas las estancias. En la configuración de los puntos de acceso se comprueba que usan WPA2/WPA3-Enterprise (802.1X) y se verifica que un equipo con credenciales corporativas se conecta y otro sin ellas es rechazado. | Media |
| **RF-03** | El sistema validará la identidad de los 30 usuarios mediante un directorio centralizado y restringirá el acceso a carpetas por departamento mediante listas de control de acceso (ACL). | Administración y RR. HH., Marketing y Comercial, Producción y Almacén | Recursos Humanos y Finanzas manejan datos personales y contables que deben protegerse (RGPD); limitar el acceso a cada departamento reduce accesos no autorizados y pérdidas de información. | Comprobar que existen las 30 cuentas en el directorio. Con un usuario de cada uno de los 4 departamentos: lee/escribe en la carpeta de su departamento y se bloquea el 100 % de los intentos de lectura/escritura en las carpetas de los otros 3 departamentos. | Alta |
| **RF-04** | El sistema dispondrá de una herramienta interna de tickets para registrar, asignar y cerrar incidencias técnicas con identificador único y seguimiento de estados. | SAT | Sin un registro centralizado de incidencias se producen pérdidas de información y retrasos en la resolución; registrar cada ticket en menos de 1 minuto evita que una incidencia se quede sin anotar. | Crear 10 tickets de prueba y comprobar que: cada uno recibe un identificador distinto, queda registrado en la base de datos en menos de 1 minuto, se notifica al técnico del SAT y su historial muestra los cambios de estado (*Abierta, En proceso, Cerrada*) con fecha y usuario. | Alta |
| **RF-05** | El sistema supervisará cada 60 segundos el estado de los servidores y enlaces de red, generando avisos automáticos en menos de 2 minutos ante caídas o consumo > 90 % de CPU/RAM. | Ciberseguridad e Informática (detección de incidentes) y Sala de vigilancia | Un sondeo de 60 s y un aviso en menos de 2 minutos reducen el tiempo en que una caída pasa desapercibida, y el umbral del 90 % permite actuar antes de que la saturación afecte a los servicios (RNF-01 y RNF-04). | Tres pruebas, cada una con alerta activa para SAT y Vigilancia en menos de 2 minutos: (1) detener un servidor virtual de prueba; (2) desactivar un enlace de red de prueba; (3) generar una carga artificial de CPU/RAM > 90 % en un servidor de prueba. | Alta |
| **RF-06** | El sistema ofrecerá una web corporativa pública bajo protocolo seguro HTTPS (TLS 1.3) y un portal de clientes (Extranet) con autenticación obligatoria y bloqueo tras 5 intentos fallidos. | Servicios externos y Marketing y Comercial | La web pública presenta los servicios de la empresa y la Extranet comparte informes con datos sensibles de clientes: TLS 1.3 protege la confidencialidad y el bloqueo tras 5 intentos dificulta los ataques de fuerza bruta. | Web: comprobar con una herramienta de análisis TLS (por ejemplo, `openssl s_client -tls1_3` o testssl.sh) que se negocia TLS 1.3 y que el certificado es válido. Extranet: el acceso sin credenciales es denegado; tras 5 intentos erróneos la cuenta se bloquea y un 6.º intento con la contraseña correcta también es rechazado durante el bloqueo. | Media |
| **RF-07** | El sistema realizará copias de seguridad automáticas (diaria incremental y semanal completa) garantizando un RPO ≤ 24 horas y un tiempo de recuperación (RTO) < 2 horas. | Seguridad de la información | Un RPO de 24 h limita la pérdida de datos a como máximo un día de trabajo y un RTO < 2 h limita la parada de los servicios; combinar copia completa semanal e incremental diaria equilibra el espacio usado y el tiempo de restauración. | (1) Revisar el registro de copias de 7 días seguidos: 6 incrementales y 1 completa finalizadas sin errores. (2) Eliminar de forma simulada una carpeta departamental y restaurar el 100 % de sus archivos desde la última copia (con antigüedad < 24 h) en menos de 2 horas. | Alta |
| **RNF-01** | El CPD de cada sede distribuirá los servicios alojando 6 servidores virtuales sobre 3 servidores físicos (2 MV por nodo en condiciones normales) sin superar el 50 % de carga media de CPU/RAM por host, de modo que si un host falla los otros dos puedan asumir las 6 MV sin superar el 80 %. | Infraestructura del CPD | Con 3 hosts al 50 %, la caída de uno lleva a los otros dos a un 75 %, por debajo del 80 %. Así la infraestructura propuesta aguanta un fallo sin saturarse, lo que además hace posible cumplir RNF-04. | Verificación en el hipervisor de que las 6 máquinas virtuales operan repartidas entre los 3 servidores físicos con una carga media ≤ 50 %. Después, poner un host en mantenimiento y comprobar que las 6 MV siguen funcionando en los otros dos con una carga ≤ 80 %. | Alta |
| **RNF-02** | La red estará segmentada mediante VLANs (estándar IEEE 802.1Q) con subredes IP diferenciadas para cada departamento, el CPD, la sala de vigilancia y la red Wi-Fi. | Seguridad de la información y Administración y RR. HH. | Separar los departamentos, el CPD, la vigilancia y el Wi-Fi limita que un equipo comprometido llegue a otras zonas y reduce los accesos indebidos a información de otros departamentos. | Comprobar en la configuración de los switches que existe una VLAN por cada segmento indicado. Desde un equipo de una VLAN, probar la conexión hacia otra VLAN: debe bloquearse salvo en los puertos de una lista de excepciones documentada, revisando también las reglas de firewall y las tablas de enrutamiento. | Alta |
| **RNF-03** | Las zonas de Internet, Extranet (DMZ) e Intranet estarán aisladas mediante un firewall perimetral con política por defecto de denegación (*Deny All*) para conexiones entrantes hacia la Intranet. | Servicios externos y Seguridad de la información | La web y la Extranet son accesibles desde fuera; si se comprometen, el firewall impide que el atacante llegue a la Intranet donde está la información interna. | Escaneo de puertos (por ejemplo, con nmap) desde Internet y desde la Extranet hacia el rango IP de la Intranet, comprobando que el 100 % de los intentos de conexión directa son rechazados y que los servicios públicos autorizados (por ejemplo, HTTPS de la web) siguen accesibles. | Alta |
| **RNF-04** | Los equipos críticos del CPD contarán con Sistemas de Alimentación Ininterrumpida (SAI) con autonomía ≥ 30 minutos a plena carga y alta disponibilidad (migración o reinicio automático de MV entre hosts) para garantizar una disponibilidad ≥ 99,9 % de los servicios críticos (como máximo unos 43 minutos de indisponibilidad al mes). | Disponibilidad y CPD | 30 minutos permiten un apagado ordenado o esperar la recuperación del suministro, y el 99,9 % es necesario para ofrecer servicios con suscripción (como la monitorización gestionada) y para que los clientes confíen en la empresa. | (1) Simulación de corte eléctrico: el SAI mantiene el CPD encendido ≥ 30 min. (2) Apagado de 1 servidor físico: las MV críticas se migran o reinician en otro host sin pérdida de servicio. (3) Durante un periodo de pruebas de 30 días se mide con la monitorización (RF-05) que la indisponibilidad acumulada de los servicios críticos es ≤ 43 minutos. | Alta |
| **RNF-05** | La arquitectura permitirá ampliar al menos un 50 % el número de usuarios (hasta 45 empleados), equipos o servicios sin rediseñar la topología ni sustituir el hardware base. | Crecimiento de la empresa (todas las áreas) | La empresa prevé crecer, y pasar de 30 a 45 empleados no debe obligar a rediseñar la red ni a comprar de nuevo el hardware base. | Verificación técnica de que: cada subred VLAN dispone de al menos un 50 % de direcciones IP libres; las bocas de switch de acceso libres son ≥ 33 % del total (suficientes para 15 usuarios más); y hay ≥ 30 % de almacenamiento libre en el CPD. | Media |
