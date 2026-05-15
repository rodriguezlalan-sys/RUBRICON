# RUBRICON
RubriCon Executive Hub v2.6 (Gold Master)
RubriCon Executive Hub es una plataforma web de alto rendimiento diseñada específicamente para docentes de Tecnología en Chile. Su objetivo es automatizar la creación de rúbricas mediante Inteligencia Artificial, acelerar el proceso de calificación en aula y generar reportes ejecutivos institucionales listos para imprimir o compartir.
🚀 Características Principales
	•	Generador Curricular con IA: Integración directa con el modelo Gemini de Google para redactar rúbricas precisas, con indicadores de logro observables y alineados a las bases curriculares (desde 5° Básico hasta 2° Medio).
	•	Dos Modalidades de Evaluación:
	◦	Proyectos (Top-Down): Rúbricas analíticas de 20 indicadores divididos por categorías, con 3 niveles de logro (Logrado, En Proceso, Inicial). Exigencia del 60%.
	◦	Metodología Ágil (Bottom-Up): Listas de cotejo de 7 indicadores de observación directa con 2 niveles (Sí/No). Exigencia del 50%.
	•	Modo Evaluación Turbo: Interfaz optimizada para calificar usando exclusivamente el teclado, reduciendo el tiempo de evaluación por estudiante a menos de 10 segundos.
	•	Cálculo de Notas en Tiempo Real: Proyección automática de la calificación (escala 1.0 a 7.0) a medida que se ingresan los puntajes.
	•	Exportación Ejecutiva (PDF): Generación de reportes PDF de alta calidad, de dos páginas, que incluyen fortalezas, áreas de mejora y la matriz técnica completa. Adaptado para no desperdiciar tinta al imprimir.
	•	Persistencia Local: Los datos de las rúbricas y las evaluaciones se guardan de forma segura en el navegador del usuario (localStorage).
⌨️ Atajos de Teclado (Modo Turbo)
Para maximizar la fluidez durante la clase, el sistema de evaluación soporta los siguientes atajos cuando estás calificando a un estudiante:
Durante la Evaluación de Indicadores:
	•	[1], [2], [3]: Asigna el puntaje correspondiente al indicador actual y avanza automáticamente al siguiente.
	•	[Enter] o [Espacio]: Avanza al siguiente indicador (si ya tiene un puntaje asignado).
En la Pantalla de Reporte Final:
	•	[Enter]: Genera y descarga el documento PDF oficial.
	•	[Espacio]: Inicia una nueva evaluación con la misma rúbrica (ideal para pasar al siguiente alumno rápidamente).
	•	[Esc]: Cierra el reporte y vuelve al historial de la rúbrica.
🛠️ Stack Tecnológico
Esta aplicación ha sido diseñada como un componente de React optimizado, renderizable de forma autónoma.
	•	Frontend: React (Hooks: useState, useEffect, useRef, useCallback)
	•	Estilos: Tailwind CSS (Clases utilitarias directas)
	•	Iconografía: SVG nativos (Optimizados en la constante Icons)
	•	Motor PDF: html2pdf.js (Configurado para alta resolución y soporte de renderizado web a escala)
	•	Inteligencia Artificial: Google Generative AI API (Modelo: gemini-2.5-flash-preview-09-2025)
📂 Flujo de Trabajo del Usuario
	1	Dashboard (Home): Vista principal donde residen todas las rúbricas creadas y las plantillas por defecto.
	2	Creador (Diseñador Curricular): Se ingresa el título, nivel y contexto. Opcionalmente, se sube un documento de texto base. La IA devuelve una estructura curricular lista para usar.
	3	Evaluador (In-App): Pantalla inmersiva libre de distracciones donde el docente califica indicador por indicador. Muestra el progreso y cálculo en vivo de la nota.
	4	Reporte Ejecutivo: Documento estático generado post-evaluación. Analiza el rendimiento del estudiante, destaca sus mejores y peores desempeños, y permite la exportación a PDF o la re-evaluación inmediata de un nuevo estudiante.
	5	Historial: Tabla de gestión donde se consultan, editan o eliminan evaluaciones pasadas asociadas a una rúbrica específica.
Documento de Referencia Oficial - Versión de Oro Certificada.
