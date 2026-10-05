# ¿Qué día fue?

Aplicación de entrenamiento para calcular mentalmente el día de la semana.

## Uso
Abre `index.html` en un navegador moderno. Para reconocimiento por voz, permite el acceso al micrófono.

Se recomienda Chrome o Edge.

## Método
día + código del mes + código del siglo + últimos 2 dígitos del año + floor(últimos 2 dígitos / 4), y después módulo 7.

La aplicación usa Domingo=0, Lunes=1, ..., Sábado=6.

## Nota
El algoritmo está implementado directamente a partir de las tablas y operación indicadas.
