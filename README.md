# MTC para todos / TCM for everyone

**Estado: BETA** · 🌐 https://robertoruizicochea.github.io/mtc-para-todos/

> ⚠️ **Aviso médico:** este sitio es solo informativo y educativo. No es consejo médico, diagnóstico ni receta. Consulta siempre a tu médico (y a un terapeuta de MTC certificado) antes de usar hierbas o cambiar cualquier tratamiento.

## Español

### Qué hace
1. El paciente escribe su **diagnóstico clínico** (obligatorio: sin diagnóstico médico la web no busca y le pide ir primero al médico).
2. Marca sus **síntomas**.
3. Recibe una ficha con:
   - **Señales de alarma** que requieren atención médica inmediata.
   - **Patrones de la Medicina Tradicional China (MTC)**, resaltando el que más coincide con sus síntomas.
   - **Fórmulas clásicas** y **hierbas** con nombre en español, pinyin, chino y latín (ej.: Azufaifo silvestre · Suan Zao Ren 酸枣仁 · *Semen Ziziphi Spinosae*).
   - **Otras opciones no convencionales** (acupuntura, probióticos, fitoterapia, etc.).
   - **Nivel de evidencia** de cada opción, seguridad e interacciones.
4. Interfaz en español e inglés.

### Niveles de evidencia
- **Fuerte:** metaanálisis o revisiones Cochrane sólidas.
- **Moderada:** varios ensayos con limitaciones.
- **Débil:** ensayos pequeños o contradictorios.
- **Tradicional:** solo uso clásico, sin eficacia probada en ensayos.
- **Sin graduar:** estudio hallado automáticamente, pendiente de revisión.
- Los estudios de revistas chinas se marcan como **calidad variable**.

### Fuentes de datos
- PubMed / NCBI (revisiones y ensayos; cada PMID verificado).
- NCCIH (NIH, EE. UU.), fichas de hierbas.
- Revistas chinas de MTC indexadas en PubMed y casos clínicos publicados (医案).
- ClinicalTrials.gov, Europe PMC y OpenAlex (en ampliación).
- Textos clásicos de MTC de dominio público. Todo el contenido está redactado con palabras propias y citando la fuente.

### Hoja de ruta
- **Parte 1 – Tratamiento según diagnóstico** (esta versión beta).
- **Parte 2 – Orientación antes del médico:** IA que ayuda a ordenar síntomas, sugiere qué análisis consultar con el médico y explica resultados (no diagnostica).
- **Parte 3 – Prevención:** metas como cuidar los pulmones (fumadores) o el corazón.
- **Ciencia emergente:** noticias de investigación etiquetadas como laboratorio / animales / humanos.

### Estructura del código
```
index.html          página única
app.js              lógica: búsqueda con sinónimos, síntomas, render de fichas, idiomas ES/EN
style.css           estilos
data/diagnoses.json base de datos de diagnósticos, patrones, fórmulas, hierbas y estudios
```
Sitio estático publicado con GitHub Pages (rama `main`, raíz). Sin backend ni cookies: **no se guardan datos personales**; la búsqueda ocurre en tu navegador.

---

## English

### What it does
1. The patient enters a **clinical diagnosis** (required; without a medical diagnosis the site asks them to see a doctor first).
2. Selects their **symptoms**.
3. Gets a page with:
   - **Red flags** that require immediate medical care.
   - **Traditional Chinese Medicine (TCM) patterns**, highlighting the best match.
   - **Classical formulas** and **herbs** with Spanish, pinyin, Chinese and Latin names.
   - **Other non-conventional options** (acupuncture, probiotics, herbal medicine, etc.).
   - **Evidence level** for each option, plus safety and interactions.
4. Spanish and English interface.

### Evidence levels
- **Strong:** solid meta-analyses or Cochrane reviews.
- **Moderate:** several trials with limitations.
- **Weak:** small or conflicting trials.
- **Traditional:** classical use only, no proven efficacy in trials.
- **Ungraded:** automatically found study pending review.
- Studies from Chinese journals are labelled **variable quality**.

### Data sources
PubMed/NCBI (every PMID verified), NCCIH (NIH), Chinese-language TCM journals indexed in PubMed and published case records (医案), ClinicalTrials.gov, Europe PMC and OpenAlex (expanding), and public-domain classical TCM texts. Content is written in our own words with citations.

### Roadmap
- **Part 1 – Treatment by diagnosis** (this beta).
- **Part 2 – Pre-doctor orientation:** AI that organizes symptoms, suggests tests to discuss with a doctor and explains results (no diagnosis).
- **Part 3 – Prevention:** goals such as lung care for smokers or heart health.
- **Emerging science:** research news labelled lab / animal / human.

### Code structure
See the tree above. Static site on GitHub Pages; no backend, no cookies, **no personal data stored**.

> ⚠️ **Medical disclaimer:** for informational and educational purposes only. Not medical advice, diagnosis or prescription. Always consult your doctor before using herbs or changing any treatment.
