# Wificrack una Herramienta automatizada de auditoria wifi para kali linux 🔥

Una herrmaienta desarrollada en Bash, con el proposito de entender como funciona las auditorias Wi-Fi, incluyendo deteccion de interfaces, escaneo de redes captura de hashshakes y ataques con diccionario aircrack.ng.

🚨*ADVERTENCIA:* NO usarlo para fines delictivos, solo para fines de aprendizaje. 🚨

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

Para empezar instala la herramienta usando el siguente codigo.
```bash
sudo apt-get install aircrack-ng
```

### paso 2 - clonar el repsitorio 

Debe de clonar el repositorio **recomendacion: escribir los scripts en modo sudo**.
```bash
sudo git clone https://github.com/ever186/Auto-wifi.git
```

### paso 3 - Descargar Diccionario y moverlo a la carpeta

Descarga el diccionario llamado rockyou.txt.
**https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt&ved=2ahUKEwinzue5_9qNAxWERTABHQoiAqAQFnoECAkQAQ&usg=AOvVaw3snAERl1mU6Ccr4WFEazBd**

Una vez descargaddo vas abrir la termina y colocar estos scripts.
```bash
sudo cd Downloads
```
Cuando estes en la carpeta de download colocaras el siguiente script.
```bash
sudo mv rockyou.txt /home/tu usuario/Auto-wifi
```

### paso 4 - verificar e iniciarlo

Para ir a la carpeta donde se encuentra el archivo de Wificrack.sh, debes escribir el siguente script.

```bash
sudo cd /home/tu_usuario/Auto-wifi
```
Una vez que te encuentres en la carpeta Auto-wifi verifica los archivos con el comando "ls".

```bash
sudo ls
```
Para **INICIARLO** deberas primero asignarle permiso y eso lo haces con el comando *chmod* y el parametro *+x*.

```bash
sudo chmod +x Wificrack.sh
```
Una vez que hayas dado los permiso al archivo esta listo para ser **INICIADO** con el siguiente comando.

```bash
sudo ./Wificrack.sh
```
con esto se comenzaria el programa.















