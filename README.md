# CyberNova – Diseño de Infraestructura Empresarial de Ciberseguridad

CyberNova es un proyecto académico de diseño de una infraestructura empresarial para una compañía especializada en **ciberseguridad**, **análisis forense digital**, **pentesting**, **auditorías de seguridad** y **Big Data aplicado a la detección de amenazas**.

El objetivo del proyecto es diseñar una infraestructura escalable, segura y preparada para operar desde múltiples sedes, manteniendo la protección de la información y la continuidad del servicio.

## Objetivos del proyecto

- Diseñar una infraestructura distribuida entre cuatro sedes.
- Implementar una arquitectura segura basada en segmentación de red.
- Definir un CPD con servidores físicos y virtualizados.
- Separar los servicios en Internet, Extranet e Intranet.
- Garantizar comunicaciones privadas entre sedes.
- Preparar una base para futuras implantaciones de servicios empresariales.

## Información general

| Característica | Detalle |
|---|---|
| Empresa | CyberNova |
| Sector | Ciberseguridad e Informática |
| Sedes | Alcoi, Barcelona, Madrid y Vigo |
| Trabajadores | 30 |
| Infraestructura | 4 sedes y 2 edificios por sede |
| CPD por sede | 3 servidores físicos y 6 servidores virtuales |

## Organización de las sedes

Cada sede dispone de dos edificios con funciones diferenciadas.

### Edificio 1

- Recepción
- Gerencia y Administración
- Departamento SAT
- Centro de Procesamiento de Datos (CPD)
- Red Wi-Fi corporativa

### Edificio 2

- Sala de vigilancia
- Departamento Comercial
- Producción
- Almacén
- Red Wi-Fi corporativa

Los cuatro emplazamientos mantienen una estructura homogénea para facilitar la administración y la comunicación entre sedes.

## Departamentos

| Departamento | Función principal | Trabajadores |
|---|---|---:|
| Ciberseguridad e Informática | Pentesting, análisis forense, auditorías, Big Data, soporte técnico y protección de sistemas | 18 |
| Recursos Humanos | Contratación, gestión de personal y formación interna | 4 |
| Finanzas y Administración | Contabilidad, facturación y presupuestos | 4 |
| Marketing y Comunicación | Imagen corporativa, campañas y comunicación con clientes | 4 |
| **Total** | | **30** |

## Arquitectura de la infraestructura

La infraestructura está diseñada para operar desde cuatro sedes interconectadas mediante redes privadas.

### Esquema lógico inicial

```text
Internet
    |
[Firewall perimetral]
    |
    +-- DMZ
    |    +-- Web corporativa
    |    +-- Portal de clientes
    |
    +-- Intranet
         +-- VLAN Administración
         +-- VLAN Ciberseguridad
         +-- VLAN Comercial
         +-- VLAN Producción
         +-- VLAN SAT
         +-- VLAN Wi-Fi corporativa
         +-- CPD
              +-- 3 servidores físicos
              +-- 6 servidores virtuales
```

Este esquema es una propuesta inicial de organización lógica. La topología definitiva, las VLAN y la ubicación de cada servicio se concretarán durante las siguientes fases del proyecto.

## Centro de Procesamiento de Datos (CPD)

Cada sede incorporará un CPD con:

- 3 servidores físicos.
- 6 servidores virtuales.
- Almacenamiento de datos.
- Copias de seguridad.
- Monitorización.
- Mecanismos de recuperación ante fallos.

La virtualización permitirá distribuir los servicios de forma eficiente y simplificar su administración. La función exacta de cada servidor virtual se definirá durante la fase de diseño.

## Segmentación de red

La red se organizará en distintas zonas con diferentes niveles de acceso.

| Zona | Uso previsto | Acceso |
|---|---|---|
| Internet | Acceso a servicios públicos | Público |
| DMZ | Servicios expuestos al exterior | Según reglas del firewall |
| Extranet | Portal de clientes y documentación contratada | Clientes y colaboradores autorizados |
| Intranet | Documentación y herramientas internas | Personal autorizado |
| CPD | Servidores y servicios críticos | Administradores y usuarios autorizados |

La separación entre redes permitirá aplicar políticas específicas y reducir la exposición de los servicios internos.

## Servicios previstos

### Servicios internos

- Gestión centralizada de usuarios y permisos.
- Almacenamiento compartido.
- Correo y comunicación corporativa.
- Copias de seguridad.
- Monitorización de sistemas.
- Gestión de incidencias del SAT.
- Centralización de registros y alertas de seguridad.
- Aplicaciones de gestión para los distintos departamentos.

### Servicios públicos y de extranet

- Web corporativa con información sobre la empresa.
- Portal de clientes.
- Consulta segura de informes y documentación contratada.

Los servicios se distribuirán entre la zona pública, la Extranet y la Intranet según el tipo de usuario y los permisos necesarios.

## Medidas de seguridad previstas

- Segmentación de red mediante VLAN.
- Firewall perimetral.
- Control de acceso según usuarios y funciones.
- Monitorización de registros y alertas.
- Copias de seguridad periódicas.
- Protección de los datos almacenados.
- Acceso restringido a los servicios internos.
- Planificación de recuperación ante incidencias.
- Evaluación de herramientas SIEM para centralizar y analizar eventos de seguridad.

Estas medidas forman parte del diseño previsto; no implican que estén ya implementadas.

## Tecnologías previstas

- Sistemas basados en Linux para determinados servicios.
- Virtualización de servidores.
- Redes privadas entre sedes.
- VLAN y segmentación de red.
- Firewall y controles de acceso.
- Monitorización y herramientas SIEM.
- Servicios corporativos internos y externos.

La selección definitiva de sistemas operativos, equipos y plataformas se realizará en fases posteriores.

## Estructura propuesta del repositorio

```text
CyberNova/
├── README.md
├── docs/
│   ├── infraestructura-red.md
│   ├── analisis-necesidades.md
│   ├── arquitectura-cpd.md
│   ├── segmentacion-vlan.md
│   ├── seguridad.md
│   └── servicios.md
└── diagrams/
    ├── topologia-general.png
    ├── cpd.png
    └── vlan.png
```

## Hoja de ruta

- [x] Definición inicial de la empresa.
- [x] Análisis inicial de necesidades.
- [x] Propuesta general de infraestructura.
- [ ] Diseño del direccionamiento IP.
- [ ] Diseño detallado de VLAN y reglas de comunicación.
- [ ] Planificación de los servidores físicos y virtuales.
- [ ] Diseño de la conectividad privada entre sedes.
- [ ] Planificación de firewall y DMZ.
- [ ] Diseño de copias de seguridad y recuperación.
- [ ] Planificación de monitorización y SIEM.
- [ ] Documentación técnica de la infraestructura.

## Autor

**Andreu Sánchez Ferre**

- GitHub: [dr3wh4k](https://github.com/dr3wh4k/)
- LinkedIn: [andreusanchezferre](https://linkedin.com/in/andreusanchezferre/)

---

> **Nota:** CyberNova y su infraestructura forman parte de un proyecto académico. Los elementos indicados como previstos o propuestos están pendientes de diseño detallado o implementación.
