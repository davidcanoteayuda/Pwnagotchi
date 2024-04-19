# Pwnagotchi Setup Guide

Bienvenido al repositorio de configuración de Pwnagotchi. Aquí encontrarás los recursos necesarios para configurar y comenzar a utilizar tu Pwnagotchi de manera efectiva.

## Descripción

Este repositorio incluye configuraciones esenciales y una imagen necesaria para poner en marcha tu dispositivo Pwnagotchi. Sigue las instrucciones detalladas para configurar correctamente tu dispositivo.

### Configuración Inicial

1. **Archivo de Configuración**:
   - Descarga el archivo `config.toml` desde este repositorio.
   - Este archivo es una configuración inicial que deberás modificar con tus propios datos para personalizar tu Pwnagotchi.
   - Coloca el archivo modificado en el directorio raíz de tu Pwnagotchi.

2. **Descarga de la Imagen**:
   - Descarga la imagen del Pwnagotchi desde este enlace de Google Drive: [Descargar Imagen](https://drive.google.com/file/d/1iVKl5CeL8vJtv2nSWjdMGA5HcChi2N9P/view?usp=sharing).
   - Esta imagen es necesaria para el funcionamiento del dispositivo con pantallas de tinta versiones 3 y 4

3. **Puertos USB**:
   - El Pwnagotchi tiene dos puertos USB. El puerto en el extremo es para alimentación y el más centrado es el puerto de datos.
   - Conecta el dispositivo al puerto de datos para la configuración.

4. **Conexión y Drivers**:
   - Al conectarlo por primera vez, la inicialización puede tardar entre 5 y 15 minutos.
   - Verifica en el administrador de dispositivos si aparece el conector de red. Si es necesario, instala los controladores de red descargándolos de aquí: [https://www.reddit.com/r/pwnagotchi/comments/jvh8hs/rndis_drivers/](https://www.reddit.com/r/pwnagotchi/comments/jvh8hs/rndis_drivers/)
   - Descarga el archivo `mod-rndis-driver-windows.zip`.

5. **Configuración de Red**:
   - Configura la nueva conexión de red con la siguiente información:
     - IP: 10.0.0.1
     - Máscara de Subred: 255.255.255.0
     - Gateway: 10.0.0.5
     - DNS: 8.8.8.8

6. **Acceso y Configuración SSH**:
   - Usa PuTTY para conectarte vía SSH a `pi@10.0.0.2` (la dirección IP de tu Raspberry Pi).
   - La contraseña por defecto es `raspberry`.
   - Cambia la contraseña del usuario `pi` ejecutando el comando `passwd` y sigue las instrucciones para aumentar la seguridad de tu dispositivo.

## Video Tutorial

Para una guía paso a paso sobre cómo realizar la configuración, mira el video en YouTube:
[![Tutorial de Configuración Pwnagotchi](https://img.youtube.com/vi/MijGc9hMg5M/0.jpg)](https://youtu.be/MijGc9hMg5M)

## Licencia

Este proyecto está liberado bajo la licencia [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html), coherente con la licencia utilizada en el proyecto original de Pwnagotchi.

---

Esperamos que este repositorio te ayude a configurar y comenzar a usar tu Pwnagotchi de manera eficiente. Para cualquier consulta o ayuda adicional, no dudes en abrir un issue en este repositorio.
