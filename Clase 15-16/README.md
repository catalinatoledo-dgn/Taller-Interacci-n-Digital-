# Apuntes de Clase 15: Sensores, Prototipado y Señales

---

## 1. Planificación y Prototipado
* **Concepto + materialización:** Traer prototipo.
* **Comunidad dentro del proyecto:** Próx. lunes.

### Idea de Proyecto
* **Sensor que atrae palomas a cierto lugar para alejarlas del espacio público transitorio de Plaza de Armas!!**[cite: 6]
  * **Crear nuevo ecosistema para ellas.
  * **Reflexión:** *¿Alguna forma de dejar de ver a las palomas como ratas con alas?*
  * **Un enfoque crítico.**
---

## 2. Sensores

* **Función:** Percibir, medir e interactuar.
* **Definición:** Dispositivo que detecta una magnitud física o cambio del entorno y lo convierte en una señal interpretable.

Magnitud Física -> Detección -> Señal.

### Del Entorno a la Acción
Convertimos cambios del entorno en respuestas útiles mediante sensores.

* **¡¡Hacer diagrama explicando el proyecto!!**
  *  El *cómo muestra nuestra interfaz* lo es todo; hay una forma de mostrar el proyecto.

### Referente: Richard Serra
* **Escultura despiadada -> Cuerpo de obra mediante el juego y manipulación con el material -> Técnica.**

---

## 3. Señales y Datos

* **Analógicas:** Varían de forma continua.
* **Digitales:** Toman 2 estados (`"1"`, `"2"`, `"prendido"`, `"apagado"`).

### Flujo de Datos
Sensor -> Señal analógica / digital -> ESP32

> *"Diseño es plan"*

---

## 4. ¿Cómo Elegir un Sensor?

* Que la belleza del proyecto dirija el sensor.
* Entorno de uso.
* Voltaje de operación.
* Compatible con la caja utilizada (ESP32).
* Rango y sensibilidad.
* Respuesta esperada[.
* Tipo de salida (analógica o digital).

## Comunidad
* **Referente:**
  Tomas Hirschorn, artista que trabaja con la comunidad.
  Propone que las personas se pueden dominar mediante la cultura -> Antonio Gramsci.

* **Autoría no compartida (todos son dueños y autores del proyecto) -> Mayor autonomía, todo ser humano es un intelectual, algo radical.**

## Sensores a la ESP32
[ Sensor ] --( 3.3V )--> [ ESP32 ]
[ Sensor ] --( GND  )-- [ ESP32 ]
[ Sensor ] --( GPIO )--> [ ESP32 ]
* ESP32 trabaja con lógica de 3,3v. Sus GPIO no toleran 5v, salvo sea una indicación específica que diga lo contrario.

## Implementar comunidad en el proyecto
**Conceptos:**
* **Coexistencia interespecie.**
* **Apropiación de espacios públicos.**
* **Adaptación.**

### Crítica
* Transmitir lo que una paloma siente.
* ¿Somos nosotros palomas?

### Relación Paloma-Humano
* **Experiencia del dominio** Concientizar sobre palomas.
* ASMR, que de miedo.

# Clase 16: Presentación y corrección
## Referente: Fly by Night - Duke Riley (2016)

* **Instalación artística** en donde se entrenaron palomas para dirigirlas a un punto específico.
* **Método:** Duke construyó un refugio elevado y acostumbró a palomas a volar juntas y volver al punto específico usando comida, rutina y luces como guía.

---

## ¿Cómo aprenden?
* Condicionamiento (recompensa).
* Asociación de estímulos.
* Aprendizaje social.
* **Agudeza visual:**
  * Perciben luz ultravioleta y frecuencias de parpadeo + altas.
* **Memorización:** Formas, texturas, olores.
  *  Retienen en su memoria mapas visuales.

---

## Corrección y Conceptos
* Entrenar una paloma.
* **¿Palomas - 3ª edad.**
* **¿Palomas mensajeras?**
* **¿Palomas - prostitutas?**

