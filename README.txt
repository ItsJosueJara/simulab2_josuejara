=========================================================
SIMULADOR EDUCATIVO DEL FUNCIONAMIENTO DE LA WEB — B2
=========================================================

Estudiante   : Josue Jara Panchez
Asignatura   : Tecnologias Web
Institucion  : Universidad Tecnica Particular de Loja (UTPL)
Periodo      : Segundo Bimestre 2026
Actividad    : APE — Rediseno con Framework CSS

---------------------------------------------------------
DESCRIPCION
---------------------------------------------------------
Mini sitio web educativo de 5 paginas que explica como
funciona la Web: desde que el usuario escribe una URL
hasta que el navegador renderiza la pagina.

Rediseno del segundo bimestre aplicando Bootstrap 5.3,
principios de usabilidad y accesibilidad WCAG 2.1.

---------------------------------------------------------
FRAMEWORK CSS UTILIZADO
---------------------------------------------------------
Bootstrap 5.3
https://getbootstrap.com

Componentes de Bootstrap implementados:
  - Navbar responsive (colapsa en movil)
  - Grid de 12 columnas (col-sm / col-md / col-lg)
  - Cards con hover
  - Accordion (pasos del proceso web)
  - Modal (glosario de terminos)
  - Tooltip (Bootstrap JS)
  - Badges
  - Progress bars
  - Botones con estados hover y focus
  - Formulario con validacion HTML5

---------------------------------------------------------
ESTRUCTURA DEL PROYECTO
---------------------------------------------------------
SimuladorB2/
  index.html         -> Inicio — Que ocurre al ingresar una URL?
  solicitud.html     -> Solicitud HTTP — Metodos GET y POST
  contenido.html     -> Servidor Web — Procesamiento y respuesta
  respuesta.html     -> Renderizado HTML5 — DOM, CSSOM y semantica
  contacto.html      -> Recursos, Checklist WCAG y Formulario
  css/
    custom.css       -> Estilos propios tema Petronas (sobre Bootstrap)
  js/
    main.js          -> Cursor, particulas y tooltips
  img/               -> Carpeta de imagenes
  README.txt         -> Este archivo

---------------------------------------------------------
COMO ABRIR EL SITIO
---------------------------------------------------------
1. Descomprime el ZIP en una carpeta
2. Abre la carpeta SimuladorB2
3. Haz doble clic en index.html
4. El sitio funciona directamente en el navegador
   (Chrome, Firefox, Edge)

---------------------------------------------------------
DECISIONES DE DISENO — USABILIDAD Y ACCESIBILIDAD
---------------------------------------------------------
1. Contraste WCAG AA
   Color teal #00D2BE sobre negro #07070A supera el
   ratio 4.5:1 requerido para texto normal.

2. Skip link
   Enlace "Saltar al contenido principal" en todas las
   paginas para usuarios de teclado y lectores de pantalla.

3. Focus visible
   Outline teal de 2px en todos los elementos interactivos
   (botones, links, inputs, acordeon, modal).

4. Semantica HTML5 completa
   header, nav, main, section, article, figure, footer
   en todas las paginas.

5. ARIA attributes
   aria-label, aria-current, aria-expanded, aria-hidden
   correctamente implementados en navbar y elementos decorativos.

6. lang="es" en todas las paginas.

7. alt en imagenes, aria-label en SVGs.

8. Navbar Bootstrap accesible desde teclado en movil y escritorio.

---------------------------------------------------------
PALETA DE COLORES (Mercedes Petronas AMG)
---------------------------------------------------------
--teal     : #00D2BE  (acento principal)
--teal2    : #00A19C  (acento secundario)
--teal3    : #007A76  (gradientes, botones)
--bg-dark  : #07070A  (fondo principal)
--bg-card  : #0D1117  (cards y acordeon)
--silver   : #A8A9AD  (texto secundario)

---------------------------------------------------------
TIPOGRAFIA
---------------------------------------------------------
Titulos   : League Spartan 900
Cuerpo    : Montserrat 300/400
Codigo    : Roboto Mono

=======
