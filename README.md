**AJF Technology: Plataforma de hosting web** 🌐💻
## 1. **Idea seleccionada 🧑‍💻**

El proyecto tiene como objetivo la creación de un servidor web en un sistema operativo Linux (Ubuntu) y el alojamiento de un sitio web dinámico. Este proyecto consiste en la creación de un servicio de alojamiento web similar a plataformas como **CDmon**, para satisfacer la necesidad de los usuarios de alojar sus páginas web. Además, se desarrollará una **página web corporativa** utilizando **HTML**, **CSS** y **JavaScript**, e incorporará prácticas de seguridad como la implementación de un **firewall** 🔒 y análisis de seguridad con **pentesting** 🕵️‍♂️ (incluyendo **Burp Suite**).

## 2. **Objetivos 🎯**

Los objetivos del proyecto son los siguientes:

- Configurar un servidor web en Linux con **Nginx** 🖥️.
- Crear y alojar un sitio web dinámico utilizando **HTML**, **CSS** y **JavaScript** 💡.
- Implementar una base de datos **MySQL** para gestionar la información 📊.
- Administrar el servidor de manera sencilla mediante **Webmin** 🛠️.
- Instalar y configurar **PHP** para el procesamiento dinámico de contenido.
- Configurar **DNS** para la correcta resolución de dominios 🌐.
- Instalar un **certificado SSL** para asegurar la transmisión de datos 🔐.
- Desarrollar una **página web corporativa** con tecnologías web modernas.
- Asegurar el servidor mediante un **firewall** (**Sophos**) 🔒.
- Realizar **pruebas de penetración** con herramientas como **Burp Suite** 🛠️.
- Analizar el tráfico de red utilizando **Wireshark** para mejorar la seguridad y el rendimiento 🐟.

## 3. **Módulos del ciclo que tienen relación con el proyecto 📚**

- **Módulo 1: Serveis de xarxa**  
  Este módulo está directamente relacionado con la configuración y gestión de servidores web, así como con la administración de redes para garantizar la disponibilidad y seguridad del sitio web. La implementación de un **firewall** 🔒 y el análisis de tráfico de red 🐟 son aspectos clave dentro de este módulo.

- **Módulo 2: Aplicacions web**  
  Aquí se abordan temas como la creación de sitios web estáticos y dinámicos con **HTML**, **CSS** y **JavaScript**, la personalización de sitios web y la implementación de bases de datos **MySQL**. Además, se incluyen conceptos sobre la seguridad web, como el uso de **certificados SSL** 🔐 y pruebas de penetración 🕵️‍♂️.

- **Módulo 3: Sistemes operatius en xarxa**  
  Este módulo se relaciona con la instalación y configuración de sistemas operativos como **Ubuntu Server** y **Kali Linux** en las máquinas virtuales. Se aprende a utilizar un nuevo sistema operativo (**Kali**) y aplicar los conocimientos adquiridos en clase en **Ubuntu Server**.

### 4. **Materiales necesarios 🛠️**

**Materiales físicos**:
- Ordenadores para ejecutar sistemas operativos Linux en máquinas virtuales 💻.
- Conexión a Internet para descargar el software necesario y mantener actualizaciones 🌐.

**Materiales lógicos**:
- **Sistema operativo**: **Ubuntu**.
- **Servidor web**: **Nginx**.
- **Base de datos**: **MySQL** (si se requiere).
- **Editor de código**: **VSCode** o **Sublime Text** 📝.
- **Certificado SSL** para asegurar la comunicación entre el servidor y los usuarios 🔐.
- **Herramientas de seguridad**:
  - **Firewall**: Para proteger el servidor y los datos 🔒.
  - **Pentesting**: Herramientas como **Burp Suite** 🕵️‍♂️ para pruebas de penetración.
  - **Wireshark**: Para analizar el tráfico de red y garantizar la seguridad 🐟.

## 5. **Justificación de la elección de la idea 💡**

