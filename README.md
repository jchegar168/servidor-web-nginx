# \# Servidor Web Nginx

# 

# \## Descripción

# Configuración de un servidor web Nginx con FTPS, autenticación básica y HTTPS

# sobre una máquina virtual Debian con Vagrant.

# 

# \## Cómo ejecutarlo

# 1\. Instalar Vagrant y VirtualBox

# 2\. Clonar el repositorio

# 3\. Ejecutar: vagrant up

# 4\. Añadir al fichero hosts de Windows: 192.168.57.10 perfect.sistema.test

# 5\. Acceder a https://perfect.sistema.test

# 

# \## Credenciales

# \- Usuario FTP: ftpuser / 1234

# \- Usuario web: jose / 1234 o checa / 1234

# 

# \## Servicios configurados

# \- Nginx sirviendo web estática con HTTPS

# \- Redirección automática de HTTP a HTTPS

# \- Autenticación básica con restricción por IP

# \- Servidor FTPS con vsftpd y certificado SSL

