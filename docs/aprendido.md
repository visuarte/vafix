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
