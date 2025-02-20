![Leonardo_Phoenix_10_A_futuristic_hightech_banner_featuring_the_0](https://github.com/user-attachments/assets/f485e7ab-a7d4-4f5b-9b10-8e2e60fea177)
# **JAF Technology: Plataforma de Hosting Web** 🌐💻

## 1. **Idea seleccionada** 🧑‍💻

El objetivo de este proyecto es la creación de un servidor web basado en **Linux (Ubuntu)** para alojar un sitio web dinámico. Se busca crear un servicio de hosting similar a **cdmon**, proporcionando una solución para los usuarios que necesiten alojar sus páginas web. Además, se desarrollará una página web corporativa utilizando **HTML**, **CSS** y **JavaScript**, e incorporaremos medidas de seguridad, como un **firewall** 🔒 y análisis de seguridad con **pentesting** 🕵️‍♂️ (incluyendo **Burp Suite**). También se analizará el tráfico de red utilizando **Wireshark** 🐟 para mejorar tanto la seguridad como el rendimiento.

## 2. **Motivo del proyecto**

Este proyecto nos supone un desafío personal y una gran oportunidad de aprendizaje. Aunque algunos aspectos nos resulten más interesantes que otros, todos coincidimos en que es una experiencia única, ya que ninguno de los miembros del equipo ha trabajado en algo similar. Con la ayuda de nuestros profesores confiamos en que este será un gran proyecto.

## 3. **Objetivos y listado de tareas** 📝

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

## 4. **Asignar roles y responsabilidades del equipo** 👥

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
  - **Optimización de Nginx y PHP/MySQL**: Mejora del rendimiento general del servidor.

## 5. **Diagrama de la red** 🌐

- **Servidor Web (Nginx)**: Conectado al **Servidor de Base de Datos (MySQL)**.
- **Firewall (Sophos)**: Protege todos los servidores del tráfico no deseado.
- **Servidor DNS**: Resuelve nombres de dominio.
- **Servidor Webmin**: Administra el servidor de manera sencilla.
- **Kali Linux (Pentesting)**: Realiza las pruebas de penetración.
- **Wireshark**: Monitorea el tráfico de red para asegurar el rendimiento y la seguridad.

<img src="https://github.com/user-attachments/assets/22408195-4e4d-46bd-b134-c15d54b684b9" width="750"/>
<p>Diagrama de red en Cisco</p>

<img src="https://github.com/user-attachments/assets/3bc51b45-6d9a-4257-9b8a-16880e643b40" width="750"/>
<p>Diagrama de red en Canva</p>

## 6. **Tecnologías y Servicios a implementar** 🛠️🚀

- **Ubuntu Server**: Sistema operativo para la gestión y administración del servidor web.
- **Nginx**: Servidor web utilizado para alojar y servir el contenido dinámico de las páginas web.
- **PHP**: Lenguaje de programación para procesar contenido dinámico en las páginas web.
- **MySQL**: Sistema de gestión de bases de datos para almacenar la información de usuarios, páginas web y otros datos relacionados.
- **Webmin**: Interfaz gráfica para la administración remota del servidor, facilitando tareas de configuración y gestión.
- **Wireshark**: Herramienta para el análisis del tráfico de red, utilizada para identificar vulnerabilidades de seguridad y mejorar el rendimiento.
- **Burp Suite**: Herramienta de pruebas de penetración para evaluar la seguridad de la aplicación web y detectar posibles fallos o brechas de seguridad.
- **Sophos**: Solución de firewall para proteger el servidor y la red de accesos no autorizados y otros tipos de ataques.
- **SSL**: Implementación de un sistema de cifrado de comunicaciones para garantizar la seguridad de las conexiones HTTPS entre los usuarios y el servidor.
- **TrueNAS**: Sistema para gestionar las copias de seguridad, asegurando la protección y recuperación de datos.

## 7. **Hardware virtual a utilizar** 🖥️

**Máquinas virtuales**:
- **Servidor Web (Nginx)**: 
  - **CPU**: 1 núcleo.
  - **RAM**: 2 GB.
  - **Almacenamiento**: 20 GB.

- **Servidor de Base de Datos (MySQL)**: 
  - **CPU**: ? núcleos.
  - **RAM**: ? GB.
  - **Almacenamiento**: ? GB.

- **Firewall (Sophos)**: 
  - **CPU**: 1 núcleo.
  - **RAM**: 4 GB.
  - **Almacenamiento**: 20 GB.

- **Servidor DNS y DHCP (Pi-hole)**: 
  - **CPU**: 1 núcleo.
  - **RAM**: 2 GB.
  - **Almacenamiento**: 20 GB.

- **Kali Linux (Pentesting y Burp Suite)**: 
  - **CPU**: ? núcleos.
  - **RAM**: ? GB.
  - **Almacenamiento**: ? GB.

- **Servidor Webmin**: 
  - **CPU**: ? núcleo.
  - **RAM**: ? GB.
  - **Almacenamiento**: ? GB.

## 8. **Sistemas operativos a utilizar** 🖥️

- **Ubuntu Server**: Para todas las máquinas excepto la de la prueba de penetración.
- **Kali Linux**: Para pruebas de penetración y seguridad.
- **Ubuntu Desktop**: Para usarla de cliente y probar el DNS y DHCP y otras pruebas que requieran interfaz gráfica.

## 9. **Diagrama de Gantt** 📅

| Fase/Actividad                      | Inicio   | Fin      | Responsable(s)       |
|--------------------------------------|----------|----------|----------------------|
| **Documentación en GitHub**          | 23/01/25 | 29/04/25 | **Alejandro** 📁   |
| **Documentación en Trello**          | 23/01/25 | 29/04/25 | **Jiajie** 📁   |
| **Configuración del Firewall (Sophos)** | 10/02/25 | 17/02/25 | **Alejandro** 🔒|
| **Configuración del DHCP**           | 13/02/25 | 20/02/25 | **Felipe** 🔧   |
| **Configuración del Servidor Web**   | 17/02/25 | 24/02/25 | **Jiajie** 🛠️   |
| **Configuración del DNS**            | 27/02/25 | 06/03/25 | **Felipe** 🌐   |
| **Desarrollo Web (HTML/CSS/JS)**     | 10/03/25 | 20/03/25 | **Todos** 🎨   |
| **Integración de Base de Datos**     | 21/03/25 | 25/03/25 | **Encargado** 📊   |
| **Configuración de PHP y Webmin**    | 26/03/25 | 31/03/25 | **Encargado** 🌐   |
| **Pruebas de Seguridad (Pentesting)**| 01/04/25 | 10/04/25 | **Encargado** 🕵️‍♂️ |
| **Análisis de Tráfico (Wireshark)**  | 11/04/25 | 17/04/25 | **Encargado** 🐟   |
| **Optimización y Ajustes Finales**   | 18/04/25 | 27/04/25 | **Encargado** 👥   |
| **Entrega del Proyecto**             | 30/04/25 | 06/05/25 | **Finalización** ✅ |

## 10. **Diagrama de Relaciones Entidad-Relación** 🗂️

![Diagrama ER](https://github.com/P-SMX123/PSMX1203/blob/main/Captura%20de%20pantalla%202025-02-07%20185852.png)

### Relaciones

#### 1️⃣ **Usuarios → Pagos**
- **Relación**: 1 a N (Uno a Muchos)
- **Descripción**: Un usuario puede realizar varios pagos, pero cada pago pertenece a un único usuario.
- **Clave Foránea**: `Usuarios.id_usuario → Pagos.id_usuario`

#### 2️⃣ **Usuarios → Configuraciones**
- **Relación**: 1 a N (Uno a Muchos)
- **Descripción**: Un usuario puede tener varias configuraciones, pero cada configuración está asociada a un solo usuario.
- **Clave Foránea**: `Usuarios.id_usuario → Configuraciones.id_usuario`

#### 3️⃣ **Planes_Hosting → Pagos**
- **Relación**: 1 a N (Uno a Muchos)
- **Descripción**: Cada pago corresponde a un único plan de hosting, pero un plan puede ser adquirido varias veces.
- **Clave Foránea**: `Planes_Hosting.id_plan → Pagos.id_plan`

#### 4️⃣ **Planes_Hosting → Configuraciones**
- **Relación**: 1 a N (Uno a Muchos)
- **Descripción**: Un plan de hosting puede tener muchas configuraciones, pero cada configuración pertenece a un único plan.
- **Clave Foránea**: `Planes_Hosting.id_plan → Configuraciones.id_plan`

#### 5️⃣ **Usuarios → Sitio_Web**
- **Relación**: 1 a N (Uno a Muchos)
- **Descripción**: Un usuario puede crear y gestionar múltiples sitios web, pero cada sitio web está asociado exclusivamente a un único usuario.
- **Clave Foránea**: `Usuarios.id_usuario → Sitio_Web.id_usuario`


## 11. **DNS y DHCP con Pi-hole**

### **1. Introducción al servicio (DNS y DHCP)**  
**DNS** traduce los nombres de dominio a direcciones IP y **DHCP** asigna automáticamente direcciones IP a los dispositivos. Usamos **Pi-hole** para gestionar ambos servicios, mejorando la eficiencia de la red y bloqueando anuncios.

### **2. ¿Qué es DNS y por qué es necesario?**  
**DNS** convierte los nombres de dominio (ej. `jaftechnology.com`) en direcciones IP. Es esencial para acceder a sitios web por su nombre y mejora la velocidad de navegación gracias a la caché.

**¿Por qué es necesario?**  
Sin **DNS** no podríamos acceder a sitios web fácilmente usando sus nombres y la navegación sería más compleja.

**¿Dónde hay información oficial?**  
Para más detalles, visita la [documentación de Pi-hole](https://docs.pi-hole.net/).

### **3. ¿Qué es DHCP y por qué es necesario?**  
**DHCP** asigna automáticamente direcciones IP a los dispositivos en la red. Es necesario para evitar configuraciones manuales y conflictos de IP.

**¿Por qué es necesario?**  
El uso de **DHCP** facilita la administración de red al asignar direcciones únicas automáticamente a los dispositivos.

**¿Dónde hay información oficial?**  
Consulta la [documentación de Pi-hole](https://docs.pi-hole.net/) para más información.

### **4. Instalación de DNS y DHCP con Pi-hole**

#### **4.1. Requisitos**  
- Servidor con **Ubuntu**.
- Conexión a Internet.
- Permisos de administrador.

#### **4.2. Actualización del sistema**  
Antes de instalar Pi-hole, actualiza el sistema con:  
```bash
sudo apt update && sudo apt upgrade -y
```

#### **4.3. Instalación de Pi-hole**  
Instala Pi-hole con el siguiente comando:  
```bash
curl -sSL https://install.pi-hole.net | bash
```

#### **4.4. Configuración del servidor DNS**  
Selecciona un proveedor de DNS (Google, Cloudflare, etc.) y activa el bloqueo de anuncios.

#### **4.5. Habilitación del servidor DHCP**  
1. Accede a la interfaz web en `http://pi.hole/admin`.  
2. Activa el servidor **DHCP** y configura el rango de IPs a asignar.  
3. Desactiva el **DHCP** del router para evitar conflictos.

### **5. Incidencias**  
Tuvimos problemas con Bind9 por lo que decidimos usar Pi-hole que también nos dió problema pero tras reinstalarlo, configurarlo nuevamente y con ayuda de los profesores todo funcionó correctamente.

### **6. Conclusión**  
Pi-hole simplificó la gestión de **DNS** y **DHCP**, mejorando la red, bloqueando anuncios y optimizando el rendimiento.

## **12.APACHE-PHP-HTML ** 📦

### **1. Introducción** 
Apache es un servidor web de código abierto que permite alojar aplicaciones y sitios web. PHP es un lenguaje de programación ampliamente utilizado para el desarrollo web. En esta guía, explicamos cómo instalar y configurar ambos en Ubuntu.

### **2. ¿Qué es Apache y por qué es necesario?** 
Apache es un servidor HTTP que permite a los usuarios acceder a páginas web alojadas en un servidor. Es altamente configurable y compatible con múltiples tecnologías.

**¿Por qué es necesario?** 
Apache permite la publicación de sitios web y aplicaciones en un entorno seguro y escalable.

### **3. ¿Qué es PHP y por qué es necesario?** 
PHP es un lenguaje de programación de servidor que se utiliza para la creación de sitios dinámicos y aplicaciones web.

**¿Por qué es necesario?**
PHP permite el procesamiento de datos en el servidor, la conexión con bases de datos y la generación de contenido dinámico.

### **4. Instalación de Apache y PHP en Ubuntu**

**4.1. Requisitos**

-Servidor con **Ubuntu**.
-Conexión a Internet.
-Permisos de administrador.

**4.2. Actualización del sistema**

Antes de instalar Pi-hole, actualiza el sistema con:
```bash
sudo apt update && sudo apt upgrade -y
```

**4.3. Instalación del Apache**

Para instalar Apache, ejecuta el siguiente comando:
```bash
sudo apt install apache2 -y
```

Para verificar que Apache está en ejecución:
```bash
sudo systemctl status apache2
```

Si Apache no está activo, puedes iniciarlo con:
```bash
sudo systemctl start apache2
```

Para asegurarte de que Apache se inicie automáticamente al arrancar el sistema:
```bash
sudo systemctl enable apache2
```

**4.4. Instalación de PHP**

Para instalar PHP junto con el módulo de Apache y soporte para MySQL, ejecuta:
```bash
sudo apt install php libapache2-mod-php php-mysql -y
```

Verifica la instalación de PHP con:
```bash
php -v
```

**4.5. Configuración de Apache para PHP**

Para asegurarte de que Apache prioriza los archivos PHP, edita el archivo de configuración:
```bash
sudo nano /etc/apache2/mods-enabled/dir.conf
```

Modifica la línea:
```bash
DirectoryIndex index.html index.cgi index.pl index.php index.xhtml index.htm
```

Asegúrate de que index.php sea el primero:
```bash
DirectoryIndex index.php index.html index.cgi index.pl index.xhtml index.htm
```

Guarda y cierra el archivo, luego reinicia Apache:
```bash
sudo systemctl restart apache2
```

### **5. Pruebas y solución de incidencias**

**5.1. Verificar que Apache y PHP funcionan correctamente**

Crea un archivo de prueba:
```bash
sudo nano /var/www/html/info.php
```

Añade el siguiente contenido:
```bash
<?php
phpinfo();
?>
```

Guarda y cierra el archivo. Luego accede a:
```bash
http://localhost/info.php
```

**5.2. Problemas comunes y soluciones**

Apache no inicia: Ejecuta ```bash sudo systemctl restart apache2.```

Página en blanco en info.php: Verifica la instalación de PHP con ```bash php -v.```

Acceso denegado a archivos PHP: Ajusta permisos con ```bash sudo chmod -R 755 /var/www/html/.```

## **6. Conclusión**

Con estos pasos, hemos instalado y configurado Apache y PHP en Ubuntu. Ahora el servidor está listo para alojar aplicaciones web dinámicas.

## **13. Recursos** 📦

- **Bibliografía:**



- **Webgrafía:**



- **Vídeos:**



- **Cursos:**



