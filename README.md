# Pwnagotchi Setup Guide

Bienvenido al repositorio de configuración de Pwnagotchi. Aquí encontrarás los recursos necesarios para configurar y comenzar a utilizar tu Pwnagotchi de manera efectiva.

## Descripción

Este repositorio incluye una imagen y configuraciones esenciales para poner en marcha tu dispositivo Pwnagotchi. Sigue las instrucciones detalladas para configurar correctamente tu dispositivo.

### Configuración Inicial

1. **Archivo de Configuración**:
   - Descarga el archivo `config.toml` desde la página principal de Pwnagotchi: [https://pwnagotchi.ai/](https://pwnagotchi.ai/)
   - Coloca el archivo en el directorio raíz de tu Pwnagotchi.

2. **Puertos USB**:
   - El Pwnagotchi tiene dos puertos USB. El puerto en el extremo es para alimentación y el más centrado es el puerto de datos.
   - Conecta el dispositivo al puerto de datos para la configuración.

3. **Conexión y Drivers**:
   - Al conectarlo por primera vez, la inicialización puede tardar entre 5 y 15 minutos.
   - Verifica en el administrador de dispositivos si aparece el conector de red. Si es necesario, instala los controladores de red descargándolos de aquí: [https://www.reddit.com/r/pwnagotchi/comments/jvh8hs/rndis_drivers/](https://www.reddit.com/r/pwnagotchi/comments/jvh8hs/rndis_drivers/)
   - Descarga el archivo `mod-rndis-driver-windows.zip`.

4. **Configuración de Red**:
   - Configura la nueva conexión de red con la siguiente información:
     - IP: 10.0.0.1
     - Máscara de Subred: 255.255.255.0
     - Gateway: 10.0.0.5
     - DNS: 8.8.8.8

5. **Acceso y Configuración SSH**:
   - Usa PuTTY para conectarte vía SSH a `pi@10.0.0.2` (la dirección IP de tu Raspberry Pi).
   - La contraseña por defecto es `raspberry`.
   - Cambia la contraseña del usuario `pi` ejecutando el comando `passwd` y sigue las instrucciones para aumentar la seguridad de tu dispositivo.

## Video Tutorial

Para una guía paso a paso sobre cómo realizar la configuración, mira el video en YouTube:
[![Tutorial de Configuración Pwnagotchi](https://img.youtube.com/vi/MijGc9hMg5M/0.jpg)](https://youtu.be/MijGc9hMg5M)

## Licencia

Este proyecto está liberado bajo la licencia [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/deed.es) que permite usar, copiar, modificar y distribuir este trabajo sin restricciones.

---

Esperamos que este repositorio te ayude a configurar y comenzar a usar tu Pwnagotchi de manera eficiente. Para cualquier consulta o ayuda adicional, no dudes en abrir un issue en este repositorio.
