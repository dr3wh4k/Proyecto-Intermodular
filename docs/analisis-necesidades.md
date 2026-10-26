# Bloque 3: Detección de Necesidades

Una vez analizada la estructura organizativa y la visión estratégica de **Cybernova Analitics**, se presenta el análisis detallado de las necesidades funcionales de cada departamento. 

El objetivo de este bloque es **identificar los problemas y riesgos operacionales** existentes antes de pasar a la selección de las soluciones técnicas definitivas.

---

## Metodología de Análisis

Para garantizar el correcto funcionamiento de la empresa y la continuidad de sus operaciones, se han evaluado las necesidades operativas de los cuatro departamentos corporativos (**Finanzas y Administración**, **Ciberseguridad e Informática**, **Recursos Humanos**, y **Marketing y Comunicación**), así como las necesidades transversales que afectan a toda la organización.

Cada necesidad se ha clasificado con un nivel de prioridad:
* **Alta:** Imprescindible para la operatividad, la continuidad del negocio, la seguridad o el cumplimiento legal.
* **Media:** Importante para la optimización de procesos internos, la colaboración y la productividad.
* **Baja:** Deseable para la mejora continua de flujos secundarios.

---

## Matriz de Necesidades por Departamento

| Departamento | Necesidad detectada | Problema o riesgo | Prioridad |
| :--- | :--- | :--- | :---: |
| **Finanzas y Administración** | Almacenar y compartir documentación financiera, presupuestos y facturas de forma centralizada y estructurada. | Duplicidad de documentos, desorganización y pérdida potencial de registros económicos críticos. | **Alta** |
| **Finanzas y Administración** | Controlar mediante permisos el acceso a la información contable, fiscal y estratégica. | Accesos no autorizados e incumplimiento de políticas de confidencialidad interna. | **Alta** |
| **Ciberseguridad e Informática** | Supervisar de forma continua servidores, servicios corporativos, red interna y plataformas de Big Data/SIEM. | Fallos técnicos o incidentes de seguridad no detectados a tiempo, provocando indisponibilidad de servicio. | **Alta** |
| **Ciberseguridad e Informática** | Segmentar y aislar lógicamente los laboratorios de prueba (pentesting y análisis forense) de la red corporativa. | Contaminación accidental de la red interna por ejecuciones de malware o pruebas de penetración. | **Alta** |
| **Recursos Humanos** | Centralizar la gestión de expedientes de personal, nóminas, contratos y el registro diario de jornada laboral. | Pérdida de datos confidenciales de empleados y sanciones legales por incumplimiento normativo (RGPD/Control horario). | **Media** |
| **Recursos Humanos** | Gestionar y hacer seguimiento del plan de formación interna y renovación de certificaciones técnicas. | Descontrol sobre el cumplimiento del objetivo del 100% de personal certificado cada 18 meses. | **Media** |
| **Marketing y Comunicación** | Almacenar y colaborar en la creación de material multimedia, notas de prensa y contenidos del blog técnico. | Uso de servicios en la nube no autorizados (Shadow IT) y pérdida o descontrol de activos digitales corporativos. | **Media** |
| **Transversal (Toda la entidad)** | Disponer de un sistema automático de copias de seguridad redundantes y sistemas de alimentación ininterrumpida. | Pérdida irreparable de datos sensibles de clientes (evidencias forenses, auditorías) e interrupción por fallos eléctricos. | **Alta** |
| **Transversal (Toda la entidad)** | Separar el tráfico de red de los distintos departamentos y desplegar una red Wi-Fi corporativa y de invitados de forma segura. | Intercepción de tráfico confidencial entre áreas y vectores de entrada a la red corporativa a través de dispositivos no autorizados. | **Alta** |

---

## Próximos Pasos

A partir de las necesidades detectadas en este documento, se procederá en los siguientes bloques al **diseño y arquitectura técnica**, donde se definirán las herramientas, infraestructura hardware, direccionamiento de red, políticas de seguridad y servicios de TI específicos que resolverán cada uno de los riesgos identificados.
