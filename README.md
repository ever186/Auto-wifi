# Auto-Wifi una Herramienta de auditoria wifi para kali linux 🔥

Una herrmaienta desarrollada en Bash, con el proposito de entender como funciona las auditorias Wi-Fi, incluyendo deteccion de interfaces, escaneo de redes captura de hashshakes y ataques con diccionario aircrack.ng

🚨*ADVERTENCIA:* NO usarlo para fines delictivos, solo para fines de aprendizaje 🚨

## Kali linux herrmientas

- 🕵 **Escaneo de Redes**
Utiliza herramientas como airodump-ng para detectar todas las redes Wi-Fi cercanas y sus propiedades (SSID, canal, tipo de cifrado).

- 💣 **Ataque de Desautenticación**
Interrumpe las conexiones enviando paquetes falsos de desautenticación con aireplay-ng, obligando a los clientes a reconectarse.

- 📡 **Captura de Handshake WPA**
Usa airodump-ng para escuchar y capturar paquetes de apretón de manos WPA/WPA2—esencial para descifrar contraseñas de forma offline.

- ⚔️ **Ataque de Diccionario**⚔
se una un lista de contraseña comunes como los es *rockyou.txt* y con ataques de fuerza bruta. Para crackear claves WPA/WPA2.

## 📍 Como usarlo 

### paso 1 - Instala la Herrmienta

para empezar instala la herramienta usando el siguente codigo
```bash
sudo apt-get install aircrack-ng
```

### paso 2 - clonar el repsitorio 

se debe de clonar el repositorio **recomendacion: escribir los scripts en modo sudo**
```bash
sudo gir colne 
```

## paso 3 - Descargar Diccionario y moverlo a la carpeta








