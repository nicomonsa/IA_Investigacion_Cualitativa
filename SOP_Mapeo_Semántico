# SOP · Mapeo semántico y geográfico v6.1

## 0. Propósito

Estandarizar el proceso mediante el cual:

1. Se leen transcripciones de entrevistas.
2. Se identifican fragmentos con contenido espacial relevante.
3. Se vinculan esos fragmentos con la Matriz de Sistematización (Eje, Subeje, Pregunta, Columna F).
4. Se traducen en registros para la matriz cartográfica, compatibles con el Libro de categorías de simbología y con las 12 zonas IZ.

---

## 1. Preparación

1. Abrir:
   - La transcripción de la entrevista.
   - La **Matriz de Sistematización** (con Eje, Subeje, Pregunta, Categoría conceptual en F).
   - El **Libro de categorías de simbología** (categoría cartográfica, geometría, icono).
2. Identificar:
   - Código de entrevista (ej. `PR - ES -102 - BOSA NOVA`).
   - Zona esperada a partir del nombre del archivo (ej. `BOSA NOVA` → `Bosa – Nova`).

---

## 2. Identificación de referencias espaciales

Para cada entrevista:

1. Leer la transcripción de manera global.
2. Marcar todas las frases o fragmentos que hagan referencia a:
   - Vías, calles, carreras, avenidas, rotondas, puentes, cruces.
   - Paraderos, estaciones, rutas de buses (SITP, rutas escolares, transporte informal).
   - Parques, plazas, coliseos, salones comunales, iglesias, CAI, cementerios, etc.
   - Sectores o zonas (“la carrilera”, “el centro de Fontibón”, “parte alta de Sierra Morena”, “zona franca”, etc.).
3. Incluir también referencias:
   - A **condiciones de la vía** (huecos, falta de iluminación, congestión, velocidad).
   - A **conflictos entre actores viales** (peatones vs. carros, ciclistas vs. buses, etc.).
   - A **acciones comunitarias o institucionales** situadas (jornadas de mantenimiento, actividades culturales en parques, ferias, etc.).
4. Cada vez que identifiques un lugar o tramo diferenciado, márcalo como **una posible unidad de registro**.

---

## 3. Segmentación por referencia espacial

1. Para cada lugar identificado:
   - Delimitar el fragmento textual mínimo que permita entender:
     - Qué lugar es.
     - Qué sucede allí (riesgo, conflicto, cuidado, exclusión, etc.).
2. No mezclar en un mismo registro referencias a lugares claramente distintos.
3. Si en una misma respuesta se mencionan varios lugares, crear **varios registros**.

---

## 4. Asignación de IZ (Localidad – Zona de Estudio)

1. Partir de la zona esperada según el código del archivo:
   - Ej.: `CB-SM-II` → `Ciudad Bolívar – Sierra Morena II`
   - `FON-CAB-I` → `Fontibón – La Cabaña I`
2. Verificar si el fragmento se refiere a:
   - El mismo barrio/zona que el archivo → usar el IZ de origen.
   - Otra de las 12 zonas de la lista (por mención explícita o inequívoca) → asignar esa IZ.
3. Si la referencia es muy amplia o ambigua y no se puede ajustar a otra zona:
   - Mantener el IZ del archivo.
   - Marcar `needs_review = 1` si esto podría generar dudas posteriores de cartografía.

---

## 5. Vinculación con la Matriz de Sistematización

1. Localizar en la Matriz de Sistematización la fila que mejor corresponda al contenido del fragmento:
   - Coincidencia de **Eje** (A, B o C).
   - Coincidencia de **Subeje**.
   - Coincidencia aproximada de **Pregunta** (Columna D).
   - Coherencia con la **Categoría conceptual** (Columna F).
2. Si varios ítems son posibles:
   - Elige el que mejor represente el **núcleo del fenómeno** descrito.
3. Registra:
   - `Eje`
   - `Subeje`
   - `Pregunta asociada` (texto breve o código según la matriz).
   - `Categoría conceptual (Columna F)` como insumo para el siguiente paso.

---

## 6. Construcción de la “Categoría integrada (F→Cartografía)”

1. Tomar el texto de la Columna F (categoría fenomenológica).
2. Revisar en el **Libro de categorías de simbología** qué categoría cartográfica:
   - Coincide con ese fenómeno.
   - Es compatible con el tipo de geometría (punto, línea, polígono).
   - Tiene un icono definido.
3. Crear una **Categoría integrada** que:
   - Mantenga la referencia al código de Eje/Subeje si existe (ej. `A2_`, `B1_`, etc.).
   - Incremente la legibilidad fenomenológica (ej.: “Riesgos por huecos e iluminación deficiente en tramo vial”).