Este proyecto tiene como objetivo crear una plataforma de **hosting web** 🖥️ donde los usuarios puedan alojar sus sitios web. Para ello, se aprenderá a configurar y administrar servidores web con **Linux** y **Nginx**, desarrollar sitios web dinámicos utilizando **HTML**, **CSS**, **JavaScript** y **PHP**, gestionar bases de datos con **MySQL**, asegurar el servidor mediante un **firewall** 🔒, y realizar pruebas de penetración con **Burp Suite** 🛠️. Además, se analizará el tráfico de red con **Wireshark** 🐟 para mejorar la seguridad.

## 6. **Máquinas virtuales necesarias 🖥️**

Se utilizarán 6 máquinas virtuales para este proyecto:

1. **Servidor Web (Nginx)**: Esta máquina será responsable de alojar y servir el sitio web dinámico utilizando el servidor web **Nginx** 🖥️.
2. **Servidor de Base de Datos (MySQL)**: En esta máquina se instalará **MySQL**, que gestionará todas las bases de datos necesarias para el funcionamiento del sitio web 📊.
3. **Ubuntu Firewall (Sophos)**: Esta máquina actuará como un **firewall** para proteger todas las máquinas del proyecto, gestionando el tráfico de red y ofreciendo protección mediante **Sophos** 🔒. También se encargará de la asignación de direcciones IP mediante **DHCP**.
4. **Ubuntu DNS**: Esta máquina se configurará para gestionar el **DNS** (Sistema de Nombres de Dominio), permitiendo la correcta resolución de nombres de dominio a direcciones IP 🌐.
5. **Kali Linux (Pentesting y Burp Suite)**: En esta máquina se instalará **Kali Linux**, un sistema operativo diseñado para pruebas de penetración. Usaremos herramientas como **Burp Suite** 🛠️ para realizar pruebas de seguridad y encontrar vulnerabilidades en el servidor web.
6. **Ubuntu con TrueNAS**: Esta máquina se configurará para gestionar las **copias de seguridad** del proyecto 💾.

## 7. **Recursos 📚**

- **Bibliografía**: (Aquí puedes incluir libros o fuentes académicas relacionadas).
- **Webgrafía**: (Incluir links a tutoriales o documentación relevante).
- **Vídeos**: (Incluir enlaces a tutoriales visuales o conferencias).
- **Cursos**: (Cursos recomendados para reforzar los conocimientos adquiridos).

## 8. **Consideraciones finales 🎯**

Este proyecto no solo se enfoca en la creación de un servidor web, sino que también implementa medidas de seguridad 🔒 como el uso de un **firewall**, **pruebas de penetración** 🕵️‍♂️ y análisis de tráfico con **Wireshark** 🐟, asegurando sitios web funcionales y protegidos.

---

## **Roles y Tareas del Equipo** 👥

- **Alejandro (Encargado del Firewall y GitHub)** 🔐  
  - **FIREWALL**: Configuración y gestión del firewall para proteger el servidor.
  - **PENTESTING**: Realización de pruebas de penetración usando herramientas como **Burp Suite**.
  - **GITHUB**: Gestión del repositorio y control de versiones del proyecto.
  - **WEB CORPORATIVA**: Colaboración en el desarrollo de la página web corporativa.

- **Jiajie (Encargado del Diseño Web)** 🎨  
  - **MySQL**: Configuración y administración de la base de datos **MySQL**.
  - **TRELLO**: Gestión de tareas y planificación del proyecto usando **Trello**.
  - **DIAGRAMAS**: Creación de diagramas (como diagrama de Gantt) y diagramas de arquitectura de la web.

- **Felipe (Encargado de la red)** 🌐  
  - **DNS**: Configuración y gestión del **DNS** para asegurar la correcta resolución de dominios.
  - **WEBMIN**: Administración del servidor mediante **Webmin** para facilitar la gestión de los servicios.
