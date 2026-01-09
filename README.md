# [CIT] Curso–Taller: Introducción a Big Data (Nivel Básico)

Repositorio oficial del **Curso–Taller “Introducción a Big Data”** del **[Centro de Innovación TIC](https://cit.pol.una.py/) – Universidad Nacional de Asunción (CIT-UNA)**, en el marco del proyecto **Paraguay–Korea (KOICA)**.

El curso está orientado a formar fundamentos prácticos para el perfil de **Arquitectura/Ingeniería de Datos**, implementando pipelines **ETL/ELT** con **PostgreSQL + Apache Airflow + Python**, usando **datos abiertos del Paraguay** y construyendo salidas para **Power BI**.

---

## Datos académicos

- **Institución:** Universidad Nacional de Asunción (UNA) – Facultad Politécnica (FP)
- **Proyecto:** Centro de Innovación TIC Paraguay-Corea
- **Duración:** 8 semanas — **40 horas**
- **Carga horaria:** 3 clases/semana — 5 horas/semana (24 clases)
- **Modalidad:** 100% virtual
- **Fecha y horario:** a definir
- **Lugar:** Zoom
- **Metodología:** Teórico–práctico (taller)
- **Dirigido a:** Personas con formación o interés en informática que quieran desarrollar competencias en arquitectura de datos para big data.
- **Requisitos previos:** Conocimientos básicos de Python y familiaridad con Linux.

---

## Docente responsable

- **Profesor:** **Ing. Richard Daniel Jiménez Riveros - Especialista en Big Data y Automatización**
- **Afiliación:** Facultad Politécnica – UNA, Campus San Lorenzo – Paraguay
- **Correo institucional:** rjimenez@pol.una.py

---

## Objetivos del repositorio

Al finalizar, el estudiante será capaz de:

1. Comprender fundamentos de Big Data y su relación con arquitectura analítica.
2. Diseñar pipelines de ingesta y transformación con prácticas correctas (ETL/ELT).
3. Modelar datos para análisis (capas raw/ods/fdw/stage/core/datamart/dwh).
4. Optimizar consultas en PostgreSQL (EXPLAIN, índices, particiones, buenas prácticas).
5. Orquestar procesos con Airflow (DAGs, scheduling, retries, logging).
6. Publicar resultados listos para consumo en Power BI u otras herramientas de visualización de datos.

---

## Stack tecnológico (estándar del curso)

- **PostgreSQL:** 15
- **Apache Airflow:** 3.1.5
- **Python:** 3.12
- **SQL / PL/pgSQL**
- **Git / GitHub**
- **Linux / Windows + WSL2 (Ubuntu recomendado) o Docker**
- **PyCharm**, **DBeaver**, **Power BI**, **SQL Power Architect**

---

## Requisitos previos (mínimos)

- SQL básico (SELECT, JOIN, GROUP BY)
- Python básico (scripts, funciones, lectura de CSV/JSON)
- Uso de terminal (WSL/PowerShell)
- Manejo de la terminal de Linux y sus comandos básicos
- Equipo recomendado: 16 GB RAM (mínimo 8 GB) + espacio libre para contenedores/datos

---

## Estructura del repositorio (vista rápida)

- `docs/` tutoriales y guías
- `setup/` levantar el entorno local (Postgres/Airflow)
- `week_01...week_08...` contenidos y prácticas por semana
- `week_06...` / `week_07...` proyectos guiados (datos reales)
- `datasets/` catálogo de fuentes + muestras pequeñas
- `airflow/` laboratorio común de DAGs
- `db/` scripts SQL, migraciones, seeds

---

## Clonar el repositorio

```bash
git clone <URL_DEL_REPO>
cd cit-intro-bigdata

