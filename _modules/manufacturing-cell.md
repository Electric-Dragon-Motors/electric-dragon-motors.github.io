---
title: "Celda robotizada"
date: 2019-05-18T12:33:46+10:00
weight: 4
---

Para alcanzar un alto nivel de automatización, seguridad y eficiencia en el proceso de ensamblaje, se planteó la incorporación de celdas robóticas especializadas y equipos industriales. Se contemplaron dos celdas, una para la instalación de las baterías y la otra para pintar las piezas.

# Etapa Seleccionada N°.1: Instalación de Baterías (Celda Robótica)
Esta etapa fue identificada como crítica y prioritaria debido a su complejidad operativa y su alto impacto en la seguridad del producto final. La manipulación e instalación de las baterías requiere precisión, fuerza controlada y repetibilidad, lo que la convierte en una candidata ideal para ser automatizada mediante robótica industrial, dado a que contribuye significativamente a reducir riesgos de fallos eléctricos por errores de conexión.

-	Aplicación del robot: Pick & Place + herramienta de torque
-	Estado del material de entrada: Paquete de baterías en bandeja, con cables parcialmente preparados
-	Estado del material de salida: Batería instalada y ajustada correctamente sobre el chasis del vehículo
  

# Etapa Opcional: Pruebas Eléctricas y Verificación de Cargadores (Celda Semiautomatizada)
Como posible ampliación, se propone una segunda celda orientada a realizar las pruebas eléctricas finales de cada unidad ensamblada, asegurando el correcto funcionamiento de los sistemas eléctricos.

- Aplicación del robot: Inspección y pruebas con sensores y visión artificial
- Estado del material de entrada: Motocicleta completamente ensamblada con sistema eléctrico activo
- Estado del material de salida: Vehículo validado en cuanto a encendido, luces, cargador y motor
  
Esta celda puede implementarse con un alto grado de automatización o como una estación semiautomatizada con interfaz HMI, sensores y procedimientos guiados para los operarios.

# Equipos Evaluados para Automatización
Se evaluaron múltiples robots industriales según la carga útil y el alcance necesarios en cada etapa del proceso:

- ABB IRB 6600 – Carga: 150 kg.
- KUKA KR 60-3 – Carga: 60 kg.
- ABB IRB 2600 – Carga: 20 kg.
  
Adicionalmente, se consideró la incorporación de centros de mecanizado CNC, como el Haas VF-2SS y el Mazak QT-Primos 100 SG, para la fabricación precisa de piezas como carcasas y ejes estructurales.
También se incluyó la instalación de una cinta transportadora especializada para motocicletas monoplaza, la cual permite un flujo continuo y sincronizado de las unidades entre estaciones de trabajo, reduciendo tiempos muertos y riesgos por manipulación manual.

![](TextoImagenes/manipuladores.png)
![](TextoImagenes/OtraMaq.png)


# Etapa Seleccionada N.° 2: Pintura en Aerosol (Celda Robótica)

En este caso, se eligió utilizar pintura con aerosol dentro de una celda automatizada debido a sus múltiples ventajas tanto operativas como económicas. Esta decisión no solo responde a criterios técnicos de calidad y eficiencia, sino también a razones logísticas, fiscales y comerciales. A continuación, se detallan los principales motivos que justifican esta elección:

## Justificación de la etapa: Pintura en Aerosol en Celda Robótica

La selección de esta etapa responde tanto a razones técnicas como estratégicas. La automatización del proceso de pintura mediante aerosol en una celda robótica ofrece ventajas clave que impactan en la calidad del producto, la eficiencia operativa y la competitividad de la empresa.

### Ventajas operativas y productivas

- **Calidad y precisión**: La precisión del robot permite pintar zonas muy específicas con excelentes acabados superficiales.
- **Accesibilidad**: El sistema robótico permite acceder a zonas difíciles que serían complicadas o riesgosas para un operario humano.
- **Alta productividad**: Se reduce el tiempo de ciclo de producción, aumentando la capacidad de respuesta frente a la demanda.
- **Control de proceso**: Se permite el monitoreo y control de parámetros críticos como presión, abanico y atomización, lo cual garantiza uniformidad y repetibilidad.
- **Versatilidad**: Los parámetros de pintura son totalmente programables para cada punto o geometría a pintar.
- **Cambio rápido**: El cambio de referencia del producto a pintar es inmediato mediante recetas preprogramadas.
- **Repetitividad**: Al automatizar el cambio de parámetros y puntos de pintura, se garantiza un proceso repetible y confiable.

### Ventajas logísticas, fiscales y estratégicas

- **Flexibilidad productiva y reducción de inventario**: Es posible personalizar el color y los acabados en línea, lo que permite atender pedidos específicos o series limitadas. Si se importan piezas ya pintadas, cada color requiere su propio inventario. Al pintar localmente, se elimina esta necesidad, favoreciendo la producción bajo demanda.

- **Reducción de costos logísticos y riesgo de daño**: Se minimizan los costos de embalaje especial necesarios para proteger acabados delicados, y se reduce el desperdicio causado por rayones, humedad u otros daños durante el transporte.

- **Control de calidad en sitio**: La inspección y el retrabajo ante defectos se realiza de inmediato. Además, se pueden ajustar parámetros como espesor, adherencia y resistencia de acuerdo con las condiciones ambientales locales, mejorando también la trazabilidad del proceso.

- **Beneficios arancelarios y fiscales**: Productos con valor agregado, como las piezas ya pintadas, pueden estar sujetos a aranceles más altos al ser importados. Además, zonas francas o acuerdos de manufactura nacional suelen exigir que parte del proceso productivo se realice en el país, lo cual se cumple con la pintura automatizada localmente.

