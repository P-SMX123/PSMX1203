![Leonardo_Phoenix_10_A_futuristic_hightech_banner_featuring_the_0](https://github.com/user-attachments/assets/f485e7ab-a7d4-4f5b-9b10-8e2e60fea177)
# **JAF Technology: Plataforma de Hosting Web** 🌐💻

[Idea seleccionada](## 1. **Idea seleccionada** 🧑‍💻)







## 1. **Idea seleccionada** 🧑‍💻

El objetivo de este proyecto es la creación de un servidor web basado en **Linux (Ubuntu)** para alojar un sitio web dinámico. Se busca crear un servicio de hosting similar a **cdmon**, proporcionando una solución para los usuarios que necesiten alojar sus páginas web. Además, se desarrollará una página web corporativa utilizando **HTML**, **CSS** y **JavaScript**, e incorporaremos medidas de seguridad, como un **firewall** 🔒 y análisis de seguridad con **pentesting** 🕵️‍♂️ (incluyendo **Burp Suite**). También se analizará el tráfico de red utilizando **Wireshark** 🐟 para mejorar tanto la seguridad como el rendimiento.

## 2. **Motivo del proyecto** 🎯

Este proyecto nos supone un desafío personal y una gran oportunidad de aprendizaje. Aunque algunos aspectos nos resulten más interesantes que otros, todos coincidimos en que es una experiencia única, ya que ninguno de los miembros del equipo ha trabajado en algo similar. Con la ayuda de nuestros profesores confiamos en que este será un gran proyecto.

## 3. **Objetivos y listado de tareas** 📝

1. **Configurar servidor web en Linux con Nginx**:
   - Instalar **Ubuntu Server** y **Nginx**.
   - Configurar **hosts virtuales** y optimizar Nginx.

2. **Crear y alojar un sitio web dinámico**:
   - Desarrollar el sitio con **HTML**, **CSS** y **JavaScript**.
   - Integrar **PHP** y **MySQL** para contenido dinámico.

3. **Implementar base de datos MySQL**:
   - Instalar y configurar **MySQL**.
   - Conectar la base de datos al sitio web.

4. **Administrar servidor con Webmin**:
   - Instalar y configurar **Webmin** para gestión remota.

5. **Instalar y configurar PHP**:
   - Instalar **PHP** y configurarlo para **Nginx**.

6. **Configurar DNS y SSL**:
   - Configurar **DNS** y **SSL** para seguridad HTTPS.

7. **Desarrollar página web corporativa**:
   - Crear una página web moderna y responsiva.

8. **Asegurar el servidor con firewall (Sophos)**:
   - Configurar **Sophos** para protección del servidor.

9. **Pruebas de penetración con Burp Suite**:
   - Realizar pruebas de seguridad con **Burp Suite**.

10. **Analizar tráfico de red con Wireshark**:
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

<img src="https://github.com/user-attachments/assets/458fd8ed-352b-4bef-bf83-6d45b8919da6" width="750"/>
<p>Diagrama de red en Cisco</p>
La ip externa que nos proporciona el centro es la 100.77.20.X, la ip pública es 77.231.11.106 y la privada es: 10.1.2.X.

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

![Diagrama ER](https://github.com/P-SMX123/PSMX1203/blob/main/Captura%20de%20pantalla%202025-02-07%20185852.png)

## 11. **DNS y DHCP con Pi-hole** 🌍

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
El uso de **DHCP** facilita la administración de la red al asignar direcciones únicas automáticamente a los dispositivos. Sin **DHCP**, cada dispositivo necesitaría ser configurado manualmente, lo que puede causar conflictos y errores en la red.

**¿Dónde hay información oficial?**  
Consulta la [página de Pi-hole](https://docs.pi-hole.net/) para más información.

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
![image](https://github.com/user-attachments/assets/13d9959b-1b35-47d0-b186-63971bef9acc)


#### **4.4. Configuración del servidor DNS**  
Selecciona un proveedor de DNS (Google, Cloudflare, etc.) y activa el bloqueo de anuncios.
![image](https://github.com/user-attachments/assets/0073e040-7a5c-46c0-b06e-ff0cadae7eb8)

#### **4.5. Habilitación del servidor DHCP**  
1. Accede a la interfaz web en `http://pi.hole/admin`.  
2. Activa el servidor **DHCP** desde la pestaña **Settings** > **DHCP**.
3. Configura el rango de IPs a asignar. Por ejemplo, si tu red usa el rango `192.168.1.0/24`, puedes asignar el rango de IPs de `192.168.1.100` a `192.168.1.200`.
4. **Desactiva el servicio DHCP** en tu router para evitar conflictos en la asignación de IPs, ya que solo debe haber un servidor DHCP en la red.
![image](https://github.com/user-attachments/assets/2b2b00c4-5235-43b3-a811-a4425e1e6743)

### **5. ¿Por qué utilizar Pi-hole para gestionar DHCP?**  
Usar Pi-hole para gestionar **DNS** y **DHCP** tiene varias ventajas:

- **Centralización**: Al gestionar ambos servicios desde una sola interfaz, facilita el mantenimiento de la red.
- **Optimización de la red**: El DHCP de Pi-hole asigna IPs de manera eficiente y el bloqueo de anuncios mejora la velocidad de navegación.
- **Seguridad**: Tener un control único sobre ambos servicios nos permite tener mejor visibilidad sobre los dispositivos conectados y gestionar posibles bloqueos.

### **6. Incidencias**  
Tuvimos problemas con **Bind9**, lo que nos llevó a optar por Pi-hole, que inicialmente también presentó algunos inconvenientes. Sin embargo, tras reinstalarlo, configurarlo nuevamente y con la ayuda de los profesores, todo comenzó a funcionar correctamente.

### **7. Conclusión**  
Pi-hole simplificó la gestión de **DNS** y **DHCP**, mejorando la red, bloqueando anuncios y optimizando el rendimiento. La centralización de estos servicios en una única plataforma facilitó el control y mantenimiento de la red en lugar de tener aquí el DNS y el DHCP en el firewall.

## 12. APACHE, PHP y HTML  📦

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

**6. Conclusión**

Con estos pasos, hemos instalado y configurado Apache y PHP en Ubuntu. Ahora el servidor está listo para alojar aplicaciones web dinámicas.

## 13. **Pfsense**  🔒

**1.	¿Qué es pfSense y para qué se utiliza?**

Es un software de firewall y enrutador de código abierto. Se utiliza para proteger redes, gestionar el tráfico y ofrecer funciones avanzadas de seguridad en entornos empresariales y domésticos.

**2.	¿En qué sistema se basa?**

PfSense está basado en el sistema operativo FreeBSD, lo que le proporciona estabilidad, seguridad y compatibilidad con diversas configuraciones de red.

**3.	¿Cuáles son las principales características de pfSense?**

-Firewall de alto rendimiento con filtrado de paquetes.

-VPN para conexiones seguras.

-Balanceo de carga y tolerancia a fallos.

-Control de tráfico y calidad de servicio .

-Registro y monitoreo del tráfico en tiempo real.

-Compatibilidad con complementos para ampliar funcionalidades.

**4.	¿Cómo se instala y configura pfSense? ¿Qué debemos tener en consideración al instalarlo en un entorno virtual?**

La instalación de pfSense se realiza descargando la imagen ISO, creando un medio de instalación y configurando el sistema en un hardware compatible o máquina virtual. Al instalarlo en un entorno virtual, es importante considerar la asignación de recursos adecuados.

**5.	¿Consideras pfSense una opción viable para empresas y redes domésticas?**

Sí, pfSense es una opción viable tanto para empresas como para redes domésticas debido a su flexibilidad, facilidad de uso y su conjunto de características avanzada. Ofrece una solución de seguridad sin los costos asociados a soluciones comerciales.

## 14. **INSTALACIÓN Pfsense**  🔒

**1.Descargar la ISO**

`bash
https://www.pfsense.org/download/
`

**2.Adaptadores RED**

`bash
-Adaptador de red: Adaptador Puente
`

`bash
-Adaptador de red: Solo Anfitrión
`

3**Configuración**

`bash
-RAM:  2048
`

`
-HDD:  16 GB
`

`
-S.O.:  BSD
`

**4.Instalación**

1.Instalamos todo por defecto. Apagamos. Quitamos la ISO y reiniciamos. Una vez que nos sale la pantalla inicial, comenzamos a configurar.
![image](https://github.com/user-attachments/assets/6798728c-7d7e-45e1-a25d-d8710129915e)

2.Las direcciones IP de la serie RFC 1918 están reservadas para uso privado en redes locales y son comunes en configuraciones de redes con NAT 

2.1
Los rangos de direcciones RFC 1918 incluyen:

`bash
-10.0.0.0/8
`

`
-172.16.0.0/12
`

`
-192.168.0.0/16
`

3.Para acceder a la configuración de pfSense desde el equipo anfitrión, ambos dispositivos deben estar en el mismo segmento de red. 

4.Accedemos a la interfaz web de pfSense.

-En la configuración básica del sistema:

`
-Se configura un dominio (por ejemplo, pfsense.kirby.local).
`

`
-Se establecen servidores DNS como 1.1.1.1 y 8.8.8.8.
`

`
-Se selecciona el timezone adecuado (por ejemplo, Europe/Madrid).
`

`
-Se cambia la contraseña del administrador para mayor seguridad.
`

5.Pasos clave:

`
-Configurar la red de pfSense para que esté en el mismo segmento de red que el equipo anfitrión.
`

`
-Habilitar DHCP en pfSense para asignar direcciones IP a las máquinas virtuales.
`

`
-Acceder al firewall desde el equipo anfitrión para realizar configuraciones iniciales.
`

`
-Instalar paquetes adicionales según sea necesario (por ejemplo, para proxy y VPN).
`

**5.OpenVPN**

-Que es?

Un servidor VPN es una herramienta esencial para garantizar la seguridad y privacidad en línea, proporcionando una conexión cifrada entre un dispositivo cliente y una red privada a través de Internet.

OpenVPN es un protocolo popular y de código abierto que se utiliza para crear estas conexiones seguras. En el caso de pfSense, una plataforma de gestión de redes, se puede integrar OpenVPN para ofrecer una solución completa de VPN.

`
-Instalar el plugin OpenVPN Client.
`
Lo primero es descargar el paquete **openvpn-client-export** y para ello vamos a **System - Package Manager - Available Packages** y buscamos el paquete **openvpn-client-export** y pulsamos en Install.
![image](https://github.com/user-attachments/assets/3b976c1a-c590-464c-84d7-c32ec756acc0)

`
-Crear certificados digitales (CA y certificado del servidor).
`

Una CA es, una entidad confiable responsable de emitir y revocar certificados digitales utilizados para transacciones y firmas electrónicas.
Abrimos la interfaz del pfSense y navegamos hasta **System - Certificate Manager** y hacemos clic en Agregar.
![image](https://github.com/user-attachments/assets/dc27824b-4420-44ce-ac4b-d5b593893c97)

`
-Configurar el servidor OpenVPN para permitir conexiones remotas.
`

Ahora vamos a configurar el servidor OpenVPN a donde se van a conectar los clientes para lo cual, nos vamos a **VPN - OpenVPN - Servers** y clicamos en Add y rellenamos las opciones:
![image](https://github.com/user-attachments/assets/a81b28dc-b88b-43c2-ab55-3e2ee11f2931)

`
-Configurar las reglas de firewall para permitir el acceso.
`

Ahora nos toca crear una regla en la WAN que nos permita el acceso a través del puerto de VPN.  

Para ello, clicamos en **Firewall - Rules - WAN**  y vamos a crear la regla, clicando donde dice Add rule to the top of the list.

![image](https://github.com/user-attachments/assets/69393009-e5bc-4239-8334-613b90c467fe)

`
-Exportar la configuración para los clientes.
`

Primero tenemos que crear un usuario nuevo, por tanto nos vamos a **System - User Manager**

Creamos un nuevo usuario y clicamos en Click to **create a user certificate** para crear el certificado para ese usuario.

Una vez creado nuestro usuario de prueba ver cómo  exportar los clientes VPN. Para ello seleccionamos en el menú  a **VPN - OpenVPN - Client Export**.

`
-Verificar el estado del servicio y las conexiones de clientes.
`

En el caso de utilizar un dispositivo móvil, tendríamos que instalar la **OpenVPN** for Android 

Hay que exportar el certificado del cliente que hemos creado a nuestro dispositivo para comprobar su funcionamiento.

## 15. **SOPHOS**  🔐

**1.	¿Qué es Sophos y para qué se utiliza?**

Shophos ofrece soluciones de protección para redes, dispositivos y sistemas informáticos. Sus productos incluyen firewalls, antivirus, protección contra malware y herramientas de gestión de seguridad, tanto para entornos empresariales como domésticos.

**2.	¿En qué sistema se basa?**

Sophos utiliza un sistema propietario y tecnologías avanzadas basadas en la nube para proteger a sus usuarios compatible en Windows, macOS y Linux. 

**3.	¿Cuáles son las principales características de Sophos?**

-Protección avanzada contra amenazas: Incluye defensa contra malware, ransomware y otras amenazas cibernéticas.

-Firewall de nueva generación: Permite un control granular del tráfico y la aplicación de políticas de seguridad.

-Protección contra intrusiones y filtrado web: Detecta y previene intentos de intrusión y controla el acceso a sitios web peligrosos.

-Gestión centralizada: Ofrece una consola única para gestionar la seguridad de todos los dispositivos conectados.

-VPN y acceso remoto seguro: Facilita la conexión remota segura para empleados.

-Prevención de pérdida de datos: Ayuda a proteger información sensible y cumple con normativas de privacidad.

**4.	¿Cómo se instala y configura Sophos? ¿Qué debemos tener en consideración al instalarlo en un entorno virtual?**

La instalación de Sophos depende del producto específico, pero generalmente incluye la descarga de la solución desde su portal, la instalación en un servidor o dispositivo y la configuración mediante la consola de administración centralizada. En entornos virtuales, es esencial verificar la compatibilidad con la plataforma de virtualización y asegurar que los recursos del sistema sean suficientes para no afectar el rendimiento.

**5.	¿Consideras sophos una opción viable para empresas y redes domésticas?**

Sí, Sophos es una opción muy viable tanto para empresas como para redes domésticas. Para empresas, ofrece soluciones completas de seguridad con una excelente capacidad de gestión centralizada, ideal para infraestructuras complejas. En redes domésticas, sus soluciones de antivirus y firewall proporcionan una protección confiable contra amenazas sin ser costosas. Además, su interfaz amigable y su soporte técnico hacen que sea una opción popular.

## 16. **Port Forward** 🔌

**1.  ¿Qué es port Forward?** 

Es un proceso mediante el cual se configuran los routers o cortafuegos para permitir que el tráfico de la red externa llegue a un dispositivo específico dentro de una red privada local.
El port forwarding es necesario en situaciones donde quieres que un dispositivo de tu red local sea accesible desde el exterior.

**2. ¿Cómo funciona el port forwarding?**

El router tiene una dirección IP pública y un número de puertos que están relacionados con servicios específicos.
Cuando alguien desde fuera de tu red intenta acceder a tu dirección IP pública usando un puerto determinado, el router dirige ese tráfico hacia un dispositivo de la red local que tiene ese puerto abierto.

**3. ¿Por qué es importante?**

Es útil cuando se desea hacer accesibles ciertos servicios o aplicaciones, como:

-Servidores web.

-Juegos en línea.

-Cámaras de seguridad.

-Servicios de acceso remoto.

**4. Conlusión**
Hemos optado por pfSense debido a que lo estamos viendo en clase y consideramos que será más fácil de configurarlo con el apoyo y soporte de nuestros profesores. Además, al ser una herramienta de código abierto, ofrece flexibilidad y una amplia gama de características avanzadas que se ajustan perfectamente a nuestras necesidades.

## **17. TrueNAS**  🖥️  

**1. ¿Qué es TrueNAS y para qué se utiliza?**

TrueNAS es un sistema operativo basado en FreeBSD y OpenZFS, diseñado para la gestión y almacenamiento de datos en red. Se usa para almacenar, proteger y gestionar datos de manera eficiente en entornos personales y empresariales.  

**2. ¿En qué sistema se basa?**  
TrueNAS se basa en FreeBSD y utiliza el sistema de archivos ZFS, que proporciona alta tolerancia a fallos, verificación de integridad y snapshots para la protección de datos.  

**3. ¿Cuáles son las principales características de TrueNAS?**

- **Almacenamiento en red (NAS/SAN):** Compatible con SMB, NFS e iSCSI para compartir archivos de manera eficiente.  
- **Gestión de copias de seguridad:** Permite realizar backups automáticos para proteger datos críticos.  
- **RAID y redundancia:** Usa **ZFS** para evitar pérdida de información y mejorar la estabilidad del almacenamiento.  
- **Interfaz web intuitiva:** Facilita la administración sin necesidad de comandos complejos.  
- **Compatibilidad con virtualización:** Se integra con Docker, Kubernetes y máquinas virtuales.  
- **Replicación y sincronización:** Permite clonar y sincronizar datos en servidores remotos para mayor seguridad.  

**4. ¿Cómo se instalará y configurará TrueNAS en nuestro proyecto?**  
En JAF Technology, TrueNAS se usará para gestionar las copias de seguridad del servidor, asegurando que los archivos del sitio web, bases de datos y configuraciones estén protegidos. La instalación incluirá:  

1. **Descarga e instalación** en un servidor dedicado o máquina virtual.  
2. **Configuración del almacenamiento y creación de pools ZFS**.  
3. **Habilitación de servicios SMB/NFS para compartir archivos en la red**.  
4. **Automatización de copias de seguridad y replicación remota**.  

**5. ¿Por qué es una opción viable para nuestro proyecto?**  
TrueNAS es ideal para nuestro servicio de hosting, ya que ofrece una solución segura, escalable y confiable para la gestión de datos. Su capacidad de recuperación ante fallos y facilidad de administración garantizan la estabilidad del proyecto sin costos adicionales de licencias.


## **18. Instalación TrueNAS**  🖥️ 







## **19. SQL**  🖥️ 

**¿Qué es SQL y para qué se utiliza?**

SQL es un lenguaje estándar utilizado para gestionar bases de datos relacionales. Permite realizar operaciones como consultas, actualizaciones, inserciones y eliminaciones de datos en bases de datos. SQL es fundamental para interactuar con sistemas de gestión de bases de datos.

**¿Cuáles son las principales características de SQL?**

Consultas complejas: Permite realizar consultas con operaciones avanzadas como joins, subconsultas y agrupaciones.

Manejo de transacciones: Permite controlar transacciones para asegurar la integridad de los datos.

Lenguaje declarativo: En lugar de indicar cómo se deben realizar las tareas, se describe qué se debe hacer (por ejemplo, obtener ciertos datos).

Seguridad de los datos: SQL incluye funcionalidades para definir roles y permisos, protegiendo los datos de accesos no autorizados.

Integridad referencial: SQL puede garantizar que los datos en diferentes tablas se mantengan consistentes mediante claves primarias y foráneas.

**¿Cómo se utilizará SQL en nuestro proyecto?**

En el proyecto de gestión de datos de clientes de la empresa, SQL será esencial por que es el lenguaje que utiliza MySql:

Creación y mantenimiento de la base de datos: Se diseñarán y creará las tablas necesarias para almacenar los datos de clientes, pedidos y productos.

Consultas y reportes: Utilizaremos MySQL para generar reportes de ventas, consultas de inventarios y otros análisis de datos.

Manejo de transacciones: SQL garantizará que las transacciones de compra y venta sean seguras, asegurando que la base de datos se mantenga coherente y libre de errores.

##**20.¿MySQL?**

**¿Qué es MySQL y para qué se utiliza?**


## **20. Instalación MySQL**  🖥️ 

Abre una terminal y ejecuta el siguiente comando:

`bash
sudo apt update
`

`bash
sudo apt upgrade
`

Para instalar MySQL, ejecuta el siguiente comando:

`bash
sudo apt install mysql-server
`

Una vez que MySQL esté instalado, el servicio debería iniciarse automáticamente. Puedes verificar si está corriendo con el siguiente comando:

`bash
sudo systemctl status mysql
`

Ahora puedes ingresar a la consola de MySQL para gestionar tus bases de datos. Usa el siguiente comando para iniciar sesión como el usuario root:

`bash
sudo mysql -u root -p
`

Los pasos para crear un usuario:

`bash
CREATE USER 'nombre_usuario'@'localhost' IDENTIFIED BY 'contraseña';
GRANT ALL PRIVILEGES ON *.* TO 'nombre_usuario'@'localhost' WITH GRANT OPTION;
FLUSH PRIVILEGES;
`

## **21. MockUp WEB**  🖥️ 
![image](https://github.com/user-attachments/assets/f90f49bd-8cf2-49de-80fb-da2f02408daa)
![image](https://github.com/user-attachments/assets/16232e48-5520-4565-9063-dfb5a9cc37c4)
![image](https://github.com/user-attachments/assets/0ab5e4ac-c15a-463b-b71e-40f1c3a9c951)
![image](https://github.com/user-attachments/assets/c2c8d762-b71a-4ca0-8050-6262f3ba0c98)
![image](https://github.com/user-attachments/assets/cb39306b-eb28-4f08-8df0-8c7f1896b61e)
![image](https://github.com/user-attachments/assets/51dd432e-f381-4416-9397-631840c9ec41)

![image](https://github.com/user-attachments/assets/0183ae86-419a-4bc4-8a5c-27234d85ca1b)






## **22. Recursos**  📚

- **Bibliografía:**
 


- **Webgrafía:**



- **Vídeos:**



- **Cursos:**

