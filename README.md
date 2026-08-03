
# ROVEC-2026-Social-Learning

Bienvenido al repositorio complementario para nuestra presentación de póster en el **Campamento de Verano Ecuatoriano sobre Telerrobótica y Tecnología Vehicular (ROVEC 2026)**.

Este repositorio contiene el resumen extendido y las demostraciones en video de nuestra investigación sobre aprendizaje social en enjambres de robots.

## Tabla de Contenido
* [Resumen Extendido](#resumen-extendido)
* [Videos de Simulación](#videos-de-simulación)

---

## Resumen Extendido
Nuestro trabajo propone un método de aprendizaje social en el cual un robot aprende de múltiples robots basándose únicamente en su percepción local.

* [**Leer el Resumen Extendido completo (PDF)**](./Abstract/Abstract.pdf)


## Videos de Simulación
Las siguientes demostraciones muestran el método de aprendizaje social evaluado en el simulador ARGoS3 utilizando el modelo de robot QUPA. 

*(Nota: En todos los videos, el lado izquierdo muestra la simulación en ARGoS3 y el lado derecho muestra la gráfica de datos en tiempo real).*

### 1. Percepción Local (Un maestro)

https://github.com/user-attachments/assets/ccb3695a-d4bb-4e09-ad2c-b4e90a92f781

> **Descripción:** Muestra al robot aprendiz (Ra) observando al robot maestro 1 (Rm1). La gráfica muestra en tiempo real los datos que el aprendiz está obteniendo.

### 2. Percepción Local (Múltiples maestros)

https://github.com/user-attachments/assets/5f17e82c-3331-4197-bbf5-0fa0ce6923fb

> **Descripción:** Vista superior de todo el escenario. La gráfica detalla los datos que el aprendiz capta simultáneamente al observar a los siete maestros en la arena.

### 3. Ejecución del Comportamiento Aprendido

El robot aprendiz (Ra) es capaz de observar a múltiples maestros (Rm_i) y aprender de forma simultánea múltiples comportamientos.

* **Primer comportamiento aprendido:**

https://github.com/user-attachments/assets/0aa90d06-d0fc-4cbc-8431-a70438ac9a57

> **Descripción:** Tras visualizar múltiples repeticiones de las demostraciones realizadas por los maestros, el robot aprendiz ejecuta el primer comportamiento aprendido (patrón triangular).

* **Segundo comportamiento aprendido:**

https://github.com/user-attachments/assets/2c5f518d-6eef-4c16-86ee-2734a7900fea

> **Descripción:** Se observa al robot aprendiz ejecutando el segundo comportamiento aprendido (patrón pentagonal).

> **Nota:** Aunque el robot aprende ambos comportamientos de manera simultánea durante el mismo proceso de observación, se presentan en videos separados para facilitar y clarificar la visualización de cada trayectoria.

---

## Autores
* **Jonatan Díaz** - *Universidad de Nariño* (jhonatandiaz1w1@udenar.edu.co)
* **Wilson Achicanoy** - *Universidad de Nariño* (wilachic@udenar.edu.co)
* **David Garzón Ramos** - *University College Dublin* (david.garzonramos@ucd.ie)
