# **AJF Technology: Creación de un servidor web en linux y alojamiento de un sitio web**

## **1. Idea seleccionada **

El proyecto tiene como objetivo la creación de un **servidor web** en un sistema operativo **Linux** (Ubuntu) y el alojamiento de un sitio web dinámico. Este proyecto consiste en la creación de un alojamiento web como el cdmon, para abordar la necesidad de los usuarios de alojar sus paginas web. Además, se incluirá una **página web corporativa** desarrollada en **HTML**, **CSS** y **JavaScript** y se incorporarán prácticas de seguridad, como la implementación de un **firewall** y análisis de seguridad con **pentesting** (incluyendo **Burp Suite**).

## **2. Objetivos**

Los objetivos del proyecto son los siguientes:

- **Configurar un servidor web** en Linux utilizando **Nginx**.
- Crear y alojar un sitio web dinámico utilizando **HTML**, **CSS** y **JavaScript**.
- Implementar una **base de datos MySQL** para gestionar la información del sitio web, si es necesario.
- Asegurar el sitio web mediante la instalación de un **certificado SSL** para garantizar la seguridad de los datos transmitidos.
- Desarrollar una **página web corporativa** utilizando **HTML**, **CSS** y **JavaScript**.
- Proteger el servidor web mediante la instalación y configuración de un **firewall** (Sophos, pfSense).
- Realizar **pruebas de penetración** (**pentesting**) a través de herramientas como **Burp Suite** para detectar vulnerabilidades.
- Analizar el **tráfico de red** utilizando herramientas como **Wireshark** para garantizar la seguridad y el rendimiento del servidor.

## **3. Módulos del ciclo que tienen relación con el proyecto**

**Módulo 1: Administración de redes**  
Este módulo está directamente relacionado con la **configuración y gestión de servidores web**, así como con la **administración de redes** para garantizar la disponibilidad y seguridad del sitio web. La implementación de un **firewall** y el análisis de **tráfico de red** son aspectos esenciales dentro de este módulo.

**Módulo 2: Desarrollo de aplicaciones web**  
Aquí se abordan temas como la creación de **sitios web estáticos o dinámicos** con **HTML**, **CSS** y **JavaScript**, la personalización de sitios web y la implementación de bases de datos **MySQL**. Además, se incluyen conceptos sobre la **seguridad web**, como el uso de **certificados SSL** y pruebas de penetración (**pentesting**).

**Módulo 3: Sistemas operativos**  
Este módulo se relaciona con la instalación y configuración de sistemas operativos como Ubuntu Server y Kali Linux en las máquinas virtuales. Lo que supone aprender a usar un nuevo sistema operativo (Kali) y aplicar los conocimientos aplicados en clase a lo largo del curso en el Ubuntu Server. 

## **4. Materiales necesarios**

**Materiales físicos:**

- **Servidor** para ejecutar un sistema operativo **Linux**.
- Conexión a **Internet** para descargar el software necesario y mantener las actualizaciones.

**Materiales lógicos:**

- **Sistema operativo**: Ubuntu .
- **Servidor web**: Nginx.
- **Base de datos**: MySQL (si se requiere).
- **Editor de código**: VSCode, Sublime Text (para personalización avanzada).
- **Certificado SSL**: Para asegurar la comunicación entre el servidor y los usuarios.
- **Herramientas de seguridad**:
  - **Firewall**: Para proteger el servidor y los datos.
  - **Pentesting**: Herramientas como **Burp Suite** para pruebas de penetración.
  - **Wireshark**: Para analizar el tráfico de red y garantizar la seguridad.

## **5. Justificación de la elección de la idea**

Este proyecto está dirigido a que aprendamos a configurar y administrar servidores web con Linux y Nginx, desarrollar sitios web dinámicos usando HTML, CSS, JavaScript y PHP, gestionar bases de datos con MySQL, asegurar el servidor con un firewall y realizar pruebas de penetración con Burp Suite, analizar el tráfico de red con Wireshark para mejorar la seguridad.

## 6. Máquinas virtuales necesarias
- **Se utilizarán 5 máquinas virtuales para este proyecto**:
- **Servidor Web (Nginx)**: Esta máquina será responsable de alojar y servir el sitio web dinámico utilizando el servidor web Nginx.
- **Servidor de Base de Datos (MySQL)**: En esta máquina se instalará MySQL, que gestionará todas las bases de datos necesarias para el funcionamiento dinámico del sitio web.
- **Ubuntu Firewall (pfSense o Sophos)**: Esta máquina actuará como un firewall para proteger todas las máquinas del proyecto, gestionando el tráfico de red y ofreciendo protección mediante pfSense o Sophos. También se encargará de la asignación de direcciones IP mediante DHCP.
- **Ubuntu DNS: Esta máquina será configurada para gestionar el DNS (Sistema de Nombres de Dominio), permitiendo resolver nombres de dominio a direcciones IP de forma adecuada para el funcionamiento del sitio web.
Kali Linux (Pentesting y Burp Suite)**: En esta máquina se instalará Kali Linux, un sistema operativo diseñado para pruebas de penetración. Usaremos herramientas como Burp Suite para realizar pruebas de seguridad y encontrar posibles vulnerabilidades en el servidor web.
- **Ubuntu con TrueNAS: Esta máquina será configurada para gestionar las copias de seguridad

## 7. Recursos

- **Bibliografía**: 

- **Webgrafía**:
 
- **Vídeos**:


- **Cursos**:
 

## **8. Consideraciones finales**

El proyecto no solo se enfoca en la creación de un **servidor web**, sino que también implementa medidas de **seguridad** como **firewall**, **pruebas de penetración** y análisis de tráfico con **Wireshark**, asegurando sitios web funcionales y protegidos.
