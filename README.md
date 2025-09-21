# Proyecto: SQLAlchemy + Pandas + PostgreSQL en Docker

Este proyecto es una práctica para experimentar con **SQLAlchemy** y su facilidad de conexión con una base de datos **PostgreSQL** corriendo en **Docker**, además del uso directo de la librería en **Pandas** para manejar datasets.

---

##  Descripción del Proyecto

El objetivo fue integrar diferentes herramientas del ecosistema de Python y bases de datos para lograr un flujo completo de trabajo:

1. **Configuración del entorno**  
   - Se creó un nuevo *Environment* de **Conda** para aislar dependencias y mantener el proyecto limpio.

2. **Carga de datos inicial**  
   - Se utilizó un **DataFrame** proveniente de una **URL pública**, con reportes de clima en *Seattle*.

3. **Limpieza y transformación de datos**  
   - Se procesaron los datos, eliminando información redundante.  
   - Se agregaron nuevas columnas y registros para generar una versión más legible del dataset.

4. **Análisis y agrupaciones**  
   - Se realizaron operaciones de agrupación y cálculo.  
   - Se generaron diferentes tablas y reportes a partir de los datos procesados.

5. **Persistencia en PostgreSQL**  
   - Todo el dataset limpio y las tablas derivadas se enviaron a la base de datos **Postgres** en Docker.  
   - Esto permite un **fácil guardado y acceso posterior** para otros análisis o proyectos.

---

## Tecnologías Utilizadas

- **Python 3.11**
- **Conda** (entorno virtual)
- **Pandas**
- **SQLAlchemy**
- **PostgreSQL** (Docker)

---

