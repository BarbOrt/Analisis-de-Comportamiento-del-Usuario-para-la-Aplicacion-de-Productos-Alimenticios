# Análisis de Comportamiento del Usuario para la Aplicación de Productos Alimenticios
# (Proyecto Integrado)

## Descripción del Proyecto

Se realizó un análisis del comportamiento del usuario para una aplicación de productos alimenticios con el objetivo de estudiar el embudo de ventas y evaluar los resultados de un test A/A/B. El análisis ayudó a comprender cómo los usuarios llegan a la etapa de compra y a decidir sobre posibles cambios en el diseño de la aplicación.

## Instrucciones para Completar el Proyecto

### Paso 1: Abrir y Leer los Datos

- **Descarga y Preparación**:
  - Se abrió el archivo de datos y se revisó la información general.

### Paso 2: Preparación de los Datos

- **Transformación y Limpieza**:
  - Se renombraron las columnas para facilitar el análisis.
  - Se verificaron tipos de datos y valores ausentes, corrigiendo según fuera necesario.
  - Se agregaron columnas de fecha y hora separadas.

### Paso 3: Estudio de los Datos

1. **Resumen de Eventos**:
   - Se determinó el número total de eventos y usuarios.
   - Se calculó el promedio de eventos por usuario.
   - Se analizó el periodo cubierto por los datos y se trazó un histograma por fecha y hora.

2. **Embudo de Eventos**:
   - Se identificaron los eventos y su frecuencia.
   - Se calculó la proporción de usuarios que realizaron cada acción y el embudo de eventos.
   - Se identificaron las etapas con mayor pérdida de usuarios y el porcentaje que completa todo el proceso hasta la compra.

### Paso 4: Análisis del Test A/A/B

1. **Comparación de Grupos de Control**:
   - Se analizaron los grupos de control (246 y 247) para verificar si había diferencias significativas entre ellos.
   - Se evaluó la proporción de usuarios que realizaron el evento más popular en cada grupo de control y se verificó la significancia estadística.

2. **Evaluación del Grupo de Prueba**:
   - Se compararon los resultados del grupo con fuentes alteradas (248) con los grupos de control.
   - Se realizaron pruebas para cada evento y se compararon los resultados con los de los grupos de control combinados.

3. **Nivel de Significación**:
   - Se estableció un nivel de significación para las pruebas estadísticas y se calcularon cuántas pruebas se realizaron.

## Descripción de los Datos

El dataset contiene información sobre eventos de usuarios con las siguientes columnas:
- `EventName`: Nombre del evento
- `DeviceIDHash`: Identificador único del usuario
- `EventTimestamp`: Hora del evento
- `ExpId`: Número del experimento (246 y 247 para grupos de control, 248 para grupo de prueba)
