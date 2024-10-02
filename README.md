# Proyecto: Generación de Energía con Plantas mediante Celdas de Combustible Microbianas

![Microbial Fuel Cell](https://github.com/rralen/Generacion-de-energia-con-plantas/blob/main/G.%20con%20plantas/Conexion.jpeg)

## Descripción del Proyecto

Este proyecto tiene como objetivo explorar la **generación de electricidad utilizando plantas** mediante el uso de **Celdas de Combustible Microbianas (MFC)**. Las MFC son una tecnología bioelectroquímica que convierte la energía química almacenada en la biomasa de las plantas en energía eléctrica utilizando microorganismos presentes en el suelo.

El sistema permite generar electricidad de manera sostenible y renovable, aprovechando la relación simbiótica entre las plantas y los microorganismos que descomponen la materia orgánica.

### ¿Cómo funciona?

1. **Raíces de las plantas**: Las plantas realizan la fotosíntesis y liberan exudados (materia orgánica) a través de sus raíces en el suelo.
2. **Microorganismos**: Las bacterias en el suelo descomponen esta materia orgánica y liberan electrones durante el proceso.
3. **Electrodos**: Un ánodo se coloca en el suelo, cerca de las raíces, donde los electrones generados por los microorganismos son capturados.
4. **Ciclo eléctrico**: Los electrones viajan a través de un circuito externo hacia el cátodo, donde reaccionan con oxígeno para generar electricidad.

### Componentes del Sistema

- **Electrodos**: Se utilizan electrodos de carbono por su alta conductividad y resistencia a la corrosión.
- **Sistema de plantas**: Cualquier planta que libere exudados ricos en carbono puede utilizarse, aunque las plantas acuáticas han demostrado ser especialmente eficientes.
- **Circuito eléctrico**: Un circuito externo conecta los electrodos para permitir la recolección y medición de la electricidad generada.
- **Sensor de voltaje**: Se utiliza un sensor para monitorear y registrar la salida de energía en tiempo real.

### Diagrama del Sistema

```mermaid
graph TD;
    A[Planta] --> B[Raíces liberan exudados]
    B --> C[Bacterias descomponen materia orgánica]
    C --> D[Electrones liberados]
    D --> E(Ánodo)
    E --> F[Electrones viajan al cátodo]
    F --> G{Oxígeno en el cátodo}
    G --> H[Generación de electricidad]

