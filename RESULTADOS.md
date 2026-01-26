# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 13 correctas de 23 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.36 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.53 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY, PRIMARY,nif

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.41 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY, id_profesor,id_grado

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.41 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 13: Error
- **Descripción**: 1054 (42S22): Unknown column 'pe.apellido' in 'field list'


## ❌ Query 14: Incorrecto
```diff
--- 
+++ 
@@ -1,63 +1,63 @@
 id | nombre
+30.00 | Administración de bases de datos
+40.00 | Administración de redes y sistemas operativos
+41.00 | Almacenes de Datos
+46.00 | Análisis y planificación de las TI
+72.00 | Bases moleculares del desarrollo vegetal
+78.00 | Bioinformática
+52.00 | Biologia celular
+57.00 | Biología vegetal y animal
+58.00 | Bioquímica
+67.00 | Biorreactores
+79.00 | Biotecnología de los productos hortofrutículas
+68.00 | Biotecnología microbiana
+80.00 | Biotecnología vegetal
+62.00 | Botánica agrícola
+47.00 | Desarrollo Rápido de Aplicaciones
+42.00 | Fiabilidad y Gestión de Riesgos
+53.00 | Física
+73.00 | Fisiología animal
+63.00 | Fisiología vegetal
+59.00 | Genética
+64.00 | Genética molecular
+81.00 | Genómica y proteómica
+48.00 | Gestión de la Calidad y de la Innovación Tecnológica
+31.00 | Herramientas y Métodos de Ingeniería del Software
+32.00 | Informática industrial y robótica
+65.00 | Ingeniería bioquímica
 22.00 | Ingeniería de Requisitos
+33.00 | Ingeniería de Sistemas de Información
+69.00 | Ingeniería genética
+70.00 | Inmunología
 23.00 | Integración de las Tecnologías de la Información en las Organizaciones
+49.00 | Inteligencia del Negocio
+43.00 | Líneas de Productos Software
+54.00 | Matemáticas I
+60.00 | Matemáticas II
+74.00 | Metabolismo y biosíntesis de biomoléculas
+61.00 | Microbiología
 24.00 | Modelado y Diseño del Software 1
+34.00 | Modelado y Diseño del Software 2
 25.00 | Multiprocesadores
+35.00 | Negocio Electrónico
+75.00 | Operaciones de separación
+76.00 | Patología molecular de plantas
+36.00 | Periféricos e interfaces
+82.00 | Procesos biotecnológicos
+44.00 | Procesos de Ingeniería del Software 1
+50.00 | Procesos de Ingeniería del Software 2
+55.00 | Química general
+56.00 | Química orgánica
+51.00 | Seguridad Informática
 26.00 | Seguridad y cumplimiento normativo
 27.00 | Sistema de Información para las Organizaciones
+37.00 | Sistemas de tiempo real
+83.00 | Técnicas instrumentales avanzadas
+77.00 | Técnicas instrumentales básicas
+38.00 | Tecnologías de acceso a red
+45.00 | Tecnologías multimedia
 28.00 | Tecnologías web
 29.00 | Teoría de códigos y criptografía
-30.00 | Administración de bases de datos
-31.00 | Herramientas y Métodos de Ingeniería del Software
-32.00 | Informática industrial y robótica
-33.00 | Ingeniería de Sistemas de Información
-34.00 | Modelado y Diseño del Software 2
-35.00 | Negocio Electrónico
-36.00 | Periféricos e interfaces
-37.00 | Sistemas de tiempo real
-38.00 | Tecnologías de acceso a red
+66.00 | Termodinámica y cinética química aplicada
 39.00 | Tratamiento digital de imágenes
-40.00 | Administración de redes y sistemas operativos
-41.00 | Almacenes de Datos
-42.00 | Fiabilidad y Gestión de Riesgos
-43.00 | Líneas de Productos Software
-44.00 | Procesos de Ingeniería del Software 1
-45.00 | Tecnologías multimedia
-46.00 | Análisis y planificación de las TI
-47.00 | Desarrollo Rápido de Aplicaciones
-48.00 | Gestión de la Calidad y de la Innovación Tecnológica
-49.00 | Inteligencia del Negocio
-50.00 | Procesos de Ingeniería del Software 2
-51.00 | Seguridad Informática
-52.00 | Biologia celular
-53.00 | Física
-54.00 | Matemáticas I
-55.00 | Química general
-56.00 | Química orgánica
-57.00 | Biología vegetal y animal
-58.00 | Bioquímica
-59.00 | Genética
-60.00 | Matemáticas II
-61.00 | Microbiología
-62.00 | Botánica agrícola
-63.00 | Fisiología vegetal
-64.00 | Genética molecular
-65.00 | Ingeniería bioquímica
-66.00 | Termodinámica y cinética química aplicada
-67.00 | Biorreactores
-68.00 | Biotecnología microbiana
-69.00 | Ingeniería genética
-70.00 | Inmunología
 71.00 | Virología
-72.00 | Bases moleculares del desarrollo vegetal
-73.00 | Fisiología animal
-74.00 | Metabolismo y biosíntesis de biomoléculas
-75.00 | Operaciones de separación
-76.00 | Patología molecular de plantas
-77.00 | Técnicas instrumentales básicas
-78.00 | Bioinformática
-79.00 | Biotecnología de los productos hortofrutículas
-80.00 | Biotecnología vegetal
-81.00 | Genómica y proteómica
-82.00 | Procesos biotecnológicos
-83.00 | Técnicas instrumentales avanzadas
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,14 @@
 nombre
-Informática
-Matemáticas
+Agronomía
+Biología y Geología
+Derecho
+Economía y Empresa
 Economía y Empresa
 Educación
-Agronomía
+Educación
+Educación
+Filología
+Matemáticas
+Matemáticas
 Química y Física
-Filología
-Derecho
-Biología y Geología
+Química y Física
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_profesor, id_departamento

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 17: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-total
+COUNT(id)
 2.00
```

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 18: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-departamento | total
+nom_departament | num_professors
 Educación | 3.00
 Informática | 2.00
 Matemáticas | 2.00
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_departamento

