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

## 5. Problemas y oportunidades de mejora

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
- **Alcance inicial:** diseño de redes, CPD, servidores físicos y virtuales, sistemas operativos, servicios de red, seguridad y mecanismos básicos de monitorización.

Se tendrá en cuenta la separación entre tres zonas:

- **Internet o zona pública:** servicios accesibles desde el exterior, como la web corporativa.
- **Extranet:** servicios destinados a clientes y colaboradores autorizados, como el portal de clientes.
- **Intranet:** servicios internos destinados exclusivamente al personal de CyberNova.

En esta primera fase se realizará el análisis y el diseño general. La selección definitiva de equipos, el direccionamiento IP, las configuraciones y la implantación se desarrollarán progresivamente en las siguientes actividades.
