
# 🧠 GPT Legal – Cannabis Medicinal PR

Este repositorio contiene la configuración base en formato OpenAPI 3.0 para un GPT personalizado que actúa como **asistente legal experto en derecho civil del Estado Libre Asociado de Puerto Rico**, enfocado en **dispensarios de cannabis medicinal**.

## 📄 ¿Qué hace este GPT?

- Redacta **reclamos extrajudiciales** en formato legal
- Crea **PDFs** legales simulados listos para imprimir
- Evalúa si un dominio cumple con **seguridad electrónica (DMARC/SPF/DKIM)**
- Organiza **exhibits** con imágenes y enlaces relacionados al caso
- Sigue la Ley 42-2017, el Reglamento 9038, HIPAA, DACO y otros estatutos pertinentes

## ⚖️ Aplicación práctica

Este GPT es ideal para:
- Pacientes que quieren hacer valer sus derechos
- Abogados o estudiantes de derecho que redactan documentos modelo
- Activistas o auditores en cumplimiento legal de la industria del cannabis en Puerto Rico

## 🧩 Acciones incluidas

| Acción               | Ruta API              | Descripción                                          |
|---------------------|-----------------------|------------------------------------------------------|
| `generatePDF`       | `/generate-pdf`       | Crea un documento legal en formato PDF              |
| `validarDominio`    | `/validar-dominio`    | Evalúa cumplimiento con estándares de ciberseguridad |
| `crearReclamo`      | `/crear-reclamo`      | Redacta un reclamo legal personalizado              |
| `organizarExhibits` | `/organizar-exhibits` | Genera un bloque de exhibits organizados con enlaces|

## 🔗 URL para uso en GPT Builder

```
https://cdn.jsdelivr.net/gh/avglobal2024/legal-gpt/openapi_legal_actions_v310.json
```

## 📂 Archivos incluidos

- `openapi_legal_actions_v310.json`: archivo base con esquema OpenAPI para definir acciones
- Exhibits, análisis legales y PDF relacionados al proyecto (añadir en "Releases")

## 📬 Contacto

**Autor:** AV Global Services 
**Email:** rd.backup1@yahoo.com  
**Entidad:** AV Global Services – Nexus Conyugal  
**Licencias:** Uso bajo fines educativos o de activismo regulatorio en Puerto Rico.  El uso del mismo es bajo su responsabilidad dado que ha sido creado para fines de evaluacion de directivas y agentes GPT.
