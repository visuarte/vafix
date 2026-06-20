# VAFIX — Fase 1: Timeline de sincronización

## Requisitos (por qué)

Santiago tiene la reunión de VFX el lunes. Necesita algo que abra en el móvil
y vea de un vistazo cómo se sincronizan las 3 capas (F/x, SVfx, Luz) en cada
viñeta. El PDF ya lo tiene. Esto es el siguiente nivel.

## Qué hace

Una barra de tiempo horizontal por viñeta donde:

```
F/x  ████████████████░░░░░░░░░░░░  ← rojo
SVfx ░░░░████████████████████████  ← azul
Luz  ░░░░░░░░░░██████████████████  ← amarillo

     ⚠ Punto crítico: fogonazo V6
     Todos los equipos activos en el mismo frame
```

## Alcance (lo que entra)

- [ ] Timeline horizontal por viñeta (modal o sección)
- [ ] 3 carriles: F/x, SVfx, Luz con colores distintivos
- [ ] Marcadores de punto crítico donde se cruzan
- [ ] Tooltip: qué dispositivo ejecuta cada tramo
- [ ] Móvil-friendly (deslizar horizontalmente)
- [ ] Datos desde VAFIX (no requiere servidor)

## Lo que NO entra (para no sobreingenierar)

- ❌ Animación automática (va en Fase 3)
- ❌ Timecode SMPTE real (va en Fase 3)
- ❌ Edición de tiempos desde la UI (va en Fase 2)
- ❌ Conexión con GOLE (VAFIX es estático)

## Cómo se conecta con lo aprendido

| Fuente | Lo que aporta a la timeline |
|---|---|
| Video 1 (PyGame) | Lógica de frames para medir tiempos |
| Video 8 (Explosivos reales) | Criterio de realismo: onda expansiva, humo |
| RD 989/2015 + ITC 8 | Margen de seguridad obligatorio |
| Catálogo dispositivos | Cada tramo = un dispositivo real |
| Secuenciador multicanal | La timeline es un secuenciador visual |

## Prioridades

1. Que se vea en móvil
2. Que los puntos críticos salten a la vista
3. Que Santiago entienda qué pasa y cuándo sin leer instrucciones
4. Que podamos iterar después del lunes basados en su feedback
