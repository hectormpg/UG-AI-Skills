# Framework de Prompts y Skills de IA para la Universidad de Guanajuato (UG)

Bienvenido al repositorio oficial del **Framework de Skills e Instrucciones de Inteligencia Artificial de la Universidad de Guanajuato**. Este proyecto proporciona un conjunto estandarizado de directivas, reglas operativas y prompts de sistema (*System Prompts*) diseñados para contextualizar cualquier modelo de Inteligencia Artificial (ChatGPT, Claude, Gemini, Ollama, LangChain) dentro del marco jurídico, administrativo, ético y de imagen institucional de la **Universidad de Guanajuato (UG)**.

---

## Marco Normativo e Institucional Incorporado

Este marco de IA integra de manera transversal y armonizada las siguientes disposiciones:

* **Ley Orgánica de la Universidad de Guanajuato** (Principios rectores, autonomía y fines).
* **Guía Institucional de Imagen de la Universidad de Guanajuato (Guía 04-2024)** (Tipografías Novecento Wide, Raleway, Gandhi Sans/Serif; colores Azul UG #0A263D, Dorado UG #8C6E39; estandarización de documentos, reconocimientos y presentaciones).
* **Acuerdo de Creación de la Autoridad Garante en materia de Transparencia y Protección de Datos Personales de la UG** (Emitido por la Rectora General Dra. Claudia Susana Gómez López en mayo de 2026).
* **Reglamento de Transparencia y Acceso a la Información Pública de la UG** y su Comité de Transparencia.
* **Código de Conducta e Integridad de las Personas Servidoras Públicas de la UG** (Aprobado por el H. Consejo General Universitario en noviembre de 2024).
* **Ley General de Protección de Datos Personales en Posesión de Sujetos Obligados (LGPDPPSO)** y Ley del Estado de Guanajuato.
* **Reglamento Académico de la UG**, Estatuto Orgánico y Código de Ética Universitario.

---

## Estructura del Repositorio

UG-AI-Skills/
- README.md: Presentación general del proyecto
- IMPLEMENTATION_GUIDE.md: Guía técnica de despliegue en plataformas de IA
- skills/
  - 00_core_legal_and_privacy.md: Directiva Raíz (Normatividad, Datos Personales y Líneas Rojas)
  - 01_asistente_estudiantil.md: Skill para Alumnado (Derechos, Trámites y Protección de Datos)
  - 02_asistente_docente.md: Skill para Personal Académico (Evaluación, Ética e Imagen)
  - 03_asistente_administrativo.md: Skill para Servidores Públicos (Transparencia y Documentos)
  - 04_asistente_garante_y_ut.md: Skill para Unidad de Transparencia y Autoridad Garante
  - 05_guia_imagen_y_diseno.md: Skill de Identidad Gráfica y Diseño UG (Documentos y Slides)
- docs/
  - matriz_normativa_ug.md: Mapeo entre artículos legales y reglas de IA
- templates/
  - aviso_privacidad_template.md: Formato para diseño de avisos de privacidad
  - version_publica_template.md: Formato de acta de testado e información reservada

---

## Módulos de Skills Incluidos

1. **`00_core_legal_and_privacy.md` (Directiva Raíz)**: Inviolable para cualquier instancia de IA en la UG. Define los principios de fundamentación legal, minimización de datos personales y prohibición absoluta de divulgación de expedientes.
2. **`01_asistente_estudiantil.md`**: Orientación clara y accesible a estudiantes sobre sus derechos académicos, revisión de evaluaciones, becas y canalización ante la Defensoría de los Derechos Humanos Universitarios.
3. **`02_asistente_docente.md`**: Asistencia en guías docentes, rúbricas de evaluación objetiva, inclusión de la privacidad en aulas virtuales y uso ético de la IA en la docencia.
4. **`03_asistente_administrativo.md`**: Asesoría en transparencia proactiva, Plataforma Nacional de Transparencia, prueba de daño, código de conducta y elaboración de oficios bajo la guía de imagen oficial.
5. **`04_asistente_garante_y_ut.md`**: Soporte especializado en la sustanciación de recursos de revisión ante la **Autoridad Garante de la UG** e inspecciones técnicas del Comité de Transparencia.
6. **`05_guia_imagen_y_diseno.md`**: Guía técnica de diseño para que la IA genere y formatee documentos, memorándums, reconocimientos y presentaciones respetando la tipografía, colores e identidad visual institucional.

---

## Cómo Utilizar este Repositorio

Consulta la **`IMPLEMENTATION_GUIDE.md`** para aprender a cargar estos prompts en:
* **Custom GPTs** (OpenAI ChatGPT)
* **Claude Projects** (Anthropic Claude)
* **Gems** (Google Gemini)
* **Ollama / Local LLMs** (Modelos locales de código abierto)
* **LangChain / LlamaIndex** (Desarrollos personalizados en Python)
