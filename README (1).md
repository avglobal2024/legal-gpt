
# ⚖️ GPT Legal Cannabis PR – Acciones OpenAPI

Este repositorio contiene la definición del esquema OpenAPI 3.1.0 para integrar acciones especializadas dentro de un GPT personalizado con enfoque **legal** sobre **dispensarios de cannabis medicinal en Puerto Rico**, basado en el derecho civil vigente, la Ley 42-2017 y el Reglamento 9038 del Departamento de Salud.

---

## 📘 Descripción del Proyecto

**GPT Legal Cannabis PR** está diseñado para ayudar a redactar:

- Reclamos extrajudiciales por derecho propio
- Demandas judiciales estructuradas
- Validaciones de cumplimiento normativo (HIPAA, DACO, Reglamento 9038)
- Análisis de dominios web, privacidad y protección de datos
- Búsqueda de jurisprudencia local
- Organización de pruebas (exhibits) legales

---

## 🔗 Integración con GPT Builder

Para importar estas acciones en tu GPT personalizado:

1. Ve a [https://chat.openai.com/gpts](https://chat.openai.com/gpts)
2. Selecciona “⚙️ Acciones”
3. Elige “Importar desde URL”
4. Pega este enlace directo:

```
https://cdn.jsdelivr.net/gh/avglobal2024/legal-gpt/openapi_legal_actions_expandido.json
```

---

## 🛠️ Acciones Definidas

| Acción                   | Método | Descripción                                                             |
|--------------------------|--------|-------------------------------------------------------------------------|
| `/generate-pdf`          | POST   | Genera un documento PDF legal listo para impresión                     |
| `/crear-reclamo`         | POST   | Redacta un reclamo extrajudicial incluyendo cronología de hechos       |
| `/generar-demanda`       | POST   | Crea una demanda judicial con formato oficial                          |
| `/organizar-exhibits`    | POST   | Organiza pruebas (URLs de imágenes/documentos) en formato legal        |
| `/buscar-jurisprudencia` | GET    | Busca jurisprudencia en PR según palabra clave                         |
| `/verificar-nombre-comercial` | GET | Valida si un nombre está registrado en PR                              |
| `/verificar-cumplimiento-hipaa` | GET | Evalúa si un sitio web cumple estándares de privacidad médica          |

---

## 🧠 ¿Quién debe usar este GPT?

- Pacientes afectados por incumplimientos de dispensarios
- Abogados en PR que atienden casos civiles y regulatorios
- Estudiantes de derecho practicando redacción legal
- Activistas de salud y derechos del consumidor

---

## 📁 Estructura del Repositorio

- `openapi_legal_actions_expandido.json` – Archivo OpenAPI 3.1.0 con todas las acciones
- `README.md` – Descripción del proyecto y guía de uso

---

## 📬 Contacto

**Creador del proyecto**: Ángel L. Villegas Torres  
📧 avillegas_pro@yahoo.com  
📍 Guaynabo, Puerto Rico  
🔗 Proyecto gestionado bajo la organización AV Global 2024

---
