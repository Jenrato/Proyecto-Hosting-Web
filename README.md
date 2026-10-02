### “Proyecto Hosting Web”
 Milan, Mario  
 Torres, Randy 
 Curso: Redes de datos 1
 Guatemala, Mayo del 2026

# Web Hosting Infrastructure on AWS EC2 (Ubuntu Server)
## 1. Resumen (Summary)

Este proyecto consiste en el diseño, despliegue y seguridad de una infraestructura de hsoting web de nivel de producción sobre la nube utilizando Amazon Web Services EC2 y utilizando el OS basado en Unix Ubuntu Server

El objetivo principal fue construir un entorno web funcional, seguro y escalable, integrando la pila de tecnologías **LAMP** (Linux, Apache, MySQL, PHP), gestión de nombres de dominio (DNS), cifrado SSL/TLS de extremo a extremo y endurecimiento (hardening) de seguridad en red y sistema operativo.

Este proyecto fue desarrollado aplicando metodologías ágiles (SCRUM), organizando el flujo de trabajo en Sprints.

###  Tecnologías y Herramientas
* **Cloud e Infraestructura:** AWS EC2 (Free Tier), Security Groups, Elastic IPs.
* **OS:** Ubuntu Server(CLI / Bash).
* **Servidor Web & Base de Datos:** Apache2, MySQL, PHP.
* **Redes & Seguridad:** SSH (Key pairs), UFW Firewall, DNS (Registros A/CNAME), SSL/TLS (Let's Encrypt / Certbot).
* **Gestión:** SCRUM

# Redes en la nube
  * Creación y configuración de la instancia EC2
  * Configuración de security groups en AWS para restringir el tráfico entrante únicamente a los puertos (22, 80, 443).
  * Mapeo de dirección pública y asociación de nombres de dominio 
# Administración de sistema Linux
  
  * Gestión de usuarios, permisos de sistema de aarchivos con 'chmod' y 'chonw' y gestión de paquetes 'apt'

   * Acceso remoto a través de SSH mediantes public key y private key

  * Configuración del firewall local 'UFW'.

# Servicios Web y bases de datos
  
  * Instalación de servidor web apache 'apache2'
  * Creación de viltual hosts
  * Creación y aseguramiento de mySQL
  * Creación de certificados SSL/TLS con Certbot para garantizar cifrado HTTPS


