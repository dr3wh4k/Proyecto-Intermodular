# A1. Análisis de la empresa y definición del proyecto

## 1. Descripción de la empresa

CyberNova es una empresa del sector de la informática y la ciberseguridad que ofrece servicios destinados a proteger los sistemas informáticos y los datos de otras empresas.

Sus principales actividades son el análisis forense digital, las auditorías de seguridad, las pruebas de penetración o pentesting, la formación en ciberseguridad y el análisis de grandes volúmenes de datos para detectar posibles amenazas.

La empresa utiliza tecnologías de análisis de datos para mejorar la detección de incidentes, anticiparse a los ataques y reducir el tiempo necesario para responder ante problemas de seguridad.

- **Misión:** proteger los sistemas y datos de los clientes mediante servicios de ciberseguridad, análisis forense, auditorías y formación.
- **Visión:** convertirse en una empresa de referencia en ciberseguridad, ofreciendo servicios fiables y mejorando continuamente sus sistemas y métodos de trabajo.
- **Clientes:** grandes empresas, corporaciones y pymes con necesidades tecnológicas y de seguridad avanzadas.
- **Tamaño:** el plan empresarial inicial contempla una plantilla de 30 trabajadores. La distribución concreta entre las cuatro sedes queda pendiente de definir.

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

| Departamento | Trabajadores |
|---|---:|
| Ciberseguridad e Informática | 18 |
| Recursos Humanos | 4 |
| Finanzas y Administración | 4 |
| Marketing y Comunicación | 4 |
| **Total** | **30** |

La sala de vigilancia estará relacionada especialmente con la supervisión de la seguridad y el funcionamiento de la infraestructura. El departamento SAT atenderá incidencias y necesidades de soporte técnico. Las zonas de producción y almacén facilitarán el desarrollo de los servicios y la gestión del material informático.

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

Para responder a las necesidades detectadas sin limitarse a enumerar tecnologías, se establecen los siguientes requisitos funcionales (RF) y no funcionales (RNF) verificables:

| Código | Requisito | Necesidad que cubre | Criterio de verificación (Cómo se comprueba) | Prioridad |
|---|---|---|---|---|
| **RF-01** | El sistema permitirá la comunicación privada entre las redes de Alcoi, Barcelona, Madrid y Vigo. | Red entre sedes | Comprobación de conectividad privada (ping y acceso a recursos) entre equipos de distintas sedes sin salir a red pública. | Alta |
| **RF-02** | El sistema conectará los dos edificios de cada sede y ofrecerá cobertura Wi-Fi en todas las áreas de trabajo. | Comunicaciones y movilidad | Conexión exitosa de dispositivos por cable y Wi-Fi tanto en el Edificio 1 como en el Edificio 2. | Media |
| **RF-03** | El sistema validará la identidad de los usuarios de forma centralizada y restringirá el acceso a carpetas según su departamento. | Administración, RR. HH., Marketing y Producción | Un usuario autenticado accede a los recursos de su departamento, pero recibe denegación de acceso al intentar abrir carpetas de otra área. | Alta |
| **RF-04** | El sistema dispondrá de una herramienta interna para registrar, asignar y cerrar incidencias técnicas. | SAT | Un trabajador registra una incidencia de prueba y el personal del SAT puede visualizarla, actualizarla y cerrarla. | Alta |
| **RF-05** | El sistema supervisará el estado de los servidores y enlaces de red, generando avisos ante fallos o caídas. | Ciberseguridad, Informática y Sala de vigilancia | Al detener un servicio o servidor virtual de prueba, el panel de supervisión registra el fallo y muestra una alerta activa. | Alta |
| **RF-06** | El sistema ofrecerá una web corporativa pública y un portal de clientes (Extranet) con acceso mediante usuario y contraseña. | Servicios externos y Comercial | Acceso libre a la web pública desde cualquier navegador y exigencia obligatoria de credenciales para consultar informes en la Extranet. | Media |
| **RF-07** | El sistema realizará copias de seguridad periódicas de la documentación y datos de los departamentos. | Seguridad de la información | Eliminación simulada de un documento compartido y recuperación íntegra del mismo a partir de la última copia almacenada. | Alta |
| **RNF-01** | El CPD de cada sede distribuirá los servicios alojando 6 servidores virtuales sobre 3 servidores físicos. | Infraestructura del CPD | Verificación en la consola de virtualización de que las 6 máquinas virtuales se ejecutan repartidas entre los 3 servidores físicos. | Alta |
| **RNF-02** | La red estará segmentada separando el tráfico de los distintos departamentos, el CPD y la red inalámbrica. | Seguridad de la información | Comprobación de que los equipos de diferentes áreas están en subredes/VLAN distintas y su tráfico pasa por reglas de control. | Alta |
| **RNF-03** | Las zonas de Internet, Extranet e Intranet estarán aisladas entre sí mediante control de acceso perimetral. | Servicios externos y Seguridad | Verificación de que un usuario externo conectado a la web o a la Extranet no puede establecer conexión directa con equipos de la Intranet. | Alta |
| **RNF-04** | Los equipos críticos del CPD contarán con protección frente a cortes eléctricos y mecanismos de recuperación ante fallos. | Disponibilidad y CPD | Ante la caída de un servidor físico o corte de suministro simulado, los servicios esenciales se mantienen o se restablecen sin pérdida de datos. | Alta |
| **RNF-05** | La arquitectura permitirá ampliar al menos un 50 % el número de usuarios, equipos o servicios sin rediseñar el sistema. | Crecimiento de la empresa | Existencia de margen libre en los rangos de red asignados y capacidad de hardware/almacenamiento disponible para nuevas ampliaciones. | Media |
