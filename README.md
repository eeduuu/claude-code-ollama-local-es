# 🤖 Claude Code + Ollama (Local & Free AI)

![Claude Code CLI](https://img.shields.io/badge/Claude-Code-black?style=flat-square&logo=anthropic)
![Ollama Local](https://img.shields.io/badge/Ollama-Local-blue?style=flat-square&logo=ollama)
![IA Privada](https://img.shields.io/badge/Privacidad-100%25-green?style=flat-square)
![Cero Tokens](https://img.shields.io/badge/Coste-0_Tokens-orange?style=flat-square)
![Español](https://img.shields.io/badge/Idioma-Español-red?style=flat-square)

Guía rápida para configurar Claude Code con modelos locales. Olvídate de los límites de tokens y las facturas de API usando la potencia de tu propio PC.

---

## 🪟 Windows

### 1. Instalar Ollama
Descarga e instala desde [ollama.com](https://ollama.com).

### 2. Descargar un cerebro local (opcional pero recomendado)
*Este paso te permite trabajar sin gastar tokens. Abre el PowerShell y elige según tu memoria RAM libre:*
- `ollama pull qwen2.5:7b` (Ideal para equipos de 16GB de RAM).
- `ollama pull glm4` (Recomendado para programación en equipos de 16GB de RAM).
- `ollama pull qwen3.5` (Requiere ~11GB de RAM libre en el sistema).

### 3. Instalar Claude Code
Ahora ejecuta este comando para descargar la herramienta oficial de Anthropic. Este proceso configurará el entorno automáticamente:
```powershell
irm https://claude.ai/install.ps1 | iex
```
*(Si la terminal te pregunta algo durante la instalación, simplemente acepta o dale a Enter para usar la configuración por defecto).*

### 4. Iniciar y configurar
Una vez instalado, usa este comando para iniciar:
```powershell
ollama launch claude
```
**Al arrancar por primera vez:**
1.  **Selección de modelo:** Verás una lista. Usa las flechas del teclado (**↑ ↓**) para elegir tu modelo (ej: `qwen2.5:7b`) y pulsa **Enter**.
2.  **Activación:** Si es tu primera vez, el programa te dará un enlace para que inicies sesión en tu cuenta de Claude (solo se hace una vez para activar el programa).
3.  **Listo:** ¡Ya puedes empezar a escribir!


---

## 🍎 macOS / Linux

### 1. Instalar Ollama
```bash
curl -fsSL https://ollama.com/install.sh | sh
```

### 2. Descargar un cerebro local
```bash
ollama pull qwen2.5:7b
```

### 3. Instalar Claude Code
Instala el paquete oficial usando NPM (asegúrate de tener Node.js instalado):
```bash
npm install -g @anthropic-ai/claude-code
```

### 4. Iniciar y configurar
Usa este comando para iniciar:
```bash
ollama launch claude
```
**Al arrancar por primera vez:**
1.  **Activación:** Sigue el enlace que aparecerá en pantalla para autorizar tu cuenta de Claude (solo se hace una vez).
2.  **Selección de modelo:** Selecciona tu modelo local (ej: `qwen2.5:7b`) usando las flechas (**↑ ↓**) y pulsa **Enter**.
3.  **Listo:** Ya tienes todo configurado.


---

## ⚖️ Tabla Maestra: Equivalencias y capacidades (28 de Marzo de 2026)

| Modelo en Terminal | Tipo de Uso | Equivalente Gratis (Local) | Descripción Técnica (Capacidad) |
| :--- | :--- | :--- | :--- |
| **glm-4.7-flash** | **GRATIS (Local)** | `glm4` (5B) | Razonamiento y generación de código local (~25GB). |
| **qwen3.5** | **GRATIS (Local)** | `qwen2.5:7b` | Razonamiento, programación y visión local (~11GB). |
| **kimi-k2.5:cloud** | **PAGO (Nube)** | `qwen3.5` | Razonamiento multimodal con sub-agentes. |
| **qwen3.5:cloud** | **PAGO (Nube)** | `qwen3.5` | Razonamiento, programación y uso de herramientas con visión. |
| **glm-5:cloud** | **PAGO (Nube)** | `glm-4.7-flash` | Razonamiento y generación de código experto. |
| **minimax-m2.7:cloud** | **PAGO (Nube)** | `llama3.2` | Programación rápida, eficiente y productividad real. |

> - **Modo LOCAL:** Recomendado para programar, redactar y consultas diarias rápidas. (Privado y Gratis).
> - **Modo NUBE:** Recomendado para tareas pesadas como auditorías completas. (Máxima velocidad).


---

## 💰 Punto clave:
*   **Privacidad:** Los modelos Locales (sin etiqueta :cloud) mantienen tus datos en tu disco duro.
*   **Agentes:** Puedes usar agentes de [Marketing](https://github.com/zubair-trabzada/ai-marketing-claude) o [SEO](https://github.com/AgriciDaniel/claude-seo) en local pero debes tener un PC muy potente.


---

## Autor

Esta versión está mantenida por:

💼 [Eduard Pampalona Viladot](https://www.linkedin.com/in/eeduuu-seo-ia/)

<p align="left">
 <a href="https://www.linkedin.com/in/eeduuu-seo-ia/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn - Eduard Pampalona Viladot" /></a>
</p>
