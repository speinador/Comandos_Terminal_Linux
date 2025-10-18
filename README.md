# 🐧 Comandos de Terminal Linux

Guía completa de los comandos más útiles del **terminal de Linux**, organizada por categorías.  
Incluye comandos básicos, de administración, red, seguridad, y más. Ideal para estudiantes, técnicos y profesionales IT.

---

## 📚 Índice

- [🧩 Comandos Básicos de Navegación y Archivos](#-comandos-básicos-de-navegación-y-archivos)
- [⚙️ Comandos del Sistema](#️-comandos-del-sistema)
- [🌐 Comandos de Red](#-comandos-de-red)
- [🔒 Comandos de Usuarios y Permisos](#-comandos-de-usuarios-y-permisos)
- [🧰 Comandos de Procesos y Recursos](#-comandos-de-procesos-y-recursos)
- [📦 Comandos de Paquetes y Actualización](#-comandos-de-paquetes-y-actualización)
- [💽 Comandos de Disco y Archivos](#-comandos-de-disco-y-archivos)
- [🧠 Comandos Avanzados / Administrativos](#-comandos-avanzados--administrativos)
- [🕵️‍♂️ Comandos de Seguridad y Pentesting](#️-comandos-de-seguridad-y-pentesting)

---

## 🧩 Comandos Básicos de Navegación y Archivos

| Comando | Descripción |
|----------|--------------|
| `pwd` | Muestra el directorio actual. |
| `ls` | Lista los archivos y carpetas. (`ls -l`, `ls -a` para más detalles). |
| `cd` | Cambia de directorio. |
| `mkdir` | Crea un nuevo directorio. |
| `rmdir` | Elimina un directorio vacío. |
| `rm` | Elimina archivos o directorios (`rm -rf carpeta/`). |
| `cp` | Copia archivos o carpetas (`cp archivo.txt /ruta/destino/`). |
| `mv` | Mueve o renombra archivos. |
| `cat` | Muestra el contenido de un archivo. |
| `less` | Muestra archivos de texto paginados. |
| `head` | Muestra las primeras líneas de un archivo. |
| `tail` | Muestra las últimas líneas (`tail -f` sigue los cambios en tiempo real). |
| `touch` | Crea un archivo vacío o actualiza su fecha. |
| `find` | Busca archivos o directorios. |
| `locate` | Busca archivos usando una base de datos indexada. |

---

## ⚙️ Comandos del Sistema

| Comando | Descripción |
|----------|--------------|
| `uname -a` | Muestra información del sistema operativo. |
| `hostname` | Muestra o cambia el nombre del host. |
| `uptime` | Muestra cuánto tiempo lleva encendido el sistema. |
| `dmesg` | Muestra mensajes del kernel. |
| `lsb_release -a` | Muestra la versión de la distribución Linux. |
| `date` | Muestra o cambia la fecha/hora del sistema. |
| `cal` | Muestra el calendario. |
| `who` | Muestra quién está conectado. |
| `last` | Muestra el historial de usuarios conectados. |
| `history` | Muestra el historial de comandos. |
| `alias` | Crea atajos para comandos. |
| `sudo` | Ejecuta comandos como superusuario. |

---

## 🌐 Comandos de Red

| Comando | Descripción |
|----------|--------------|
| `ifconfig` | Muestra o configura interfaces de red (obsoleto, reemplazado por `ip`). |
| `ip a` | Muestra direcciones IP de las interfaces. |
| `ping` | Verifica conectividad con otro host. |
| `traceroute` | Muestra la ruta hasta un destino. |
| `nslookup` | Consulta DNS de dominios. |
| `dig` | Consulta DNS de forma más avanzada. |
| `netstat` | Muestra conexiones de red activas. |
| `ss` | Reemplazo moderno de `netstat`. |
| `curl` | Realiza solicitudes HTTP y descarga contenido. |
| `wget` | Descarga archivos desde Internet. |
| `scp` | Copia archivos entre equipos vía SSH. |
| `rsync` | Sincroniza archivos y carpetas entre sistemas. |
| `ssh` | Conecta remotamente a otro equipo Linux. |

---

## 🔒 Comandos de Usuarios y Permisos

| Comando | Descripción |
|----------|--------------|
| `whoami` | Muestra el usuario actual. |
| `id` | Muestra UID, GID y grupos del usuario. |
| `adduser` / `useradd` | Crea un nuevo usuario. |
| `passwd` | Cambia la contraseña del usuario. |
| `deluser` / `userdel` | Elimina un usuario. |
| `groupadd` | Crea un grupo nuevo. |
| `chmod` | Cambia permisos de archivos (`chmod 755 archivo`). |
| `chown` | Cambia propietario y grupo (`chown user:group archivo`). |
| `sudoers` | Define qué usuarios pueden ejecutar comandos como root. |
| `visudo` | Edita el archivo sudoers de forma segura. |

---

## 🧰 Comandos de Procesos y Recursos

| Comando | Descripción |
|----------|--------------|
| `ps aux` | Muestra procesos en ejecución. |
| `top` | Muestra procesos en tiempo real. |
| `htop` | Versión mejorada y visual de `top`. |
| `kill` | Envía señales a un proceso (`kill -9 PID`). |
| `pkill` | Mata procesos por nombre. |
| `jobs` | Muestra trabajos en segundo plano. |
| `bg` / `fg` | Envía procesos al fondo o frente. |
| `nice` / `renice` | Cambia la prioridad de procesos. |
| `free -h` | Muestra el uso de memoria RAM. |
| `df -h` | Muestra el uso de disco. |
| `du -sh *` | Muestra tamaño de archivos o carpetas. |

---

## 📦 Comandos de Paquetes y Actualización

| Comando | Descripción |
|----------|--------------|
| `apt update` | Actualiza la lista de paquetes (Debian/Ubuntu). |
| `apt upgrade` | Instala las actualizaciones disponibles. |
| `apt install paquete` | Instala un paquete. |
| `apt remove paquete` | Elimina un paquete. |
| `apt autoremove` | Elimina dependencias no usadas. |
| `dpkg -l` | Lista paquetes instalados. |
| `yum install` | Instala paquetes (CentOS/RHEL). |
| `dnf update` | Actualiza paquetes en Fedora/RHEL 8+. |
| `snap install` | Instala paquetes snap. |
| `flatpak install` | Instala paquetes Flatpak. |

---

## 💽 Comandos de Disco y Archivos

| Comando | Descripción |
|----------|--------------|
| `lsblk` | Muestra dispositivos de bloques (discos). |
| `fdisk -l` | Lista particiones y discos. |
| `df -h` | Muestra espacio en disco. |
| `mount` | Monta una unidad. |
| `umount` | Desmonta una unidad. |
| `mkfs.ext4 /dev/sdX` | Formatea un disco. |
| `blkid` | Muestra UUID de discos. |
| `parted` | Administra particiones. |
| `fsck` | Verifica y repara sistemas de archivos. |

---

## 🧠 Comandos Avanzados / Administrativos

| Comando | Descripción |
|----------|--------------|
| `systemctl` | Controla servicios y procesos del sistema. |
| `journalctl` | Muestra registros del sistema. |
| `service` | Inicia o detiene servicios. |
| `crontab -e` | Edita tareas programadas. |
| `at` | Programa tareas puntuales. |
| `reboot` | Reinicia el sistema. |
| `shutdown -h now` | Apaga el equipo inmediatamente. |
| `lsmod` | Lista módulos del kernel cargados. |
| `modprobe` | Carga o descarga módulos del kernel. |
| `alias` | Define comandos personalizados. |

---

## 🕵️‍♂️ Comandos de Seguridad y Pentesting

| Comando | Descripción |
|----------|--------------|
| `nmap` | Escanea redes y puertos. |
| `netcat` (`nc`) | Escucha o envía datos por red. |
| `tcpdump` | Captura tráfico de red. |
| `wireshark` | Analiza paquetes de red (GUI). |
| `hydra` | Fuerza bruta de contraseñas. |
| `john` | Crackeo de contraseñas (John the Ripper). |
| `airmon-ng` | Gestiona interfaces Wi-Fi en modo monitor. |
| `aircrack-ng` | Audita redes Wi-Fi. |
| `hashcat` | Crackeo de hashes con GPU. |
| `msfconsole` | Abre Metasploit Framework. |
| `searchsploit` | Busca exploits en la base de datos de Exploit-DB. |
| `whois` | Consulta información de dominios. |
| `dig` | Consulta DNS. |
| `curl` / `wget` | Descarga o consulta URLs (para OSINT). |
| `ssh` | Conexión remota segura. |

---

## 🧾 Créditos

📘 **Autor:** Sebastián Peinador  
👨‍🏫 **Profesor de Seguridad Informática**  
🏥 **Jefe de Soporte y Sistemas - Hospital José M. Penna (CABA)**  
📍 **Argentina**

---

> 💡 *Este documento puede usarse libremente con fines educativos o de referencia técnica. Creado para estudiantes y profesionales de IT que deseen dominar el uso del terminal Linux.*
