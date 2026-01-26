# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 5 correctas de 23 queries

## ❌ Query 1: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-apellido1 | apellido2 | nombre
+primer_cognom | segon_cognom | nom
 Domínguez | Guerrero | Antonio
 Gea | Ruiz | Sonia
 Gutiérrez | López | Juan
```

⏱ Tiempo: 0.39 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'DESC apellido1, apellido2, nombre' at line 2


## ✅ Query 7: Correcto

⏱ Tiempo: 0.56 ms
✅ Se usó índice(s) en la consulta: PRIMARY,nif, PRIMARY, PRIMARY,id_asignatura,id_curso_escolar

---

## ❌ Query 8: Error
- **Descripción**: 1146 (42S02): Table 'universidad.profesores' doesn't exist


## ❌ Query 9: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | apellido1 | apellido2
+nom | primer_cognom | segon_cognom
 Inma | Lakin | Yundt
 Irene | Hernández | Martínez
 Sonia | Gea | Ruiz
```

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1 @@
-departamento | apellido1 | apellido2 | nombre
-Agronomía | Monahan | Murray | Micaela
-Economía y Empresa | Fahey | Considine | Antonio
-Economía y Empresa | Lemke | Rutherford | Cristina
-Educación | Ruecker | Upton | Guillermo
-Educación | Spencer | Lakin | Esther
-Educación | Streich | Hirthe | Carmen
-Informática | Hamill | Kozey | Manolo
-Informática | Ramirez | Gea | Zoe
-Matemáticas | Kohler | Schoen | Alejandro
-Matemáticas | Schmidt | Fisher | David
-Química y Física | Schowalter | Muller | Francesca
-Química y Física | Stiedemann | Morissette | Alfredo
+nombre_departamento | primer_cognom | segon_cognom | nombre_profesor
```

⏱ Tiempo: 0.41 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 11: Incorrecto
```diff
--- 
+++ 
@@ -1 +1 @@
-apellido1 | apellido2 | nombre
+primer_cognom | segon_cognom | nom_professor
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 12: Error
- **Descripción**: 1054 (42S22): Unknown column 'p.id_profesor' in 'where clause'


## ❌ Query 13: Error
- **Descripción**: 1054 (42S22): Unknown column 'p.apellido' in 'field list'


## ❌ Query 14: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'LEFTO JOIN profesor p ON a.id_profesor = p.id_profesor WHERE p.id_profesor IS NU' at line 2


## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,14 @@
-nombre
-Informática
-Matemáticas
+nom_departament
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
✅ Se usó índice(s) en la consulta: id_departamento, id_profesor

---

## ❌ Query 16: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-total
+COUNT(id)
 12.00
```

⏱ Tiempo: 0.31 ms
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

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 18: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'DESC num_professor' at line 2


## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
-departamento | total
+nom_departament | num_profesor
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

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 20: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'DESC num_assignatura' at line 2


## ❌ Query 21: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'DESC num_assignatura' at line 2


## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,6 +1,6 @@
-grau | tipo | total_creditos
+nom_grau | tipus_assignatura | credits_totals
+Grado en Biotecnología (Plan 2015) | básica | 60.00
+Grado en Biotecnología (Plan 2015) | obligatoria | 120.00
 Grado en Ingeniería Informática (Plan 2015) | básica | 72.00
 Grado en Ingeniería Informática (Plan 2015) | obligatoria | 54.00
 Grado en Ingeniería Informática (Plan 2015) | optativa | 180.00
-Grado en Biotecnología (Plan 2015) | básica | 60.00
-Grado en Biotecnología (Plan 2015) | obligatoria | 120.00
```

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: id_grado, PRIMARY

---

## ❌ Query 23: Error
- **Descripción**: 'NoneType' object is not iterable

