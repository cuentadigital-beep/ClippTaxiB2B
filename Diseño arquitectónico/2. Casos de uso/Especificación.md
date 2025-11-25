<p align="right">
  <img src="https://i.postimg.cc/13qQdqZs/utpllogo.png" alt="Logo UTPL" width="150"/>
</p>


# Diagrama de casos de uso 

## ¿Qué es un diagrama de casos de uso?

Un diagrama de casos de uso es una representación gráfica empleada en el modelado de sistemas para describir las interacciones entre los actores (usuarios, sistemas externos u otros componentes) y las funcionalidades principales que ofrece un sistema. Este tipo de diagrama, basado en el estándar UML (Lenguaje Unificado de Modelado), se utiliza para documentar **qué hace el sistema** desde la perspectiva de los usuarios, sin entrar en detalles sobre **cómo se implementa**.

---

## ¿Para qué sirve un Diagrama de Casos de Uso?

El diagrama de casos de uso es una herramienta clave para el desarrollo y documentación de sistemas, ya que permite:

1. **Especificar requisitos funcionales**: Identificar y detallar las funcionalidades principales que debe cumplir el sistema.
2. **Facilitar la comunicación**: Servir como un medio común entre los interesados, desarrolladores y analistas para garantizar la comprensión de los requisitos.
3. **Definir el alcance del sistema**: Determinar los límites del sistema, especificando qué incluye y qué excluye.
4. **Identificar actores clave**: Describir quiénes interactuarán con el sistema, ya sean usuarios humanos o sistemas externos.
5. **Priorizar funcionalidades**: Ayudar a evaluar y clasificar las funcionalidades en función de su importancia o impacto para los usuarios.

---

## Estructura de un Diagrama de Casos de Uso

La estructura de un diagrama de casos de uso incluye los siguientes componentes principales:

1. **Actores**:
   - Representan las entidades externas que interactúan con el sistema.
   - Pueden ser personas, organizaciones o sistemas.
   - Se representan gráficamente como una figura humana o una etiqueta que los identifica.
   - Ejemplo: *Usuario*, *Administrador*, *Sistema Externo*.

2. **Casos de Uso**:
   - Representan las funcionalidades o servicios específicos que el sistema proporciona a los actores.
   - Se representan como óvalos con un nombre que describe la acción.
   - Ejemplo: *Registrar Usuario*, *Generar Informe*, *Procesar Pago*.

3. **Relaciones**:
   - **Asociación**: Representa la interacción entre un actor y un caso de uso (línea sólida).
   - **Inclusión** (`<<include>>`): Indica que un caso de uso incluye la funcionalidad de otro, generalmente para evitar redundancia.
   - **Extensión** (`<<extend>>`): Señala un caso de uso opcional que extiende la funcionalidad de otro principal, dependiendo de ciertas condiciones.
   - **Generalización**: Define relaciones de herencia entre actores o entre casos de uso.

4. **Sistema**:
   - Representa los límites del sistema modelado.
   - Se ilustra como un rectángulo que contiene los casos de uso.

---
## 1. Diagrama de caso de uso (Planificación)
![Caso de uso Planificacion](https://github.com/user-attachments/assets/4d9b9ccc-9bef-4023-bbde-42e91d42ad10)


 ## Descripción del primer caso de uso: Planificación
 ## Caso: Gestión de Zonas

 | *Nombre*       | Gestión de Zonas                                                                                                                                                                                                                                                            |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| *Actores*      | Administrador                                                                                                                                                                                                                                                               |
| *Flujo normal* | 1. Administrador accede al módulo de gestión de zonas.<br>2. Administrador Define las áreas geográficas de operación en el mapa.<br>3. El mapa devuelve el area geografica al Administrador.<br>4. Administrador Configura las zonas de cobertura en el area geografica <br>5. Administrador Establece las zonas tarifadas en la zona de cobertura.<br>

 ## Caso: Programación de Recursos
 | *Nombre*       | Programación de Recursos                                                                                                                                                                                                                                                                                   |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| *Actores*      | Administrador                                                                                                                                                                                                                                                                                              |
| *Flujo normal* | 1. Administrador accede al módulo de programación de recursos.<br>2. Registra la flota disponible para la operación.<br>3. Verifica la disponibilidad de los conductores.<br>4. Comprueba el cumplimiento normativo de vehículos y conductores.<br>5. Confirma la asignación de recursos para el servicio. |


## Caso: Optimización Avanzada
| *Nombre*       | Optimización Avanzada                                                                                                                                                                                                                                                          |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| *Actores*      | Administrador                                                                                                                                                                                                                                                                  |
| *Flujo normal* | 1. Administrador accede al módulo de optimización avanzada.<br>2. Analiza el balance entre oferta y demanda del servicio.<br>3. Aplica estrategias de optimización para mejorar la asignación de recursos.<br>4. Genera ajustes y recomendaciones para optimizar la operación. |



