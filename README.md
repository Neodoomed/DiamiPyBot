<h1 align="center">
    <img src="docs/assets/diami_banner.png">
    <br>
    Diami Bot - Edición Python 🐍 
    <br>
</h1>

<h4 align="center"> Diami es un bot de Discord versátil y multipropósito, reescrito desde cero en Python. </h4>

<!-- Badges -->
<p align="center">
    <img src="https://img.shields.io/badge/Status-En%20Desarrollo-blue" alt="Staus">
    <a href="https://github.com/Xardax88/DiamiPyBot/releases">
        <img src="https://img.shields.io/github/v/release/Xardax88/DiamiPyBot?include_prereleases&label=version&color=blue" alt="Latest Release">
    </a>
    <img src="https://img.shields.io/github/last-commit/Xardax88/DiamiPyBot" alt="Último Commit">
    <img src="https://img.shields.io/github/repo-size/Xardax88/DiamiPyBot" alt="Size">
    <img src="https://img.shields.io/github/license/Xardax88/DiamiPyBot" alt="Licencia">
    <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python" alt="Versión de Python">
    <img src="https://img.shields.io/badge/discord.py-v2.3.2-blue?logo=discord&logoColor=white" alt="discord.py">
    <a href="https://github.com/psf/black">
        <img src="https://img.shields.io/badge/Code%20Style-Black-000000.svg" alt="Code Style: Black">
    </a>
    <a href="https://discord.com/invite/3x8uMdpeHR">
        <img src="https://img.shields.io/discord/774727090188320808?color=5865F2&logo=discord&logoColor=white" alt="Discord Server">
    </a>
</p>

> [!NOTE]
> Este proyecto está en desarrollo activo. Algunas funcionalidades pueden no estar completamente implementadas o pueden cambiar.  
> ¡Tu feedback es muy bienvenido!
---
# ✨ Características Principales

| Característica | Descripción |
| :---: | :--- |
| **🧠 IA Conversacional** | Impulsado por **Google Gemini**, Diami puede entender imágenes, mantener conversaciones contextuales y participar proactivamente con una personalidad única. |
| **🤖 Comandos Intuitivos** | Implementación completa de **Comandos Slash** y **Menús Contextuales** para una integración perfecta con la interfaz de Discord. |
| **⚙️ Configuración por Servidor** | Cada servidor puede personalizar sus propios canales principales y de logs a través de una base de datos **MongoDB**. |
| **📅 Tareas Programadas** | Publicaciones automáticas y eventos recurrentes, como el clásico meme de "Feliz Jueves". |
| **🧩 Arquitectura Modular** | Código organizado en **Cogs** para una fácil expansión y mantenimiento. |

---
# 🚀 Uso y Configuración

Una vez invitado a tu servidor, puedes empezar a interactuar con Diami.

* `/config` - Configura los canales principales y de logs del servidor.
* `/config toggle` - Activa o desactiva módulos específicos, como los logs de moderación.
* `/help` - Muestra la lista de comandos disponibles. (No disponible aún)
* Respondera en el canal principal cada vez que se le mencione.

> [!IMPORTANT]  
> Asegúrate de tener un servidor de MongoDB en funcionamiento y actualiza el archivo `.env` con la URI de conexión correcta. 
> El bot creará automáticamente las colecciones necesarias al iniciar.
---
# 📖 Acerca del Proyecto

**Diami** es la nueva encarnación de mi bot personal de Discord, esta vez escrito completamente en **Python** utilizando la librería `discord.py`.

Este proyecto nace de varios motivos:
1.  **Migración Tecnológica:** Dejar atrás plataformas de hosting que comenzaban a tener un costo elevado.
2.  **Aprendizaje y Crecimiento:** Poner en práctica y profundizar mis conocimientos en el ecosistema de Python, creando un bot más robusto, eficiente y con una base de código limpia.
3.  **Implementación de IA:** Mejorar la integración de la IA con el codigo.
4.  **Optimizar el uso de Tasks:** Python tiene un mejor manejo del tiempo y de aplicación de tareas.

El objetivo final es crear un asistente para servidores de Discord que no solo ofrezca las funcionalidades estándar, sino que también integre sistemas complejos de economía, juegos de rol, entretenimiento e inteligencia artificial.

## Origen: De TypeScript a Python

La versión original de Diami fue desarrollada en **TypeScript**. Si bien fue un excelente proyecto para aprender y validar conceptos, la migración a Python se realizó por varias razones estratégicas:

1.  **Ecosistema de IA y Machine Learning:** Python es el lenguaje líder indiscutible en el campo de la IA. La integración con librerías como `google-generativeai` y el acceso a un vasto ecosistema de herramientas de data science es nativa y mucho más sencilla.
2.  **Facilidad y Rapidez de Desarrollo:** La sintaxis limpia de Python permiten un desarrollo más ágil y un código más legible, ideal para un proyecto con una hoja de ruta tan ambiciosa.
3.  **Rendimiento y Manejo de Concurrencia:** Con `asyncio` como pilar, `discord.py` ofrece un manejo de la concurrencia extremadamente eficiente y maduro, perfecto para un bot que debe manejar cientos de eventos simultáneos.
4.  **Optimización de Hosting:** Este cambio también fue motivado por la necesidad de migrar desde plataformas de hosting (como Railway) que comenzaban a tener un costo elevado, hacia soluciones más personalizadas y rentables como un servidor dedicado.
5.  **Crecimiento Personal:** Poner en práctica y profundizar mis conocimientos en el ecosistema de Python, creando un bot más robusto y con una base de código profesional.
<!-- Aquí es un excelente lugar para una captura de pantalla de un comando en acción -->
<!-- ![Ejemplo del Bot](URL_DE_LA_CAPTURA_DE_PANTALLA.png) -->

