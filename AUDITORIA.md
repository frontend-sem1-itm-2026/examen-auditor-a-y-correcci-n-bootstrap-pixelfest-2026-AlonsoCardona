# Auditoría rápida — PixelFest 2026

| # | Problema detectado | Categoría | ¿Por qué es problema? |
|---|---|---|---|
| 1 | Falta  el meta viewport | Responsive designn | Si no lo tiene, no se adapta bien a dispositivos moviles y ademas tiene una vista no agradable |
| 2 | Navbar sin container | Layout | El contenido no esta alineado y se va de largo con los bordes
| 3 | ID del navbar-collapse no coincide con data-bs-target | Navegacion| El botón toggler apunta a "menu-principal pero el collapse tiene id menu, por lo que no funciona en celular |
| 4 | Hero sin container ni padding | Layout/Jerarquía visual | el hero se ve muy pegado a los lados y no se ve estetico |
| 5 | Row sin gutters y cards sin h-100 | Grid/Responsive | las cards se ven asimeticas |
| 6 | Columns sin breakpoints responsive adecuados | Responsive design | Solo usa col-md-4 nno se vera bien en una presentacon de tamano largo |
| 7 | Botón compra no funciona | UX | El link tiene href vacio en lugar de apuntar a la sección de boletos |
| 8 | Secciones sin el padding  | Jerarquía visual | las secciones no tienen el suficiente espaciado para que se vean esteticos |
