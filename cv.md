# Juan David Páez Rivadeneira

**Desarrollador backend .NET · IA aplicada · Automatización documental**

Madrid, España · [juan.davidpaez@hotmail.com](mailto:juan.davidpaez@hotmail.com) · [linkedin.com/in/juan-david-paez](https://www.linkedin.com/in/juan-david-paez/) · [github.com/kats76](https://github.com/kats76)

## Perfil

Desarrollador backend .NET con 3 años de experiencia en APIs y automatizaciones en producción. Construí prácticamente en solitario DocFormat, que automatizó la maquetación que antes cubrían maquetadores contratados, y un generador de contenido académico con IA (OpenAI) que hoy pilotan profesores.

## Experiencia

### Desarrollador backend .NET (autónomo) · IDEF21 Sistemas, Madrid

10/2024 - actualidad · Automatización de la revisión y maquetación de documentos formativos para el sector universitario.

**DocFormat: maquetación automática (en producción)**

- API en .NET 9 con OpenXML SDK que adapta documentos Word a 5 plantillas institucionales (estilos, índices, cabeceras y portadas). Reemplazó el trabajo que antes requería contratar maquetadores: menos de 2 segundos por documento, también en lotes.
- Clasificación de secciones con fuzzy matching (FuzzySharp) y motor de reglas de corrección.
- JWT con roles, MySQL con EF Core y frontend en JavaScript; Docker en servidor Linux y flujo Git dev/main.

**Generador de documentos académicos con IA (piloto en uso por profesores)**

- API en .NET 9 que genera documentos Word maquetados (OpenXML) a partir de la estructura de una asignatura en JSON, con OpenAI (gpt-4o, structured outputs).
- Generación paralela (Task.WhenAll, SemaphoreSlim) con reintentos ante límites de uso: de unos 10 minutos a 1 minuto por documento.
- LLM-as-judge para la calidad: tono genérico de IA de 13 a entre 0 y 5 detecciones por documento. Fuentes con Semantic Scholar, PDF (PdfPig) y publicación por SFTP.

### Desarrollador backend · Fundación Oftalmológica del Valle, Quito (Ecuador)

10/2022 - 09/2023 · Comunicación automatizada con pacientes.

- API en ASP.NET con SQL Server y MongoDB, y Worker Services para tareas en segundo plano.
- Recordatorios automáticos de citas por SMS con Twilio, gestión de respuestas e informes.

## Habilidades técnicas

- **Backend:** C#, .NET 9, ASP.NET Core, Entity Framework Core, REST, Worker Services
- **IA y documentos:** OpenAI API, LLM-as-judge, OpenXML SDK, PdfPig
- **Datos e infraestructura:** SQL Server, MySQL, MongoDB, Docker, Linux, Git, JWT
- **También:** JavaScript, HTML, CSS, Python, Java; desarrollo asistido por IA con revisión y pruebas propias

## Formación

- **Certificado de Profesionalidad IFCT0509: Administración de Servicios de Internet (nivel 3)** · Comunidad de Madrid (Impulso06), con prácticas en IDEF21 · 2025
- **Tecnólogo Superior en Desarrollo de Software** · Instituto Superior Tecnológico Japón, Quito · 2020-2023

## Idiomas

- **Español:** nativo
- **Inglés:** básico (lectura de documentación técnica)

---

¿Necesitas el CV completo en PDF? Escríbeme por [correo](mailto:juan.davidpaez@hotmail.com) o por [LinkedIn](https://www.linkedin.com/in/juan-david-paez/).
