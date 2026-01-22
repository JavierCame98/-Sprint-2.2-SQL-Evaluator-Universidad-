# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 2 correctas de 7 queries

## ❌ Query 1: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near ': 'alumno' ORDER BY (apellido1, apellido2, nombre)' at line 2


## ❌ Query 2: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near ': 'alumno' AND telefono IS NULL' at line 2


## ✅ Query 3: Correcto

⏱ Tiempo: 0.47 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 4: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near ''profesor' AND telefono IS NULL AND nif LIEK '%K'' at line 2


## ✅ Query 5: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'DESC(apellido1, apellido2, nombre)' at line 2


## ❌ Query 7: Error
- **Descripción**: 'NoneType' object is not iterable