## Justificación de la robotización y valor agregado

También se realizó un análisis para justificar la implementación de la robotización en esta etapa del proceso:

| Criterio                    | Argumento a favor de la robotización                                                       |
|-----------------------------|--------------------------------------------------------------------------------------------|
| Calidad del acabado         | Alta repetibilidad, precisión en el espesor de capa y cobertura uniforme.                  |
| Seguridad                   | Elimina la exposición del operario a vapores tóxicos y disolventes.                        |
| Productividad               | Incrementa la velocidad de aplicación y reduce el desperdicio de material.                 |
| Trazabilidad y control      | Los parámetros de pintura son monitoreados y registrados automáticamente.                  |
| Consistencia                | Disminución de defectos y retrabajos.                                                      |
| Ahorro de material          | Uso eficiente de la pintura mediante pulverización controlada.                             |
| Cumplimiento normativo      | Mejora las condiciones para cumplir con normativas ambientales y de salud ocupacional.     |


## Seguridad en sistemas robotizados

La seguridad en sistemas robotizados es un aspecto crítico que debe garantizarse desde el diseño hasta el mantenimiento del sistema. Para evitar riesgos, es fundamental que la instalación esté en condiciones óptimas antes de su activación, corrigiendo cualquier anomalía y reportando incidentes no solucionables de inmediato.

### Medidas físicas de protección

- Vallados de rejilla de 3 metros de altura evitan el ingreso accidental a zonas peligrosas.
- Se dejan espacios libres de al menos 1 metro para tareas de programación, carga, descarga y mantenimiento.
- Cerrojos de seguridad interrumpen el funcionamiento si están abiertos, asegurando condiciones seguras.

### Acceso restringido y controlado

- Solo personal autorizado y capacitado puede ingresar a la celda.
- Las puertas deben permanecer cerradas durante el funcionamiento, ya que el robot puede ejercer fuerzas peligrosas incluso a baja velocidad.
- Dispositivos de seguridad como puertas enclavadas, barreras fotoeléctricas y vallados no deben ser vulnerados ni retirados.
- Los operadores deben conocer la ubicación de los botones de paro de emergencia y los controles de encendido/apagado.

### Sistemas de seguridad integrados

- Frenos electroimantados mantienen la posición del robot en caso de fallo eléctrico.
- Sensores de par motor detectan bloqueos o movimientos anómalos y detienen el sistema automáticamente.
- En modo manual, se limita la velocidad a 300 mm/s para reducir riesgos.
- Sistemas como SafeMove y múltiples paradas de emergencia permiten detener la operación de forma inmediata ante cualquier situación de peligro.

### Cumplimiento normativo

- Cumplimiento con directivas europeas sobre:
  - Seguridad de máquinas
  - Compatibilidad electromagnética
  - Requisitos eléctricos
- Se emite una Declaración UE de Conformidad, firmada por el responsable del proyecto, que certifica el cumplimiento con normas como:
  - EN ISO 10218-1
  - EN ISO 10218-2
  - UNE-EN 775

### Evaluación continua de riesgos

A pesar de las medidas implementadas, es indispensable:
- Evaluar riesgos durante todas las fases: montaje, programación, mantenimiento y uso diario.
- Adoptar medidas adicionales para reducir la probabilidad y gravedad de posibles accidentes.

## Identificación de peligros y gestión del riesgo

| Tipo de peligro       | Descripción                                                                 |
|-----------------------|------------------------------------------------------------------------------|
| Físico                | Aplastamiento por movimiento del robot, colisión con partes móviles          |
| Químico               | Exposición a vapores de pintura, disolventes y partículas atomizadas         |
| Incendio/explosión    | Presencia de sustancias inflamables y posibles atmósferas explosivas (ATEX)  |
| Eléctrico             | Riesgos en sistemas de control y motores                                     |
| Ergonómico            | Mala postura o acceso inseguro en tareas de mantenimiento                    |
| Ambiental             | Mala ventilación o acumulación de vapores                                    |


## Anpalisis de riesgo inicial (antes de aplicar medidas)

| Riesgo                    | NP | FE | LO | DPH | HRN (NP × FE × LO × DPH)  | Nivel de riesgo |
|---------------------------|----|----|----|-----|---------------------------|-----------------|
| Aplastamiento por robot   | 1  | 5  | 2  | 3   | 30                        | Alto            |
| Exposición a vapores      | 1  | 8  | 2  | 3   | 48                        | Muy alto        |
| Incendio por vapores      | 1  | 3  | 3  | 4   | 36                        | Alto            |


## Medidas propuestas para mitigación del riesgo

| Riesgo                  | Medidas técnicas y organizacionales                                                                 |
|-------------------------|-----------------------------------------------------------------------------------------------------|
| Aplastamiento           | Cerramiento perimetral, sensores de presencia, parada de emergencia, PLC de seguridad               |
| Vapores tóxicos         | Cabina con ventilación forzada, extracción localizada, uso de EPP (respiradores)                    |
| Incendio o explosión    | Sensores de gases, equipos con protección contra ignición                                           |
| Electricidad            | Puesta a tierra, protecciones diferenciales, mantenimiento regular                                  |
| Mantenimiento           | Procedimientos LOTO, acceso por enclavamientos seguros, capacitación técnica                        |


## Evaluación del riesgo residual

| Riesgo                  | HRN residual | Nivel esperado |
|-------------------------|--------------|----------------|
| Aplastamiento por robot | 6            | Bajo           |
| Exposición a vapores    | 8            | Bajo           |
| Incendio por vapores    | 10           | Moderado       |



