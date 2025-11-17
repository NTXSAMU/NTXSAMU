<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/ca0d6118-bb1f-4b2e-9557-80520198b1f0" /><img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/6b0468dc-6442-4ef7-b638-fb4780c721ab" /><div style="
      width: 400px;
      display: block;
      margin-left: auto;
      margin-right: auto;
    ">
      <img width="400" align="center" src="https://github-stats.tonimatas.dev/api?username=NTXSAMU&show_icons=true&include_all_commits=true&hide_border=true&number_format=long&show=reviews,prs_merged,prs_merged_percentage&theme=ambient_gradient&cache_seconds=3600" />
      <img width="400" align="center" src="https://github-stats.tonimatas.dev/api/top-langs?username=NTXSAMU&hide_border=true&langs_count=8&theme=ambient_gradient&cache_seconds=300" />
<br>    
</div>


from pypandoc import convert_text

content = """# Estudio del Diagrama de Gantt – *IGNIS APP*

## Proyecto: InstitutoProyecto  
##  Aplicación: IGNIS APP  
##  Duración total: **Septiembre 2025 – Junio 2026**  
##  Horas estimadas: **1440h**

---

# 1. Lista de tareas y duraciones

| Nº | Tarea                 | Duración | Periodo estimado |
|----|-----------------------|----------|------------------|
| 1  | Análisis del proyecto | 880h     | Sep 2025 – Feb 2026 |
| 2  | Diseño                | 560h     | Sep 2025 – Ene 2026 |
| 3  | Desarrollo Frontend   | 880h     | Ene 2026 – Jun 2026 |
| 4  | Desarrollo Backend    | 880h     | Ene 2026 – Jun 2026 |
| 5  | BBDD                  | 680h     | Ene 2026 – May 2026 |
| 6  | Integración           | 560h     | Feb 2026 – May 2026 |
| 7  | Pruebas               | 640h     | Mar 2026 – Jun 2026 |
| 8  | Deployment            | 520h     | Abr 2026 – Jun 2026 |
| 9  | Documentación         | 160h     | May 2026 – Jun 2026 |

---

# 2. Diagrama Gantt (Mermaid)

```mermaid
gantt
    title IGNIS APP - Cronograma del Proyecto
    dateFormat  YYYY-MM-DD
    axisFormat  %b %Y

    section Análisis y Diseño
    Análisis del proyecto      :2025-09-01, 2026-02-28
    Diseño                     :2025-09-15, 2026-01-31

    section Desarrollo
    Desarrollo Frontend        :2026-01-01, 2026-06-30
    Desarrollo Backend         :2026-01-01, 2026-06-30
    BBDD                       :2026-01-01, 2026-05-31

    section Integración y Calidad
    Integración                :2026-02-15, 2026-05-31
    Pruebas                    :2026-03-01, 2026-06-20

    section Entrega y Cierre
    Deployment                 :2026-04-01, 2026-06-30
    Documentación              :2026-05-15, 2026-06-30


3. Dependencias del proyecto

El Diseño se solapa con el Análisis, aunque depende parcialmente de él.

Frontend y Backend dependen del Diseño.

BBDD depende del Diseño y se coordina con Backend.

Integración depende de Frontend + Backend + BBDD.

Pruebas dependen de Integración.

Deployment depende de Pruebas.

Documentación se realiza en paralelo al cierre del proyecto.

4. Camino crítico


Análisis → Diseño → Backend/Frontend → Integración → Pruebas → Deployment

5. Riesgos del proyecto
Riesgo	Impacto	Probabilidad	Mitigación
Cambios en requisitos	Alto	Medio 	Validaciones tempranas
Inconsistencias FE/BE	Alto	Medio	      API clara y reuniones
Problemas en integración	Muy alto	Medio	Integración continua
Pocas pruebas	Muy alto	Alto	      Automatización + QA
Documentación limitada  	Medio	Medio      	Documentación incremental

6. Recomendaciones

Extender tiempo de pruebas y documentación.

Definir hitos entre fases.

Reuniones semanales entre equipos.

"""
