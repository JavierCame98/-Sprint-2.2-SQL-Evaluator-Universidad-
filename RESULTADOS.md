# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 5 correctas de 8 queries

## ❌ Query 1: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-apellido1 | apellido2 | nombre
+primer cognom | segon cognom | nom
 Domínguez | Guerrero | Antonio
 Gea | Ruiz | Sonia
 Gutiérrez | López | Juan
```

⏱ Tiempo: 0.45 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.35 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'DESC apellido1, apellido2, nombre' at line 2


## ✅ Query 7: Correcto

⏱ Tiempo: 0.57 ms
✅ Se usó índice(s) en la consulta: PRIMARY,nif, PRIMARY, PRIMARY,id_asignatura,id_curso_escolar

---

## ❌ Query 8: Error
- **Descripción**: 'NoneType' object is not iterable

