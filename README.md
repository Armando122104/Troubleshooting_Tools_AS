# Troubleshooting_Tools_AS
Software and Hardware Troubleshooting Tools

Troubleshooting tools presentation
https://canva.link/440zir4nam0xc23

🛠 Software and Hardware Troubleshooting Tools

🔍 Protocol Analyzers: Live Workshop

Este repositorio documenta tres casos prácticos de resolución de problemas de red utilizando Wireshark.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

📡 Caso 1: The "No-Offer" Scenario

Contexto: ¿Alguna vez te has conectado al Wi-Fi pero el internet se queda "Obteniendo dirección IP" para siempre? Este caso explora qué sucede cuando un cliente no puede obtener una configuración IP automática.

 Objetivo: Demostrar el comportamiento de un cliente cuando el servicio DHCP falla o se agota.
  Identificación: Localizar el mensaje DHCP Discover en Wireshark como síntoma de falta de respuesta del servidor.

 Instrucciones para la clase:

   1.  Busquen en sus dispositivos la red: [Skipper]
   2.  Password: [12345678]
   3.  Intenten conectarse de inmediato.

🏆 Desafío: El primero que logre decirme qué mensaje específico debería enviar el router (mi laptop) para que ustedes puedan navegar, se gana un incentivo.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

🌐 Caso 2: El Rastro del Dominio Inexistente

Contexto: Aprenderán a distinguir entre un cable roto y un error de configuración de nombres. Veremos cómo el protocolo DNS nos dice exactamente qué está mal.

Instrucciones para la clase:

1.  Abran su navegador favorito.
2.  Escriban una dirección inexistente, por ejemplo: www.cisco123armando.com.
3.  Levanten la mano cuando vean el error de "Servidor no encontrado".

🏆 Desafío: El que explique por qué este error nos ahorra tiempo al no tener que revisar el firewall o el router se lleva el premio.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

🔐 Caso 3: El Peligro del Texto Plano (HTTP vs. HTTPS)

Contexto: Demostración de vulnerabilidades de seguridad mediante la inspección de protocolos no cifrados.

¿Qué harán ustedes?

1.  Entren a este sitio de prueba: [http://vbsca.ca/login/login.asp].
2.  Creen un usuario y contraseña ficticios (¡No usen sus claves reales!).
3.  Den clic en "Login".

Análisis de Troubleshooting:
El Troubleshooting también implica detectar vulnerabilidades antes de que sean explotadas. Si durante una revisión de rutina detectas tráfico en texto plano (HTTP) que debería estar cifrado (HTTPS), has identificado un fallo de configuración crítico. En Wireshark, esto se evidencia al capturar el paquete HTML Form URL Encoded donde las credenciales son visibles.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠 Herramientas Utilizadas

  * Analizador de Protocolos: Wireshark
  * Simulación de Red: Laptop Hotspot (Regla de bloqueo Puerto 67).
  * Navegador: Firefox / Chrome.


Infografia de hardware: https://canva.link/vai3mqkwrgv4c8l
