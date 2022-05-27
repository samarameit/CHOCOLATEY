**Instalación de chocolatey.**
Para instalar Chocolatey necesitamos acceder a la página de instalación: https://chocolatey.org/install y seguir las instrucciones.

1. REQUISITOS
En la página de instalación comenzarán infomando que necesitamos disponer de un software determinado en nuestro ordenador:

*Windows 7 o superior o Windows Server 2003 en adelante*
*Powershell v2 o superior*
*.NET Framework 4.5 o superior (Que si no lo tienes instalado en tu sistema necesitarías instalarlo o dejar que el instalador de Chocolatey se encargue de hacerlo)*

2. PASOS INSTALACIÓN

-Abrir un terminal como Administrador
-Permitir ejecución e instalación de programas firmados
    -Get-executionPolicy y comprobar que no esté en restricted.
-Finalmente la instalación del software la conseguimos con el comando siguiente:
    **Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))**
1
-Actualizamos: choco upgrade chocolatey

YA ESTARÍA LISTO PARA PODER USARLO
