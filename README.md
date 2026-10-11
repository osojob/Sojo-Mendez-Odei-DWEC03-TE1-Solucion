# 📘 DWEC03 - Tarea de Evaluación [1/2]

## 📝 Descripción general

Como tarea de esta UD **desarrollarás un minijuego de tu elección**. Pero, debes tener en cuenta que la tarea está dividida en dos fases:

- *Presentación y planificación de la idea [TE 1].*

- *Desarrollo del juego [TE 2].*

Este enunciado es el referente a la primera fase y consiste en presentar **un diseño con una propuesta de minijuego en JavaScript**. 

> [!IMPORTANT]
> 
> Para que la propuesta sea considerada **APTA** deberá:
> 
> - plantear un juego sencillo **diferente del presentado en el ejemplo**;
> - incluir las interfaces solicitadas;
> - diferenciar tres niveles de dificultad;
> - cumplir los requsitos de eventos indicados en el Ejercicio 3.

## 🎯 Objetivos de aprendizaje

- Desarrollar la idea de manera esquematica y visual.
- Planificar el uso de eventos y la interacción con el DOM que se desarrollarán en la segunda fase.

## 📚 Antes de empezar

Antes de empezar:

- Lee el enunciado con detenimiento.
- Si tienes una idea de juego que te gustaría desarrollar pero que no se ajusta a los requisitos que pido ponte en contacto conmigo y pregúntame.

## 🛠️ Instrucciones de la tarea

> [!TIP]
> 
> En los recursos de la tarea tienes un ejemplo completo de entrega que puedes utilizar
> como referencia para preparar tu propuesta.

### Ejercicio 1: Presentación del juego

Explica brevemente los siguientes apartados: 

- Nombre: 

- Objetivo: 

- Descripción: 

### Ejercicio 2: Diseño de interfaces (wireframes)

**Diseña las siguientes cuatro interfaces** teniendo en cuenta que cumplan con los requisitos indicados.

- **Inicio de Sesión:** formulario con los campos `nombre de usuario`,`contraseña` y `enviar`

- **Bienvenida:** interfaz que muestra las instrucciones del juego y permite seleccionar un nivel de dificultad: `principiante`, `intermedio`o `avanzado`.

> [!NOTE]
> 
> La selección de nivel de dificultad generalmente integra una funcionalidad que cambia dinámicamente el tamaño del tablero de juego según el nivel seleccionado.

- **Juego:** interfaz donde se desarrolla la partida. Deberá incluir:
  
  - **Área de juego:** zona donde se desarrolla la mecánica del juego.
  - **Área de presentación de información:** 
    - zona destinada a mostrar controles, instrucciones, puntuaciones u otra información relevante durante la partida. 
    - deberá mostrar también el **tiempo disponible o restante para completar la partida**.

- **Resultado:** interfaz que muestra información generada durante la partida. Por ejemplo puntuación obtenida, victoria, derrota, etc.

### Ejercicio 3: Interacción con el DOM y eventos

- Define en qué se verá afectado el tablero de juego según el nivel de dificultad elegido en la interfaz de *Bienvenida*.
- Define los eventos que utilizarás en la interfaz de *Juego* para implementar la mecánica del minijuego.
- **Como mínimo se deben emplear 3 eventos** diferentes de los utilizados en el resto de interfaces.
- Para cada uno de los eventos indica:
  - qué evento utilizarás;
  - cuándo se activará;
  - sobre qué elemento de la interfaz actuará;
  - qué cambio o comportamiento producirá.

> [!WARNING]
> 
> Las interfaces de *Inicio de Sesión*, *Bienvenida* y *Resultado* deberán incluir los eventos necesarios para realizar las acciones previstas en cada una de ellas (fundamentalmente el evento `click`)
> 
> Estos eventos **no se contabilizarán** en el mínimo de 3 eventos exigido en este apartado. Es decir, **deben ser eventos diferentes a los ya utilizados anteriormente.**
