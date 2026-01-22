# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 4 correctas de 7 queries

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

⏱ Tiempo: 0.38 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'DESC apellido1, apellido2, nombre' at line 2


## ❌ Query 7: Error
- **Descripción**: 'NoneType' object is not iterable

