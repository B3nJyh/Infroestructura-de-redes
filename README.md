# Manual técnico: Empalme de fibra óptica por termofusión

**Asignatura:** Infraestructura de Redes (TCB304) · Unidad 2: Infraestructura de redes de fibra óptica
**Autor:** Benjamin Araya Carrizo
**Docente:** Daniel Ruz Moreno
**Sede:** INACAP La Serena

> Manual práctico para consultar en el banco de trabajo desde el celular o el laptop. Describe cómo se realizó un empalme por fusión en el taller.

## Contenido

1. [Glosario exprés](#1-glosario-exprés)
2. [Seguridad y EPP](#2-seguridad-y-epp)
3. [Herramientas y materiales](#3-herramientas-y-materiales)
4. [Guía paso a paso](#4-guía-paso-a-paso)
5. [Errores comunes](#5-errores-comunes)
6. [Presupuesto óptico](#6-presupuesto-óptico) *(pendiente)*
7. [Mediciones y verificación](#7-mediciones-y-verificación) *(pendiente)*

---

## 1. Glosario exprés

| Término | Definición |
|---|---|
| **Núcleo (core)** | Parte central de vidrio por donde viaja la luz. En monomodo mide cerca de 9 µm. |
| **Cladding (revestimiento)** | Capa de vidrio que rodea al núcleo (125 µm en total) y mantiene la luz dentro por reflexión. |
| **Cleaving (corte de precisión)** | Corte de la fibra con un cleaver para dejar la cara plana y perpendicular (~90°) al eje. |
| **Atenuación** | Pérdida de potencia óptica de la señal, medida en dB (por distancia, empalmes y conectores). |

---

## 2. Seguridad y EPP

> [!WARNING]
> Los restos de fibra son vidrio microscópico y muy afilado. Pueden clavarse en la piel o en los ojos sin que lo notes.

- **Lentes de seguridad:** se usan durante todo el proceso.
- **Contenedor de residuos:** los trozos de fibra se desechan solo en el recipiente indicado para eso (nunca en el suelo, la mesa o el basurero común).
- **Arco eléctrico:** la fusionadora genera un arco de alta temperatura. No se toca la zona de electrodos mientras el equipo trabaja.
- **Alcohol isopropílico:** es inflamable. Se mantiene lejos del arco y de fuentes de calor.
- **Mesa limpia:** sin comida ni bebida, y sin tocar la fibra desnuda con los dedos.

<!-- FOTO PENDIENTE: EPP (lentes de seguridad) -> ![EPP](assets/img/epp.jpg) -->
<!-- FOTO PENDIENTE: contenedor de residuos de fibra -> ![Residuos](assets/img/residuos.jpg) -->

---

## 3. Herramientas y materiales

| Herramienta / material | Para qué sirve |
|---|---|
| Fusionadora de fibra óptica | Alinea las fibras y las une con un arco eléctrico. |
| Pinza peladora (stripper) | Retira las capas protectoras hasta dejar el vidrio de 125 µm. |
| Cortadora de precisión (cleaver) | Deja la punta de la fibra plana y perpendicular. |
| Alcohol isopropílico de alta pureza | Limpia el vidrio de grasa y polvo. |
| Paños libres de pelusa | Limpian sin dejar fibras ni residuos. |
| Manguitos termocontraíbles (heat shrink) | Protegen mecánicamente el empalme. |
| Lentes de seguridad | Protección ocular (EPP). |
| Contenedor de residuos | Desecho seguro de trozos de fibra. |

<!-- FOTO PENDIENTE: herramientas sobre la mesa de trabajo -> ![Herramientas](assets/img/herramientas.jpg) -->
<!-- FOTO PENDIENTE: fusionadora (modelo: [COMPLETAR]) -> ![Fusionadora](assets/img/fusionadora.jpg) -->

---

## 4. Guía paso a paso

### Paso 1. Preparar el puesto y el EPP
Ponte los lentes, ordena las herramientas y deja a mano el contenedor de residuos.
**Por qué:** la fibra se contamina y se rompe con facilidad, y un puesto ordenado evita accidentes.

### Paso 2. Insertar el manguito termocontraíble
Pasa el manguito por **una** de las dos fibras antes de pelarla y déjalo alejado de la punta.
**Por qué:** una vez fusionada, ya no se puede insertar. Es el olvido más común.

> [!CAUTION]
> Si fusionas sin haber puesto el manguito, hay que cortar y rehacer el empalme.

### Paso 3. Pelar la fibra (stripping)
Con la pinza peladora retira las cubiertas protectoras (chaqueta, buffer y recubrimiento) hasta dejar el vidrio desnudo de **125 µm**. Hazlo en tramos cortos y con un movimiento firme y recto.
**Por qué:** el vidrio es la parte que transmite la luz; si se mella, queda débil y puede romperse.

> [!WARNING]
> No gires ni tuerzas la pinza y no raspes el vidrio. Una mella reduce la resistencia y aumenta la pérdida.

<!-- FOTO PENDIENTE: pelado de la fibra -> ![Stripping](assets/img/stripping.jpg) -->

### Paso 4. Limpiar la fibra
Humedece un paño sin pelusa con alcohol isopropílico y pasa la fibra desnuda en una sola dirección, de la chaqueta hacia la punta. Repite hasta que el paño no se ensucie.
**Por qué:** el polvo o la grasa causan atenuación y empalmes defectuosos.

> [!NOTE]
> Después de limpiar, la fibra desnuda no debe tocar nada (mesa, dedos, ropa).

<!-- FOTO PENDIENTE: limpieza con alcohol isopropílico -> ![Limpieza](assets/img/limpieza.jpg) -->

### Paso 5. Cortar con el cleaver (cleaving)
Coloca la fibra limpia en el cleaver, en la posición de corte que indica el equipo, y acciona la cuchilla. El objetivo es una cara plana y **perpendicular, cercana a 90°**. El trozo sobrante va directo al contenedor de residuos.
**Por qué:** si el ángulo es malo, los núcleos no encajan y la pérdida del empalme sube.

> [!WARNING]
> Después del corte la fibra no se vuelve a limpiar ni a tocar la punta. Si algo la roza, se repite desde el paso 3.

<!-- FOTO PENDIENTE: corte bueno vs. defectuoso -> ![Corte](assets/img/corte.jpg) -->

### Paso 6. Cargar las fibras en la fusionadora
Abre la tapa y coloca cada fibra en su soporte (V-groove), con la punta entre los electrodos y sin tocarlos. Cierra la tapa.
**Por qué:** la posición correcta permite que el equipo alinee y funda el vidrio exactamente en el punto del arco.

<!-- FOTO PENDIENTE: fibra cargada en la fusionadora -> ![Carga](assets/img/carga-fusionadora.jpg) -->

### Paso 7. Configurar el programa de fusión
Selecciona en la fusionadora el tipo de fibra (por ejemplo monomodo) y el programa de empalme. Si el docente indicó valores de arco, aplícalos.
**Por qué:** cada tipo de fibra necesita parámetros de arco distintos.

> Modelo y programa usados: **[COMPLETAR]**

### Paso 8. Alinear y fusionar
Inicia el proceso. La fusionadora:
1. Revisa el estado de las puntas y el ángulo de corte.
2. Alinea las fibras (núcleos y cladding).
3. Aplica el arco eléctrico y las une.
4. Muestra una **estimación de pérdida** en dB.

**Por qué:** la unión debe quedar sin desfase y sin burbujas para perder la menor señal posible.

> [!NOTE]
> Si el equipo avisa que el ángulo de corte es malo o que hay suciedad, repite el procedimiento desde el paso 3 en vez de forzar la fusión.

<!-- FOTO PENDIENTE: pantalla de la fusionadora con la pérdida estimada -> ![Resultado](assets/img/resultado-fusion.jpg) -->

### Paso 9. Revisar el resultado
Anota la pérdida estimada y observa la imagen del empalme en pantalla. Un buen empalme se ve continuo, sin líneas, burbujas ni ensanchamientos.
**Por qué:** es la primera verificación de calidad. Si el valor es alto, el empalme se rehace.

### Paso 10. Proteger el empalme con el manguito
Retira la fibra con cuidado, desliza el manguito para centrarlo sobre el empalme y colócalo en el horno de la fusionadora. Espera a que termine el ciclo de calentamiento y deja enfriar unos segundos.
**Por qué:** el empalme desnudo es muy frágil; el manguito aporta resistencia mecánica.

> [!WARNING]
> Mueve la fibra con cuidado al sacarla de la fusionadora, porque el empalme aún no está protegido. El manguito caliente puede quemar.

<!-- FOTO PENDIENTE: manguito colocado en el horno -> ![Manguito](assets/img/manguito.jpg) -->

### Paso 11. Orden final
Desecha todos los restos de fibra en el contenedor, limpia la mesa y guarda las herramientas.

---

## 5. Errores comunes

| Error | Consecuencia | Cómo evitarlo |
|---|---|---|
| Olvidar el manguito antes de fusionar | Hay que rehacer el empalme | Insertarlo en el paso 2 |
| Mellar el vidrio al pelar | Fibra frágil y con más pérdida | Movimiento recto y firme, sin girar |
| Limpieza insuficiente | Atenuación alta o fusión fallida | Repetir con paño limpio |
| Tocar la fibra después de limpiar o cortar | Contaminación de la punta | Cargar directo en el cleaver y la fusionadora |
| Corte con mal ángulo | Núcleos mal unidos, pérdida alta | Revisar el corte y repetirlo |
| Dejar restos de fibra en la mesa | Riesgo de pinchazos | Usar siempre el contenedor |

---

## 6. Presupuesto óptico

*Pendiente de desarrollar.*

## 7. Mediciones y verificación

*Pendiente de desarrollar.*

---

## Estructura del repositorio

```text
tcb304-fusion-fibra-optica/
├── README.md
├── .gitignore
└── assets/
    └── img/
```
