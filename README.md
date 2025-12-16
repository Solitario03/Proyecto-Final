# Parcial - Lenguaje de Programación II
<table>
  <tr>
    <td style="padding-right: 20px;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Unalm_logo.png" width="115" />
    </td>
    <td style="vertical-align: top; font-size: 20px; line-height: 1.0;">
      <strong>Universidad Nacional Agraria La Molina</strong><br><br>
      Facultad de Economía y Planificación<br><br>
      Departamento de Estadística e Informática
    </td>
  </tr>
</table>

**Docente:** Ana Cecilia Vargas Paredes  
📧 *anavargas@lamolina.edu.pe*  
🕒 *Horario de atención:* Martes y jueves, 11:00 – 12:00 h  
🏫 *Oficina:* N.º 13, Facultad de Economía y Planificación  

---

## 🧮 Evaluación Grupal 2 

**Análisis de precios y disponibilidad de libros académicos**  
Proyecto que consiste en recopilar automáticamente información de distintas plataformas en línea sobre precios, stock y formatos de libros académicos, con el fin de comparar costos, identificar disponibilidad y apoyar la toma de decisiones de estudiantes e instituciones educativas.

**Relevancia:**  
Facilita la comparación de precios para estudiantes

**Fuentes:**  
Tiendas online de libros + APIs de comercio electrónico. 

**Producto:**  
Conjunto de datos con precios, autores y editoriales. DAMA 3 fuentes

**Fecha de entrega:** 16 de diciembre  
**Fecha de presentación:** 23 o 30 de diciembre  

---

## 👥 Integrantes del grupo

| Integrante   | Usuario   | Código   |
|---------------|----------|----------|
| Malvacedo Quiñonez, Jean Franco  | Solitario03  | 20231496  |
| Mejia Auccapoma, Piero Cesar     | PC-011  | 20230399  |

---
## 📚 Fuentes de Datos

### 🌐 Web Scraping

<ol>
  <li>
    <strong>Buscalibre Perú</strong><br>
    <a href="https://www.buscalibre.com.pe" target="_blank">https://www.buscalibre.com.pe</a><br>
    Plataforma de comercio electrónico que ofrece un amplio catálogo de libros académicos.
    Se extraerá información como título del libro, autor, editorial, precio, disponibilidad,
    stock y reseñas. Para la recolección de datos se utilizará <em>BeautifulSoup</em> en páginas
    estáticas y <em>Selenium</em> para el manejo de filtros dinámicos.
  </li>
  <br>
  <li>
    <strong>Crisol Librerías</strong><br>
    <a href="https://www.crisol.com.pe" target="_blank">https://www.crisol.com.pe</a><br>
    Tienda online especializada en libros técnicos y universitarios. Se extraerán datos
    relacionados con precios promocionales, disponibilidad en tienda física y virtual,
    así como detalles editoriales de cada libro.
  </li>
</ol>

---

### 🔗 API Pública

<ol start="3">
  <li>
    <strong>Google Books API</strong><br>
    <a href="https://developers.google.com/books" target="_blank">
      https://developers.google.com/books
    </a><br>
    API pública que proporciona metadatos estandarizados de libros académicos,
    como ISBN, autores, editoriales, descripciones y avances. Esta fuente complementará
    el web scraping permitiendo enriquecer la base de datos y validar la información
    obtenida de las tiendas online.
  </li>
</ol>

---

### 📖 Referencias complementarias

<ul>
  <li>
    <a href="https://publicapis.dev/" target="_blank">Public APIs</a> – Directorio de APIs públicas.
  </li>
  <li>
    <a href="https://www.datacamp.com/es/blog/web-scraping-projects" target="_blank">
      DataCamp – Proyectos de Web Scraping
    </a>
  </li>
  <li>
    <a href="https://www.octoparse.es/blog/70-fuentes-de-datos-gratuitas-en-2020" target="_blank">
      Octoparse – Fuentes de datos gratuitas
    </a>
  </li>
</ul>
