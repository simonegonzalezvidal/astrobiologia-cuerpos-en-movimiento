# AstrobiologIA de cuerpos en movimiento — Maqueta

**Maqueta del dispositivo para la postulación al Concurso Nacional Ciencia Pública 2027, línea Dispositivos de Comunicación de Conocimientos CTCI, MinCiencia.**
Postulante: Consultoría Andes Data Science Limitada · Región del Biobío, Chile.

---

Una instalación interactiva en la que una inteligencia artificial reconoce el cuerpo de quien
participa y proyecta sobre él un planeta. Al moverse, la persona encarna el movimiento del
planeta y el clima se reorganiza en la proyección sobre su piel: la temperatura del océano y
del aire, la humedad y las nubes. Con ese clima aparecen o desaparecen los organismos que
podrían habitarlo.

La instalación no existe todavía: es lo que se postula. Lo que esta maqueta muestra son las
**dos herramientas de autoría propia que el proyecto integra por primera vez**, cada una ya
funcionando por separado, y la línea gráfica en desarrollo.

---

## Cómo funciona el dispositivo

```
cuerpo en movimiento
        ↓
cámara sensible a infrarrojo (iluminadores de 850 nm)
        ↓
detección de pose con inteligencia artificial
        ↓
parámetro de inclinación, entre 0° y 90°
        ↓
estado climático correspondiente, de las simulaciones de la tesis
        ↓
proyección mapeada sobre el cuerpo  +  sonificación de los datos
```

No hay botones, pantallas táctiles ni mandos: el cuerpo es la interfaz.

---

## Qué contiene esta maqueta

| Componente del dispositivo | Qué lo representa aquí | Dónde verlo |
|---|---|---|
| Los datos planetarios y su visualización | **DancingGlobe**, visualizador web de las simulaciones de la tesis | [Demo en vivo](https://simonegonzalezvidal.github.io/dancinglobe/) · [Repositorio](https://github.com/simonegonzalezvidal/dancinglobe) |
| El cuerpo como interfaz | **LuzCuerpo**, prototipo de detección de cuerpo y visuales interactivas en tiempo real | Videos de prueba, más abajo |
| La identidad visual de la experiencia | Línea gráfica en desarrollo | Imágenes, más abajo |

---

## 1. DancingGlobe — los datos de la investigación previa

**▶ [Abrir el demo interactivo](https://simonegonzalezvidal.github.io/dancinglobe/)**

Visualizador web de los acuaplanetas simulados en la tesis de Magíster en Astronomía, con
oblicuidades entre 0° y 90°. Es la capa de datos del dispositivo: la que traduce cada
inclinación en un estado climático concreto.

Al ser una aplicación web, representa además el **segundo formato del dispositivo**: el
micrositio con la versión web del planeta interactivo, comprometido en las metas de cobertura.

Qué probar en el demo:

- Cambiar la inclinación y observar cómo se reorganizan la temperatura del océano y la
  distribución de nubes y humedad.
- Comparar los extremos: un planeta casi sin inclinación contra uno inclinado a 90°.

En la instalación, ese control deja de ser del ratón y pasa a ser del cuerpo.

---

## 2. LuzCuerpo — el cuerpo como interfaz

Prototipo propio de detección de cuerpo con visión por computador (YOLOv8-pose) y proyección
de visuales interactivas en tiempo real. En los registros aparecen tres personas moviéndose
con distintos templates visuales, acompañadas por una música de referencia compuesta para
mostrar el estilo del paisaje sonoro que tendrá la instalación.

<!-- Reemplaza por tu GIF cuando lo tengas: se reproduce solo, sin que nadie tenga que hacer clic -->
![LuzCuerpo en funcionamiento](media/luzcuerpo-demo.gif)

**Videos completos:**

- [Prueba 1 — template [NOMBRE]](PEGAR_LINK_YOUTUBE_NO_LISTADO)
- [Prueba 2 — template [NOMBRE]](PEGAR_LINK_YOUTUBE_NO_LISTADO)
- [Prueba 3 — template [NOMBRE]](PEGAR_LINK_YOUTUBE_NO_LISTADO)

**Sobre el código fuente.** LuzCuerpo es desarrollo propio previo y su código no se publica
aquí. Según el numeral 8.1 de las bases, la institución postulante conserva la propiedad
intelectual del desarrollo y la Subsecretaría recibe una licencia de uso no exclusiva,
gratuita y no comercial de los archivos y el código al cierre del proyecto. Lo que se muestra
en esta maqueta es el prototipo en funcionamiento.

---

## 3. Línea gráfica

Prototipos de la identidad visual de la experiencia, en desarrollo. La versión definitiva se
cierra en la etapa de diseño, después de las sesiones de codiseño con la comunidad de la
Oficina de la Discapacidad e Inclusión de San Pedro de la Paz, porque los apoyos visuales, los
pictogramas y la guía en lectura fácil se definen con ellas y ellos.

<!-- Sube tus imágenes a la carpeta linea-grafica/ y ajusta los nombres -->
![Línea gráfica — propuesta 1](linea-grafica/01.png)
![Línea gráfica — propuesta 2](linea-grafica/02.png)

---

## 4. Qué es lo inédito

La instalación nunca ha sido publicada, exhibida ni distribuida. LuzCuerpo y DancingGlobe son
herramientas de autoría propia previas, sin exhibición pública: solo pruebas privadas.

Lo inédito es **conectarlas**: que el movimiento del cuerpo detectado por LuzCuerpo gobierne en
tiempo real el estado climático simulado que DancingGlobe visualiza, y que ese resultado se
proyecte mapeado sobre el propio cuerpo, con los datos convertidos también en sonido.

---

## 5. La experiencia completa

La instalación se acompaña de mediación gratuita. Antes de entrar, cada persona recibe una guía
en lectura fácil con pictogramas que anticipa qué va a ver, qué va a pasar con la luz y el
sonido, cuánto dura y qué hacer para salir o descansar. En la zona de espera se desarrollan
**actividades participativas** orientadas a profundizar en los conceptos de la investigación,
cuyo formato y dinámicas se definen progresivamente mediante prototipado en la etapa de diseño,
el codiseño y los tres testeos. Al salir, cada participante se lleva **láminas ilustradas
conmemorativas** que refuerzan los conceptos científicos abordados.

---

## Investigación previa

*Modeling of Archean Earth-like aquaplanets atmospheres: the effect of obliquity on habitability
and observables of exoplanets*. Simone González-Vidal. Tesis para optar al grado de Magíster en
Astronomía, Universidad de Concepción, 2024.

Modeló diez acuaplanetas con atmósfera tipo Tierra Arcaica y oblicuidades entre 0° y 90°, y
evaluó su habitabilidad mediante la temperatura superficial del mar y la temperatura de bulbo
húmedo.

[Acceso libre en el repositorio institucional](https://repositorio.udec.cl/items/c81fe24f-f6c9-4d11-99c6-708e0ea860f8)

---

## Equipo y autoría

| | |
|---|---|
| Contenidos científicos y desarrollo de software | Simone González-Vidal |
| Diseño de experiencia y composición sonora | Maximiliano Rioseco |
| Dirección general | Francisco Córdoba |
| Música de referencia del demo | [NOMBRE DEL ARTISTA DE AUDIO] |

Instituciones asociadas: Balmaceda Arte Joven Biobío (Concepción) y Oficina de la Discapacidad
e Inclusión, Ilustre Municipalidad de San Pedro de la Paz.
