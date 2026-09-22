# UG-AI-Skills: Framework de Skills y Directivas de Inteligencia Artificial
### Universidad de Guanajuato

Este repositorio contiene el marco normativo, técnico y de identidad gráfica para configurar modelos de Inteligencia Artificial (ChatGPT, Claude, Gemini, Ollama, LlamaIndex, LangChain) adaptados al marco jurídico de la Universidad de Guanajuato (UG).

## 🏛 Contenido del Repositorio

```
UG-AI-Skills/
├── README.md                          # Visión general y guía rápida
├── CONTRIBUTING.md                    # Guía para colaborar y proponer cambios
├── LICENSE                            # Licencia MIT / Uso Institucional
├── .gitignore                         # Archivos ignorados para Git
├── .github/                           # Plantillas para Issues y Pull Requests
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       └── feature_request.md
├── skills/                            # Directivas de sistema (System Prompts)
│   ├── 00_core_legal_and_privacy.md   # Directiva Raíz y Protección de Datos
│   ├── 01_asistente_estudiantil.md    # Asistente para la Comunidad Estudiantil
│   ├── 02_asistente_docente.md        # Asistente Académico y Docente
│   ├── 03_asistente_administrativo.md # Asistente para Servidores Públicos y UT
│   ├── 04_asistente_garante_y_ut.md   # Asistente de Transparencia y Autoridad Garante
│   └── 05_guia_imagen_institucional.md# Guía de Imagen y Papelería Oficial UG (04-2024)
├── docs/                              # Documentación jurídica y matrices
│   └── matriz_normativa_ug.md         # Mapeo de leyes y reglamentos UG
├── templates/                         # Plantillas operativas
│   ├── avisos_privacidad.md           # Formatos de Avisos de Privacidad UG
│   ├── version_publica_testado.md     # Guía y lineamientos de versión pública
│   └── derechos_arco.md               # Formatos para ejercicio de Derechos ARCO
└── scripts/                           # Código de ejemplo para desarrollo
    ├── ejemplo_pptx_ug.py             # Generación automatizada de diapositivas UG
    └── ejemplo_api_ug.py              # Integración de Skills en Python / OpenAI / Claude
```

## 🚀 Instalación Rápida

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/TU-USUARIO/UG-AI-Skills.git
   cd UG-AI-Skills
   ```
2. **Elegir la Skill deseada**: Navega a la carpeta `skills/` y copia el contenido del archivo `.md` correspondiente al rol que deseas configurar en tu plataforma de IA.
3. **Plataformas Compatibles**:
   - **ChatGPT**: Crear un *Custom GPT* e incluir en *Instructions* la Skill 00 + Skill elegida.
   - **Claude**: Crear un *Project* e importar las skills en *Project Knowledge*.
   - **Gemini**: Crear un *Gem* copiando la instrucción de sistema.
   - **Ollama**: Crear un `Modelfile` integrando el sistema localmente.

---
Universidad de Guanajuato | *La verdad os hará libres*