---

## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
-departamento | total
+nom_departament | num_professors
+Agronomía | 1.00
+Biología y Geología | 0.00
+Derecho | 0.00
+Economía y Empresa | 2.00
+Educación | 3.00
+Filología | 0.00
 Informática | 2.00
 Matemáticas | 2.00
-Economía y Empresa | 2.00
-Educación | 3.00
-Agronomía | 1.00
 Química y Física | 2.00
-Filología | 0.00
-Derecho | 0.00
-Biología y Geología | 0.00
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 20: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-grau | total
+nom_grau | num_assignatures
 Grado en Ingeniería Informática (Plan 2015) | 51.00
 Grado en Biotecnología (Plan 2015) | 32.00
 Grado en Ingeniería Agrícola (Plan 2015) | 0.00
```

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 21: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-grau | total
+nom_grau | num_assignatures
 Grado en Ingeniería Informática (Plan 2015) | 51.00
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,6 +1,6 @@
-grau | tipo | total_creditos
+nom_grau | tipus_assignatura | total_credits
+Grado en Biotecnología (Plan 2015) | básica | 60.00
+Grado en Biotecnología (Plan 2015) | obligatoria | 120.00
 Grado en Ingeniería Informática (Plan 2015) | básica | 72.00
 Grado en Ingeniería Informática (Plan 2015) | obligatoria | 54.00
 Grado en Ingeniería Informática (Plan 2015) | optativa | 180.00
-Grado en Biotecnología (Plan 2015) | básica | 60.00
-Grado en Biotecnología (Plan 2015) | obligatoria | 120.00
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado, PRIMARY

---

## ❌ Query 23: Error
- **Descripción**: 'NoneType' object is not iterable

