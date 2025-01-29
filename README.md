# **AJF Technology: Plataforma de hosting web** 🌐💻
## 1. **Idea seleccionada** 🧑‍💻

El proyecto tiene como objetivo la creación de un servidor web en un sistema operativo **Linux (Ubuntu)** y el alojamiento de un sitio web dinámico. Este proyecto consiste en la creación de un servicio de alojamiento web similar a **cdmon**, para abordar la necesidad de los usuarios de alojar sus páginas web. Además, se incluirá una página web corporativa desarrollada con **HTML**, **CSS** y **JavaScript** y se incorporarán prácticas de seguridad, como la implementación de un **firewall** 🔒 y análisis de seguridad mediante **pentesting** 🕵️‍♂️ (incluyendo **Burp Suite**). También se analizará el tráfico de red usando **Wireshark** 🐟 para mejorar la seguridad y el rendimiento.


## 2. **Motivo del proyecto**

A nivel personal nos supone un desafío y es una gran oportunidad para aprender a hacer cosas nuevas. Indiferentemente de que haya algunas cosas que nos gusten o motiven más y otras menos, es un proyecto interesante, ya que ninguno de los integrantes hemos hecho algo parecido antes. Creemos que con la ayuda de nuestros profesores, puede salirnos muy bien y ser un gran proyecto.


## 3. **Objetivos 🎯 y Listado de tareas 📝**


1. **Configurar servidor web en Linux con Nginx** 🖥️:
   - Instalar **Ubuntu Server** y **Nginx**.
   - Configurar **hosts virtuales** y optimizar Nginx.

2. **Crear y alojar un sitio web dinámico** 💡:
   - Desarrollar el sitio con **HTML**, **CSS** y **JavaScript**.
   - Integrar **PHP** y **MySQL** para contenido dinámico.

3. **Implementar base de datos MySQL** 📊:
   - Instalar y configurar **MySQL**.
   - Conectar la base de datos al sitio web.

4. **Administrar servidor con Webmin**:
   - Instalar y configurar **Webmin** para gestión remota.

5. **Instalar y configurar PHP** 🔧:
   - Instalar **PHP** y configurarlo para **Nginx**.

6. **Configurar DNS y SSL** 🌐🔐:
   - Configurar **DNS** y **SSL** para seguridad HTTPS.

7. **Desarrollar página web corporativa**:
   - Crear una página web moderna y responsiva.

8. **Asegurar el servidor con firewall (Sophos)** 🔒:
   - Configurar **Sophos** para protección del servidor.

9. **Pruebas de penetración con Burp Suite** 🛠️:
   - Realizar pruebas de seguridad con **Burp Suite**.

10. **Analizar tráfico de red con Wireshark** 🐟:
      - Monitorizar el tráfico de red con **Wireshark**.

11. **Optimización y rendimiento**:
      - Ajustar configuraciones de **PHP** y **MySQL**.
      - Implementar **caché** en **Nginx**. 



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
  - **Optimización de Nginx y PHP/MySQL:** Mejora del rendimiento general del servidor.

## 5. **Diagrama de la red 🌐**

- **Servidor Web (Nginx)**: Conectado al **Servidor de Base de Datos (MySQL)**.
- **Firewall (Sophos)**: Protege todos los servidores del tráfico no deseado.
- **Servidor DNS**: Resuelve nombres de dominio.
- **Servidor Webmin**: Administra el servidor de manera sencilla.
- **Kali Linux (Pentesting)**: Realiza las pruebas de penetración.
- **Wireshark**: Monitorea el tráfico de red para asegurar el rendimiento y la seguridad.

<img src="https://github.com/user-attachments/assets/22408195-4e4d-46bd-b134-c15d54b684b9" width="500"/>
<img src="https://github.com/user-attachments/assets/3bc51b45-6d9a-4257-9b8a-16880e643b40" width="500"/>


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


## 7. **Hardware virtual a utilizar 🖥️**

**Máquinas virtuales**:
- **Servidor Web (Nginx)**: 
  - **CPU:** ? núcleos.
  - **RAM:** ? GB.
  - **Almacenamiento:** ? GB.

- **Servidor de Base de Datos (MySQL)**: 
  - **CPU:** ? núcleos.
  - **RAM:** ? GB.
  - **Almacenamiento:** ? GB.

- **Firewall (Sophos)**: 
  - **CPU:** ? núcleo.
  - **RAM:** ? GB.
  - **Almacenamiento:** ? GB.

- **Servidor DNS**: 
  - **CPU:** ? núcleo.
  - **RAM:** ? GB.
  - **Almacenamiento:** ? GB.

- **Kali Linux (Pentesting y Burp Suite)**: 
  - **CPU:** ? núcleos.
  - **RAM:** ? GB.
  - **Almacenamiento:** ?G B.

- **Servidor Webmin**: 
  - **CPU:** ? núcleo.
  - **RAM:** ? GB.
  - **Almacenamiento:** ? GB.


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

- **Ubuntu Server**: Para las máquinas principales.
- **Kali Linux**: Para pruebas de penetración y seguridad.
- **Ubuntu Desktop** (opcional): Para tareas de desarrollo con interfaz gráfica.



## 10. **Diagrama de Gantt 📅**

| Fase/Actividad                      | Inicio   | Fin      | Responsable(s)       |
|--------------------------------------|----------|----------|----------------------|
| **Configuración del Servidor Web**   | ??/??/?? | ??/??/?? | **Encargado** 🛠️    |
| **Desarrollo Web (HTML/CSS/JS)**     | ??/??/?? | ??/??/?? | **Encargado** 🎨    |
| **Integración de Base de Datos**     | ??/??/?? | ??/??/?? | **Encargado** 📊    |
| **Configuración de PHP y Webmin**    | ??/??/?? | ??/??/?? | **Encargado** 🌐    |
| **Pruebas de Seguridad (Pentesting)**| ??/??/?? | ??/??/?? | **Encargado** 🕵️‍♂️    |
| **Análisis de Tráfico (Wireshark)**  | ??/??/?? | ??/??/?? | **Encargado** 🐟    |
| **Optimización y Ajustes Finales**   | ??/??/?? | ??/??/?? | **Encargado** 👥    |
| **Documentación en GitHub**          | ??/??/?? | ??/??/?? | **Encargado** 📁    |


## **11. Recursos** 📦

- **Bibliografía:**



- **Webgrafía:**



- **Vídeos:**



- **Cursos:**



