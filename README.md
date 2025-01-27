# **AJF Technology: Plataforma de hosting web** 🌐💻
## 1. **Idea seleccionada** 🧑‍💻

El proyecto tiene como objetivo la creación de un servidor web en un sistema operativo **Linux (Ubuntu)** y el alojamiento de un sitio web dinámico. Este proyecto consiste en la creación de un servicio de alojamiento web similar a **cdmon**, para abordar la necesidad de los usuarios de alojar sus páginas web. Además, se incluirá una página web corporativa desarrollada con **HTML**, **CSS** y **JavaScript** y se incorporarán prácticas de seguridad, como la implementación de un **firewall** 🔒 y análisis de seguridad mediante **pentesting** 🕵️‍♂️ (incluyendo **Burp Suite**). También se analizará el tráfico de red usando **Wireshark** 🐟 para mejorar la seguridad y el rendimiento.


## 2. **Objetivos 🎯**

Los objetivos del proyecto son los siguientes:

- **Configurar un servidor web en Linux con Nginx** 🖥️.
- **Crear y alojar un sitio web dinámico** utilizando **HTML**, **CSS** y **JavaScript** 💡.
- **Implementar una base de datos MySQL** para gestionar la información 📊.
- **Administrar el servidor de manera sencilla** mediante **Webmin**.
- **Instalar y configurar PHP** para el procesamiento dinámico de contenido 🔧.
- **Configurar DNS** para la correcta resolución de dominios 🌐.
- **Instalar un certificado SSL** para asegurar la transmisión de datos 🔐.
- **Desarrollar una página web corporativa** con tecnologías web modernas.
- **Asegurar el servidor mediante un firewall** (**Sophos**) 🔒.
- **Realizar pruebas de penetración** con herramientas como **Burp Suite** 🛠️.
- **Analizar el tráfico de red** usando **Wireshark** para mejorar la seguridad y rendimiento 🐟.


## 3. **Listado de tareas 📝**

### Tareas por objetivo:

- **Configurar servidor web en Linux con Nginx**:
  - Instalación de **Ubuntu Server**.
  - Instalación y configuración de **Nginx**.
  - Configuración de **hosts virtuales** en **Nginx**.
  - Optimización de **Nginx** para rendimiento.

- **Crear y alojar un sitio web dinámico**:
  - Diseño y desarrollo de la página web en **HTML**, **CSS** y **JavaScript**.
  - Implementación de **PHP** para funcionalidades dinámicas.
  - Integración con **MySQL** para la gestión de datos.

- **Implementar seguridad**:
  - Configuración del **firewall Sophos**.
  - Instalación y pruebas de penetración con **Burp Suite**.
  - Monitoreo de tráfico de red con **Wireshark**.

- **Optimización y rendimiento**:
  - Ajustes de configuración de **PHP** y **MySQL**.
  - 

## 4. **Asignar roles y responsabilidades del equipo 👥**

- **Alejandro (Encargado del Firewall y GitHub)** 🔐:
  - **Firewall**: Configuración del **firewall Sophos**.
  - **Pentesting**: Realización de pruebas de penetración con **Burp Suite**.
  - **GitHub**: Gestión del repositorio de código y documentación.
  - **Web Corporativa**: Colaboración en el desarrollo y seguridad de la página web.

- **Jiajie (Encargado del Diseño Web)** 🎨:
  - **MySQL**: Implementación y gestión de la base de datos **MySQL**.
  - **Trello**: Gestión del proyecto en **Trello**.
  - **Diagramas**: Creación de diagramas de arquitectura y flujos de trabajo.

- **Felipe (Encargado de la Red)** 🌐:
  - **DNS**: Configuración del **DNS** para la correcta resolución de dominios.
  - **Webmin**: Administración del servidor mediante **Webmin**.
  - 

## 5. **Diagrama de la red 🌐**

El diagrama de la red debe mostrar las conexiones entre las máquinas virtuales y los servicios implementados:

