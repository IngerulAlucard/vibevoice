
# VibeVoice en Colab 🎙️✨

Este repositorio proporciona un entorno optimizado para ejecutar **VibeVoice** (Generación de Voz con IA) de forma rápida y sencilla utilizando **Google Colab**. Diseñado para aprovechar al máximo la aceleración por GPU en la nube sin complicaciones de configuración local.

---

## 🚀 Características

* **Configuración en un Clic:** Scripts automatizados para instalar dependencias, entorno virtual y modelos base.
* **Interfaz Gráfica (WebUI):** Acceso directo mediante un túnel público seguro (Gradio / Localtunnel).
* **Optimización de VRAM:** Configuración ajustada para correr de forma fluida tanto en GPUs gratuitas (T4) como de pago (V100/A100).
* **Gestión de Audio:** Listo para cargar audios de referencia y exportar los resultados generados fácilmente.

---

## 🛠️ Requisitos Previos

* Una cuenta de **Google** (para acceder a Colab).
* Entorno de ejecución con **GPU** activado.
* *(Opcional)* Un token de Hugging Face o Ngrok si deseas usar almacenamiento o túneles personalizados.

---

## 🚀 Guía de Inicio Rápido

### 1. Abrir el Notebook


### 2. Configurar el Entorno de Ejecución

Antes de correr cualquier celda, verifica que la aceleración por hardware esté activa:

> **Entorno de ejecución** > **Cambiar tipo de entorno de ejecución** > Seleccionar **GPU T4** (o superior).

### 3. Ejecución

Ejecuta cada celda en orden hasta que te arroje la ip que deberás abrir para usar el programa

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso |
| --- | --- |
| **Python 3.10+** | Lenguaje base del ecosistema. |
| **Google Colab** | Infraestructura y cómputo en la nube. |
| **PyTorch** | Framework de Deep Learning para la inferencia del modelo. |
| **Gradio** | Creación de la interfaz de usuario interactiva. |

---

## 📝 Notas e Inferencia

> ⚠️ **Recordatorio sobre Colab:** Las sesiones de la versión gratuita tienen un límite de tiempo y se desconectan tras periodos de inactividad. Asegúrate de descargar tus modelos entrenados o audios generados a tu PC local o guardarlos directamente en tu Google Drive antes de cerrar la sesión.


---


Repo original: https://github.com/microsoft/VibeVoice
