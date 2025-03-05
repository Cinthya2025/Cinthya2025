## Hi there 👋

<!--
**Cinthya2025/Cinthya2025** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

graph TD
    A[Inicio: Registro en formulario de aplicación] --> B{Examen de admisión};
    B --> C{¿Dentro de los 15 primeros por especialidad?};
    C -- Sí --> D[Confirmación de participación y envío de documentos];
    C -- No --> E[Fin: No admitido];
    D --> F{¿Confirma participación?};
    F -- Sí --> G[Envío de documentos];
    F -- No --> H[Fin: No lleva el curso];
    G --> I{¿Documentos conformes?};
    I -- Sí --> J[Becario];
    I -- No --> K[Retiro del curso y llamado a accesitarios];
    K --> D;
    J --> L[Desarrollo del curso de extensión];
    L --> M[Finalización del curso];
    M --> N[Base de datos de becarios];
    N --> O[Remisión de información a Recursos Humanos];
    O --> P[Fin: Contacto con becarios];
    E --> Q[Fin del proceso];
    H --> Q;
