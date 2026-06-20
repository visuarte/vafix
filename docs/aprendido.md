# Aprendido — Fuentes de conocimiento para VAFIX

## Video 1: PyGame Sprite Animation — Explosions
`https://www.youtube.com/watch?v=d06aVDzOfV8`

**Qué nos da:**
- Lógica de animación por frames para explosiones
- Sprite sheets como metodología para separar fases de una explosión
- Timing: cuántos frames dura cada fase (fogonazo → expansión → humo)

**Para VAFIX:**
- La timeline de sincronización debe reflejar fases, no solo viñetas
- Cada viñeta tiene fases: preparación → ejecución → post-efecto
- Las capas F/x, SVfx, Luz pueden tener duraciones diferentes

---

## Video 2: Filmar escenas de fuego y explosiones
`https://www.youtube.com/watch?v=lqYvrSHERZ0`

**Qué nos da:**
- La práctica real de grabar explosiones en un set
- Cómo se coordinan cámara, pirotecnia y seguridad
- La diferencia entre lo que se planea y lo que se rueda

**Para VAFIX:**
- La herramienta no solo planifica, también documenta lo real vs lo planeado
- Cada viñeta debería poder tener "notas de rodaje" después de grabarse
- La timeline es un documento vivo, no un plano estático

---

## Video 3: Creating (safe!) Explosion FX
`https://www.youtube.com/watch?v=nZHO0ZSdLvc`

**Qué nos da:**
- Seguridad como prioridad: distancias, protecciones, protocolos
- La pirotecnia real tiene tiempos de seguridad que no se negocian
- Los profesionales (como Santiago) trabajan con márgenes de error

**Para VAFIX:**
- Las viñetas con explosivos (V6, V7, V9) necesitan campo "seguridad"
- La timeline debe incluir "zona de seguridad" antes/después del efecto
- Esto es lo que hace a VAFIX una herramienta profesional, no un juguete

---

## Lo que estas 3 fuentes nos enseñan juntas

| Video | Área | Lo que aporta |
|---|---|---|
| 1 | Programación | Cómo modelar el tiempo y las fases |
| 2 | Cine | Cómo se ruedan las explosiones de verdad |
| 3 | Seguridad | Cómo no matar a nadie mientras tanto |

**Conclusión para VAFIX:**
La herramienta vale si integra las tres. No sirve de nada una timeline bonita 
que no contemple los tiempos de seguridad. No sirve de nada la seguridad 
si no entiendes cómo se rueda. No sirve de nada rodar si no tienes la lógica 
temporal bien modelada.

---

## Video 4: Creating BULLET HIT Movie Special FX
`https://www.youtube.com/watch?v=FH17Zh09rGY`

**Qué nos da:**
- Técnicas prácticas para impactos de bala en rodaje
- Cómo se prepara el set para impactos controlados
- La diferencia entre un impacto visto desde lejos vs un primer plano
- Pequeños explosivos controlados para simular impactos

**Para VAFIX:**
- El proyecto StuG vs T-34 tiene impactos de proyectil (V6, V7)
- No todos los impactos son iguales: distancia, ángulo, material
- La viñeta necesita campo "tipo de impacto" para planificar seguridad
- Los impactos en primer plano (V6) requieren más coordinación que los generales

**Conexión con las otras fuentes:**

| Video | Técnica | Para qué viñeta |
|---|---|---|
| 1 - PyGame | Animación por frames de explosión | V6 (fogonazo), V9 (dos impactos) |
| 2 - Filmación | Cómo se rueda fuego real | Todas, pero especialmente V7 (explosión torreta) |
| 3 - Seguridad | Protocolos de distancia y protección | V6, V7, V9 (las que tienen pirotecnia) |
| 4 - Bullet hits | Impactos controlados | V6 (primer disparo), V7 (impacto T-34) |
| 5 - Animatrónica | Movimiento mecánico de vehículos | V10 (torreta despedida), V6 (retroceso cañón) |
| 6 - Animatrónica práctica | Construcción de mecanismos reales | V5 (vegetación dinámica), V9 (árboles sacudidos) |
| 7 - Python `fxy` | Librería científica para modelado | Modelado de tiempos y físicas en VAFIX |
| 8 - Explosivos reales | Lo que parece real vs lo que no | TODAS — criterio de calidad para las viñetas |

---

## Video 5: Cómo empezar con Animatrónica
`https://www.youtube.com/watch?v=8VzQshnrvN0`

**Qué nos da:**
- Flujo de trabajo para crear movimiento mecánico en set
- Materiales, motores, control remoto
- Cómo se integra la animatrónica con los FX físicos
- La diferencia entre un vehículo real y uno animatrónico

**Para VAFIX:**
- V10 (torreta volando) puede ser cable o presurizada — decisión de ingeniería
- El retroceso del cañón en V6 necesita sincronización mecánica
- Las viñetas con movimiento requieren campo "tipo de accionamiento"
- La timeline debe considerar tiempos mecánicos (no solo explosivos)

---

## Video 6: Making the Halloween Animatronic
`https://www.youtube.com/watch?v=uesl7em6btA`

**Qué nos da:**
- Continuación práctica de animatrónica: construcción real
- Motores, servos, articulaciones, control por Arduino
- Cómo se integra el movimiento con el resto de la escena

**Para VAFIX:**
- V5 (ocultamiento en la ladera): la vegetación dinámica puede ser animatrónica
- V9 (árboles sacudidos por onda expansiva): impacto mecánico
- Las viñetas con "movimiento" necesitan pensar en motores, no solo en pólvora

---

## Video 7: Common scientific imports — pip install fxy
`https://www.youtube.com/watch?v=xkbRmfd86u8`

**Qué nos da:**
- Librería Python `fxy` para computación científica
- Modelado matemático de fenómenos físicos
- Herramientas que podemos usar para simular tiempos de FX

**Para VAFIX:**
- No para el lunes, sí para después
- Podemos modelar la física de una explosión y compararla con la timeline
- `fxy` como posible backend científico si VAFIX crece

---

## Video 8: Experto en explosivos puntúa películas
`https://www.youtube.com/watch?v=8V5I5WQpfh0`

**Qué nos da:**
- Criterio profesional: qué hace que una explosión parezca real
- Errores comunes: fuego sin onda expansiva, humo incorrecto, tiempos irrealistas
- La diferencia entre una explosión que funciona y una que "se ve de mentira"

**Para VAFIX:**
- Cada viñeta debería poder tener un "índice de realismo" basado en estos criterios
- V6 define el realismo de toda la escena (las notas ya lo dicen)
- Podemos añadir checklist por viñeta: ¿onda expansiva visible? ¿humo coherente?
- Esto convierte VAFIX de herramienta de planificación a herramienta de control de calidad

**Conexión directa con las viñetas de Santiago:**

| Criterio del experto | Viñeta afectada | Riesgo si se ignora |
|---|---|---|
| Onda expansiva invisible | V6 (fogonazo), V7 (impacto) | Parece fuego artificial |
| Humo incoherente | V4 (polvo), V8 (retirada) | Rompe la profundidad |
| Fragmentos mal sincronizados | V7 (blindaje), V9 (duelo) | Se ve a cámara lenta de mentira |
| Luz de explosión sin reflejo | V6, V7, V9 | El metal no reacciona |
| Torreta que no pesa | V10 | Parece de corcho |
