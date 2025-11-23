# TimeTrack U · Academic Software

**TimeTrack U** es un prototipo de sistema web desarrollado para la Universidad de Guanajuato, como proyecto final de la materia **Sistemas de Información de Recursos Humanos**.

Su objetivo es apoyar a los estudiantes en la **gestión de sus Unidades de Aprendizaje (UDPS)** y créditos, centralizando en un solo lugar:

- La **difusión de actividades** (deporte, cultura, emprendimiento y desarrollo personal).
- El **registro visual** de UDPS acumuladas.
- Un flujo de **carga de evidencias** para comprobar asistencia.

> Referencia: en este sistema, **25 UDPS = 1 crédito**.

---

## 🎯 Problema que resuelve

En la práctica, muchos estudiantes tienen dificultades para:

- Enterarse de las actividades que otorgan UDPS.
- Llevar un seguimiento claro de cuántas UDPS llevan.
- Contar con un registro ordenado de sus evidencias.

**TimeTrack U** propone una interfaz única donde todo esto se integra de forma sencilla y visual.

---

## 🧩 Funcionalidades principales (versión demo)

- 🗓️ **Calendario mensual de actividades**  
  - Vista por mes con días clickeables.  
  - Puntos de color según tipo de actividad:
    - Azul: Deporte  
    - Morado: Cultura  
    - Naranja: Emprendimiento  
    - Verde: Desarrollo personal  
  - Al seleccionar un día, se muestran las actividades correspondientes y las **UDPS** que aporta cada una.

- 📊 **Panel de progreso del estudiante**  
  - Muestra UDPS acumuladas y su equivalente en créditos.  
  - Distribución por categoría (deporte, cultura, emprendimiento y desarrollo personal) con barras de progreso.

- 📎 **Módulo de evidencias (flujo demo)**  
  - Área tipo “drag & drop” para cargar evidencias.  
  - Selección de archivo desde el dispositivo.  
  - En una versión institucional real, estas evidencias se vincularían a la matrícula y a cada actividad.

- ⭐ **Actividades recomendadas**  
  - Lista de eventos sugeridos con sus UDPS, pensada para dar mayor visibilidad a oportunidades relevantes.

---

## 🛠️ Tecnologías utilizadas

- **HTML5** — estructura de la aplicación.
- **CSS3 (sin frameworks)** — diseño responsivo y estilo tipo web-app profesional.
- **JavaScript vanilla** — interacción básica:
  - Selección de días en el calendario.
  - Render dinámico de actividades.
  - Manejo del input de archivo en el módulo de evidencias.
- **GitHub Pages** — despliegue gratuito del prototipo en la web.

---

## 🚀 Cómo ver el proyecto

El sitio está publicado con **GitHub Pages**:

```text
https://TU-USUARIO.github.io/timetrack-u-ug/