## 🛠️ Construido Con

Esta es la tecnológica que da vida a Diami:

*   **Lenguaje Principal:**
    *   ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
*   **Framework de Discord:**
    *   ![discord.py](https://img.shields.io/badge/discord.py-5865F2?style=for-the-badge&logo=discord&logoColor=white)
*   **Base de Datos:**
    *   ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) (con `motor` para operaciones asíncronas)
*   **IA:**
    *   ![Gemini](https://img.shields.io/badge/Google%20Gemini-8E77F0?style=for-the-badge&logo=google-gemini&logoColor=white)
*   **IDE**
    *   ![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)
*   **Despliegue y Hosting:**
    *   ![Railway](https://img.shields.io/badge/Railway-131415?style=for-the-badge&logo=railway&logoColor=white)
    *   ![Fedora Server](https://img.shields.io/badge/Fedora%20Server-51A2DA?style=for-the-badge&logo=fedora&logoColor=white)

---
## 💾 Instalación

1.  **Clona el repositorio:**
    ```sh
    git clone https://github.com/Neodoomed/DiamiPyBot.git
    cd DiamiPyBot
    ```

2.  **Crea y activa un entorno virtual** (recomendado):
    ```sh
    # Para Linux/macOS
    python3 -m venv venv
    source venv/bin/activate
    
    # Para Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```

3.  **Instala las dependencias:**
    ```sh
    pip install -r requirements.txt
    ```

4.  **Configura tus variables de entorno:**
    *   Crea un archivo llamado `.env` en la raíz del proyecto y usa la siguiente plantilla:
    ```env
    # .env
    DISCORD_TOKEN="EL_TOKEN_DE_TU_BOT_AQUÍ"
    MONGO_URI="TU_URI_DE_CONEXIÓN_A_MONGODB_AQUÍ"
    
    # Opcional: Para sincronización instantánea de comandos en un servidor de pruebas
    GUILD_ID="EL_ID_DE_TU_SERVIDOR_DE_PRUEBAS"

    # Token de Gamini Api para el uso de la IA
    GEMINI_API_KEY="AQUÍ_VA_TU_CLAVE_DE_API_DE_GEMINI"
    ```

5.  **Ejecuta el bot:**
    ```sh
    python main.py
    ```

---
# 🗺️ Hoja de Ruta (Roadmap)

Esta es la lista de funcionalidades planificadas y su estado actual. ¡Hay mucho por hacer!
    
<details>
<summary><strong>✅ Fundamentos del Bot (Completado)</strong></summary>

- [x] Comandos Slash.
- [x] Logger para depuración.
- [x] Configuración por servidor (con MongoDB).
- [x] Historial de auditoría.
- [x] Tareas programadas (`tasks`).
- [x] Menús contextuales.
- [x] Funciones activables/desactivables.
</details>

<details>
<summary><strong>🛡️ Administración y Moderación</strong></summary>

- [ ] Anti-Spam.
- [ ] Anti-Flood.
- [ ] Anti-Raid.
- [ ] Comandos de moderación (`/mute`, `/unmute`, `/kick`, `/ban`).
  - [ ] Aplicable también mediante menú contextual.
</details>

<details>
<summary><strong>💬 Interacción y Utilidades</strong></summary>

- [ ] Mensajes de bienvenida y despedida personalizables.
- [ ] Comandos de ayuda (`/help`).
- [ ] Comandos de información (`/serverinfo`, `/userinfo`).
- [ ] Sistema de tarjeta de usuario (`/profile`).
- [ ] Comandos de búsqueda (`/search`).
- [ ] Dashboard web para configuración.
- [ ] Avatar animado (cambia según eventos o el día).
</details>

<details>
<summary><strong>🎵 Música</strong></summary>

- [ ] Reproducción desde YouTube, Spotify, etc.
- [ ] Cola de reproducción y control de volumen.
</details>

<details>
<summary><strong>💰 Sistema de Economía</strong></summary>

- [ ] **Fundamentos:** `/balance`, `/extract`, `/deposit`, `/daily`, `/pay`.
- [ ] **Sistema de Empleos:** Trabajos con cooldown y diferentes pagos.
- [ ] **Tienda y Objetos:** Compra de insignias (badges) y objetos.
- [ ] **Inventario:** Comando `/inventory`.
</details>

<details>
<summary><strong>🎲 Juegos y Eventos</strong></summary>

- [ ] **Sistema de Rol (RPG):**
  - [ ] Comando de dados (`/roll 1d20+5`).
  - [ ] Hojas de personaje simplificadas.
- [ ] **Juegos:**
  - [ ] Gachapón (colección de personajes/objetos).
  - [ ] Combate de héroes automático (Auto-battler).
  - [ ] Tower Defense (Concepto en desarrollo).
  - [ ] Lectura de cartas del Tarot.
  - [ ] Mascota virtual para el servidor.
- [ ] Eventos globales periódicos.
</details>

<details>
<summary><strong>🧠 Inteligencia Artificial</strong></summary>

- [x] Implementación de IA conversacional.
- [x] Comportamiento proactivo, uniéndose a conversaciones.
- [x] Soporte para imágenes y contexto visual.
- [x] Respuestas personalizadas según contexto.
- [ ] Generación de imágenes con IA.
- [ ] Integración de IA para juegos y eventos.
- [ ] Integración de IA para moderación de contenido.
- [ ] Implementación de IA para usar comandos de forma natural.
- [ ] Efemérides con IA (mediante `task` y/o comando).
</details>

---
# ✨Agradecimientos

* A todos los que han contribuido al proyecto, ya sea con código, ideas o feedback.
* A la comunidad de Discord de El Diagrama.
