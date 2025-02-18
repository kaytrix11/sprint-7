# sprint-7
sprint 7 pfsense


Tareas Realizadas
1. Instalación y configuración de Suricata (IDS/IPS)
Instalación de Suricata desde el Package Manager en pfSense.
Configuración del servicio Suricata en la interfaz LAN para monitorear el tráfico.
Activación de las reglas de Snort desde la comunidad de Snort.
Se crea una cuenta en snort.org para obtener las reglas necesarias.

Captura de la instalación de Suricata.
Captura de la configuración de Suricata en la interfaz LAN.
2. Ataque DoS y protección con Suricata
Realización de un ataque DoS sobre el servidor web de la red DMZ (IP 10.0.3.2) desde la máquina Kali Linux.
Se utilizó el comando para generar tráfico masivo desde Kali.
Antes de activar Suricata, se observó que no hubo protección.
Habilitación de Suricata en modo IPS (Legacy Mode).
Ejecución del ataque nuevamente y verificación en los logs de Suricata en Services → Suricata → Alerts.
El tráfico malicioso fue detectado y bloqueado.


Captura del ataque DoS antes de habilitar IPS.
Captura del log en Suricata donde se muestra el ataque detectado y bloqueado.
3. Configuración del Servidor VPN en pfSense
Instalación y configuración del servidor OpenVPN.
Se configuraron parámetros como el protocolo UDP y la asignación de IPs para los clientes (10.0.2.0/24).
Reglas en el firewall para habilitar el tráfico OpenVPN.
Activación del servicio.


Captura de la configuración del servidor VPN OpenVPN en pfSense.
Captura de las reglas de firewall configuradas para OpenVPN.
4. Exportación del Archivo .ovpn para Clientes
Instalación del paquete OpenVPN Client Export desde el Package Manager.
Se intentó exportar el archivo .ovpn para los clientes, pero se presentó un error durante la instalación del paquete, impidiendo la exportación.


5. Instalación y Uso de ntopng para el análisis de tráfico
Instalación de ntopng desde el Package Manager para el análisis de tráfico de red.
Acceso a Diagnostics → ntopng para visualizar estadísticas de tráfico, dispositivos conectados y consumo de ancho de banda.
Se presentó un error al intentar acceder a la herramienta.
