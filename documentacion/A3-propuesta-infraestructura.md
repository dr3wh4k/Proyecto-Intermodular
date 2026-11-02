# A3. Propuesta general de la infraestructura

La propuesta consiste en diseñar un sistema informático empresarial basado en cuatro sedes conectadas, con una estructura similar en cada una y con servicios organizados según las necesidades de CyberNova.

## 1. Infraestructura física y hardware

Se contemplan los siguientes elementos:

- Servidores físicos para alojar los servicios virtualizados.
- Equipos cliente para los trabajadores.
- Switches y dispositivos de interconexión.
- Dispositivos de seguridad perimetral.
- Puntos de acceso Wi-Fi para las zonas de trabajo.
- Sistemas de almacenamiento y copias de seguridad.
- Sistemas de alimentación ininterrumpida (SAI) para proteger los equipos esenciales.

Se priorizarán equipos eficientes energéticamente, duraderos y ampliables, para aprovechar mejor los recursos y reducir los costes de mantenimiento.

## 2. Sistemas operativos y virtualización

La infraestructura contará con sistemas operativos adecuados para los servidores y los equipos cliente.

Se valorará el uso de sistemas basados en Linux para determinados servicios de servidor y entornos de ciberseguridad, así como sistemas compatibles con las aplicaciones de oficina que necesite la empresa.

La virtualización permitirá ejecutar seis servidores virtuales sobre los tres servidores físicos de cada sede, de acuerdo con el escenario establecido en el proyecto.

La elección concreta de los sistemas operativos y las plataformas de virtualización se realizará en las siguientes fases.

## 3. Redes y segmentación

La red de cada sede se organizará para separar las distintas áreas y controlar las comunicaciones entre ellas.

Se tendrán en cuenta:

- Las redes de los departamentos y zonas de trabajo.
- La red de servidores del CPD.
- Las redes Wi-Fi.
- La zona pública.
- La extranet.
- La intranet.
- La comunicación privada entre sedes.

Esta organización permitirá aplicar permisos y medidas de seguridad diferentes según la función de cada red. El direccionamiento IP y las configuraciones concretas se definirán en una fase posterior.

## 4. Seguridad y protección de la información

Como CyberNova trabaja en el sector de la ciberseguridad, la protección de su propia infraestructura será especialmente importante.

Se propone contemplar:

- Control de acceso a los sistemas.
- Segmentación de redes.
- Protección perimetral.
- Monitorización de registros y alertas.
- Copias de seguridad periódicas.
- Protección de los datos almacenados.
- Acceso restringido a los servicios internos.
- Medidas de recuperación ante incidencias.

También se estudiará la incorporación de herramientas SIEM y soluciones de análisis de registros para facilitar la detección de amenazas.

## 5. Aplicaciones y servicios empresariales

La infraestructura deberá dar soporte a las aplicaciones que necesiten los departamentos:

- Gestión administrativa y financiera.
- Gestión de recursos humanos.
- Gestión comercial y de clientes.
- Comunicación y colaboración.
- Gestión de incidencias del SAT.
- Herramientas de análisis de seguridad y Big Data.
- Web corporativa y portal de clientes.

La implantación se realizará progresivamente, empezando por los servicios básicos de red y sistemas y añadiendo después las aplicaciones y los servicios avanzados.

## 6. Disponibilidad, monitorización y crecimiento

El sistema deberá diseñarse para facilitar la detección de fallos y la recuperación de los servicios.

Para ello se valorarán las copias de seguridad, la monitorización, la redundancia de los componentes necesarios y la posibilidad de ampliar los recursos.

Estas medidas ayudarán a mantener los servicios disponibles y a reducir las interrupciones que puedan afectar al trabajo de los empleados o a la prestación de servicios a los clientes.

## Relación entre A1, A2 y A3

| Actividad | Qué aporta al proyecto |
|---|---|
| A1. Análisis de la empresa | Define qué es CyberNova, cómo se organiza, qué necesita y qué problema debe resolver el proyecto |
| A2. Análisis de necesidades y servicios | Identifica los servicios internos y externos, las necesidades de comunicación y la estructura de las cuatro sedes |
| A3. Propuesta general | Plantea la infraestructura física, las redes, los servidores, los sistemas, las aplicaciones y la seguridad necesarios |
