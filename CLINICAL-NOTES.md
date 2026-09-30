# StrengthLab Clinical

Abrir `clinical.html` para la versión clara. `index.html` conserva el diseño anterior.

- Dashboard con fecha, entrenamiento del día, progreso semanal, adherencia, volumen completado, próxima sesión e historial.
- La adherencia usa sesiones completamente registradas frente a sesiones programadas hasta hoy. El historial muestra la fecha programada, no una fecha real de ejecución inferida.
- Modo entrenamiento con kg/reps/RPE o RIR, controles +/−, datos anteriores, descanso por tiempo transcurrido, pausa y confirmación de salida.
- Usa el almacenamiento existente en el mismo origen del navegador. No hay sincronización entre dispositivos. Abrir desde archivo o desde una URL diferente puede mostrar otro almacenamiento; para trasladar registros usa el respaldo JSON existente.
- Mantiene las calculadoras, Técnica, Sobre RIR, reportes y respaldo de la aplicación original.

## Verificación

Prueba aislada: 62,5 kg × 8 reps a RPE 8,5; 25 kg × 10 reps a RIR 0. Persistencia confirmada al recargar. Volumen total esperado incluyendo 480 kg previos: 1230 kg. Adherencia esperada: 100%, dos sesiones completadas. Confirmación de salida: cancelar y guardar comprobados. Pausa bloquea la edición. Vista de entrenamiento sin desbordamiento a 320 px. Sintaxis JavaScript y unicidad de IDs verificadas.

No se ha realizado una prueba en Safari de iPhone físico. Las fotos y bibliotecas externas necesitan conexión; los ejercicios sin imagen muestran un respaldo.
