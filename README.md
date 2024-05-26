# Design of Reconfigurable Array of Reaction Wheels based on Möbius Strip for the Attitude Control of CubeSat Satellites.
An innovation project to explore the feasibility of reconfigure the position of attitude actuators (reaction wheels) in order to control the orientation of a 3U CubeSat satellite.

## Year: 2021 - 2023.

## Description. 

### English. 

The design of a new, improved and more powerful version of the Reaction Wheel Array (RWA) is presented, with features such it allows to relocate the actuators in different directions. Conventionally, the reaction wheels are fixed inside the satellite structure, which implies that the generated angular momentum can only be transferred in a single direction. This severely limits the potential of the actuators, because there is a risk of losing one degree of freedom in case one fails. 

In this sense, the objective of this work is to design an RWA that it is capable of relocating the actuators in different sections of the structure; and with it, ensure the survival of the satellite and the continuity of the mission. This is achieved thanks to the study of the Möbius Strip which, after some modifications, a surface capable of allowing the necessary relocation is found. A secondary actuator in charge of the displacement is also proposed, since the wheels are not able to relocate by themselves.

Consequently, the content of this work focuses on the analysis of the RWA and its properties, the modeling of the actuators and the realization of the necessary topological adjustments for the Möbius Strip. Finally, the simulation of all the components is offered under a cascade control architecture, whose controllers are proposed from the PID family and are tuned by using the Evans method. The overall simulation offers four main cases where different attitude references are desired for a 3U CubeSat satellite based on divers RWAs.

The simulations show that the design is effective, since in all the cases the correct regulation of the
attitude is achieved in a satisfactory finite time.

### Spanish. 

Se presenta el diseño de una versión novedosa, mejorada y más potente de los Arreglos de Ruedas de Reacción (RWA, por sus siglas en inglés), con características tales que le permiten reubicar a los actuadores que lo conforman en diferentes direcciones. Convencionalmente, las ruedas de reacción están fijos dentro de la estructura satelital, lo que implica que el momento angular generado sólo pueda ser transferido en una única dirección. Esto limita severamente el potencial de los actuadores, ya que en caso de fallar uno, existe el riesgo de perder un grado de libertad.

En ese sentido, el objetivo de este trabajo es diseñar un RWA tal que sea capaz de reubicar los actuadores que lo conforman en diferentes partes de la estructura; y con ello, asegurar la supervivencia del satélite y la continuidad de la misión. Este cometido se logra gracias al estudio de la Banda de Möbius que, tras algunas modificaciones, se da con una superficie capaz de permitir la reubicación necesaria. También se propone un actuador secundario encargado de realizar el desplazamiento, ya que las ruedas de reacción no son capaces de reubicarse por si mismas.

En consecuencia, gran parte de lo plasmado gira en torno al análisis de los RWA y sus propiedades, el modelado de los actuadores y la realización los ajustes topológicos necesarios para la Banda de Möbius. Por último, se ofrece la simulación de todos los elementos bajo una arquitectura de control en cascada, cuyos controladores son propuestos de la familia PID y son sintonizados mediante el método de Evans.

La simulación conjunta ofrece cuatro escenarios principales en los que se desean diferentes referencias de actitud para un satélite CubeSat de 3U a través de diferentes RWA seleccionados.
Las simulaciones demuestran que el diseño es efectivo, ya que en todos los escenarios se logra la correcta regulación de la actitud en un tiempo finito satisfactorio.

# Simulations.

## Reconfigurations cases for Reaction Wheel Array. 

![tableeee](https://github.com/Lechuga-Geronimo/MoebiusCubeSatReactionWheel/assets/142461885/e3b21c66-b3d2-4d39-aee9-2391e2e0dff2)

## Attitude Control Response.

![imCase_1_a](https://github.com/Lechuga-Geronimo/Moebius-CubeSat-Reaction-Wheel/assets/142461885/7eae24d9-9273-4e5f-9478-73c478634cc1)

## Attitude Error by Quaternions.

![imCuaternion_error_1](https://github.com/Lechuga-Geronimo/Moebius-CubeSat-Reaction-Wheel/assets/142461885/95598451-f3f0-4ed5-9336-c5f5bf9e4584)

## Reaction Wheel's inputs and outputs.

![imCase_4_b](https://github.com/Lechuga-Geronimo/Moebius-CubeSat-Reaction-Wheel/assets/142461885/92e50235-c230-4fc4-a01d-3c7fcd66cb73)

## Multi-loop Tuning. 

![1710182433151](https://github.com/Lechuga-Geronimo/Moebius-CubeSat-Reaction-Wheel/assets/142461885/6f0b2a6b-da1b-4e49-8396-81edc72f81cd)

# Topologic Adjustment. 

## Original Moebius Strip.

![imBanda_1](https://github.com/Lechuga-Geronimo/MoebiusCubeSatReactionWheel/assets/142461885/0eb53858-1c47-482d-9737-659a496a021b)

## Modified Moebius Strip.

![imSuperficie_M](https://github.com/Lechuga-Geronimo/Moebius-CubeSat-Reaction-Wheel/assets/142461885/1e8b6de1-1120-40e3-818f-95db6b8f345d)
