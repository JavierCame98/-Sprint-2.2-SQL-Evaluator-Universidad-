# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 4 correctas de 7 queries

## ❌ Query 1: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,13 @@
-apellido1 | apellido2 | nombre
-Domínguez | Guerrero | Antonio
-Gea | Ruiz | Sonia
-Gutiérrez | López | Juan
-Heller | Pagac | Pedro
-Herman | Pacocha | Daniel
-Hernández | Martínez | Irene
-Herzog | Tremblay | Ramón
-Koss | Bayer | José
-Lakin | Yundt | Inma
-Saez | Vega | Juan
-Sánchez | Pérez | Salvador
-Strosin | Turcotte | Ismael
+nom | primer cognom | segon cognom
+Antonio | Domínguez | Guerrero
+Sonia | Gea | Ruiz
+Juan | Gutiérrez | López
+Pedro | Heller | Pagac
+Daniel | Herman | Pacocha
+Irene | Hernández | Martínez
+Ramón | Herzog | Tremblay
+José | Koss | Bayer
+Inma | Lakin | Yundt
+Juan | Saez | Vega
+Salvador | Sánchez | Pérez
+Ismael | Strosin | Turcotte
```

⏱ Tiempo: 0.39 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'DESC apellido1, apellido2, nombre' at line 2


## ❌ Query 7: Error
- **Descripción**: 'NoneType' object is not iterable

