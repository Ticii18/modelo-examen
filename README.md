
# Actividad - Análisis de calificaciones y asistencia estudiantil 📊

Este proyecto contiene un cuaderno de Jupyter donde se analiza información sobre calificaciones y asistencia de estudiantes. Se utilizan las bibliotecas **Pandas** y **Matplotlib** para realizar la exploración, limpieza, visualización y exportación de los datos.

---

## 📋 Contenido del cuaderno

1. **Importación del dataset** usando `pandas.read_csv()`.
2. **Exploración de los datos** con métodos como `info()` y `isnull()`.
3. **Limpieza y normalización** de columnas como 'estudiante', 'Materia', 'Asistencia' y las todo referido a notas.
4. **Estadísticas descriptivas** por materia y generales.
5. **Visualización de datos** con `matplotlib.pyplot`.
6. **Exportación de datos limpios** a un archivo SQLite con `to_sql()`.

---

## 💻 ¿Cómo clonar y correr el proyecto?

1. Cloná este repositorio a tu computadora:

```bash
git clone https://github.com/Ticii18/modelo-examen.git
```

2. Navegá a la carpeta del proyecto:

```bash
cd modelo-examen
```

3. Abrí la carpeta con:

```bash
code .
```

4. Ejecutá cada celda del cuaderno con `Ctrl + Alt + Enter` para ver los resultados del análisis.

---

## ℹ️ Notas importantes

- Se normalizaron nombres y valores para un análisis más coherente.
- Se eliminaron registros incompletos y se ajustaron valores de asistencia mayores a 100.
- Los gráficos permiten visualizar mejor la distribución de notas y asistencia.
- La base de datos SQLite generada puede utilizarse para consultas posteriores.

---

## 🧑‍💻 Autor

Ticiano Vera

---
