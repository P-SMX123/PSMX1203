# 1.	Matriz de requisitos y funcionalidades
   
| **ID**  | **Prioridad** | **Objetivo**                               | **Funcionalidad**                                                                                                  | **Fecha Entrega** | **Estado**  |
|---------|---------------|--------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------|-------------|
| **ID0** | Media         | Registrar usuarios                        | Crear un sistema para que los usuarios se registren con su correo, contraseña y guardar los datos de forma segura. | ??/??/????         | Pendiente   |
| **ID1** | Alta          | Login y autenticación de usuarios         | Permitir que los usuarios inicien sesión con su correo y contraseña de forma segura.                               | ??/??/????         | Pendiente   |
| **ID2** | Alta          | Administración de páginas web             | Los usuarios podrán crear, editar o borrar sus páginas web fácilmente.                                            | ??/??/????         | Pendiente   |
| **ID3** | Alta          | Subir archivos web                        | Dejar que los usuarios suban archivos como HTML, CSS, imágenes, etc, para su página web.                         | ??/??/????         | Pendiente   |
| **ID4** | Media         | Base de datos y conexión MySQL            | Configurar la base de datos para guardar toda la información de los usuarios y sus páginas web.                    | ??/??/????         | Pendiente   |
| **ID5** | Alta          | Implementar firewall y medidas de seguridad | Instalar un firewall para proteger el servidor y hacer pruebas de seguridad.                                        | ??/??/????         | Pendiente   |
| **ID6** | Media         | Análisis de tráfico de red con Wireshark  | Revisar el tráfico de la red con Wireshark para encontrar problemas de seguridad o rendimiento.                     | ??/??/????         | Pendiente   |
| **ID7** | Baja          | Crear página web corporativa              | Hacer una página web para explicar qué es la plataforma de hosting y qué servicios ofrece.                         | ??/??/????         | Pendiente   |
| **ID8** | Alta          | Configuración de SSL y seguridad de la web | Configurar SSL para que las páginas web sean seguras y usen HTTPS.                                                 | ??/??/????         | Pendiente   |
| **ID9** | Baja          | Implementación de sistema de copias de seguridad | Crear un sistema de copias de seguridad para que los datos estén protegidos.                                        | ??/??/????         | Pendiente   |


# Arquitectura del sistema:

| **Componente de sistema**     | **Tecnología o framework** | **Versión** | **Puerto** | **Descripción de uso o requisitos**                                                          | **Enlace a documentación**        |
|-------------------------------|----------------------------|-------------|------------|---------------------------------------------------------------------------------------------|-----------------------------------|
| **Hardware**                   | Optiplex 7490 AIO Intel core i7-11700, 16 GB RAM, 400 GB disco | -           | -          | Servidor virtualizado con recursos adecuados para el proyecto.                             | Enlace a documentación           |
| **Sistema operativo**          | Ubuntu Server              | 20.04 LTS   | -          | Ubuntu Server será el sistema operativo base del servidor.                                  | Documentación Ubuntu Server      |
| **Interfaz de usuario (Frontend)** | HTML, CSS, JavaScript (con Bootstrap) | HTML5, CSS3, ES6 | -          | Capa visual interactiva usando tecnologías estándar web y diseño responsivo.               | Documentación HTML, Bootstrap    |
| **Lógica de negocio (Backend)** | PHP                        | 8.0+        | -          | PHP procesará el contenido dinámico y generará páginas interactivas.                        | Documentación PHP                |
| **Servidor web**               | Nginx                      | 1.18+       | 80 (HTTP), 443 (HTTPS) | Nginx gestionará las solicitudes HTTP/HTTPS y mejorará la eficiencia del servidor.         | Documentación Nginx              |
| **Base de datos**              | MySQL                      | 8.0+        | 3306       | MySQL almacenará datos como usuarios y contenido web.                                        | Documentación MySQL              |
| **Sistema gestor de base de datos** | phpMyAdmin                | 5.1.0+      | 80 (HTTP)  | phpMyAdmin permitirá gestionar la base de datos MySQL de manera remota.                     | Documentación phpMyAdmin         |
| **Servicios de APIs**          | REST API                   | -           | -          | API REST permitirá la comunicación eficiente entre frontend y backend con datos en JSON.    | Documentación REST               |
| **Seguridad**                  | SSL (Let's Encrypt)        | -           | -          | SSL cifrará las conexiones entre cliente y servidor para proteger los datos.                | Documentación Let's Encrypt      |
| **Firewall**                   | Sophos Firewall            | -           | -          | Sophos Firewall protegerá el servidor de accesos no autorizados y ataques de red.           | Documentación Sophos             |
| **Análisis de tráfico**        | Wireshark                  | 3.4.0+      | -          | Wireshark monitoreará el tráfico de red para detectar problemas de seguridad o rendimiento.  | Documentación Wireshark          |
| **Copias de seguridad**        | TrueNAS                    | 12.0+       | -          | TrueNAS gestionará las copias de seguridad del servidor para proteger los datos.            | Documentación TrueNAS            |
