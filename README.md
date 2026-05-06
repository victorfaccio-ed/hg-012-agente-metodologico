# Hugo (HG-012) - Asistente de Investigación y Estructuración Metodológica

## 1. Presentación Inmediata: ¿Qué es y para qué sirve?

Hugo es un agente de Inteligencia Artificial configurado como un asistente metodológico estricto. Su propósito principal es servir de Andamio Dinámico para la investigación, específicamente enfocado y calibrado para las ciencias sociales y de la conducta.

Ayuda a orquestar el aparato crítico de una investigación, asignar roles a la evidencia (triangulación de fuentes académicas, grises y periodísticas) y estructurar argumentos, absteniéndose estrictamente de realizar análisis de datos empíricos. Hugo no hace el trabajo por ti; estructura el terreno para que tú, como único sujeto cognoscente, puedas operar con máxima claridad.

## 2. Fundamentos Metodológicos y Posicionamiento

Este agente fue diseñado por J. Víctor Faccio Lucero tomando como base profundas consideraciones metodológicas recuperadas del trabajo de pensadores y académicos como Hugo Sáez Arreceygor, Noemí Luján P., Michel Alhadeff Jones y Restituto Sierra Bravo, entre otros/as pensadores críticos.

Nota sobre la arquitectura técnica: Para optimizar las instrucciones del sistema (System Prompting), nos servimos de algunos elementos estructurales en idioma inglés. Esto responde a la anatomía actual de los Modelos de Lenguaje Grande (LLMs). Sin embargo, mantenemos este diseño con la profunda esperanza de que en el futuro emerja una arquitectura algorítmica latinoamericana que nos ayude a prescindir de estas limitantes técnicas coloniales.

## 3. Guía de Instalación (Configuración del Entorno)

Hugo no es una aplicación ejecutable tradicional, sino una Personalidad de Sistema (System Prompt) codificada en formato JSON. Para instanciar a Hugo, requieres un entorno que soporte directivas de sistema avanzado.

Pasos para la reproducibilidad:

1. Copia el contenido completo del archivo hugo_agent.json.
2. Abre un entorno de ejecución de LLMs (ej. Google AI Studio, OpenAI Playground, o interfaces de código abierto como LM Studio / AnythingLLM).
3. Pega el JSON en la sección designada para el System Prompt, System Instructions o Configuración del Agente.
4. Ajusta la temperatura del modelo a un nivel bajo (ej. 0.2 a 0.4) para priorizar la rigurosidad analítica, o a un nivel medio (ej. 0.5 a 0.7) si se desea ampliar el margen de creatividad.

## 5. Instrucciones de Uso y Ejemplos Prácticos

A continuación, se muestran ejemplos de cómo interactuar con Hugo para activar sus flujos de trabajo principales.

### A) Iniciando un Proyecto (Onboarding)

Para comenzar a definir tu investigación, utiliza este prompt:

[Prompt de la Persona Usuaria]:
Hola Hugo. Quiero iniciar un nuevo proyecto de investigación sobre la gentrificación en la Ciudad de México. Inicia tu protocolo de Onboarding, por favor.


Salida esperada: Hugo iniciará su calibración sistémica, haciéndote un máximo de 2 preguntas metodológicas a la vez para evitar sobrecarga cognitiva.

### B) Aplicando el "Winter Protocol" (Bloqueo del Investigador)

Si te encuentras atascado, indícalo claramente:

[Prompt de la Persona Usuaria]:
Hugo, estoy agotada. No avanzo con la redacción del marco teórico y siento que mis fuentes se contradicen. No puedo más.


Salida esperada: Hugo no hará el trabajo por ti, sino que aplicará su diagnóstico sistémico: validará tu esfuerzo previo y te propondrá una meta micro viable ("Sólo un párrafo hoy") enfocada en un solo rol de evidencia.

### C) Ingeniería de Consultas para Herramientas Externas

Si necesitas buscar literatura, pide ayuda con los operadores:

[Prompt de la Persona Usuaria]:
Necesito hacer una búsqueda en Google Scholar sobre la percepción social de la gentrificación. Quiero usar literatura gris y periodística. Dame la cadena de búsqueda.


Salida esperada: Hugo generará una cadena booleana exacta y copiable, adaptada para encontrar documentos institucionales y reportes de prensa.

## 5. Límites Operativos (Guardrails)

Por diseño metodológico, Hugo tiene restricciones codificadas:

🛑 **PROHIBICIÓN**: No procesa, codifica, interpreta ni analiza datos brutos (entrevistas, encuestas, estadísticas).

🛑 **NO GENERA CÓDIGO ANALÍTICO:** No escribirá scripts en Python, R o SQL para análisis de datos.

🛑 **NO ES AUTOR:** Hugo exigirá que declares su uso y pedirá marcadores como [CITA NECESARIA] cuando asuma información teórica.

## 6. Comunidad y Contribución

Hugo está pensado para funcionar en múltiples contextos de investigación y para ser mejorado por la comunidad académica y tecnológica.

¿Cómo contribuir?

1. Clona/Descarga el repositorio o archivo base.
2. Si detectas mejoras en el esquema de Prompting o en los paradigmas epistémicos, propón la adición en el archivo JSON.
3. Comparte tus adaptaciones locales (por ejemplo, si calibraste a Hugo para enfocarse exclusivamente en metodologías decoloniales o teoría fundamentada).

## 7. Atribución y Licencia

Este proyecto se distribuye bajo la licencia GNU General Public License v3.0 (GPLv3). Eres libre de usar, modificar y distribuir esta arquitectura, siempre y cuando mantengas la misma licencia en tus obras derivadas y otorgues el crédito correspondiente.

Cita sugerida:

Faccio Lucero, J. V. (2024). Hugo (HG-012): Asistente de Investigación y Estructuración Metodológica basado en LLMs. Publicado bajo licencia GPLv3.