- **Servidor Web (Nginx)**: Conectado al **Servidor de Base de Datos (MySQL)**.
- **Firewall (Sophos)**: Protege todos los servidores del tráfico no deseado.
- **Servidor DNS**: Resuelve nombres de dominio.
- **Servidor Webmin**: Administra el servidor de manera sencilla.
- **Kali Linux (Pentesting)**: Realiza las pruebas de penetración.
- **Wireshark**: Monitorea el tráfico de red para asegurar el rendimiento y la seguridad.


## 6. **Tecnologías a implementar 🛠️**

- **Ubuntu Server**: Para la gestión del servidor.
- **Nginx**: Para alojar y servir el contenido web.
- **PHP**: Para procesar contenido dinámico.
- **MySQL**: Para la gestión de bases de datos.
- **Webmin**: Para la administración del servidor.
- **Wireshark**: Para el análisis del tráfico de red.
- **Burp Suite**: Para pruebas de penetración.
- **TrueNAS**: Para la gestión de las copias de seguridad.
- **Sophos**: Para el firewall y protección de la red.


## 7. **Hardware a utilizar 🖥️**

**Máquinas virtuales**:
- **Servidor Web (Nginx)**: 
  - CPU: ? núcleos.
  - RAM: ? GB.
  - Almacenamiento: ? GB.

- **Servidor de Base de Datos (MySQL)**: 
  - CPU: ? núcleos.
  - RAM: ? GB.
  - Almacenamiento: ? GB.

- **Firewall (Sophos)**: 
  - CPU: ? núcleo.
  - RAM: ? GB.
  - Almacenamiento: ? GB.

- **Servidor DNS**: 
  - CPU: ? núcleo.
  - RAM: ? GB.
  - Almacenamiento: ? GB.

- **Kali Linux (Pentesting y Burp Suite)**: 
  - CPU: ? núcleos.
  - RAM: ? GB.
  - Almacenamiento: ?G B.

- **Servidor Webmin**: 
  - CPU: ? núcleo.
  - RAM: ? GB.
  - Almacenamiento: ? GB.


## 8. **Servicios a implementar 🚀**

- **Nginx**: Servir el contenido web dinámico.
- **MySQL**: Gestión de bases de datos.
- **Webmin**: Interfaz gráfica de administración.
- **DNS**: Resolución de dominios.
- **SSL**: Cifrado de la comunicación.
- **Sophos Firewall**: Protección contra ataques.
- **Pentesting (Burp Suite)**: Evaluación de la seguridad.
- **Wireshark**: Análisis del tráfico de red.
- **TrueNAS**: Gestión de copias de seguridad.


## 9. **Sistemas operativos a utilizar 🖥️**

- **Ubuntu Server 20.04 LTS**: Para las máquinas principales.
- **Kali Linux**: Para pruebas de penetración y seguridad.
- **Ubuntu Desktop** (opcional): Para tareas de desarrollo con interfaz gráfica.



## 10. **Diagrama de Gantt 📅**

| Fase/Actividad                      | Inicio   | Fin      | Responsable(s)       |
|--------------------------------------|----------|----------|----------------------|
| **Configuración del Servidor Web**   | 01/02/25 | 05/02/25 | **Alejandro** 🛠️    |
| **Desarrollo Web (HTML/CSS/JS)**     | 06/02/25 | 12/02/25 | **Jiajie** 🎨       |
| **Integración de Base de Datos**     | 13/02/25 | 17/02/25 | **Jiajie** 📊       |
| **Configuración de PHP y Webmin**    | 18/02/25 | 20/02/25 | **Felipe** 🌐       |
| **Pruebas de Seguridad (Pentesting)**| 21/02/25 | 23/02/25 | **Alejandro** 🕵️‍♂️ |
| **Análisis de Tráfico (Wireshark)**  | 24/02/25 | 26/02/25 | **Alejandro** 🐟   |
| **Optimización y Ajustes Finales**   | 27/02/25 | 28/02/25 | **Todos** 👥        |
| **Documentación en GitHub**          | 01/03/25 | 02/03/25 | **Todos** 📁        |

