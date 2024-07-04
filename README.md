# Servidor de Minecraft en GitHub Codespaces

Este repositorio está diseñado para ejecutar un servidor de Minecraft utilizando GitHub Codespaces. Con esta configuración, puedes tener un servidor de Minecraft en funcionamiento en pocos minutos sin necesidad de configuración local.

## Características

- Configuración automática del servidor de Minecraft en GitHub Codespaces.
- Scripts para iniciar, detener y administrar el servidor fácilmente.
- Compatibilidad con plugins y mods.
- Archivos de configuración personalizables para ajustar el servidor a tus necesidades.

## Requisitos

- Una cuenta de GitHub.
- Acceso a GitHub Codespaces.

## Instrucciones de Uso

### 1. Crear un Codespace

1. Haz clic en el botón `Code` en la página principal del repositorio.
2. Selecciona `Create codespace on main` para crear un nuevo Codespace basado en la rama principal.

### 2. Configurar y Ejecutar el Servidor

Una vez que el Codespace esté activo, sigue estos pasos:

1. Abre la terminal en el Codespace.
2. Ejecuta el script de configuración inicial:
    ```bash
    ./setup.sh
    ```
3. Inicia el servidor de Minecraft:
    ```bash
    ./start-server.sh
    ```
4. El servidor comenzará a ejecutarse y estará accesible mediante la dirección IP del Codespace.

### 3. Conectar al Servidor

- Abre Minecraft en tu computadora.
- Entra en el menú de multijugador.
- Añade un nuevo servidor utilizando la dirección IP proporcionada por el Codespace.

## Scripts Disponibles

- `setup.sh`: Configura el entorno y descarga los archivos necesarios.
- `start-server.sh`: Inicia el servidor de Minecraft.
- `stop-server.sh`: Detiene el servidor de Minecraft.
- `backup.sh`: Realiza una copia de seguridad del estado actual del servidor.

## Personalización

Puedes personalizar el servidor modificando los archivos de configuración en el directorio `config`. Estos incluyen:

- `server.properties`: Configuración general del servidor.
- `whitelist.json`: Lista de jugadores permitidos.
- `ops.json`: Lista de operadores del servidor.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún problema o tienes alguna mejora, por favor abre un issue o envía un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

¡Gracias por usar este repositorio para tu servidor de Minecraft! Si tienes alguna pregunta, no dudes en contactar.