# 🤖 Claude Code + Ollama (Local & Free AI)

Guía rápida para configurar Claude Code con modelos locales. Olvídate de los límites de tokens y las facturas de API usando la potencia de tu propio PC.

---

## 🪟 Windows (PowerShell)

### 1. Instalar Ollama
Descarga e instala desde [ollama.com](https://ollama.com).

### 2. Descargar un Cerebro Local (Opcional pero recomendado)
*Este paso te permite trabajar sin gastar tokens. Elige según tu memoria RAM libre:*
- `ollama pull qwen2.5:7b` (Ideal para equipos de 16GB de RAM).
- `ollama pull glm4` (Recomendado para programación en equipos de 16GB de RAM).
- `ollama pull qwen3.5` (Requiere ~11GB de RAM libre en el sistema).

### 3. Instalar Claude Code
```powershell
irm https://claude.ai/install.ps1 | iex
```

### 4. Iniciar
```powershell
ollama launch claude
```

---

## 🍎 macOS / Linux

### 1. Instalar Ollama
```bash
curl -fsSL https://ollama.com/install.sh | sh
```

### 2. Descargar un Cerebro Local
```bash
ollama pull qwen2.5:7b
```

### 3. Instalar Claude Code
```bash
npm install -g @anthropic-ai/claude-code
```

### 4. Iniciar
```bash
ollama launch claude
```

---

## ⚖️ Tabla Maestro: Equivalencias y Capacidades (28 de Marzo de 2026)

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

## 💰 Punto Clave:
*   **Privacidad:** Los modelos Locales (sin etiqueta :cloud) mantienen tus datos en tu disco duro.
*   **Agentes:** Puedes usar agentes de [Marketing](https://github.com/zubair-trabzada/ai-marketing-claude) o [SEO](https://github.com/AgriciDaniel/claude-seo) sin coste alguno siempre que elijas la opción **LOCAL** al iniciar la sesión.