4. Ejemplos de formatos:
   - `A2_Puntos críticos por huecos y mala iluminación`
   - `B2_Conflictos de uso peatón–vehículo en corredor comercial`
   - `C2_Acciones comunitarias de mantenimiento de vías`
5. Documentar internamente (aunque no se vea como columna):
   - La geometría asociada (PUNTO / LÍNEA / POLÍGONO / RUTA).
   - El icono/símbolo concreto tomado del Libro de categorías.

---

## 7. Definición de Tipo_ubicación

Usar las descripciones del Prompt v6.1:

- `PUNTO`
- `TRAMO_VIAL`
- `ZONA_SECTOR`
- `RUTA`
- `LUGAR_AMPLO`
- `NO_ESPACIAL` (solo cuando sea estrictamente necesario y el proyecto lo exija).

La decisión debe ser coherente con:
- La Categoría integrada.
- La geometría esperada según el Libro de categorías.

---

## 8. Redacción de “Dirección–Lugar” y “Descripción ampliada (snippet)”

1. **Dirección–Lugar**:
   - Sintetizar en pocas palabras:
     - Vía, cruce o hito principal.
     - Ej.: `Avenida Guayacanes frente al Colegio Atalaya`, `Rotonda del monumento a la Unión`, `Parque central de Sierra Morena I`.
   - No normalizar de forma agresiva ni inventar numeraciones o tipos de vía.

2. **Descripción ampliada (snippet)**:
   - Escribir un párrafo corto que:
     - Describa el fenómeno espacial (riesgo, conflicto, apropiación, exclusión, etc.).
     - Incluya actores involucrados (peatones, PCD, niños, mujeres, ciclistas, transporte informal, etc., cuando sea relevante).
     - Mantenga un tono descriptivo, no valorativo.

---

## 9. Enfoques transversales D*

1. Revisar si el fragmento se relaciona con alguno de los enfoques:

   - D1 Movilidad multimodal incluyente y sostenible  
   - D2 Enfoque diferencial  
   - D3 Enfoque poblacional  
   - D4 Interseccionalidad / derechos  
   - D5 Enfoque territorial  
   - D6 Enfoque de género  

2. Criterios prácticos:
   - D2 / D3 / D6 → cuando se menciona explícitamente un grupo (niñ@s, mayores, PCD, población LGBTI, mujeres, campesinado, victimas del conflicto, etc.).
   - D4 → cuando se evidencian desigualdades estructurales o discriminación en el uso del espacio.
   - D5 → cuando la condición de borde, ruralidad, periferia, centralidad o territorio específico es central al relato.
   - D1 → cuando se habla de integración entre modos (caminar–bus–bici, rutas accesibles, etc.).

3. Escribir en el campo `Enfoques transversales D*` una lista separada por `;`.
   - Ej.: `D2 Enfoque diferencial; D3 Enfoque poblacional`.

---

## 10. Criterios para `needs_review`

Marcar `needs_review = 1` en estas situaciones:

1. **Ambigüedad geográfica**:
   - La referencia es muy vaga (“por acá”, “el barrio”, “el centro”) y no permite geocodificar de forma confiable.
   - Existen múltiples lugares que podrían corresponder al mismo nombre sin más pistas.

2. **Duda sobre IZ**:
   - El fragmento parece pertenecer a otra zona de estudio pero no hay certeza suficiente.

3. **Contradicciones o información incompleta**:
   - Se mencionan direcciones incongruentes o incompatibles entre sí.
   - Falta un elemento clave para ubicar el lugar (ej. avenida sin cruce, nombre sin contexto).

No marcar `needs_review` por detalles menores; úsalo solo cuando los analistas puedan necesitar volver al audio o al mapa para resolver la duda.

---

## 11. Construcción del registro

Por cada referencia espacial, llenar una fila con:

1. `Código de entrevista`
2. `IZ (Localidad – Zona de Estudio)`
3. `Eje`
4. `Subeje`
5. `Pregunta asociada`
6. `Categoría integrada (F→Cartografía)`
7. `Dirección–Lugar`
8. `Tipo_ubicación`
9. `Coordenadas` (vacío en esta fase)
10. `Descripción ampliada (snippet)`
11. `Enfoques transversales D*`
12. `needs_review` (0 o 1)

---

## 12. Coherencia y control de calidad

Antes de entregar un lote de registros:

1. Verificar que:
   - Todos los códigos de entrevista están bien escritos.
   - Todos los IZ pertenecen a la lista de 12 zonas.
   - No existan mezclas de varios lugares en un solo registro.
   - El tipo de ubicación sea coherente con la categoría integrada.
2. Revisar rápidamente los `needs_review = 1` para comprobar que la marca está justificada.
3. Mantener siempre la **misma estructura de columnas**, sin simplificaciones.

Este SOP v6.1 reemplaza cualquier versión anterior y debe ser el único referente operativo para el mapeo semántico y geográfico.
