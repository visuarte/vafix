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
