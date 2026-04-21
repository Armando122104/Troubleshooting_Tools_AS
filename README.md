# Troubleshooting_Tools_AS
Software and Hardware Troubleshooting Tools

Troubleshooting tools presentation
https://canva.link/440zir4nam0xc23

Protocol Analyzers

Caso 1: The "No-Offer" Scenario

Contexto:
¿Alguna vez te has conectado al Wi-Fi pero el internet se queda "Obteniendo dirección IP" para siempre?
Este caso explora qué sucede cuando un cliente no puede obtener una configuración IP automática.

Objetivo de la Dinámica: Demostrar el comportamiento de un cliente cuando el servicio DHCP falla o se agota. 
Identificar el mensaje DHCP Discover en Wireshark como síntoma de falta de respuesta del servidor.

Instrucciones para la clase:
Busquen en sus dispositivos mi red: [Skipper] Password: [12345678].
Intenten conectarse de inmediato.

El primero que logre decirme qué mensaje específico debería el router(mi laptop) para que ustedes puedan navegar, se gana un incentivo.

Caso 2: El Rastro del Dominio Inexistente
¿De qué trata?
Aprenderán a distinguir entre un cable roto y un error de configuración de nombres. Veremos cómo el protocolo DNS nos dice exactamente qué está mal.

Instrucciones para la clase:

  Abran su navegador favorito.

  Escriban una dirección inexistente, por ejemplo: www.cisco123armando.com

  Levanten la mano cuando vean el error de "Servidor no encontrado".


El que explique por qué este error nos ahorra tiempo al no tener que revisar el firewall o el router, se lleva el premio.

Caso 3: El Peligro del Texto Plano (HTTP vs. HTTPS)

Demostración de vulnerabilidades de seguridad mediante la inspección de protocolos no cifrados.

¿Qué harán ustedes?
  Entren a este sitio de prueba: http://vbsca.ca/login/login.asp 
  Creen un usuario y contraseña ficticios (¡No usen sus claves reales!). 
  Den clic en "Login".

El Troubleshooting también implica detectar vulnerabilidades antes de que sean explotadas.
Si durante una revisión de rutina detectas tráfico en texto plano (HTTP) que debería estar cifrado (HTTPS), has identificado un fallo de configuración crítico

Infografia de hardware: https://canva.link/vai3mqkwrgv4c8l
