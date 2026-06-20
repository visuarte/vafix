# Referencias — Manuales, guías y normativa sobre FX en España

Fuentes obtenidas de investigación en Google (junio 2026).
Aplicable a rodajes en territorio español.

## 1. Normativa legal — Explosivos y pirotecnia

| Recurso | Qué regula |
|---|---|
| **Real Decreto 989/2015** (BOE) | Reglamento de Artículos Pirotécnicos y Cartuchería. Fabricaación, almacenamiento, uso. |
| **ITC 8** (Instrucción Técnica Complementaria) | Espectáculos Pirotécnicos por Expertos. Categoría T2: artículos para teatro, escenarios, rodajes de cine. Solo manipulables por profesional con carné de experto y empresa autorizada. |

**Implicación para Santiago:**
- Necesita **carné de experto T2** para manipular los explosivos
- La empresa que contrate debe estar **autorizada** por el Ministerio del Interior
- Cada viñeta con pirotecnia (V6, V7, V9) debe poder demostrar que quien la ejecuta tiene la acreditación

## 2. Prevención de riesgos laborales

| Recurso | Tema |
|---|---|
| **Manual FREMAP** — Artes Escénicas y Espectáculos | Planes de contingencia, montajes seguros, gestión de incidentes |
| **Spain Film Commission** — Guía de Buenas Prácticas de Rodajes Seguros | Responsabilidades del productor y coordinador de seguridad al integrar elementos peligrosos |
| **Junta de Andalucía** — Prevención en Espectáculos en Vivo | Gestión de emergencias, obligaciones del empresario ante fuego y detonaciones |

**Implicación para Santiago:**
- El **productor** tiene responsabilidades legales sobre la seguridad del set
- El **coordinador de seguridad** debe estar presente en las viñetas con explosivos
- VAFIX puede incluir checklist de seguridad basada en estas guías

## 3. Estadísticas de siniestralidad

| Recurso | Tema |
|---|---|
| **Fundación MAPFRE** — Víctimas de Incendios y Explosiones en España | Datos reales de accidentes con fuego y deflagraciones |

**Implicación para VAFIX:**
- Datos reales para evaluación de riesgos objetiva
- Cada viñeta puede tener un nivel de riesgo basado en estadísticas reales

## 4. Efectos visuales (VFX) — Simulación digital

| Recurso | Tema |
|---|---|
| "Creating Big Dust Explosions in FumeFX" | Simulación de explosiones digitales |
| Guías prácticas en Notodoanimacion | Tutoriales de animación VFX |

**Implicación para VAFIX:**
- Documentación técnica para coordinar con el equipo SVfx
- Entender qué pueden hacer ellos digitalmente para complementar lo físico

## Cómo se integra en VAFIX — Checklist legal por viñeta

Cada viñeta con contenido explosivo debería responder:

```
V6 — Primer disparo (CRÍTICO)
  □ ¿Cumple RD 989/2015? → categoría T2
  □ ¿Manipulador con carné T2 asignado?
  □ ¿Empresa autorizada?
  □ ¿Plan de contingencia (FREMAP)?
  □ ¿Coordinador de seguridad presente?
  □ ¿Margen de seguridad en timeline?
  □ ¿Evaluación de riesgos documentada?
```

Esto convierte VAFIX en una herramienta que no solo planifica la secuencia,
sino que **certifica que lo planeado cumple la ley.** En una industria donde
un error puede ser un accidente, eso no es un lujo — es una obligación.

---

## 5. Dispositivos mecánicos para simular explosiones

Tecnología real que los técnicos FX usan en España para generar explosiones
sin pólvora (o reduciéndola al mínimo). Cada viñeta puede referenciar el
dispositivo concreto que ejecuta el efecto.

### 5.1 Cañones neumáticos (Air Cannons)

| Dispositivo | Función | Para qué viñeta |
|---|---|---|
| **Debris Cannon** | Aire comprimido lanza corcho, turba, polvo | V1 (polvo orugas), V4 (polvo volumétrico) |
| **Air Squib** | Micro-impactos de bala bajo ropa | V3 (impacto visor), V6 (impacto T-34) |

Seguridad: Sin fuego, sin pólvora, sin metralla real.
Materiales: Corcho, polvo de madera, espuma, plástico blando.

### 5.2 Dispositivos de gas y fuego controlado

| Dispositivo | Función | Para qué viñeta |
|---|---|---|
| **Propane Cannon** | Gas propano + chispa → llamarada limpia | V6 (fogonazo cañón), V7 (explosión torreta) |
| **Lanzallamas DMX** | Fuego secuencial controlado por mesa de luz | V9 (dos fogonazos simultáneos), V10 (fuego torreta) |

