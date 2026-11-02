# A2. Análisis de necesidades y servicios del sistema

Esta parte recoge las necesidades de información y comunicación que deberá cubrir la infraestructura de CyberNova.

## 1. Servicios internos

La intranet deberá proporcionar servicios para los trabajadores de las cuatro sedes, con acceso limitado según el departamento y las funciones de cada usuario.

Servicios previstos:

- **Almacenamiento compartido:** guardar documentos y recursos corporativos.
- **Gestión de usuarios y permisos:** controlar quién puede acceder a cada servicio.
- **Correo corporativo y comunicación interna:** facilitar el trabajo entre departamentos.
- **Copias de seguridad:** recuperar información ante pérdidas o fallos.
- **Monitorización:** supervisar el estado de los sistemas y detectar incidencias.
- **Servicios de red:** permitir la comunicación correcta entre equipos y servidores.
- **Aplicaciones de gestión:** apoyar las tareas de administración, recursos humanos, finanzas y marketing.
- **Servicios de ciberseguridad:** centralizar registros, gestionar alertas y facilitar la investigación de incidentes.

## 2. Servicios públicos y de extranet

| Zona | Servicios previstos | Quién puede acceder |
|---|---|---|
| Pública | Web corporativa e información general de los servicios | Usuarios de Internet |
| Extranet | Portal de clientes, consulta de informes y acceso a documentación contratada | Clientes y colaboradores autorizados |
| Intranet | Gestión interna, documentación corporativa y herramientas de trabajo | Personal autorizado |

La separación de estas zonas permitirá reducir la exposición de los servicios internos y limitar el acceso a la información según el tipo de usuario.

## 3. Comunicación entre las cuatro sedes

Las sedes de Alcoi, Barcelona, Madrid y Vigo deberán comunicarse utilizando redes privadas.

El diseño tendrá que contemplar:

- Un direccionamiento IP que permita identificar correctamente las redes de cada sede.
- La comunicación entre las redes privadas de las distintas ubicaciones.
- El acceso a los servicios compartidos desde las sedes autorizadas.
- La separación de las redes según las funciones y necesidades de seguridad.
- La protección de las comunicaciones entre sedes.
- La posibilidad de supervisar y solucionar problemas de conectividad.

El objetivo es que un trabajador autorizado de una sede pueda acceder a un servicio situado en otra sede utilizando su dirección IP privada, sin exponer innecesariamente ese servicio a Internet.

## 4. Infraestructura de los CPD

Cada sede dispondrá de un CPD con **3 servidores físicos y 6 servidores virtuales**.

La virtualización permitirá distribuir los servicios en distintos servidores virtuales, aprovechando mejor los recursos físicos y facilitando la administración.

La planificación deberá tener en cuenta:

- La función de cada servidor virtual.
- Los recursos necesarios para ejecutar los servicios.
- El almacenamiento de datos.
- Las copias de seguridad.
- La protección de los servidores.
- La recuperación de los servicios en caso de fallo.
- La monitorización del funcionamiento.

La distribución exacta de los seis servidores virtuales se definirá en la fase de diseño, según los servicios que finalmente se asignen a cada sede.
