# UG-AI-Skills: Framework Normativo e Inteligencia Artificial para la Universidad de Guanajuato 🐝⚖️

Bienvenido al repositorio **UG-AI-Skills**, una suite completa de **prompts, directivas del sistema (System Prompts) y directrices normativas** diseñadas para contextualizar agentes de Inteligencia Artificial (LLMs) dentro del marco legal, ético y de protección de datos de la **Universidad de Guanajuato (UG)**.

Esta iniciativa permite que cualquier estudiante, profesor, investigador, enlace administrativo o autoridad de la UG pueda desplegar y utilizar asistentes de IA que respondan con riguroso apego a la normatividad universitaria vigente, garantizando en todo momento la **protección de datos personales**, la **transparencia**, los **derechos humanos** y el **Código de Ética**.

---

## 📐 Arquitectura del Repositorio

El proyecto está estructurado de forma modular y jerárquica:

```text
ug-ai-skills/
├── README.md                          # Guía principal del repositorio
├── IMPLEMENTATION_GUIDE.md             # Guía técnica para desplegar en ChatGPT, Claude, Gemini, Ollama y APIs
├── skills/
│   ├── 00_core_legal_and_privacy.md   # Directive Raíz: Marco Constitucional, Ley Orgánica, Transparencia y Datos
│   ├── 01_asistente_estudiantil.md     # Skill para Estudiantes: Reglamento Académico, Becas, Derechos ARCO, Defensoría
│   ├── 02_asistente_docente.md         # Skill para Académicos: Evaluación, Privacidad en Aula, Guía Docente, Ética
│   ├── 03_asistente_administrativo.md  # Skill para Servidores Públicos/Enlaces: PNT, Clasificación, Prueba de Daño
│   └── 04_asistente_garante_y_ut.md    # Skill para Unidad de Transparencia, Comité y Autoridad Garante UG
├── templates/
│   ├── aviso_privacidad_template.md    # Plantilla de Aviso de Privacidad Institucional
│   ├── formato_version_publica.md      # Guía y plantilla para la elaboración de Versiones Públicas
│   └── solicitud_derechos_arco.md      # Plantilla orientativa para ejercicio de Derechos ARCO en la UG
└── docs/
    └── matriz_normativa_ug.md         # Compendio y mapeo del marco jurídico universitario aplicado a la IA
```

---

## 🏛️ Marco Normativo Integrado

Todas las directivas incluidas en este repositorio incorporan la normatividad universitaria y el marco normativo nacional y estatal correspondiente, con especial atención a los ordenamientos actualizados:

1. **Constitución Política de los Estados Unidos Mexicanos** (Arts. 1, 3 Fracc. VII, y 6 Ap. A).
2. **Constitución Política para el Estado de Guanajuato** (Arts. 3 y 14 Ap. B).
3. **Ley Orgánica de la Universidad de Guanajuato** (D.O. 15 de junio de 2007, reforma 20 de julio de 2018).
4. **Acuerdo por el que se crea la Autoridad Garante en materia de Transparencia y Protección de Datos Personales de la UG** (Emitido el 06 de mayo de 2026, publicado en Gaceta Universitaria el 08 de mayo de 2026 por la Rectora General Dra. Claudia Susana Gómez López).
5. **Ley General de Transparencia y Acceso a la Información Pública (LGTAIP)** y **Ley de Transparencia y Acceso a la Información Pública para el Estado de Guanajuato (LTAIPEG)** (Reforma P.O. 08 de abril de 2026).
6. **Ley General de Protección de Datos Personales en Posesión de Sujetos Obligados (LGPDPPSO)**.
7. **Reglamento de Transparencia y Acceso a la Información Pública de la Universidad de Guanajuato** (Gaceta Universitaria 30 de octubre de 2018, reformado el 05 de marzo de 2021 y 30 de agosto de 2021).
8. **Código de Ética** y **Código de Conducta e Integridad de las Personas Servidoras Públicas de la UG** (Aprobado por el CGU el 15 de noviembre de 2024, publicado en Gaceta Universitaria el 03 de diciembre de 2024).
9. **Reglamento Académico de la UG** (Reforma Gaceta Universitaria 30 de agosto de 2021).
10. **Reglamento del Personal Académico de la UG** (Reforma Gaceta Universitaria 30 de agosto de 2021).
11. **Reglamento de la Defensoría de los Derechos Humanos en el Entorno Universitario**.
12. **Reglamento de Responsabilidades en el Entorno Universitario** y **Reglamento de Responsabilidades y Sanciones en Materia de Violencia de Género**.

---

## 🚀 Inicio Rápido (Quick Start)

### Opción A: Uso Directo en Interfaces Web (ChatGPT Custom GPT, Claude Projects, Gemini Gems)
1. Copia el contenido de `skills/00_core_legal_and_privacy.md` como la instrucción base de tu asistente.
2. Añade el módulo específico según tu rol (`01_asistente_estudiantil.md`, `02_asistente_docente.md`, etc.) en las instrucciones personalizadas (*System Instructions*).

### Opción B: Integración en API / Frameworks (LangChain, LlamaIndex, OpenAI API, Ollama)
Carga el prompt combinado en la variable de sistema de tu modelo:
```python
with open("skills/00_core_legal_and_privacy.md", "r") as f:
    core_prompt = f.read()

with open("skills/01_asistente_estudiantil.md", "r") as f:
    role_prompt = f.read()

system_prompt = core_prompt + "\n\n" + role_prompt
```

---

## 🔒 Compromisos Implicados en la Protección de Datos
La Inteligencia Artificial **nunca** debe vulnerar el principio de confidencialidad de la comunidad universitaria. Por ello, todas las *skills* obligan al asistente a:
- **No recopilar ni almacenar datos personales sensibles** (calificaciones con nombres completos, expedientes médicos, datos bancarios, CURP, domicilio, etc.) en los chats.
- Requerir la aplicación del principio de **minimización de datos** y el uso de **pseudonimización o anonimización** antes de procesar listados o textos institucionales.
- Exigir la existencia del **Aviso de Privacidad** correspondiente antes de cualquier tratamiento de datos personales por parte de las áreas institucionales.

---

## 🤝 Contribuciones y Licencia
Este repositorio ha sido creado para servir a la comunidad de la **Universidad de Guanajuato (UG)** bajo el principio de **Verdad, Libertad, Respecto, Responsabilidad y Justicia** (*"La verdad os hará libres"*). 

Las contribuciones son bienvenidas mediante *Pull Requests* para actualizar artículos, añadir plantillas o mejorar la integración técnica.

*Licencia: MIT - Libre distribución para uso educativo e institucional de la Universidad de Guanajuato.*