Clave: El DMX permite **sincronizar con código de tiempo de cámara.**
Esto es exactamente lo que la timeline de VAFIX debe reflejar.

### 5.3 Impulsión de vehículos

| Dispositivo | Función | Para qué viñeta |
|---|---|---|
| **Nitrogen Jack** | Pistón de nitrógeno voltea vehículos | V10 (torreta despedida) |

Sin explosivos. El pistón golpea el suelo con fuerza masiva
y el vehículo salta mientras los VFX añaden humo y fuego alrededor.

### 5.4 Sistemas de disparo secuencial (Show Control)

| Sistema | Función |
|---|---|
| **Secuenciador multicanal** | 12-36 canales, programación en ms |
| **E-Match (ignitor eléctrico)** | Retardo cero en electroválvulas |
| **Código de tiempo** | Sincronización con cámara (timecode) |

Clave: el secuenciador permite coreografiar la onda expansiva:
Cañón 1 a 0ms → Cañón 2 a 150ms → Cañón 3 a 300ms = avance real.

### 5.5 Morteros de propano líquido (Gas Cannons)

| Componente | Función |
|---|---|
| Botella propano con sifón | Extrae fase líquida (no gas) |
| Electroválvula criogénica 1.5-2" | Soporta congelación del gas |
| Cámara de mezcla + piloto electrónico | Chispa continua 12V en boca |

Funcionamiento: abre válvula 0.2s → propano líquido se atomiza → 
chispa lo enciende → bola de fuego limpia → al cerrar, desaparece sin brasas.

### 5.6 Flujo híbrido físico-digital

| Técnica | Función |
|---|---|
| **Trackers LED activos** | Esferas LED entre escombros para tracking VFX |
| **Flasheadores DMX 1000W** | Luz naranja/amarilla 1 frame sincronizada con cañón |
| **ActionVFX / librerías** | Llamaradas digitales hiperrealistas post-producción |

Clave: el efecto físico se diseña para que el VFX digital lo complete.
Los flasheadores DMX dan la luz ambiental real que la explosión digital
necesita para no parecer pegada en post.

### 5.7 Consumibles de seguridad

| Material | Función | Para qué viñeta |
|---|---|---|
| **Breakaway Glass** | Resina frágil que imita cristal | (no aplica directamente al proyecto actual) |
| **Polvos de dispersión** | Harinas inertes para humo/polvo visual | V1, V4, V8 (polvo, humo, niebla) |

### 5.8 Nivel avanzado — Nitrógeno industrial + Timecode SMPTE

| Sistema | Especificación |
|---|---|
| Nitrógeno seco 200 bar | Botellas industriales (Carburos Metálicos, Linde) |
| Válvula mariposa Rack&Pinion | 3-6", apertura en <30ms, acero inoxidable |
| E-Match retardo cero | Ignición en microsegundos para cámaras 1000fps |
| Consolas Galaxis / Fireone / Pyrodigital | Encriptación militar, testeo bidireccional, deadman switch |
| Timecode LTC | Sincronización con cámara y sonido |
| Motion Control Bolt | Trayectoria robótica programada para seguir vehículo |

**Secuencia automatizada tipo:**
```
T-5s:  Extractores de humo
T-100ms: Flasheadores LED DMX (luz naranja)
T+0ms:  Cañón nitrógeno (fotograma 0)
T+250ms: Ráfagas escombros secundarias
```

**Requisitos legales España:**
- Carné T2/P2 (Delegación del Gobierno)
- Plan de Emergencia firmado por Ingeniero
- Distancias de seguridad calculadas (overpressure + radiación térmica)
- Seguro responsabilidad civil cinematográfica
- Dotación de Bomberos en set

### Mapa dispositivo → viñeta

| Viñeta | Efecto | Dispositivo recomendado |
|---|---|---|
| V1 | Polvo orugas + niebla | Debris Cannon |
| V2 | Humo motor | Air compressor + humo artificial |
| V3 | Impacto visor | Air Squib |
| V4 | Polvo volumétrico 18 tanques | Debris Cannon + VFX |
| V5 | Vegetación moviéndose | Servos / Animatrónica |
| V6 | Fogonazo + retroceso cañón | Propane Cannon + Nitrogen Jack |
| V7 | Explosión torreta + fragmentos | Propane Cannon + Air Squibs |
| V8 | Humo + niebla retirada | Máquina de humo + Debris Cannon |
| V9 | Dos fogonazos simultáneos | 2× Propane Cannon sincronizados DMX |
| V10 | Torreta despedida + fuego | Nitrogen Jack + Lanzallamas DMX |
